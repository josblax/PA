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

Resultado:

Se demuestran interacciones entre el héroe y los enemigos con mensajes personalizados que reflejan la lógica de combate.
