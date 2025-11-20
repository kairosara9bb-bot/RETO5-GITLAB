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
