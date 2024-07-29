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
-ir a la pagina de admin http:0.0.0.0:8000/admin
-ingresar usuario y password admin

## ENDPOINTS
# Metodos posts
- url:http://localhost:8000/api/posts/
- Crear nuevo posts
- ![image](https://github.com/user-attachments/assets/8fc4d12c-a5db-4a71-82ff-c37c3ad61f92)
# Metodos Get
- url:http://localhost:8000/api/posts/
- Obtener listado de posts
- ![image](https://github.com/user-attachments/assets/6cb0ca2f-3e48-4a43-84b3-517292865735)
- Obtener posts por id
- url:http://localhost:8000/api/posts/1
- ![image](https://github.com/user-attachments/assets/0a1f935f-d760-417d-a3a3-a22e12c7b343)



