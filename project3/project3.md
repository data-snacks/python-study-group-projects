# Enunciado del Proyecto
Este proyecto está diseñado para que los participantes aprendan a realizar tareas básicas de web scraping y manejo de archivos en Python. El objetivo es descargar el contenido de múltiples páginas web desde el sitio de Infoleg y guardar cada página como un archivo de texto, lo cual puede ser útil para análisis de texto posterior o simplemente para archivar contenido.

# Objetivos del Proyecto
- Utilizar Python para descargar el contenido HTML de varias páginas web enumeradas.
- Guardar el contenido de cada página web en un archivo de texto plano.
- Organizar los archivos de manera eficiente para facilitar el acceso y la referencia futura.

# Pasos del Proyecto
## Paso 1: Preparar la Lista de URLs
Primero, necesitas tener una lista de URLs que quieres descargar (tomando como base la página: infoleg.com.ar). Esta lista puede estar codificada directamente en el script o puede ser leída desde un archivo externo.

## Paso 2: Descargar el Contenido de las Páginas
Para descargar el contenido de las páginas, utilizaremos la biblioteca requests. Aquí está el código para descargar una página y guardar su contenido en un archivo de texto

## Paso 3: Verificación y Mantenimiento
Una vez que los scripts están corriendo y los archivos están siendo guardados, es importante verificar que los datos se están capturando correctamente. Revisa algunos de los archivos para asegurarte de que el contenido es el esperado y no hay errores como páginas no encontradas o captchas que bloquean la descarga.

# Conclusión
Este proyecto básico de web scraping y manejo de archivos te proporcionará una introducción práctica a técnicas útiles en Python que pueden ser aplicadas en una variedad de tareas de automatización de datos y recopilación de información. A medida que te familiarices con estas operaciones, podrás explorar bibliotecas más avanzadas para scraping como BeautifulSoup o Scrapy para proyectos más complejos.