# Grupo 16

Este es el repositorio del *Grupo 16*, cuyos integrantes son:
* Elson Navarrete - 202273582-1
* María Silva - 202004684-0
* Fernando Xais - 202273551-1
* Gabriela Yáñez - 202273511-2
* **Tutor**: Alex Urrutia

## Wiki

Puede acceder a la Wiki mediante el siguiente [enlace](https://github.com/Gaby20785/Grupo16-INF225/wiki)

## Videos

* [Video presentación cliente](https://www.youtube.com/watch?v=abJau21SDIk)
* [Video prototipo](https://youtu.be/uakP8lTkoxk)
* [Video presentación final proyecto](https://youtu.be/biPBmX9duXE?si=PDzDYRDL1AYbFLQ4)

## Aclaraciones

- Se continuará con este proyecto del semestre 2024-2 en el curso de Ingenieria de Software 2025-1.

## Aspectos ténicos:
-Para la ejecución del código es necesario el uso de Xampp con Apache y MySQL (https://www.apachefriends.org/es/download.html)

-Para su creación se hizo uso de Visual Studio Code (https://code.visualstudio.com/Download) mediante el uso de complemementos de php. Incluye además el uso de Xampp (se recomienda ver tutoriales para su correcto funcionamiento)

**Instrucciones:**

  1- Tener instalado Xampp con Apache y MySQL (Xampp permite la descarga de Apache y MySQL dentro de él) (asegurar mismas versiones que las utilizadas para los archivos siguientes), caso contrario, debe instalarlo asegurando seguir un tutorial para su correcta instalación (verifique permisos del usuario y path) (https://youtu.be/TlrEvfbGTJ4?si=oPLV4z0CCkWrslIC recomendación)
  
  2- Descargar archivos del tag "Hito-3"
  
  3- Descomprimir el archivo "Grupo16-INF225-Hito-3"
  
  4- Llevar **los archivos descomprimidos de "proyecto2025-hito3.zip"** a htdocs en Xampp (se recomienda borrar los archivos presentes en htdocs, a menos que sea un proyecto en carpeta) (se deja el código del avance anterior 'proyecto.zip' en caso de necesitarlo)

  5- Instalar las dependencias para python: mysql-connector-python, requests, beautifulsoup4
	    Para esto basta con escribir en la consola:
		    pip install mysql-connector-python
		    pip install requests
		    pip install beautifulsoup4
  
  5- Abrir el panel de control de Xampp e iniciar Apache y MySQL

  6- Abrir PhpMyAdmin de MySQL y crear una nueva base de datos llamada 'boletines', seleccionar la base de datos e importar el archivo 'boletines.sql'
  
  7- Abrir "http://localhost/proyecto2025-hito2/proyecto/init.html" con google u otro navegador

  7.1- Cuando se ingrese a la sección de parámetros y fuentes, se pueden agregar una de estas dos fuentes (o ambas), para recopilar noticias y/o productos en sus respectivas tablas en la base de datos:
	  https://www.agritechfuture.com/
	  https://www.agritechtomorrow.com/products.php

Siguiendo estas instrucciones podrá utilizar los archivos presentes de manera correcta

**IMPORTANTE:** 
- Xampp control versión 3.3.0
- Apache HTTP versión 2.4.58
- PHP versión 8.2.12
- MySQL versión 10.4.32.0
- Versión del servidor: 10.4.32-MariaDB
- **Creación en Windows**
- **Guarde en htdocs de la forma: proyecto2025-hito3/proyecto/...**
  
**NOTAS:** 
- Dentro hay una carpeta 'config' con un archivo 'config.php' que tiene el host, usuario y contraseña por defecto para ingresar a la base de datos si tienen un puerto, usuario o contraseña en especifico deben cambiar esos apartados, y también deben cambiarlos en el archivo scrape.py.
- Sólo hay 6 productos en la segunda página, en la página de noticias hay muchas pero solo dejé las primeras 20 para que no tarde demasiado.
- Para probar funcionamiento, solo se tienen tres usuarios de prueba; email: admin@admin.cl password: adminpass   , email: user@gmail.com password: userpass   , email: especialista@especialista.cl password: especialista123
- Se tienen 5 boletines para buscar; "El cultivo del pepino dulce", "Boletín de vitivinicultura para la zona de mesoclima de la Patagonia occidental de la Región de Aysén", "Manual del maestro quesero", "Recetario Charcutería Cerdo Avellanero de Lumaco" y "Estrategia de Innovación y Desarrollo Agrícola para la Región de Tarapacá"
- Para el ingreso de parámetros para crear boletines se sugieren dos combinaciones; palabras clave: "agua" y/o "hidricos"  fuente: www.wikipedia.cl,  palabras clave: "climatico" y/o "mitiga"  fuente: www.wikipedia.cl
            

