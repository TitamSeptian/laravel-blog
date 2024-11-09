# Adjustment



```bash
touch /var/www/html/database/database.sqlite
docker compose exec -it blog-app sh
php artisan make:cache-table
php artisan migrate
php artisan migrate:fresh --seed
```
