# tercera_pre-entrega_rizzi

## Tercera pre-entrega del curso Python de Coderhouse.

Es un proyecto Django de ejemplo que muestra cómo crear una aplicación web básica. Aplicando el concepto de herencia de HTML y formularios para insertar datos en todas las clases de models.

## Instalación y ejecución

Sigue estos pasos para instalar el proyecto en tu máquina local:

1. Clone este repositorio en su máquina local usando el comando `git clone https://github.com/MiguelRizzi/tercera_pre-entrega_rizzi.git`.

2. Si usa Visual Studio Code, abra el archivo `requirements.txt` y haga clic en Crear ambiente, luego elegir Venv y el intérprete Python, y finalmente pregunta por las dependencias: elegimos `requirements.txt`. Esto creara el entorno virtual e intalara todas las librerias necesarias para ejecutar el proyecto.

Si prefiere instalarlo de manera manual, use el comando `python -m venv .venv`. Esto creará una carpeta llamada `.venv` dentro del directorio del proyecto.
Active el entorno virtual usando el comando `source .venv/bin/activate` en Linux o Mac, o `.venv\Scripts\activate` en Windows.
Instale las dependencias del proyecto usando el comando `pip install -r requirements.txt`. 

3. Ejecute las migraciones de la base de datos usando el comando `python manage.py migrate`. Esto creará las tablas necesarias en la base de datos.


4. Para ejecutar el servidor de desarrollo, muevase hasta el directorio del proyecto usando el comando `cd project` y use el comando `python manage.py runserver`. Esto iniciará el servidor en el puerto 8000 de tu máquina local. Abre tu navegador y navega a `http://localhost:8000` para ver la aplicación en acción.

5. Si quieres detener el servidor, simplemente presiona `CTRL + C` en la consola donde está ejecutándose.

