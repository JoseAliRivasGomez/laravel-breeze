<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## Indicaciones para probar localmente la aplicación creada con Laravel 9, Docker, MySQL:

# 1. Instalar y abrir Docker

# 2. Clonar el repositorio

# 3. Duplicar el .env.example y renombrarlo a .env

# 4. __docker run --rm -u "$(id -u):$(id -g)" -v "$(pwd):/var/www/html" -w /var/www/html laravelsail/php81-composer:latest composer install --ignore-platform-reqs__

# 5. __alias sail='bash vendor/bin/sail'__

# 6. __sail up__

# 7. __sail npm install__

# 8 __sail artisan migrate__

# 9. __sail npm run dev__