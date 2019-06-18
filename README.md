# Contiene algunos lineas de comando de git 
 
## Eliminar un archivo local
`git rm file.css` 
## Elimina un archivo remoto
`git rm --cached file.css` 

## Eliminar una  carpeta remoto
`git rm -r --cached wp-content/uploads/`
## Decuperar archivo eliminado en el repositirio local
`git ls-files -d | xargs git checkout`
