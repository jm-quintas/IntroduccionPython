# Programación en Python.

## Objetos en Python.

En Python, **todo es un objeto**. Desde un simple número entero hasta las funciones y las clases que tú mismo defines. Para entenderlo de forma sencilla: un **objeto es una entidad que combina datos** (características o atributos) y **comportamiento** (acciones o métodos).

### 1. Las dos componentes de un objeto.

Si comparamos un objeto con un automóvil del mundo real:

  - **Atributos (Datos)**: Son las *variables internas* del objeto. (Ejemplo: el color o marca).

  - **Métodos (Funciones)**: Son funciones que pertenecen al objeto y *definen lo que puede hacer*. (Ejemplo: acelerar, frenar o encender luces).

### 2. Clases: El "molde" de los objetos.

Para crear tus propios objetos, primero necesitas definir una Clase (class). La **clase es el plano arquitectónico o molde**, y el objeto es la casa real construida con ese molde (a esto se le llama instancia).

### 3. Objetos Mutables vs. Inmutables.

En Python, los objetos se dividen en dos grandes categorías según si se pueden modificar después de ser creados:

| Tipos de Objetos | ¿Se puede modificar? (Mutabilidad) | Ejemplos |
| :-------: | :-------: | :-------: |
| Inmutables | No. Si cambias su valor, Python crea un objeto nuevo en memoria | **int**, **float**, **str**, **tuple**, **bool** |
| Mutables | Sí. Se pueden modificar directamente sus elementos internos sin cambiar su identidad | **list**, **dict**, **set** |

### 4. Tres funciones clave para investigar objetos.

Python te da herramientas para "espiar" dentro de cualquier objeto:

  - **type(objeto)**: Te dice a qué clase pertenece.

  - **id(objeto)**: Te da el identificador único (la dirección de memoria) del objeto.

  - **dir(objeto)**: Te muestra una lista de todos los atributos y métodos que tiene disponibles.

**Dato curioso**: Cuando haces algo tan simple como ``` x = 5 ``` , Python no solo guarda el número 5. Crea un objeto de la clase int que tiene un montón de métodos ocultos detrás de escena.

## Tipos de Objetos en Python.

En Python, los objetos se dividen en dos grandes categorías según su estructura interna: **escalares** y **no escalares** (o compuestos).

  - **Escalares**: Es aquel que representa un **valor único y atómico**. Es decir, es la *unidad más básica de información* y no contiene otros objetos dentro de sí mismo. **No puedes descomponerlo ni iterar** a través de él con un bucle. En Python, todos los objetos escalares básicos son además *inmutables* (no se pueden modificar una vez creados). Ejemplos: enteros, flotantes, booleano, None.

  - **No Escalares**: Es una entidad que se **puede descomponer en partes más pequeñas**, contiene múltiples elementos internamente y, por lo general, te **permite interactuar** con su contenido mediante bucles o índices. Ejemplos: listas, tuplas, cadenas de textos, diccionarios, conjuntos.

## Palabras Clave (Keywords): Las verdaderas "Reservadas".

Estas palabras **son los pilares del lenguaje**. Python las necesita para entender la estructura de tu código. Si intentas registrar una variable con cualquiera de estos nombres, el programa se detendrá inmediatamente con un error de sintaxis. Algunas de las más comunes divididas por su uso son:

  - **Control de flujo**: if, elif, else, for, while, break, continue, pass, return.

  - **Lógica y Booleanos**: True, False, None, and, or, not, in, is.

  - **Definiciones**: def (para funciones), class (para clases), lambda (funciones anónimas).

  - **Manejo de excepciones**: try, except, finally, raise, assert.

  - **Módulos**: import, from, as.



