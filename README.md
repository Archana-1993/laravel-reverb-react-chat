<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel Reverb

Reverb basically allows you to run an application on a single server – but if the application starts to outgrow that server, you can add multiple additional servers. Then those servers can all communicate with each other to distribute the messages between themselves.

This will let you easily implement WebSocket communications between your backend and frontend.

## System configuration

- PHP: version 8.2 or above (run php -v to check the version)
- Composer (run composer to check that it exists)
- Node.js: version 20 or above (run node -v to check the version)
- MySQL: version 5.7 or above (run mysql --version to check if it exists, or follow the docs to install it)

## Command list

- composer install
- php artisan migrate:fresh
- php artisan ui react --auth
- npm install && npm run dev
- npm run build
- php artisan queue:listen (for local)
- php artisa reverb:start
- php artisa serve
