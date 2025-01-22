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
