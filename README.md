<p align="center">
    <a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="150" alt="Laravel Logo"></a>
    <a href="https://docs.docker.com" target="_blank"><img src="https://cdn.worldvectorlogo.com/logos/docker.svg" width="100" alt="Docker Logo"></a>
</p>


# Docker & Laravel

This is a template for interacting with Laravel via Docker

**Note: Change the `.env` and `docker-compose.yml` file, add your settings!**

## Available Scripts

In the project directory, you can run:

    docker-compose up -d

Runs the app in the development mode.

    docker-compose down

Сancels the launch the app.

**Note: If your project don`t migrate the database you will first enter the main container like this:**

    docker exec -it { CONTAINER_NAME } bash

And

    php artisan migrate