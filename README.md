# Symfony Docker
## Installation

- Download the repository

- You can edit docker-compose.yaml to personnalize container's name and credentials.

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

## Source
Based on tutorial : [BY OLUYEMI OLUSUSI 2021-05-24](https://www.twilio.com/blog/get-started-docker-symfony)
