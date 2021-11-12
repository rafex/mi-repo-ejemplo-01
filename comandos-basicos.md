# Creación de un repositorio

git init

# Nos muestra el estatus de nuestro repositorio

git status

# Agregar archivos al seguimiento de git

git add <aqui va el nombre del archivo>

# Crear un commit con mensaje

git commit -m "<aqui va el mensaje>"

# Hacer un commit de un archivo ya rastreado por git se puede ahorrar el git add

git commit -am "mensaje"

# Cómo ver el historico de git

git log

# Restablecer un archivo a su estado anterior

git checkout <archivo>

git restore <archivo>

# Sacar un archivo del stage

git restore --staged <archivos>

# Como agregar todos los archivos en git

git add .

# Configuración de nombre y correo electronico

git config --global user.name "Raul"
git config --global user.email "rafex@rafex.dev"

# Mostrar la configuracion de github

git config --list

# Ver ramas

git branch

# crear una rama y cambiarse a ella

git checkout -b "nombre-de-la-nueva-rama"

git branch "nombre"

# para cambiar entre ramas

git chekout <nombre de la rama>

# para mezclar cambios

git merge <rama a mezclar>

# visualizar las diferencias

git diff <nombre archivo>

# revertir un cambio

git revert <hash del commit>

# Clonar repositorio

git clone <URL>

> Repositorio de ejemplo:

git clone git@github.com:rafex/mi-repo-ejemplo-01.git

# comando reset 

git reset --soft HEAD

git reset --hard HEAD

# Estructura del git pull/push

git pull origin NOMBRE_DE_LA_RAMA

git pull origin main

git push origin NOMBRE_DE_LA_RAMA

git push origin main

# revertir un commit

git revert <UUID del commit>

git revert dacfa9716f5c2e4038c14f5785bc01831191a8c8