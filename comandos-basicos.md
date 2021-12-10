### Creación de un repositorio
```shell
git init
```
### Nos muestra el estatus de nuestro repositorio
```shell
git status
```
### Agregar archivos al seguimiento de git
```shell
git add <aqui va el nombre del archivo>
```
### Crear un commit con mensaje
```
git commit -m "<aqui va el mensaje>"
```
### Hacer un commit de un archivo ya rastreado por git se puede ahorrar el git add
```
git commit -am "mensaje"
```
### Cómo ver el historico de git
```shell
git log
```
### Restablecer un archivo a su estado anterior
```shell
git checkout <archivo>

git restore <archivo>
```
### Sacar un archivo del stage
```
git restore --staged <archivos>
```
### Como agregar TODOS los archivos en git
```shell
git add .
```
### Como agregar un archivo(s) en específico(s)
```shell
git add NOMBRE_DEL_ARCHIVO

git add NOMBRE_DEL_ARCHIVO2 NOMBRE_DEL_ARCHIVO2
```
### Configuración de nombre y correo electronico
```shell
git config --global user.name "Raul"
git config --global user.email "rafex@rafex.dev"
```
### Mostrar la configuracion de github
```shell
git config --list
```
### Ver ramas
```shell
git branch
```
### crear una rama y cambiarse a ella
```shell
git checkout -b "nombre-de-la-nueva-rama"

git branch "nombre"
```
### para cambiar entre ramas
```shell
git chekout <nombre de la rama>
```
### para mezclar cambios
```
git merge <rama a mezclar>
```
### visualizar las diferencias
```
git diff <nombre archivo>
```
### revertir un cambio
```shell
git revert <hash del commit>
```
### Clonar repositorio
```shell
git clone <URL>
```
> Repositorio de ejemplo:
```shell
git clone git@github.com:rafex/mi-repo-ejemplo-01.git
```
### comando reset
```shell
git reset --soft HEAD

git reset --hard HEAD
```
### Estructura del git pull/push
```shell
git pull origin NOMBRE_DE_LA_RAMA

git pull origin main

git push origin NOMBRE_DE_LA_RAMA

git push origin main
```
### revertir un commit
```shell
git revert <UUID del commit>

git revert dacfa9716f5c2e4038c14f5785bc01831191a8c8
```
### borrado de ramas local
```shell
git branch -d <Nombre de rama>
```
### Borrado local forzado
```shell
git branch -D <nombre de rama>
```
### borrado de rama remoto
```shell
git push origin --delete <Nombre de rama>
```
### visualizar remotos
```shell
git remote -v
```
### agregar un remoto
```shell
git remote add <Nombre_remoto> <URL_REMOTO>
```
### cambiar el nombre del remoto
```shell
git remote rename <old_name> <new_name>
```
### hacer un pull de un remote especifico
```shell
git pull <remote> <rama>
```
### hacer un push a un remote especifico
```shell
git push <remote> <rama>
```
### crear un tag
```shell
git tag <nombre_tag> <rama>
```
### subir tag
```shell
git push <remote> <tag>
```
### listar tags
```shell
git tag -l
```
