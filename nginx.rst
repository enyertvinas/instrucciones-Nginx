Nginx Instalación
=================

Si existe el acceso a los repositorios:
---------------------------------------

1. Se debe agregar el ppa con el siguiente comando: sudo add-apt-repository ppa:nginx/stable
2. Utilizar el comando sudo apt-get update
3. Correr la instalación de nginx: sudo apt-get install nginx

Si no hay acceso a los repositorios(Tenemos el archivo con extension *.tar.gz):
-------------------------------------------------------------------------------

1. Descargar el archivo de la version correspondiente http://nginx.org/download/nginx-1.8.0.tar.gz
2. Descomprimir el archivo en la cualquier ubicacion del disco
3. Acceder al directorio que se aca de crear
4. Correr ./configure, make y make install
5. Realizar las configuraciones necesarias
