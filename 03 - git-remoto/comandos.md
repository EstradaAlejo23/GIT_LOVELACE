# comando para conectar mi git local con git en la nube

git remote add nombre_conexion url_conexion

# comando para clonar o traer un repositorio de git remoto

git clone url_conexion

# comando para listar las conexiones remotas

git remote -v

# comando para eliminar una conexion remota

git remote remove nombre_conexion

# comando para enviar informacion al git remoto

git push
git push nombre_conexion nombre_rama
git push -u nombre_conexion nombre_rama (busca la rama y si no existe la crea)

# comando para obtener cambios o la informacion que hoy en el git remoto

git pull
git pull nombre_conexion nombre_rama

