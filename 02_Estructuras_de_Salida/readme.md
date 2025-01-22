# Estructuras de Salida

## Instrucción print()

print(). Es la función estandar de salida de python.

Sintaxis

```

print(object(s), sep=separator, end=end, file=file, flush=flush)

```

Parámetros:

* object(s): Uno o más objetos a imprimir. Pueden ser cadenas, números, listas, etc.
* sep: Separador de objetos.
* end: Caracteres de control para denotar una nueva linea. Por defecto es un salto de línea ('\n').
* file: Objeto de archivo donde se enviará la salida. Por defecto es sys.stdout (la pantalla).
* flush: Si es True, fuerza el vaciado del buffer de salida. Por defecto es False.