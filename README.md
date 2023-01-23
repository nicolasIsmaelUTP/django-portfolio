# django-portfolio
Este es un proyecto de un portafolio web construido con Django. Incluye funcionalidades como la creación de entradas de blog, manejo de imágenes y visualización de trabajos en portafolio.

## Requisitos
Para poder utilizar este proyecto, es necesario tener instalado Python y Django en tu sistema. Una vez clonado o descargado el repositorio, debes ejecutar el siguiente comando en la raíz del proyecto:
```
pip install -r requirements.txt
```
Este comando instalará las dependencias necesarias para el funcionamiento del proyecto.

Una vez hecho esto, debes crear un archivo .env en la raíz del proyecto y especificar las variables de entorno necesarias para la configuración del proyecto, como la clave secreta de Django, la configuración de la base de datos, entre otras.

## Ejecutar el proyecto
Para ejecutar el proyecto en un servidor de desarrollo, debes utilizar el siguiente comando:
```
python manage.py runserver
```
Ahora ya podrás acceder a la aplicación en tu navegador utilizando la URL http://localhost:8000/

Para poder utilizar las funcionalidades de blog y portafolio, debes ejecutar las siguientes tareas de migración:
```
python manage.py makemigrations
python manage.py migrate
```
## Personalización
Este proyecto esta diseñado para servir como una base para aquellos que buscan construir su propio portafolio o sitio web personal con Django. El código esta comentado y estructurado para que sea fácil de entender y personalizar. Si tienes alguna duda o sugerencia, no dudes en abrir un issue en el repositorio.

## Agradecimientos
¡Gracias por usar este proyecto!