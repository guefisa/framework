# Zero
Zero es un pequeño framework PHP sobre el que se pueden construir sencillas aplicaciones web.
Fue creado con caracter general pero posteriormente se utilizó para desarrollar una aplicación web para una inmobiliaria por lo que incorpora algunos componentes para este proposito.

# Requerimientos
- PHP 5.2.10 +
- MySQL (Se puede adaptar a otro SGDB relacional con poco esfuerzo)

# Instalación
- git clone git://github.com/guefisa/zero.git
- crear una base de datos con las tablas incluidas en el archivo modelo_db.sql
- configurar el acceso a la base de datos en los archivos 'core/db_abstract.php' y 'administrator/core/db_abstract.php'
