-----------------------CRUDPHP_Sin_Framework--------------------------------------
-----------------------------------------------------------------------------------------

Es una aplicación CRUD realizada en PHP sin utilizar ningún framework.

Para desplegar la aplicación primero deberemos crear e importar la base de datos.

Database: crud_tutorial

Los datos de la base de datos pueden ser modificados desde el archivo database.php situado en el raíz de la aplicación.

Para importar la base de datos puedes se puede utilizar este comando desde el terminal:

mysql -u root -p database_name < CRUD_PHP_Simple.sql

Posteriormente deberemos mover la carpeta de la aplicacion a nuestro directorio de apache en /var/www/html o en el directorio de nuestro virtualhost Configurado.

Posteriormente colocar en la barra de derecciones del navegador:

localhost/nombreProyecto
