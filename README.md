# IA-Medica-Remota-
1. En primer lugar se debe clonar el repositorio o en caso tal descargarlo y abrirlo con ayuda de Visual Studio Code
2. En segundo lugar una vez en el proyecto debemos abrir la terminal de Visual, ya sea en el Powershell o en el CMD con ayuda de "CTRL + Ñ"
3. Luego una vez abierta la terminal ejecutar el comando "python -m venv venv" esto para poder instalar nuestro entorno virtual
4. Siguiente ".\venv\Scripts\activate" poner este comando una vez se instale el entorno, este siguiente codigo es para activarlo y poder trabajar en este mismo
5. Una vez activado nos aparecera "(venv).\ruta\del\archivo"
6. Para ejecutar el codigo primero deberemos instalar los requerimientos o librerias que necesitaremos para esto usaremos el codigo "pip install -r requirements.txt" en la misma terminal en el entorno virtual
7. Una vez haya terminado de instalar todas las librerias ejecutaremos el programa con ayuda de "uvicorn main:app  --reload" esto nos ejectura el proyecto y nos dara una URL tipo Local Host la cual usaremos para abrir el proyecto en el navegador
8. Para hacer uso de este anteriormente se debe tener instalado y ejecutado el ollama se recomienda la version 0.1.30, ya despues de esto se podra usar la IA medica ya sea por comando de voz o por texto, esta se tardara cierto tiempo mientras se carga toda la respuesta de la IA, sin embargo la dara y la camara se activara de una vez ejecutado el programa para una mejor interacción.
9. 
