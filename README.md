## Cheat sheet comandos Git

#### SETUP
**git config --global user.name [Nombre Apellido]**  
**git config user.name** (te dice el nombre que hay configurado)  
**git config --global user.email [email@gmail.com]**  
**git config user.email** (te dice el email que hay configurado)

#### INICIALIZAR REPOSITORIO
**git init [nombre del repositorio]** (inicializar un directorio existente como un repositorio Git)  

#### SUBIR FICHEROS/CAMBIOS
**git status** (ver en que situación se encuentran nuestros ficheros)  
**git add .** (añadir todos los ficheros a la staging area)  
**git add [nombre fichero]** (añadir un solo fichero a la staging area)  
**git rm -cached [nombre fichero]** (quitar fichero de la staging area)  
**git commit -m "[descripción]"** (pasar ficheros del staging area al repositorio local)  
**git push** (subir cambios al repositorio remoto)  
**git log** (visualizar historial de commits realizados)

#### BAJARSE FICHEROS/CAMBIOS
**git clone [link]** (copiar el repositorio remoto en un nuevo directorio)  
**git pull origin main** (bajarse los cambios del repositorio remoto y fusionarlos con el repositorio local)  
**git fetch** (bajarse los cambios del repositorio remoto)  
**git merge** (integrar todas las ramas independientes ceadas en una sola - la main/principal)

#### RAMAS
**git branch** (muestra todas tus ramas)
**git branch [nombre de la rama]** (crea una nueva rama des del commit actual)

#### CREAR UN NUEVO REPOSITORIO
Seguir el orden:  
**git init**  
**git add README.md** (si queremos añadir un fichero readme)  
**git commit -m "first commit"**  

#### ASOCIAR REPOSITORIO LOCAL CON REMOTO
Seguir el orden:  
**git remote -v** (ver los repositorios remotos asociados)  
**git remote add origin [link]**  (añadir el repositorio online del link)
**git branch -M main**  (crear rama la rama main/principal)  
**git push -u origin main** (subir los ficheros al repositorio online)  
  


*Cositas interesantes en VSCode:*  
👌 -- poner emojis usando 'windows + .'   
🧐 mostrar terminal usando 'ctrl + shift + ñ'