# Mini Proyecto 1: Django Web Application

Este es el Mini Proyecto 1 desarrollado como parte del curso **Python y la Web** de Clase Ejecutiva UC. El proyecto consiste en una aplicación web básica creada con el framework Django, que incluye la estructura y diseño de una página web utilizando HTML y CSS.

## Desarrollador
**Raúl Rosales R.**  
Desarrollador web

## Requisitos del Proyecto
El proyecto pone en práctica los siguientes conocimientos:
- Inicialización de un proyecto utilizando **Django**.
- Creación de la estructura de una página web con **HTML**.
- Aplicación de estilos a la página con **CSS**.

## Instrucciones para la Ejecución

### 1. Clonar el repositorio:
```bash git clone https://github.com/usuario/mini-proyecto-django.git cd mini-proyecto-django ```

### 2. Crear un entorno virtual y activarlo:
```bash python -m venv venv source venv/bin/activate  # En Windows: venv\Scripts\activate ```

### 3. Instalar las dependencias:
```bash pip install -r requirements.txt```

### 4. Realizar las migraciones de la base de datos:
```bash python manage.py migrate```

### 5. Ejecutar el servidor de desarrollo:
```bash python manage.py runserver```

## Estructura del Proyecto
manage.py: Script para la gestión del proyecto.
settings.py: Archivo de configuración de Django.
urls.py: Definición de rutas de la aplicación.
templates/: Directorio que contiene los archivos HTML.
static/: Directorio que contiene los archivos CSS y otros estáticos.

## Notas Importantes
Asegúrese de seguir las instrucciones de formato y ejecución del proyecto. Los proyectos que no cumplan con los requisitos indicados serán calificados con la nota mínima, sin derecho a nueva entrega.
