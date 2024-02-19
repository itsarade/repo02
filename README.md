## Cheat sheet comandos Git

#### SETUP
`git config --global user.name [Nombre Apellido]`  
`git config user.name` (te dice el nombre que hay configurado)  
`git config --global user.email [email@gmail.com]`  
`git config user.email` (te dice el email que hay configurado)

#### INIT & CLONE
**git init [nombre del repositorio]** (inicializar un directorio existente como un repositorio Git)  
**git clone [url]**


**git status** (ver en que situación se encuentran nuestros ficheros)

**git add .** (añadir todos los ficheros a la staging area)

**git add [nombre fichero]** (añadir un solo fichero a la staging area)

**git rm -cached [nombre fichero]** (quitar fichero de la staging area)

**git commit -m "[descripción]"** (pasar ficheros del staging area al repositorio local)

**git log** (visualizar historial de commits realizados)

`git push` (subir cambios al repositorio remoto)

**git pull origin main** ()

**git clone [link]**

#### ASOCIAR REPOSITORIO REMOTO CON LOCAL
**git remote -v** (ver los repositorios remotos asociados)  
**git remote add origin [link]**  
**git branch -M main**  
**git push -u origin main**


👌 -- ficar emojis i + utilitzant 'windows + .'