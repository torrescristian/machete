# machete
Resumen de todo un poco relacionado con desarrollo

# Git

## nombre de usuario y email
git config --global user.name "<John Doe>" <br/>
git config --global user.email <johndoe@example.com>

## descargar cambios de un repositorio remoto
git pull origin <nombre_rama>

## agregar todos los cambios
git add .

## hacer un commit comentado
git commit -m "<comentario así nomas>"

## enviar cambios a un repositorio remoto
git push origin <nombre_rama>

## eliminar rama
git branch -d <nombre_rama>

## cambiar de rama
git checkout <nombre_rama>

## crear una nueva rama con el contenido de la rama que se está parado
git checkout -b <nombre_nueva_rama>

## fusionar una rama a la rama en la rama que se está parado
git merge <nombre_nueva_rama>

## borrar los cambios realizados hasta el último commit
git checkout .

## ver diferencias entre 2 commits
git diff <commit_a>^..<commit_b>
