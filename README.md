# Banco-MVC
# Instalación:
Paso 1. Crear archivo .env con base al archivo ejemplo .env.example para poder cargar la configuración de la base de datos.
$ cp .env.example .env
# Paso 2. Instalar dependencias.
$ pip install -r requirements.txt
# Paso 3. Aplicar migraciones.
$ python manage.py makemigrations
$ python manage.py migrate
