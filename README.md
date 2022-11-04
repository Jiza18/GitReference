# TUTORIAL GIT

Explicación comandos Git mas importantes.

## Git tag

Es el impulsor principal de una etiqueta: creación, modificación y eliminación.

## Git pull

Sirve para descargar el contenido de un repositorio.

## Git Switch

Sirve para cambiar entre distintas ramas, lo cual facilita el trabajo.

 ## Comando git Rebase

git commit: sirve para crear un commit, que es una foto de los ficheros existentes en el programa (en ese momento).

Ejemplo: 
```
git commit -a -m "git commit"
```

## Comando git branch

Sirve para crear una rama, para trabajar en el programa independientemente sin afectar a la versión actual.

Ejemplo: git branch Jose

## Comando git checkout

Sirve para cambiar de una rama a otra

Ejemplo 1: si estamos en la rama main y queremos cambiar a una rama ya existente
usamos el comando: 
```
git checkout nombre_de_la_rama.
```

Ejemplo 2: si estamos en la rama main y queremos cambiar a una rama que aun no esta creada
usamos el comando: git checkout -b nombre_de_la_rama||-b para idicarle que si la rama no existe la cree.

## Comando git merge

Sirve para unir todas las ramas que derivan de la rama main, para unir todo el codigo o los cambios
que se hayan hecho independientemente en ellas.

Ejemplo: Si tenemos 3 ramas que derivan de la rama main (Junior, Jose, Candido)
y usamos el comando: git merge||Git automaticamente unira las tres brancas en la rama main,
uniendo el codigo o los cambios del archivo y dando opción a organizar este mismo antes de guardar los cambios.


git rebase es la forma de integrar los cambios de una rama en otra.

## Comando git remote

Git remote permite ver todos los repositorios remotos, conectando el dispositivo local con otro remoto.

# Comando git bisect

Git bisect se utiliza para realizar una búsqueda binaria a través de su historial de commits para ayudar a identificar lo más rápidamente posible qué commit introdujo un problema.

## COMANDO git cherry-pick

```
Dado uno o más commits existentes, aplica el cambio que cada uno introduce, registrando un nuevo commit para cada uno. Esto requiere que su árbol de trabajo esté limpio (sin modificaciones del compromiso HEAD).
```

## COMANDO git clone

explicacion del comando.
```
Se usa para copiar un repositorio de Git existente en un nuevo directorio local.

El comando de clonación de Git creará un nuevo directorio local para el repositorio, copiará todo el contenido del repositorio especificado, creará las ramas remotas rastreadas y extraerá una rama inicial localmente. De forma predeterminada, git clone creará una referencia al repositorio remoto llamado origen.
```

## COMANDO git branch -f

```
Este comando sirve para dejar una rama en su estado inicial, y en combinacion con -d borra la rama, independientemente de su estado
```
