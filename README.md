________________________________________
Guía para Desplegar un Proyecto en XAMPP y Configurar una Base de Datos en MySQL
→ Descargar XAMPP ←
________________________________________
Paso 1: Preparar el Entorno de Trabajo en XAMPP:

1.1 Localizar la carpeta htdocs
•	Una vez descargado e instalado XAMPP, busca la carpeta de instalación, que normalmente se encuentra en C:\xampp.
•	Dentro de esta carpeta, abre la subcarpeta htdocs.

1.2 Pegar el proyecto en htdocs
•	Copia la carpeta de tu proyecto descargada de GitHub y pégala en htdocs.
•	Ejemplo: Si tu proyecto se llama "MiProyecto", la ruta completa será C:\xampp\htdocs\MiProyecto.


________________________________________
Paso 2: Iniciar XAMPP y Acceder al Proyecto:

2.1 Iniciar los servicios de XAMPP
•	Abre la aplicación de XAMPP.
•	Haz clic en Start al lado de Apache para activar el servidor web.
•	Haz clic en Start al lado de MySQL para activar el servidor de base de datos.

2.2 Acceder al proyecto en tu navegador
•	Abre tu navegador y escribe:
text
Copiar código
http://localhost/MiProyecto
Esto te permitirá ver tu proyecto en funcionamiento.


________________________________________
Paso 3: Configurar la Base de Datos en MySQL:

3.1 Acceder a phpMyAdmin
•	Con MySQL activo, haz clic en el botón Admin junto a MySQL en XAMPP. Esto abrirá phpMyAdmin en tu navegador.

3.2 Crear la base de datos
•	En phpMyAdmin, haz clic en Nueva en la barra lateral izquierda.
•	Introduce el nombre de la base de datos (por ejemplo, artemus) y haz clic en Crear.
•	Nota: No es necesario modificar el segundo campo.

3.3 Importar el archivo SQL
•	Una vez creada la base de datos, haz clic en la pestaña Importar.
•	Selecciona el archivo .sql de tu base de datos en la opción Archivo a importar.
•	Desplázate hacia abajo y haz clic en Importar para cargar el archivo.


________________________________________
Done by *AVK*
