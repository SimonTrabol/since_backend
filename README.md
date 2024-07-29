## INSTALACION


# paso 1
- Crear el entorno virtual
- $ python -m venv venv
# paso 2
- Activar el entorno virtual
- $ .\venv\Scripts\Activate
# paso 3
- Instalar dependencias del entorno virtual
- $ pip install -r requirements

## MIGRACION

# paso 1
- Correr migracion para crear usuario admin
- $ python manage.py migrate
# paso 2
- Crear usuario admin
- $ python manage.py createsuperuser
- Ingresar valor:
   - usuario:admin
   - email:sin data
   - contraeña:admin

## INICAR EL PROYECTO
# paso 1
- Ir a la ruta principal del proyecto
- $ cd blog_project
# paso 2
- Correr el servidor en el puerto web 8000
- $ python manage.py runserver 0.0.0.0:8000

# paso 3 
ir a la pagina de admin http:0.0.0.0:8000/admin
ingresar usuario y password admin
