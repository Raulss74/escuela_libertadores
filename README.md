# Sistema Escolar - Libertadores

Sistema web básico para administrar alumnos de la escuela secundaria "Libertadores", usando:
- MySQL
- PHP
- HTML/CSS/JavaScript
- XAMPP (en entorno local)

## Funcionalidades
- Registro de nuevos alumnos  
- Consulta y filtrado por grado/grupo/turno  
- Edición de datos  
- Eliminación lógica (estatus activo/inactivo)

## Estructura de BD
Ver `db.sql` para crear la base de datos y tabla necesaria.

## Instalación
1. Clona el repositorio
2. Copia la carpeta en `/htdocs/libertadores`
3. Crea la base de datos desde phpMyAdmin
4. Importa `db.sql`
5. Configura `.env` con tus credenciales de MySQL
6. Inicia Apache y MySQL en XAMPP