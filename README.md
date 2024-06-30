# python-final
Actividad clase 11
Hoy vamos a hacer actividad en Python en un día como programadores:
1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window
2. Creamos una carpeta o directorio: 
**mkdir python-final**
3. Entramos en ella: 
**cd python-final**
4. Iniciamos el repositorio:
**git init**
5. Creamos un archivo:
**touch finales.py**
6. Abrimos VSC:
**code .**
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
**python -V**
**python3 -V**
8. Creamos el entorno virtual en Python:
**python3 -m venv venv**  #Creamos el entorno virtual
9. Activamos el entorno virtual:
**source venv/bin/activate** #Activamos el entorno virtual en Linux
**venv/scripts/activate** #En windows
10. Hacemos actualización del pip de Python
**python -m pip install --upgrade pip** #Actualizamos el pip
11. Investigar ¿Qué es el pip y porque lo actualizamos?
12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
# Actividad del punto 11
Pip es una herramienta de gestión de paquetes en Python, utilizada para instalar y administrar bibliotecas y dependencias que no están incluidas en la biblioteca estándar de Python. El término "pip" es un acrónimo recursivo que significa "Pip Installs Packages".

Funciones principales de pip:
Instalación de paquetes: Puedes instalar bibliotecas desde el Índice de Paquetes de Python (PyPI) y otras fuentes.

código:

pip install nombre_paquete
Actualización de paquetes: Puedes actualizar los paquetes instalados a sus versiones más recientes.

código:

pip install --upgrade nombre_paquete
Desinstalación de paquetes: Puedes eliminar paquetes que ya no necesitas.

código:
pip uninstall nombre_paquete

Listar paquetes instalados: Puedes ver un listado de todos los paquetes instalados y sus versiones.

código:
pip list

Gestión de dependencias: Pip puede gestionar las dependencias de los paquetes, instalando automáticamente cualquier biblioteca necesaria para los paquetes que estás instalando.

¿Por qué actualizar pip?
Seguridad: Las versiones más recientes de pip pueden incluir parches de seguridad que corrigen vulnerabilidades descubiertas en versiones anteriores.
Nuevas funcionalidades: Las actualizaciones de pip pueden traer nuevas características y mejoras que hacen que la herramienta sea más fácil de usar o más eficiente.
Corrección de errores: Las nuevas versiones de pip corrigen errores que pueden haber estado presentes en versiones anteriores, mejorando la estabilidad y el rendimiento.
Compatibilidad: Mantener pip actualizado asegura que sea compatible con las versiones más recientes de Python y con los paquetes que estás utilizando.
Para actualizar pip a la versión más reciente, puedes utilizar el siguiente comando:

código:
pip install --upgrade pip

Este comando descarga e instala la versión más reciente de pip desde PyPI. Es recomendable mantener pip actualizado para beneficiarte de las últimas mejoras y mantener tu entorno de desarrollo seguro y eficiente.

