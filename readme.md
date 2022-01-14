Base para laravel 8
PHP 8.0.5.
-porta: 7000
-banco local: 9306
-banco docker: 3306


git clone projeto
docker-compose up -d --build

docker-compose run composer create-project --prefer-dist laravel/laravel .

sudo chmod -R 777 src