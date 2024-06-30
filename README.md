<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Logo de Laravel"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Estado de construcción"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Descargas totales"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Última versión estable"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="Licencia"></a>
</p>

## Acerca de Laravel

Laravel es un framework para aplicaciones web con una sintaxis expresiva y elegante. Creemos que el desarrollo debe ser una experiencia agradable y creativa para ser realmente satisfactorio. Laravel simplifica el desarrollo al facilitar tareas comunes en muchos proyectos web, como:

- [Motor de enrutamiento simple y rápido](https://laravel.com/docs/routing).
- [Contenedor de inyección de dependencias potente](https://laravel.com/docs/container).
- Múltiples backends para almacenamiento de [sesiones](https://laravel.com/docs/session) y [cache](https://laravel.com/docs/cache).
- ORM de base de datos expresivo e intuitivo: [Eloquent](https://laravel.com/docs/eloquent).
- [Migraciones de esquema](https://laravel.com/docs/migrations) agnósticas de la base de datos.
- Procesamiento robusto de trabajos en segundo plano: [Colas](https://laravel.com/docs/queues).
- [Transmisión de eventos en tiempo real](https://laravel.com/docs/broadcasting).

Laravel es accesible, potente y proporciona herramientas necesarias para aplicaciones grandes y robustas.

## Aprendiendo Laravel

Laravel tiene la documentación más extensa y completa y una amplia biblioteca de tutoriales en video de todos los frameworks modernos de aplicaciones web, lo que facilita comenzar con el framework.

También puedes probar el [Laravel Bootcamp](https://bootcamp.laravel.com), donde te guiarán a través de la creación de una aplicación moderna de Laravel desde cero.

Si prefieres aprender viendo videos, [Laracasts](https://laracasts.com) puede ayudarte. Laracasts contiene miles de tutoriales en video sobre una variedad de temas que incluyen Laravel, PHP moderno, pruebas unitarias y JavaScript. Mejora tus habilidades explorando nuestra biblioteca integral de videos.

## Patrocinadores de Laravel

Nos gustaría agradecer a los siguientes patrocinadores por financiar el desarrollo de Laravel. Si estás interesado en convertirte en patrocinador, visita el [programa de socios de Laravel](https://partners.laravel.com).

### Patrocinadores Premium

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[WebReinvent](https://webreinvent.com/)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Jump24](https://jump24.co.uk)**
- **[Redberry](https://redberry.international/laravel/)**
- **[Active Logic](https://activelogic.com)**
- **[byte5](https://byte5.de)**
- **[OP.GG](https://op.gg)**

## Contribuir

¡Gracias por considerar contribuir al framework Laravel! La guía de contribución se encuentra en la [documentación de Laravel](https://laravel.com/docs/contributions).

## Código de Conducta

Para asegurar que la comunidad de Laravel sea acogedora para todos, por favor revisa y cumple con el [Código de Conducta](https://laravel.com/docs/contributions#code-of-conduct).

## Vulnerabilidades de Seguridad

Si descubres una vulnerabilidad de seguridad en Laravel, por favor envía un correo electrónico a Taylor Otwell a través de [taylor@laravel.com](mailto:taylor@laravel.com). Todas las vulnerabilidades de seguridad serán tratadas de manera inmediata.

## Licencia

El framework Laravel es software de código abierto bajo la licencia [MIT](https://opensource.org/licenses/MIT).

## Sobre este proyecto

El siguiente proyecto es un sistema que tiene una API básica para gestionar tareas.
El proyecto consta de tres componentes principales:

1. API de Gestión de Tareas
   - Provee operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para tareas
   - Incluye un modelo de Tarea con campos como título, descripción, estado y fecha de vencimiento
   - Sigue las convenciones de enrutamiento de Laravel para las rutas CRUD
   - Utiliza el sistema de validación de Laravel a través de la clase TaskRequest
   - Maneja errores devolviendo respuestas JSON apropiadas
   - Sigue las mejores prácticas de Laravel en la estructuración del controlador, separando la lógica en métodos específicos

2. Autenticación JWT
   - Implementa autenticación JWT (JSON Web Token)
   - Provee rutas para registro e inicio de sesión de usuarios
   - Protege las rutas CRUD de tareas con un middleware de autenticación
   - Usa la biblioteca tymon/jwt-auth para la implementación JWT
   - Sigue las mejores prácticas de Laravel en la estructuración del controlador de autenticación

3. Filtrado Avanzado y Pruebas
   - Permite filtrar tareas por estado y fecha de vencimiento
   - Incluye pruebas unitarias para las rutas CRUD de tareas, cubriendo casos de éxito y error
   - Implementa la funcionalidad de filtrado en el método index() del controlador
   - Utiliza el sistema de pruebas unitarias de Laravel para validar el comportamiento de la API
   - El proyecto tiene como objetivo demostrar las habilidades del desarrollador en el uso de Laravel para construir una API segura y testeable, siguiendo las mejores prácticas y directrices.

## Instalación

Nota: Para nuestra aplicación, es necesario tener PHP en versiones 8.1 o superiores, Composer versión 2.7.2 y XAMPP versión 3.3.0 o superior.

La versión estable actual de PHP 8.3.8 se puede descargar desde el sitio web oficial de PHP en https://www.php.net/downloads.php. Las versiones están etiquetadas y firmadas en el Repositorio Git de PHP, y las claves GnuPG oficiales del actual Administrador de Lanzamientos de PHP se pueden usar para verificar las etiquetas.

La versión 2.7.7 de Composer se puede descargar desde el sitio web oficial de Composer en https://getcomposer.org/download/. El instalador proporciona varias opciones como --install-dir, --filename, --version y --preview para personalizar la instalación. Composer también ofrece diferentes canales de descarga para seleccionar rangos de versiones específicos.

La versión 3.3.0 o superior de XAMPP se puede descargar desde el sitio web oficial de XAMPP en https://www.apachefriends.org/es/download.html. XAMPP es una solución de pila de servidor web multiplataforma, gratuita y de código abierto desarrollada por Apache Friends, que incluye el servidor HTTP Apache, la base de datos MariaDB e intérpretes para scripts escritos en los lenguajes de programación PHP y Perl.

Si ya tienes instaladas estas versiones necesarias, puedes omitir esta nota. De lo contrario, por favor visita los enlaces proporcionados para descargar e instalar el software necesario.

1. Clonamos el repositorio:
```sh
git clone https://github.com/stiv120/test-backend
```
2. Accedemos al directorio donde lo descargamos:
```sh
cd test-backend
```
3. Luego utilizamos el siguiente comando:
```sh
composer install
```
4. Ejecutamos las migraciones usando el siguiente comando:
```sh
php artisan migrate
```

## Iniciar la aplicación

Primero debemos ejecutar nuestro servidor Apache de XAMPP y la base de datos MySQL.

Luego ejecutamos el siguiente comando:
```sh
php artisan serve
```
Esto iniciará el servidor, con todos los servicios necesarios para ejecutar nuestra aplicación, incluyendo el servidor al cual accederemos a través de este enlace: http://127.0.0.1:8000 para ver la aplicación.

## Acceder a las APIs

Nota: En mi caso, utilicé Postman para probar las APIs, si no lo tienes instalado aquí está el enlace:
https://www.postman.com/downloads/

Registro de Usuario: Introducimos los datos requeridos para el registro de usuario (nombre, correo electrónico y contraseña).
Ruta de acceso: http://localhost/register método POST

Inicio de Sesión: Si el usuario se creó correctamente, introducimos las credenciales de acceso.
Ruta de acceso: http://localhost/login método POST

Nota: Al iniciar sesión, devolverá el token de acceso (access_token), que necesitaremos añadir al encabezado de cada solicitud de tarea, dado que hemos implementado el sistema de autenticación JWT y las rutas de tarea están protegidas por un middleware que verifica si el usuario está autenticado y si el token es válido, además de otras validaciones.
La configuración sería la siguiente:
```sh
key: Authorization
value: Bearer token
```
Reemplazamos la palabra "token" con nuestro token de acceso generado.

3. Crear Tarea: Introducimos los datos requeridos en el cuerpo de la solicitud (título, descripción, estado, fecha de vencimiento).
Ruta de acceso: http://localhost/tasks método POST

4. Obtener Tareas: http://localhost/tasks método GET

5. Obtener Tareas filtradas por estado y fecha de vencimiento: http://localhost/tasks?status=pending&due_date=2023-06-30 método GET

6. Mostrar Tarea: http://localhost/tasks/{id} método GET

7. Actualizar Tarea: Introducimos los datos que queremos actualizar. Ruta de acceso: http://localhost/tasks/{id} método PUT

8. Eliminar Tarea: http://localhost/tasks/{id} método DELETE

## Tests

1. Ejecutamos el siguiente comando:
```sh
php artisan test
```
Esto ejecuta el observador de pruebas en modo interactivo.

## Acceder a phpMyAdmin
Accedemos a través del siguiente enlace: http://localhost/phpmyadmin/
Esto cargará el administrador de nuestra base de datos.
