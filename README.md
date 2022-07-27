# Banco-MVC
# Instalación:
<h3>Paso 1. Crear archivo .env con base al archivo ejemplo .env.example para poder cargar la configuración de la base de datos.</h3>
$ cp .env.example .env
<h3> Paso 2. Instalar dependencias.</h3>
$ pip install -r requirements.txt
<h3> Paso 3. Aplicar migraciones.</h3>
$ python manage.py makemigrations
<br> $ python manage.py migrate
