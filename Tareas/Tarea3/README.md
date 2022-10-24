# Manipulación avanzada en git

## Ejercicio 1

- Mostrar el historial de cambios del repositorio.
- Crear la carpeta capítulos y crear dentro de ella el fichero capitulo1.txt con el siguiente texto.

"Git es un sistema de control de versiones ideado por Linus Torvalds."

- Añadir los cambios a la zona de intercambio temporal.
- Hacer un commit de los cambios con el mensaje Añadido capítulo 1.
- Volver a mostrar el historial de cambios del repositorio.

![<>](img/captua%202-1.png)

## Ejercicio 2

- Crear el fichero capitulo2.txt en la carpeta capítulos con el siguiente texto.

"El flujo de trabajo básico con Git consiste en: 1- Hacer cambios en el repositorio. 2- Añadir los cambios a la zona de intercambio temporal. 3- Hacer un commit de los cambios."

- Añadir los cambios a la zona de intercambio temporal.
- Hacer un commit de los cambios con el mensaje Añadido capítulo 2.
- Mostrar las diferencias entre la última versión y dos versiones anteriores.

![<>](img/Captura%202-2.png) 

## Ejercicio 3

- Crear el fichero capitulo3.txt en la carpeta capítulos con el siguiente texto.

Git permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera simultanea en ellas.

- Añadir los cambios a la zona de intercambio temporal.
- Hacer un commit de los cambios con el mensaje Añadido capítulo 3.
- Mostrar las diferencias entre la primera y la última versión del repositorio.

![<>](img/Captura%202-3.png)

## Ejercicio 4

- Crea el fichero índice.txt la siguiente línea:

Indice de los cápitulos, con conceptos avanzados de git

- Añadir los cambios a la zona de intercambio temporal.
- Hacer un commit de los cambios con el mensaje "Indice de los cápitulos, con conceptos avanzados de git.
- Mostrar quién ha hecho cambios sobre el fichero indice.txt.

![<>](img/Captura%202-4.png)

## Ejercicio 5

- Crear una nueva rama bibliografía y mostrar las ramas del repositorio.


## Ejercicio 6

- Crear el fichero capitulos/capitulo4.txt y añadir el texto siguiente:

En este capítulo veremos cómo usar GitHub para alojar repositorios en remoto.

- Añadir los cambios a la zona de intercambio temporal.
- Hacer un commit con el mensaje “Añadido capítulo 4.”
- Mostrar la historia del repositorio incluyendo todas las ramas.

![<>](img/Captura%202-6.png)

## Ejercicio 7

- Cambiar a la rama bibliografía.
- Crear el fichero bibliografia.txt y añadir la siguiente referencia:

Chacon, S. and Straub, B. Pro Git. Apress.

- Añadir los cambios a la zona de intercambio temporal.
- Hacer un commit con el mensaje “Añadida primera referencia bibliográfica.”
- Mostrar la historia del repositorio incluyendo todas las ramas.

![<>](img/Captura%202-7.png)

## Ejercicio 8

- Fusionar la rama bibliografía con la rama main.
- Mostrar la historia del repositorio incluyendo todas las ramas.
- Eliminar la rama bibliografía.
- Mostrar de nuevo la historia del repositorio incluyendo todas las ramas.

![<>](img/Captura%202-8.png)

## Ejercicio 9

- Crear la rama bibliografía.
- Cambiar a la rama bibliografía.
- Cambiar el fichero bibliografia.txt para que contenga las siguientes referencias:

Scott Chacon and Ben Straub. Pro Git. Apress.
Ryan Hodson. Ry’s Git Tutorial. Smashwords (2014)

- Cambiar a la rama main.
- Cambiar el fichero bibliografia.txt para que - contenga las siguientes referencias:

Chacon, S. and Straub, B. Pro Git. Apress.
Loeliger, J. and McCullough, M. Version control with Git. O’Reilly.

- Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje “Añadida nueva referencia bibliográfica.”
- Fusionar la rama bibliografía con la rama main.
- Resolver el conflicto dejando el fichero bibliografia.txt con las referencias:

Chacon, S. and Straub, B. Pro Git. Apress.
Loeliger, J. and McCullough, M. Version control with Git. O’Reilly.

Hodson, R. Ry’s Git Tutorial. Smashwords (2014)

- Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje “Resuelto conflicto de bibliografía.”
- Mostrar la historia del repositorio incluyendo todas las ramas.

![<>](img/Captura%202.9.png)

No se pudo resolver el conflicto en el fichero bibliografía.