# machete
Resumen de todo un poco relacionado con desarrollo

# VS Code

## Colapsar Todo
<code>ctrl + k -> ctrl + 0</code> 

## Buscar en archivo actual
<code>ctrl + f</code> 

## Buscar en todos los archivos
<code>ctrl + alt + f</code>

## nueva terminal 
<code>ctrl + shift + ñ</code> 

## comentar / descomentar
<code>ctrl + ç</code>

# Git

## nombre de usuario y email
<code>git config --global user.name "<John Doe>" <br/></code><br/>
<code>git config --global user.email <johndoe@example.com></code>

## descargar cambios de un repositorio remoto
<code>git pull origin <nombre_rama></code>

## agregar todos los cambios
<code>git add .</code>

## hacer un commit comentado
<code>git commit -m "<comentario así nomas>"</code>

## enviar cambios a un repositorio remoto
<code>git push origin <nombre_rama></code>

## eliminar rama
<code>git branch -d <nombre_rama></code>

## cambiar de rama
<code>git checkout <nombre_rama></code>

## crear una nueva rama con el contenido de la rama que se está parado
<code>git checkout -b <nombre_nueva_rama></code>

## fusionar una rama a la rama en la rama que se está parado
<code>git merge <nombre_nueva_rama></code>

## borrar los cambios realizados hasta el último commit
<code>git checkout .</code>

## ver diferencias entre 2 commits
<code>git diff <commit_a>^..<commit_b></code>

## borrar el último commit
<code>git reset --hard HEAD~</code>

## conectarte a un repositorio con el certificado SSL vencido
<code>git config --global http.sslVerify false</code>

# Git Submodules

## clonar un proyecto con submódulos en cierta rama
<code>git clone --recursive --branch <nombre_rama> <url_repo></code>
  
## después de clonar un proyecto hay que inicializar los submódulos
<code>git submodule update --init --recursive</code>
  
## setear todos los submódulos a una misma rama
<code>git submodule foreach --recursive git checkout <nombre_rama></code>
