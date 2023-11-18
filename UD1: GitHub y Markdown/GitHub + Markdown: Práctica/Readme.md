# **GitHub + Markdown: Práctica**
### Por: _Enrique Gallén Roda_

## **Introducción:**
GitHub es una plataforma de desarrollo colaborativo que facilita el alojamiento de proyectos de software y proporciona herramientas para el control de versiones, seguimiento de problemas, y colaboración entre desarrolladores.

En este texto, se detallan paso a paso las acciones necesarias para comenzar a utilizar GitHub y Git en el desarrollo de software. Desde la creación de una cuenta en GitHub hasta la instalación de Git en un entorno Linux, el texto proporciona instrucciones claras para realizar cada tarea. Se destaca la creación de un archivo en C como ejemplo práctico y se explican los comandos esenciales de Git, como `git add`, `git commit` y `git push`.

En las conclusiones, se resalta la importancia de comprender y utilizar estos comandos clave, así como la necesidad de configurar un repositorio en GitHub y generar un token de acceso personal. 

## **Pasos a seguir para conseguir las diferentes acciones:**
En el texto proporcionado, se pueden identificar varias acciones relacionadas con el uso de GitHub y Git. Aquí hay una lista de las acciones específicas que se mencionan:

1. **Creación de una cuenta en GitHub:**
- Crear una cuenta en la página web de GitHub.

2. **Instalación de Git en Linux:**
- Abrir la terminal de Linux con `Ctrl+T`.
- Actualizar el sistema con el comando `$ sudo apt update`.
- Instalar Git con el comando `$ sudo apt install git`.

3. **Verificación de la versión de Git instalada:**
- Verificar la versión de Git instalada con el comando `$ git --version`.

4. **Creación de un archivo en C:**
- Crear un directorio llamado "pruebaGitHub" con el comando `$ mkdir pruebaGitHub`.
- Moverse al directorio con el comando `$ cd pruebaGitHub`.
- Crear un archivo llamado "prueba.c" con el comando `$ touch prueba.c`.
- Abrir el archivo en un editor de texto (en este caso, Gedit) con `$ gedit prueba.c`.

5. **Contenido del archivo "prueba.c":**
- Escribir el contenido del programa en el archivo "prueba.c".

6. **Configuración de Git en local:**
 - Configurar el correo electrónico de usuario con `$ git config --global user.email "<miCorreoElectrónicoEnGitHub>"`.
 - Configurar el nombre de usuario con `$ git config --global user.name "<miNombreEnGitHub>"`.

7. **Iniciar un nuevo repositorio local:**
- Iniciar un nuevo repositorio Git en el directorio actual con `$ git init`.

8. **Añadir archivos al área de preparación:**
- Agregar todos los archivos al área de preparación con `$ git add .`.

9. **Realizar un commit:**
- Realizar un commit con el mensaje "Subida del archivo de prueba" usando `$ git commit -m "Subida del archivo de prueba"`.

10. **Subir el repositorio a GitHub:**
- Subir el repositorio al servidor de GitHub con `$ git push`.

11. **Generar un token de acceso personal en GitHub:**
- Obtener un token en la sección "Developer Settings" de la configuración de la cuenta en GitHub.
- Acceder a "GitHub --> Settings de la cuenta --> Developer Settings --> Personal access tokens --> Generate new token".

12. **Verificar que el archivo se ha subido correctamente:**
- Comprobar en la página web de GitHub que el archivo se ha subido correctamente.

13. **Investigar los comandos Git utilizados:**
- Investigar y comprender los comandos Git utilizados en el proceso.
- Comandos a investigar: `git init`, `git add .`, `git commit -m "String"`, `git push`.

## Conclusiones
En la introducción a Github,  nos están mostrando cómo dar los primeros pasos en GitHub y Git para el desarrollo de software. Empezamos creandonos una cuenta en GitHub, seguido de los pasos para instalar Git en Linux. Nos enseñan un ejemplo práctico de creación de un archivo en C y se detallan los comandos fundamentales de Git, desde la configuración local hasta la creación de un repositorio en GitHub y la realización de commits.

El documento se centra en la importancia de comprender y utilizar comandos clave como `git init`, `git add`, `git commit`, y `git push`. Además, destaca la necesidad de generar un token de acceso personal en GitHub para ciertas operaciones. En resumen, nos proporciona una introducción paso a paso del uso básico de GitHub y Git, destacando la importancia de la configuración inicial y la gestión de archivos.
