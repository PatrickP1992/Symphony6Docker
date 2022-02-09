# Docker-Symfony-Stack

With this Docker-Symfony-Stack it's possible to setup a local development environment in seconds. Every component is selected for running Symfony 6 in a flavored way.

## Getting started

Only start docker-compose to start your environment:
```
docker-compose up
```

After booting the container, you can use composer and the symfony cli insight the php-apache container:
```
docker exec -it symfony-apache-php bash
symfony check:requirements
composer create-project symfony/skeleton ./
```

## Installed Packages
You have three container running: Apache-PHP, MariaDB and Adminer.
- [Web-App](https://localhost:8000)
- [Adminer](https://localhost:8080)
