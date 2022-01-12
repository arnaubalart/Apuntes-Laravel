# Apuntes-Laravel

### Crear proyecto y testearlo
```
composer create-project --prefer-dist laravel/laravel projectname
php artisan serve //Testear la app
```
### Crear modelo, controlador y relacion
```
php artisan make:model Author -mcr
```
### Cambiar la base de datos: .env
### Correr migraciones Base de Datos: (Generar o actualizar la Base de datos)
```
php artisan migrate //la primera vez
php artisan migrate:refresh // refresca la base de datos
```


### Arreglar error DB en controller
```
use Illuminate\Support\Facades\DB;
```
