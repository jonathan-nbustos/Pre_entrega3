# Preentrega 3 Comisión 56060

## Nombre

- Jonathan Bustos

## Resumen del proyecto

- Resumen, de que trata el proyecto:

## Pasos para ejecutar el proyecto

- Link de GitHub: https://github.com/jonathan-nbustos/Pre_entrega3

- Creación del entorno virtual: python -m venv .venv
- Activar el entorno virtual: .\.venv\Scripts\activate
- Instalar Django: pip install django 

- Crear archivo requirements: pip freeze >> requirements.txt
- Iniciar proyecto: django-admin startproject Proyecto.
- Colocar clave secreta.

- Crear aplicación: django-admin  startapp core (guardo en settings en aplicaciones creadas)

- Crear modelos y registrarlo en admin.py

- Utilizo python manage.py makemigrations
- Luego python manage.py migrate  

- Creo lo superusuarios: python manage.py createsuperuser

- Activo run server: python manage.py runserver
- Registrarlo en admin.

- Creo las vistas.
- Creo carpeta templates y core.

- Creo archivo base.html para heredar.
- Creo archivo index.html para heredar extends

- Crear botones.
- Crear funciones en vistas.
- Crear vista en la url de core
- Creo las funciones en views de core
 - Cuando cree profesor list, lo guardo en una instancia (consulta) luego lo paso como un contexto

- Crear el form.
- Colocar token sino da error.
- Agregar boton tipo submit.
- Crear el archivo form.py entro de core
- Dentro de vista, cargo/importo forms y creo la funcion
- Fin