# RETO5-GITLAB
REPOSITORIO PARA RETO 5 DEMOSTRACION DE GIT Y RAMAS
# Clonar a tu máquina
git clone https://gitlab.com/tu_usuario/reto5-gitlab.git
cd reto5-gitlab

# Verifica el remoto configurado PULL
git remote -v

# Traer información sin mezclar
git fetch origin

# Ver el estado del remoto frente al local
git status
git log --oneline --graph --decorate --all

# Para integrar cambios en tu rama actual (por ejemplo main)
git pull origin main


cd 
reto5-gitlab

echo "<!doctype html><html><body><h1>Reto 5 — Demo</h1></body></html>" > index.html

git status
# Salida:
#   new file: index.html

git add index.html README.md

git commit -m "Agregar index.html y actualizar README"

git push origin main


git status — estado de archivos.

git add <archivo> — añadir al staging.

git commit -m "mensaje" — guardar en historial local.

git push origin <rama> — subir al remoto.

git pull origin <rama> — traer y unir cambios del remoto.

git fetch origin — traer sin mezclar.

git log --oneline — ver historial compacto.

git remote -v — ver URL remotas.



