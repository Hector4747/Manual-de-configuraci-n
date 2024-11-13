# Manual de configuración (MySQL)
Primer paso: Abrir MsyQL desde la terminal y la abres en modo administrador despues con los permisos se te abrira (mysql) que es el programa que quieres abrir y se entra como root significa que tu estas usando la cuenta principal la qual tiene todos los permisos.

segundo paso: 
Vamos a proceder a hacer la creación de la base de datos en MySQL, se ah de crear como contenedor llamado (bbdd) es una cosa que guarda toda la información y que se llama (bbdd) en el comando.


Tercer paso: 
Crear nuestro propio usuario. Ahora necesitas un usuario que puedes usar en esa base de datos. Despues pones en comando para poder conectarlo y te pedira un usuario y una contrasenya que seria usuario: usario contrasenya: password con esto el usuario se conectará desde la misma computadora (localhost).

Cuarto paso: 
Tenemos que dar privilegios al usuario. Ahora lo qué se ah de hacer es que el usuario en la base de datos a de dar todos los permisos, lo que significa que puede ver o agregar o cambiar y borrar datos dentro de la base de datos que creaste.

Quinto paso: Salir de MySQL. 
Cuando terminas de configurar la base de datos y los permisos del usuario has de salir de MySQL para volver a la terminal normal. Esto se confirma que ya no necesitas hacer más configuraciones como administrador.

Sexto paso: vamos a comprobar la conexión de nuestra base de datos.
Para asegurarte de que todo funciona bien tienes que volver a entrar a MySQL, pero esta vez usas la cuenta del usuario que acabas de crear. Cuando ingresas la contraseña que le asignaste, deberías poder acceder a la base de datos con todos los permisos que le diste. Esto indica que el usuario puede usar la base de datos correctamente.

<img src="conexio base de dades captura.png" alt="conexio base de dades">

Y por ultimo el permiso y ver que todo funciona correctamente: Aqui estara el listado de permisos.
1- cd /var/www/html

2- sudo chmod -R 775 .

3- sudo chown -R usuario:www-data .


Accedemos al navegador para ver que todo funciona correctamente.

. usuari: usuario
. contrasenya: password
. base de dades: bbdd
. domini: localhost
