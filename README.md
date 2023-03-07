# primerRepository

aprendiendo a usar la herramienta de gitHub :) 

## Algunos codigos para la consola de git bash

Para facilitar a la hora del aprendizaje sino aún no se sabe de memory 

```bash
Hola mundo
```

## Git

```java
//para clonar un repositorio 
git clone -link-

//para acceder a este 
cd -nombre del repository-/

//para ver en qué rama estamos 
git branch

//para cambiar de rama
git checkout nombredelarama

//para crear una rama nueva
git checkout -b nombredelarama
 
//para subir la rama al servidor 
git push –set-upstream origin nombredelarama

//para ver que hay en esta carpeta 
dir

//para ver updates que se le han hechos 
git status

//para agregar todos los cambios
git add . 

//para subir estos cambios 
git commit -m “titulo de este cambio”

//para subir a github (push)
git push

//para traer todo del main a una rama
git pull

//para hacer un guardado local y utilizarlo después 
git stash

//para traer esos cambios que guardamos en stash
git stash apply

//para revertir estos cambios del stash y volver a la rama original 
git checkout . 

//para ver las modificaciones o commit que se han hecho 
git log


para ignorar una carpeta dentro de un repocitory debemos crear un archivo con la extension 

“.gitignore”  dentro de este colocamos el nombre de la carpeta, si queremos add un comentario colocamos “#comentario” 

si queremos ignorar todas las extensiones, por ejemplo las html se coloca 

“*.html” el * funciona para tomar todos los nombres que tengan extensión html

```
