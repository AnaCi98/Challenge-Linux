La solución que tengo para el primer ejercicios es el siguiente script:

#!/bin/bash

## Resolución Ejercicio 1
## Creo la carpeta foo
mkdir foo
## Ingreso a la carpeta foo
cd foo/
## Creo los subdirectorios dummy y empty
mkdir dummy empty
## Ingreso a la carpeta dummy
cd dummy/
## Creo los dos archivos: file1.txt y file2.txt
touch file1.txt file2.txt
## Sobreescribo la oración en el archivo file1.txt
echo "Me encanta bash!!" > file1.txt

# Resolución Ejercicio 2
## Para copiar el contenido de file1 a file2
cp file1.txt file2.txt
## Para mover el file2.txt a la carpeta de empty
mv file2.txt empty

# Resolución Ejercicio 3

