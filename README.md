# machete
Resumen de todo un poco relacionado con desarrollo

# Git

## usuario y contraseña
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

## descargar cambios del repositorio remoto
git pull origin nombre_rama

## agregar todos los cambios
git add .

## hacer commit con comentario
git commit -m "comentario así nomas"

## enviar cambios a repositorio remoto
git push origin nombre_rama

## eliminar rama
git branch -d nombre_rama

## crear una nueva rama con el contenido de la en que se está posicionado
git checkout -b nombre_nueva_rama

## fusionar una rama a la rama en la que se está posicionado
git merge nombre_nueva_rama
