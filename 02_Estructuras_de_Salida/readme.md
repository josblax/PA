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
