# iaw-proyecto-php
Proyecto final PHP

> IES Celia Viñas (Almería) - Curso 2020/2021
Módulo: IAW - Implantación de Aplicaciones Web
Ciclo: CFGS Administración de Sistemas Informáticos en Red

**Introducción**
------------
Esta práctica consiste en un sistema muy básico para añadir, editar, borrar y ver registros de una base de datos, haciendo uso de PHP y MySQL. De hecho, se le conoce como CRUD (Create, Read, Update, Delete)

Se pueden realizar pruebas en: 
http://3.80.58.96/

**Líneas y términos de interés**
------------
- CRUD: Create, Read, Update, Delete. Un sistema sencillo para trabajar registros de base de datos.
- MySQLi: controlador de base de datos usado en php. Aparece en numerosos comandos a lo largo de la práctica.
- $stmt: 'statement' es una variable de propósito general, como puede serlo 'foo' o 'bar'. Usado en con MySQLi en diversas líneas.
- jumbotron: Aparece en un <div> y es una caja grande para llamar la atención sobre aquello a lo que rodea. https://www.w3schools.com/bootstrap/bootstrap_jumbotron_header.asp
- fetch: En la práctica, 'tomar' datos.
- $res: Variable utilizada para simplificar variables de resultado más complejas, agilizando el proceso y minimizando los fallos.

**Archivos en el repositorio**
------------
1. **README**               Documentación.
2. **docker.sh**            Ejecutable de docker+arrancar contenedores
3. **docker-compose.yml**   Organizador contenedores docker.
3. **/src**                 Directorio con la estructura php empleada
4. **/db**                  Directorio de script para montar la base de datos "users"
5. **/apache**              Dockerfile para Apache. Se respeta al autor original.            


**Referencias**
------------
- Guía original para la práctica.
https://josejuansanchez.org/iaw/proyecto-php/index.html
- Basado en el siguiente repositorio:
https://github.com/chapagain/crud-php-simple
- Guía paso a paso para principiantes sobre CRUD (Inglés)
http://blog.chapagain.com.np/very-simple-add-edit-delete-view-in-php-mysql/


**Editor Markdown**
------------
- Markdown editor. Alternativamente, investigar atajos de teclado como Ctrl+B= bold (negrita) 
https://markdown-editor.github.io/