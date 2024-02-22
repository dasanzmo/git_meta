# Configuración

Comando para conocer la versión version de github

- git -v
- git --version

## Comandos para configurar git por primera vez:

- git config --global user.name "Your name"
- git config --global user.email "hola@correo.com"

## Comando para ver que usuario está configurado o con que correo electronico.

- git config --global user.name
- git config --global user.email
- git config --list

## Comando para inicializar git en un directorio

- git init

## Comando para ver el estado de los archivos

- git status

## Comando para ver todas la versiones de mi proyecto

- git log
- git log --oneline

## Comando para cambiar entre versiones

- git checkout <nombre de la rama o del identificador de la version>
- git checkout -- . //Atajo

## Pasos para crear una version de mi código

1.  Agregar los cambios

- git add .
- git add *.js
- git add home.html

2. Comprometer los archivos

- git commit -m "Descripción del commit"
