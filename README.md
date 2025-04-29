
# EcoRecolecciones

Sistema de gestión para el reciclaje de residuos orgánicos e inorgánicos.

## Características principales
- Registro de recolecciones
- Sistema de puntos por reciclaje
- Programación de recolecciones

## Requisitos
- PHP 8.0+
- Composer
- MySQL 5.7+

## Instalación
1. `composer install`
2. Copiar `.env.example` a `.env`
3. `php artisan key:generate`
4. Configurar base de datos en `.env`
5. `php artisan migrate --seed`
   
