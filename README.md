# 2022-S2 Laboratorio1

El siguiente laboratorio consiste en una serie de ejercicios para practicar el desarrollo de programación en sintaxis de Python, además de evaluación de conceptos vistos en clases anteriores.
El objetivo de este laboratorio está en el uso de y manipulación archivos, recuerde que en cada función que desarrollen agregar los comentarios (nombre, parámetros entrada, salida y restricciones).
Finalizado el laboratorio subir el archivo con el nombre de usted, es decir **Laboratorio1.py**, la entrega cierra a las **10pm del sábado 20 de agosto del 2022**.

## Ejercicio 1. Valor 5 puntos.
- Escriba una función llamada **escribirArchivo** que reciba como parámetro de entrada el **nombre de un archivo**, y haciendo uso del **input** ingresar el contenido y guardarlo en el archivo.
- El **input** debe enviar el siguiente mensaje "Ingresar contenido: "
- El segundo parámetro será **"modo"**, en este caso solo permitira **"a"** o **"w"**
- Tomar en cuenta que cada vez que se ingrese contenido al archivo este debe iniciar en la siguiente línea, no debe existir líneas vacías
- Evitar funciones built-in.

```python
>>> escribirArchivo("miArchivo.txt", "w")
Ingresar contenido: Hola mundo
'Hola mundo'

>>> escribirArchivo("miArchivo.txt", "a")
Ingresar contenido: Hola mundo
'Hola mundo'
'Hola mundo'
```

## Ejercicio 2. Valor 10 puntos.
Escriba una función llamada **verArchivo** que reciba como parámetro de entrada el **nombre de un archivo**, debe retornar todo el contenido del archivo

```python
>>> verArchivo("miArchivo.txt")
'Hola mundo'
'Hola mundo'
```

## Ejercicio 3. Valor 10 puntos.
Escriba una función llamada **contarLineas** que reciba como parámetro de entrada el **nombre de un archivo**, debe retornar el total de líneas que contiene el archivo

```python
>>> contarLineas ("miArchivo.txt")
2
```

## Ejercicio 4. Valor 10 puntos.
Escriba una función llamada **contarCaracteres** que reciba como parámetro de entrada el **nombre de un archivo**, debe retornar el total de caracteres que tiene el archivo, debe también contar los caracteres invisibles como el de cámbio de línea

```python
>>> contarCaracteres ("miArchivo.txt")
24
```
