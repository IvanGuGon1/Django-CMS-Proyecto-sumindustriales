# Django-CMS-Proyecto-sumindustriales
Version en construcción de la web creada para el proyecto de ASIR Sumindustriales, utilizando Django-CMS y adaptado la plantilla de bootstrap modern business.

# Instalacion en local
## Instalacion Python 2.7, el gestor de dependencias pip y la herramienta de entornos virtuales virtualenv en linux y git
- Instalaciones previas
sudo apt-get update && sudo apt-get -y upgrade \n
sudo apt-get install python-pip \n
pip install virtualenv \n
sudo apt-get install git \n

# Instalacion djangocms

- Creamos el entorno virtual y repositorio local git.
$ mkdir proyecto
$ cd proyecto
$ virutalenv .
$ source bin/activate
$ (proyecto) git init
- Usamos el instalador
(proyecto) $ pip install djangocms-installer
- Creamos el proyecto con la opción "wizard" para especificar las configuraciones que necesitemos.
(proyecto) $ djangocms -w -p modern_web modern_web 
- En la instalación las opciones mas relevantes son: Selecciónar la version 3.2 y Django 1.9, no instalar bootstrap, no instalar plantillas, seleccionar idioma español.
(proyecto) $ cd modern_web
- Iniciamos servidor por la dirección y puerto que queramos, por defecto el 127.0.0.1:8000
(proyecto) $ python manage.py runserver 



