cp .env.example .env

docker compose up

Abrir outra instancia do terminal e rodar os seguintes comandos:

docker compose exec app composer install

docker compose exec app php artisan key:generate

docker compose exec app php artisan storage:link

docker compose exec app php artisan migrate

docker compose exec app php artisan db:seed

---------------------------------------------------
Dados de acesso:
http://localhost:8000/
Login: admin@admin.com
senha: 123456
