# Tarea 1: Introducción a Git

## Descripción:
En esta tarea utilizamos lo que es Git y GitHub para usar repositores locales y remotos y tambien saber los comando de Git para hacer nuestros trabajos y archivos que creemos 
y usando Git Bash para subir nuestros archivos que creemos de ahi (repositorio local) a GitHub (repositorio remoto)

## Instrucciones de uso 
Lo que debemos hacer es crear una carpeta en nuestra computadora que va hacer nuestro repositor local para luego subirlo o cargarlo a GitHub y la carpeta la llame ProyectoEjemploGit y ahi comence a hacer mis archivos creandolos con comandos como era el de java que lo que hice fue:

1.-Envie el archivo **HolaMundo.java**

2.-Hice despues git.ignore y **debug.log** dentro de ahi escribi el comando para que lo ignorara o no estuviera en el repositor remoto

3.-Luego cambie en el archivo **HolaMundo.java** cambiando el mensaje que iba a imprimir

4.-Despues ejecute los comandos para cambiar o subirlos a GitHub (repositorio remoto)

## Comandos utilizados
```
git config --global user.name "Nombre"
git config --global user.email "Email.@gmail.com"
git init
git add
git status
git touch
git commit
git push
ls -al
git remote add origin
```

## Notas sobre el archivo **.gitignore**
Este archivo que se utiliza para que Git revisa que archivo deseamo ignorar significa que no los incluirá ni enviará al repositorio remoto. Este archivo es útil para evitar que algunos archivos se vayan al repositorio. Para este trabajo se utiliza para ignorar el archivo **debug.log**.
El archivo al crearlo se puede al entrar y en este podemos utilizar comandos para evitar enviar archivos especificos o incluso los que tengan una terminacion en especifico al ser archivos ejetucables que terminen en _.exe_ 
