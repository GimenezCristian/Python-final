# Actividad de Python: Configuración inicial y gestión de entorno

Este repositorio contiene los pasos iniciales y configuraciones necesarias para comenzar a trabajar en Python de manera organizada y efectiva.

## Pasos realizados

1. **Crear directorio y repositorio Git:**
   ```bash
   mkdir python-final
   cd python-final
   git init
Crear archivo Python:

bash
Copiar código
touch finales.py
Abrir Visual Studio Code:

bash
Copiar código
code .
Verificar la versión de Python:

bash
Copiar código
python -V
python3 -V
Crear y activar entorno virtual:

bash
Copiar código
python3 -m venv venv  # Crear entorno virtual
source venv/bin/activate  # Activar en Linux
venv\Scripts\activate  # Activar en Windows
Actualizar pip:

bash
Copiar código
python3 -m pip install --upgrade pip
¿Qué es pip y por qué lo actualizamos?
pip es un sistema de gestión de paquetes utilizado para instalar y administrar paquetes de software escritos en Python. Es fundamental mantenerlo actualizado para asegurarse de tener acceso a las últimas características y correcciones de seguridad en los paquetes Python.

Primer commit y repositorio remoto
Realiza tu primer commit para este trabajo inicial y enlázalo con un repositorio remoto. Asegúrate de incluir en tu README.md los detalles de todos los comandos ejecutados y la respuesta a la siguiente pregunta:

¿Qué es pip y por qué lo actualizamos?
