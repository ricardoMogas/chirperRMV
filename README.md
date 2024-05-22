<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Install sail docker
- Activa las opciones de windows plataforma de maquina virtual y subsstema ![alt text](image.png)
    - Instala wsl y ejecuta (wsl --set-default-version 2) para cambiar y saber si se instalo wsl --install.
- asegurar que esta seleccionado ![alt text](image-1.png)
- ver lista de distribuciones que se tiene con (wsl --list --online)
- Instalar una con por ejemplo (wsl --install -d Distrox).
- ahora activar en resources/wsl integration desde el docker descktop la distro instalado ![alt text](image-2.png), despues comprobar usando (wsl --list --verbose)

## desplegarl proyect
- reinicie docker y vuelva a abrir la terminal
- estando en la termina de linux pegar la siguiente linea (curl -s "https://laravel.build/chirperRMV" | bash), este ultimo para crear un proyecto tal cual.