### Revisen si tienen artisan y php

1.  Pongan los comandos en la terminal

    -php -v
    -composer -v

2. Si lo tienen solo tienen que correr el comando para que instale las dependencias

    composer install

3. Si se dan cuenta tienen un archivo que se llama .env.example cambienle el nombre a solo .env y le ponen esto para que jale con nuestra base

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=posAnalisis 
    DB_USERNAME=root
    DB_PASSWORD=

4. Ponen el comando php artisan key:generate para que haga una key

5. Este comando crea la base de datos con el modelo que ya tenemos

    php artisan migrate

6. php artisan db:seed (esto mete un usuario el usuario es admin@gmail.com y la pass 12345678)

7. La configuracion de arriba solo se hace cuando hacen el clone incial luego de esto solo con este comando y con el xampp abierto corren el proyecto

    php artisan serve




Se esta utilizando Laravel 11, PHP, html, css y blade.php

para base de datos mysql


Cualquier error fabian les ayuda xD