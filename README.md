# TUTORIAL GIT

## Comando git commit

git commit: sirve para crear un commit, que es una foto de los ficheros existentes en el programa (en ese momento).

Ejemplo: git commit -a -m "git commit"

## Comando git branch

Sirve para crear una rama, para trabajar en el programa independientemente sin afectar a la versión actual.

Ejemplo: git branch Jose

## Comando git checkout

Sirve para cambiar de una rama a otra

Ejemplo 1: si estamos en la rama main y queremos cambiar a una rama ya existente
usamos el comando: git checkout nombre_de_la_rama.

Ejemplo 2: si estamos en la rama main y queremos cambiar a una rama que aun no esta creada
usamos el comando: git checkout -b nombre_de_la_rama||-b para idicarle que si la rama no existe la cree.

## Comando git merge

Sirve para unir todas las ramas que derivan de la rama main, para unir todo el codigo o los cambios
que se hayan hecho independientemente en ellas.

Ejemplo: Si tenemos 3 ramas que derivan de la rama main (Junior, Jose, Candido)
y usamos el comando: git merge||Git automaticamente unira las tres brancas en la rama main,
uniendo el codigo o los cambios del archivo y dando opción a organizar este mismo antes de guardar los cambios.


