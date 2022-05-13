<p align="center"><a href="https://redcapital.cl" target="_blank"><img src="https://www.paymentmedia.com/gallery/59b6ecdbce3a4red_capita_dfgfgf_623.jpg" width="400"></a></p>

Proyecto desarrollado por [Nector Cortés R.](https://github.com/nector95/) para la solución de la prueba técnica [Red Capital CL](https://redcapital.cl).

## INTRODUCCIÓN

El propósito de la siguiente evaluación es validar el conocimiento específico y técnico
requerido para el cargo mencionado. Los conocimientos a evaluar son:    

- [Laravel 6+.](https://laravel.com).
- [PHP-UNIT.](https://www.php.net).
- [Eloquent.](https://laravel.com/docs/8.x/eloquent).
- [GIT.](https://github.com).
- [Docker | Docker-container.](https://www.docker.com).

## REQUERIMIENTOS

**1-** Crear un login de usuario, el cual permitirá identificar el usuario según su **ROL y PERMISOS**.

*Validaciones y/o reglas de negocio:*

● Utilizar buenas prácticas para mostrar errores ocurridos dentro del sistema.
● Se deberá crear un modelo que permita gestionar menú, sub-menú y vista para cualquier usuario del sistema, independiente de su rol, la cual mediante un middleware controlar el acceso de un usuario a la vista.
● Generar Seeders de carga inicial, con los menús y submenús

**2-** El usuario podrá subir documentos **PDF, XML, WORD, ETC.**, los cuales serán almacenados en Laravel, y que luego el usuario podrá revisar históricamente todos los archivos que están asociados a él y descargarlos.

*Validaciones y/o reglas de negocio:*

● Si un usuario administrador posee permisos para visitar esta vista, podrá revisar todo los archivos históricos.
● El usuario administrador podrá subir archivos y asociar a qué persona se creará el nuevo registro.
● Un usuario normal solo podrá ver sus archivos históricos.

## PLUS

- Utilizar algún cliente de git como Github, Gitlab o Bitbucket para visualizar el
proyecto.
● Crear un Readme para seguir los pasos para la ejecución de Seeders y migraciones.
● Crear imagen de Proyecto Laravel mediante un Dockerfile.
● Crear contenedor con el Proyecto Laravel y MySql 8.0.16 o superior a 8.
● Uso del Framework UI Bootstrap.
● Uso Eloquent o QueryBuilder.


