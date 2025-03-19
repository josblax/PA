# Clases y objetos


## Mapa de clases

```
Personaje
│
├── Heroe
└── Enemigo
    ├── Dragon
    └── Ogro
```


## Clase Personaje:

 Sirve como la clase base que define atributos como el nombre y la salud, y un método para recibir daño (recibir_dano).

### Subclase Heroe:

Incluye un atributo único (poder) y un método para atacar a un enemigo. La implementación muestra cómo el héroe aplica daño a cualquier objeto del tipo Enemigo.

### Subclase Enemigo:

Es la clase base para los enemigos. Los detalles específicos del ataque se delegan a las subclases (Dragon y Ogro).

### Polimorfismo:

Los métodos atacar en las clases Dragon y Ogro sobrescriben la versión base de Enemigo. Esto permite que cada enemigo ataque de manera única.

### Resultado:

Se demuestran interacciones entre el héroe y los enemigos con mensajes personalizados que reflejan la lógica de combate.

Explicación

# Herencia
La herencia es el mecanismo mediante el cual una clase (la subclase) hereda atributos y métodos de otra clase (la clase base). Esto permite reutilizar código y extender funcionalidades.

En el ejercicio:

## Clase Base: Personaje

Personaje es la clase base, de la cual heredan las demás clases. Define atributos comunes a todos los tipos de personajes, como nombre y salud, y un método recibir_dano para reducir la salud.

## Subclases: Heroe y Enemigo

La clase Heroe hereda de Personaje y añade el atributo poder, así como el método atacar, que está específicamente diseñado para interactuar con enemigos.

La clase Enemigo también hereda de Personaje y actúa como la base para otros tipos de enemigos. Aunque la implementación del método atacar es genérica en Enemigo, se sobrescribe en las subclases específicas (Dragon y Ogro).

Sub-Subclases Específicas: Dragon y Ogro

Estas Sub-subclases heredan de Enemigo y sobrescriben el método atacar para implementar comportamientos únicos de ataque (por ejemplo, lanzar fuego o golpear con fuerza).

# Polimorfismo

El polimorfismo permite utilizar un método de manera genérica en un objeto sin importar su clase exacta. En otras palabras, el comportamiento de un método dependerá del objeto que lo implemente.

En el ejercicio:

## Método atacar:

En la clase base Enemigo, atacar se define como un método genérico que las sub-subclases (Dragon y Ogro) sobrescriben.

Cuando llamas al método atacar en un objeto, el comportamiento se ajusta según la clase del objeto específico.

Ejemplo práctico en el código:

```Python
dragon.atacar(heroe)  # Ejecuta el método 'atacar' de la clase Dragon
ogro.atacar(heroe)    # Ejecuta el método 'atacar' de la clase Ogro
```
