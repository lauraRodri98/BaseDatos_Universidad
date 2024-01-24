<h1 align="center">Base de Datos Universidad</h1>
<div align="center">![base-datosPHP](https://github.com/lauraRodri98/BaseDatos_Universidad/assets/131816452/5fbd3ad3-fa36-4091-b078-77ad0b94236b)
</div>

Para descargar y usar la base de datos con XAMPP, puedes seguir los siguientes pasos. Aquí asumiremos que ya tienes instalado XAMPP en tu sistema.

<h4>Paso 1: Descargar el Proyecto desde GitHub</h4>
Dirígete al repositorio en GitHub donde se encuentra el proyecto de la base de datos.
Haz clic en el botón "Code" y selecciona la opción de "Download ZIP".
Descomprime el archivo ZIP descargado en una ubicación de tu elección.

<h4>Paso 2: Configurar XAMPP y Mover Archivos</h4>
Asegúrate de tener XAMPP instalado en tu sistema. Puedes descargarlo desde el sitio oficial de XAMPP.
Abre la carpeta donde tienes instalado XAMPP y busca la carpeta htdocs. Este es el directorio raíz donde debes colocar tus proyectos web.

<h4>Paso 3: Mover el Proyecto a la Carpeta htdocs</h4>
Copia la carpeta del proyecto descomprimido y pégalas dentro de la carpeta htdocs de XAMPP. Por ejemplo, podrías tener una estructura como xampp/htdocs/universidad-proyecto.

<h4>Paso 4: Configurar la Base de Datos</h4>
Inicia el panel de control de XAMPP y asegúrate de que los servicios de Apache y MySQL estén activos.
Abre tu navegador web y visita http://localhost/phpmyadmin/ para acceder a la interfaz de administración de MySQL.

<h4>Paso 5: Importar la Base de Datos</h4>
En phpMyAdmin, crea una nueva base de datos con el nombre que desees, por ejemplo, universidad_db.
Selecciona la base de datos recién creada y haz clic en la pestaña "Importar".
Haz clic en "Seleccionar archivo" y elige el archivo SQL que viene con el proyecto (por ejemplo, universidad_db.sql).
Haz clic en "Continuar" para importar la estructura y datos a la base de datos.

<h4>Paso 6: Configurar la Conexión a la Base de Datos en PHP</h4>
Abre el código PHP que se conecta a la base de datos (por ejemplo, el archivo de conexión conexion.php).
Asegúrate de que las credenciales de la base de datos (nombre de usuario, contraseña, nombre de la base de datos) coincidan con tu configuración local de XAMPP.

<h4>Paso 7: Ejecutar la Aplicación</h4>
Abre tu navegador web y visita http://localhost/universidad-proyecto (ajusta la URL según la estructura de tu proyecto).
Si todo está configurado correctamente, deberías poder ver y utilizar la aplicación web que utiliza la base de datos.
