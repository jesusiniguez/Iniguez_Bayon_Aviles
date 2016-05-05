# Iniguez_Bayon_Aviles
Ejercicio 1

Jesús 

Ejercicio 2

git init

git pull https://github.com/jesusiniguez/Iniguez_Bayon_Aviles.git

Para saber el contenido de la rama master:

git checkout master

ls 

para guardar la rama

git push https://github.com/jesusiniguez/Iniguez_Bayon_Aviles.git


Ejercicio 3


git init

git pull https://github.com/jesusiniguez/Iniguez_Bayon_Aviles.git

Compruebo con ls lo que hay, modifico pb.c y creo el makefile, cada uno con su correspondiente

git commit -m "motivo" 

Seguido finalmente de un git push https://github.com/jesusiniguez/Iniguez_Bayon_Aviles.git

Ejercicio 4

El * de la rama master indica la rama en donde nos encontramos

Cambiamos de la rama master, a la rama alumno2

Si, git checkout -b nombrerama con ello nos genera la rama si no la tenemos.

Ejercicio 5

git checkout -b RamaAlumno2 Para crear la rama local
git pull https://github.com/jesusiniguez/Iniguez_Bayon_Aviles RamaAlumno2 Para unirla a la rama remota

git checkout master y vuelvo al master

git merge RamaAlumno2 master Une las 2 ramas en master y hace la fusion "fast forward" sin conflictos

Ejercicio 6

git whatchanged --format=full

Ejercicio 7

Ángel: yo como alumno2 he realizado mi parte muy pronto y no ha dado error, pero he vuelto a hacer y ha salido que había un error y que merge no sabía como solucionarlo, me ha indicado que lo solucionara a mano y así lo hemos hecho.

Ejercicio 8

git add pb.c 

git commit -m "poniendo favorites"

git push https://github.com/jesusiniguez/Iniguez_Bayon_Aviles master

Ejercicio 9

Cambiamos a la rama master y realizamos la fusión de la ramaAlumno2 con la rama master:

git checkout master

git merge ramaAlumno2

A continuación realizamos los cambios en el codigo y lo añadimos al repositorio

gedit pb.c

git add . 

git commit -m "Comentario sobre la función de probabilidad"

Por ultimo subimos los cambios realizados:

git push https://github.com/jesusiniguez/Iniguez_Bayon_Aviles.git master

Para ver la cantidad de commits realizados entre los diferentes miembros del grupo introducimos:

git shortlog -s -n

Ejercicio 10

git branch

git ls-remote --heads https://github.com/jesusiniguez/Iniguez_Bayon_Aviles

git push https://github.com/jesusiniguez/Iniguez_Bayon_Aviles :RamaAlumno2

Para borrar la rama local uso branch -d RamaAlumno2

Ejercicio 11

git cherry --help para encontrar si hay algo que añadir a la instrucción, una vez que se ve usamos:

	git cherry -v "Nombre de la rama"

y lo hacemos tanto para master como para RamaAlumno2

Ejercicio 12

Para ver la información sobre el entorno de trabajo con respecto al repositorio con el que estamos trabajando usamos la siguiente orden:

git remote show https://github.com/jesusiniguez/Iniguez_Bayon_Aviles.git

Como la rama master esta desactualizada, la actualizamos usando el siguiente comando:

git checkout master

A continuación realizamos un pull y comprobamos el contenido de la rama con ls

git pull https://github.com/jesusiniguez/Iniguez_Bayon_Aviles.git master


Ejercicio 13

Para comprimir se aplica git archive HEAD(para indicar que sea la actual) --format=zip Comprimido.zip

con esto compactamos todo lo que hay en el repositorio.

