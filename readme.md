Base para laravel 8<br>
PHP 8.0.5.<br>
-porta: 7000<br>
-banco local: 9306<br>
-banco docker: 3306<br>

<br>git clone projeto
<br>docker-compose up -d --build

<br>docker-compose run composer create-project --prefer-dist laravel/laravel .

<br>sudo chmod -R 777 src

<br>docker-compose run artisan migrate (Exemplo de rodar o php artisan no docker)
