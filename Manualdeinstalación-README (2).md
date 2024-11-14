# Manual de instalación de owncloud
Primer paso: Esto sirve para poder actualitzar la maquina.

1- sudo apt update 

<img src="sudo apt update captura.png" alt="sudo apt update captura">

. contraseña: usuario

2- sudo apt upgrade

<img src="sudo apt upgrade captura.png" alt="sudo apt upgrade captura">

Segundo paso: Ahora procederemos a instalar el servidor web llamado apache2.

1- sudo apt install -y apache2

Tercer paso: Instalar el servidor de la base de datos (mysql-server) 

1- sudo apt install -y mysql -server

Cuarto paso: Instalar las librerias de (php) es un lenguaje principal que utilizan las aplicaciones.

1- sudo apt install -y php libapache2-mod-php

2- sudo apt install -y php-fpm php-common php-mbstring php-xmlrpc php-soap php-gd php-xml php-intl php-mysql php-cli php-ldap php-zip php-curl

Quinto paso: Procederemos a reinicar el servidor que hemos creado de apache2.

1- sudo systemctl restart apache2



