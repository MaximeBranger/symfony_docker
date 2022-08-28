# Symfony Docker

## Installation

- Download the repository

- Move your symfony project into app/

- Build images and containers

```
docker compose up -d --build
```

After the building, you can access to the php container terminal and run composer install
```
docker exec -it php bash
composer install
```
