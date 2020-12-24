## Sample Laravel Sail with Postgres

1. Replace the laravel `docker-compose.yml` with the one in this project.

2. Update the laravel `.env` with the following:

**Remember to replace `app_name` with your project name**

```
DB_CONNECTION=pgsql
DB_HOST=postgres
DB_PORT=5432
DB_DATABASE=app_name
DB_USERNAME=laravel
DB_PASSWORD=secret
```