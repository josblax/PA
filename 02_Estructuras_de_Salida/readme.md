# Estructuras de Salida

## Instrucción print()

print(). Es la función estandar de salida de python.

Sintaxis

```

print(objeto(s), sep=separador, final=end, archivo=file, limpiar=flush)

```

Parámetros:

* object(s): Uno o más objetos a imprimir. Pueden ser cadenas, números, listas, etc.
* sep: Separador de objetos. Por defecto se usa la coma (,)
* end: Caracteres de control para denotar una nueva linea. Por defecto es un salto de línea ('\n').
* file: Objeto de archivo donde se enviará la salida. Por defecto es sys.stdout (la pantalla).
* flush: Si es True, fuerza el vaciado del buffer de salida. Por defecto es False.

Ejemplo:

```python
# Escriba la instrucción print(), dentro de esta escriba en comillas dobles o simples Hola Mundo.
print("Hola # como estas")

# Uso de separador
print("Hola", "Mundo!")
```

___

# Palabra Reservada.

Son palabras usadas para escribir una gramática correcta que puede ser interpretada o compilada por la computadora para producir un resultado.

___

## Variables y Nombres de Variables

Los nombres de variables deben de reflejar el uso para el que es usado la variable, y para que posteriores programadores puedan comprender el código.


1. Los nombres de variables pueden ser de cualquier longitud
3. Los nombres son diferenciables en mayúsculas o minúsculas.
4. Se pueden separar las asignaciones en la misma línea mediante punto y coma.
5. Puedes usar guión bajo "_" como separador o iniciador de un nombre de una variable.
6. Todas las variables deben llevar un tipo de variable.

## No debes...

1. No iniciar el nombre con un número.
2. No usar caracteres especiales como #,!,%,$ etc...
3. No existen espacios en ningun punto del nombre de una variable.
4. No uses mayúsculas y minúsculas, asumiendo que es la misma variable.

___


### Tipos de variables

En python las variables son simbolicas, es decir en realidad son objetos referenciados en memoria. La asociación a un tipo es dinámica o interpretada, es decir, no necesitas asociar un tipo de variable.

Tipos de variables comúnes en python:
___

#### Numérico

Asignar usando el operador de asignación "=" un numero a una variable. Este numero puede ser entero, fraccionario o complejo.

Ejemplos:

```python

# numerico entero
edad = 22
print(edad)
print(type(edad))

# numerico fraccionario
peso = 34.5
print(peso)
print(type(peso))

# numerico complejo
y = 2 + 3j
print(y)
print(type(y))
```
___

#### Textos

Asignar valores alfanuméricos encerrados entre doble comillas " " o comilla simple ' ', sin mezclarlas.

Ejemplos:

```python

# string
saludo = 'Hola',' Buenos dias'
print(saludo)
print(type(saludo))
```
___

#### boolean

Asignar un valor True o False.

Ejemplos:

```python

# boolean
frio = True
print(frio)
print(type(frio))
```
___

#### binarios

Ejemplos:

```python
# Bytes 
saludo = b'A'
print(saludo)
print(type(saludo))
binary_string = bin(int.from_bytes(saludo, 'big'))[2:].zfill(8 * len(saludo))
print(binary_string)

# bytearray. Arreglo de bytes

binario = bytearray(5)
print(binario)
print(type(binario))
binary_string = bin(int.from_bytes(binario, 'big'))[2:].zfill(8 * len(binario))
print(binary_string)
```

Ejercicio:

> El dataset en la parte inferior  contiene el conjunto de datos de predicción de deserción de empleados con 10,000 filas de datos, que representan una variedad de empleados de diferentes departamentos y roles dentro de una organización. 

> Incluye información demográfica, métricas relacionadas con el trabajo, evaluaciones de rendimiento y factores que influyen en la deserción (rotación) de los empleados.

Cuantos bits se necesitan para convertir los datos de este dataset en registro binario?

DataSet : https://www.kaggle.com/datasets/ziya07/employee-attrition-prediction-dataset

