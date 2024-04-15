
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **¿Que es?:** CRUD es el acrónimo de Create (Crear), Read (Leer), Update (Actualizar) y Delete (Borrar). Este concepto se utiliza para describir las cuatro operaciones básicas que pueden realizarse en la mayoría de las bases de datos y sistemas de gestión de información.
- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Adaptacion a Usuarios

![image](https://github.com/PFLC/624-crus-basicos-ZaidSantos/assets/114132407/4f1235e9-735a-406e-a483-3fece62dc20c)

Las operaciones se adaptan a las necesidades de los sistemas y de los usuarios, pueden usarse para gestionar bases de datos o para aplicaciones. Otra característica de las primeras es que presentan los datos orientados a los objetos, y que para desarrollarse utilizan capas de persistencia que se encuentran dentro de módulos de framework.

La aplicación del CRUD varía según el tipo de usuario que pueda acceder al programa de desarrollo. La forma de ejecución de las cuatro acciones por parte del usuario, dependiendo del permiso de modificación que tenga, conforma lo que se llama ciclo de CRUD.

El CRUD permite, por lo tanto, reunir las operaciones básicas en un solo elemento, lograr que el cliente entienda más fácilmente cómo funciona el sistema, así como reutilizar el código y especificar los casos de uso sin demandar mucho tiempo ni esfuerzo.

## Ventajas y desventajas del CRUD

![image](https://github.com/PFLC/624-crus-basicos-ZaidSantos/assets/114132407/a548c78b-ebda-4446-b6a2-f7a6542f062f)

**Ventajas:**
- Facilita la creación y gestión de datos.
- Proporciona una estructura coherente y fácil de entender para su manipulación.
- Ayuda a minimizar los errores y garantiza la integridad de los datos.
- Proporciona una base sólida para el desarrollo de aplicaciones.

**Desventajas:**
- Puede ser demasiado simplista para aplicaciones complejas.
- En ocasiones, es menos eficiente para aplicaciones de alta velocidad o de gran escala.
-A veces, requiere una gran cantidad de código y configuración para implementarlo completamente.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

