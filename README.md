# Manual de configuración (MySQL)
Primer paso: Vamos a proceder a entrar tipo de consola desde la terminal donde seguimos root hemos de ejecutar la siguiente comanda.

1- sudo mysql 

segundo paso: Vamos a proceder a hacer la creación de la base de datos.

1-CREATE DATABASE bbdd;

Tercer paso: Crear nuestro propio usuario.

1- CREATE USER 'usuario'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

Cuarto paso: Tenemos que dar privilegios al usuario.

1- GRANT ALL ON bbdd.* to 'usuario'@'localhost';

Quinto paso: Salir de nuestra base de datos.

1- exit

Y por ultimo paso: vamos a comprobar la conexión de nuestra base de datos.

1- mysql -u usuario -p
