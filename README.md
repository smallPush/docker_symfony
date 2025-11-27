# Docker Symfony

```bash
docker compose up -d --build
```

### Use a symfony project

```bash
docker compose exec app composer install
```

[http://localhost:8080](http://localhost:8080)


```env
DATABASE_URL="mysql://root:admin@database:3306/symfony_db?serverVersion=8.0&charset=utf8mb4"
```
