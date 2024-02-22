<<<<<<< HEAD
# Comando para listar las ramas
=======
# Comando para acrear una listar las ramas
>>>>>>> 2823a03b43a5d9911509aef67eb956cc093fedec

git branch

# Comando para crear una nueva rama

git branch nombre_rama

# Comando para eliminar una Rama

git branch -D nombre_rama

# Cambiar entre ramas

git switch nombre_rama
git checkout nombre_rama
git checkout -b nombre_rama

# Desvincular un archivo de git que se le estaba dando seguimiento

git rm --cached nombre_archivo

# Crear una nueva versión con archivos que ya se estaban dando seguimiento

git commit -am "nombre commit"

# Comando para unir ramas

git merge nombre_rama
