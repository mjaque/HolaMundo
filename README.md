# HolaMundo
Repo de pruebas

Pasos para importar un repositorio de GitHub en Eclipse (con EGIT):
1. Ir al menú File->Import->Git->Projects from Git
1. Elegir "Clone URI"
1. Completar con la URI del repositorio: https://github.com/mjaque/HolaMundo
1. Next. Elegir la rama: master
1. Next. ¡Establecer el directorio de destino! Será el mismo que el proyecto de Eclipse.
  Por ejemplo: /home/mjaque/workspace/HolaMundo
1. Next. 
1. Elegir "Import Using Project Wizard"
1. Elegir "Java Project"
1. Establecer el nombre del proyecto y
1. ¡Especificar la localizacin IGUAL que en el paso 5!
1. Finish.

## Comandos ##
* Añadir un fichero al control de versiones (git add): **Add to index**
* Quitar un fichero al control de versiones (git rm --cached): **Remove from index**
* Ver la historia de un archivo (git log): **Show in history**

(Estas operaciones se hacen "inteligentemente": mezclando la versión local y la remota)
* Subir los cambios de un fichero local al repositorio (git commit, git push): **git commit & push**
* Para actualizar la copia en local con los cambios de versión del repositorio, hacemos (git pull): **git pull**

* Revertir un fichero local a la última versión del repositorio (git reset HEAD): **Revert to HEAD revision**
* Ver una versión anterior de un fichero con: **Show in history** (doble click en la versión)

## Signos ##
* ?: Fichero no sujeto a control de versiones (untracked).
* +: Fichero añadido al control de versiones.
* *: Fichero preparado para actulizar al repositorio (stagged).
* (repo): Fichero bajo control de versiones actualizado, igual en repo y en local (unmodified).


