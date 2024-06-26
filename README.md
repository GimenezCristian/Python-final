### Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio:

mkdir python-final
3. Entremos en ella:

cd python-final
4. Iniciamos el repositorio:

git init
5. Creamos un archivo:

touch finales.py
6. Abrimos VSC:

code .
7. En la terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V
8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual
9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y la respuesta del punto 11 de más arriba.

¿Que es el pip y porque lo actualizamos?

PIP es el gestor de paquetes de Python. Permite instalar, actualizar y gestionar bibliotecas y herramientas adicionales desde el repositorio de Python Package Index (PyPI).

Razones para actualizar PIP:
Compatibilidad: Asegura compatibilidad con las últimas versiones de Python y bibliotecas.
Seguridad: Incorpora parches de seguridad importantes.
Corrección de Errores: Soluciona errores presentes en versiones anteriores.
Nuevas Funcionalidades: Introduce mejoras y nuevas características.
