Paso 1:
Crear un repositorio : git init

Paso 2:
Dar seguimiento a los archivos de nuestro repositorio
git add .


Paso 3:
Crear una version (commit) del repositorio
git commit -m "Version 1 de mi repositorio"


Paso 4:
Renombra la rama master a main
git branch -M main

Paso 5:
Conectar nuestro repositorio local con un origen remoto
git remote add origin https://github.com/BramajoLucas/Primer-repo-mentira.git

Paso 6:
Subir nuestros cambios al repositorio remoto
git push -u origin main


Ver historial de commits:
git log

Ver el estado actual de nuestro repositorio:
get status

PASOS PARA ACTUALIZAR EL PROYECTO:

Paso 1:
añadimos los cambios
git add .