--> Link para descargar XAMPP : https://www.apachefriends.org/es/index.html <--

Guía para Desplegar un Proyecto en XAMPP y Configurar una Base de Datos en MySQL

_________________________________________________________________________________________________________________________________________________________________________________
- Paso 1: Preparar el Entorno de Trabajo en XAMPP
Localizar la carpeta htdocs:

Una vez descargado e instalado XAMPP, busca la carpeta de instalación, que normalmente está en C:\xampp.
Dentro de esta carpeta, abre htdocs.
Pegar el proyecto en htdocs:
Copia la carpeta de tu proyecto descargada de GitHub y pégala en htdocs. Por ejemplo, si tu proyecto se llama "MiProyecto", la ruta será C:\xampp\htdocs\MiProyecto.

_________________________________________________________________________________________________________________________________________________________________________________
- Paso 2: Iniciar XAMPP y Acceder al Proyecto
Iniciar los servicios de XAMPP:

Abre la aplicación de XAMPP.
Haz clic en Start al lado de Apache para activar el servidor web.
Haz clic en Start al lado de MySQL para activar el servidor de base de datos.
Acceder al proyecto en tu navegador:

Abre tu navegador y escribe http://localhost/"MiProyecto" para ver tu proyecto en funcionamiento.


_________________________________________________________________________________________________________________________________________________________________________________
- Paso 3: Configurar la Base de Datos en MySQL
Acceder a phpMyAdmin:

En XAMPP, con MySQL activo, haz clic en el botón Admin junto a MySQL. Esto abrirá phpMyAdmin en tu navegador.
Crear la base de datos:

En phpMyAdmin, haz clic en Nueva en la barra lateral izquierda.
Introduce el nombre de tu base de datos (por ejemplo, artemus) y haz clic en Crear. No es necesario cambiar nada en el segundo campo.

Para importar el archivo SQL:
Una vez creada la base de datos, haz clic en la pestaña Importar.
Selecciona el archivo .sql desde tu explorador de archivos en la opción Archivo a importar.
Haz clic en Importar al final de la página.

Done by AVK
