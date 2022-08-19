# 2021-S2 Laboratorio1

El siguiente laboratorio consiste en una serie de ejercicios para practicar el desarrollo de programación en sintaxis de Python, además de evaluación de conceptos vistos en clases anteriores.
El objetivo de este laboratorio está en el uso de y manipulación archivos, recuerde que en cada función que desarrollen agregar los comentarios (nombre, parámetros entrada, salida y restricciones).
Finalizado el laboratorio subir el archivo con el nombre de usted, es decir **Laboratorio1.py**, la entrega cierra a las **10pm del viernes 20 de agosto del 2021**.



## Ejercicio 1. Valor 10 puntos.
Escriba una función llamada **contarCaracteres** que reciba como parámetro de entrada el **nombre de un archivo**, y debe contar todos los caracteres que tiene este archivo. Para determinar el largo de la cadena de texto, hacer uso de la recursión y evitar funciones built-in.

```python
>>> contarCaracteres(“miArchivo.txt”)
Total de caracteres 156
>>> contarCaracteres(“miArchivoVacio.txt”) # En el caso de que el archivo esté vacío
Total de caracteres 0
```

## Ejercicio 2. Valor 10 puntos.
Escriba una función llamada **contarPalabras** que reciba como parámetro de entrada el nombre de un archivo y otro parámetro con el carácter o palabra que se desea en el conteo. Hacer uso de la recursión y evitar funciones built-in.

```python
>>> contarPalabras (“miArchivo.txt”, “es”)
Total palabras “es”: 4
>>> contarPalabras (“miArchivo.txt”, “XYZ”) # En el caso de que el archivo no encuentre coincidencia
Total palabras “XYZ”: 0
```

## Ejercicio 3. Valor 10 puntos.
Escriba una función llamada **concatenarArchivos** que reciba tres parámetros de entrada, el nombre de un **archivo1**, **archivo2** y el nombre del **nuevo archivo**, este último tendrá el contenido ambos archivos concatenados. Evitar funciones built-in.
Archivo1:  Hola mundo
Archivo2: con Python
Archivo nuevo: Hola mundo con Python
Tomar en cuenta como restricción que los archivos 1 y 2 deben de existir

```python
>>> concatenarArchivos(“archivo1.txt”, “archivo2.txt”, “nuevoArchivo.txt”)
El contenido del nuevo archivo es: 
Hola mundo
con Python
```
