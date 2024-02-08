# Inventario Biblioteca
## Descripción:

Este repositorio contiene el código fuente para un sistema de gestión de inventario para una biblioteca. El sistema permite a los usuarios:

1. Registrar libros, autores, editoriales y categorías.
2. Agregar, modificar y eliminar libros del inventario.
3. Buscar libros por título, autor, editorial o categoría.
4. Prestar y devolver libros.
5. Generar informes sobre el inventario.

## Tecnologías:

1. Python
2. Django
3. Sqlite3

## Instalación:

1. Clonar el repositorio:
### git clone https://github.com/vcdanielj/inventario_biblioteca.git
2. Crear un archivo virtual:
### python3 -m venv venv
3. Activar el archivo virtual:
### source venv/bin/activate
4. Instalar las dependencias:
### pip install -r requirements.txt
5. Crear la base de datos:
### python manage.py makemigrations
### python manage.py migrate
6. Iniciar el servidor:
### python manage.py runserver

## Uso:

Acceder a la interfaz web en http://localhost:8000/.
Crear una cuenta de usuario para iniciar sesión.
Utilizar el menú para acceder a las diferentes funcionalidades del sistema.
Documentación:

## Contribuciones:

Se anima a la comunidad a contribuir al desarrollo del sistema. Para ello, se pueden enviar pull requests al repositorio principal.

## Licencia:

Este software se encuentra bajo la licencia MIT.