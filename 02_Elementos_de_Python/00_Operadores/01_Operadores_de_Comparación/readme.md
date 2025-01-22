# Operadores comparativos

Son usados para comparar valores. Y solo regresan un valor de verdadero o falso. De acuerdo a la expresión evaluada.
___

Todos los ejemplos usan las siguientes variables 

```python
# Enteros
n1 = 10
n2 = 20

# Floats
f1 = 1.5
f2 = 5.2
```
___

## ">" Mayor a - Verdadero si el operando izquierdo es mayor al derecho, x > y.

```python
# 1. Mayor que
	print("(n1 > n2): " , (n1 > n2))
	print("(f1 > f2): " , (f1 > f2))
```

___

## "<" Menor a - Verdadero si el operando izquierdo es menor al de la derecha, x < y.

```python

# 2. Menor que
print("(n1 < n2): " , (n1 < n2))
print("(f1 < f2): " , (f1 < f2))
```
___

## "==" Igual a - Verdadero si ambos operandos son iguales, x==y.

```python
# 3. Igualdad
print("(n1 = n2): " , (n1 == n2))
print("(f1 = f2): " , (f1 == f2))
```

___

## "!=" Diferente a - Verdadero si ambos operadores son diferentes, x!= y.

```python
# 4. Desigualdad

print("(n1 != n2): " , (n1 != n2))
print("(f1 != f2): " , (f1 != f2))
```
___

## ">=" Mayor o igual - Verdadero si el operando izquierdo es mayor o igual al derecho, x >= y.

```python
# 5. Mayor o igual que
print("(n1 >= n2): " , (n1 >= n2))
print("(f1 >= f2): " , (f1 >= f2))
```	

___

## "<=" Menor o igual - Verdadero si el operando izquierdo es menor o igual al derecho, x <= y.

```python
# 6. Menor o igual que
print("(n1 <= n2): " , (n1 <= n2))
print("(f1 <= f2): " , (f1 <= f2))
```

___

## Ejemplos mixtos

```python
# Enteros
n1 = 10
n2 = 20

# Floats
f1 = 1.5
f2 = 5.2

# 7. Comparaciones de tipos mixtos
print("(n1 > f2): " , (n1 > f2))
print("(f1 < n2): " , (f1 < n2))

# 8. Valores negativos
print("(n1 > -n2): " , (n1 > -n2))
print("(f1 < -f2): " << (f1 < -f2))

# 9. Combinación de comparaciones
# Puedes usar la palabra and 
# Puedes usar la palabra or 

print("((n1 < n2) and (f1 > f2)): " , ((n1 < n2) && (f1 > f2)))
print("((n1 == 10) || (f1 == 5.2)): " , ((n1 == 10) || (f1 == 5.2)))

# Comparaciones anidadas

print("(n1 > n2 - 10): " , (n1 > n2 - 10))
print("(f1 <= f2 + 10.5): " , (f1 <= f2 + 10.5))

# 11. Comparacón con constantes

print("(n1 == 10): " , (n1 == 10))
print("(f1 == 5.2): " , (f1 == 5.2))

# Compración con los resultados de las operaciones aritméticas

print("((n1 + n2) < (f1 * f2)): " , ((n1 + n2) < (f1 * f2)))
print("((n1 + n2) >= (f1 / f2)): " , ((n1 - n2) >= (f1 / f2)))

# 13. Comparación de resultados negativos y positivos

print("((-n1) < n2): " , ((-n1) < n2))
print("((-f1) > f2): " , ((-f1) < f2))

# 14. Combinación de aritméticas y compración
print("((n1 * n2) > (f1 - f2)): " , ((n1 * n2) > (f1 - f2)))
print("((n2 / n1) <= (f1 + f2)): " , ((n2 / n1) <= (f1 + f2)))

# 15. Comparaciones encadenadas

print("(n1 < n2 and n2 < f1): " , (n1 < n2 and n2 < f1))
print("(f2 > f1 and f1 > n1): " , (f2 > f1 and f1 > n1))

# Compración de módulos

print("((n2 % n1) == 0): " << ((n2 % n1) == 0))

```
