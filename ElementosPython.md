# Elementos de Python.

Resumir Python es como describir una caja de herramientas: es simple a primera vista, pero increíblemente poderosa. Aquí tienes un resumen estructurado con los elementos esenciales que componen este lenguaje:

## 1. Sintaxis Básica y Variables.

Python se caracteriza por su legibilidad. No usa llaves {} para definir bloques de código, sino la indentación (espacios en blanco).

  - **Variables**: No necesitas declarar su tipo; se asignan dinámicamente con el operador =.

  - **Comentarios**: Se usa # para comentarios de una línea y triple comilla (""") para comentarios multilínea.

## 2. Tipos de Datos Primitivos.

Son los ladrillos básicos de información:

  - **Enteros (int)**: Números sin decimales (e.g., 10, -5).

  - **Flotantes (float)**: Números con decimales (e.g., 3.14).

  - **Cadenas (str)**: Texto entre comillas (e.g., "Hola Mundo").

  - **Booleanos (bool)**: Solo pueden ser *True* o *False*.

## 3. Estructuras de Datos (Colecciones).

Python tiene formas nativas muy potentes para agrupar datos:

| Estructura | Sintaxis | Características | Ejemplo |
| :-------: | :-------: | :-------: | :-------: |
| Listas | [ ] | Ordenadas y modificables (mutables) | ['manzana', 'banana'] |
| Tuplas | ( ) | Ordenadas e inmutables (no se pueden cambiar) | (10, 20) |
| Diccionarios | { } | Pares de clave: valor, sin orden sintáctico | {"nombre" : "Ana", "edad" : 25} |
| Conjuntos (Sets) | { } | Elementos únicos y sin orden | {1, 2, 3} |

## 4. Operadores.

Permiten manipular los datos:

  - **Aritméticos**: +, -, *, /, % (módulo), ** (potencia), // (división entera).
  
  - **Comparación**: == (igual a), != (diferente de), >, <, >=, <=.

  - **Lógicos**: and, or, not.

## 5. Control de Flujo.

Deciden qué camino toma el código según las condiciones:

### Condicionales.

Utiliza **if**, **elif** (**else if**), y **else**.

### Bucles (Loops).

  - **for**: Ideal para iterar sobre una colección o un rango numérico (**range()**).

  - **while**: Se ejecuta mientras una condición sea verdadera.

## 6. Funciones (def).

Bloques de código reutilizables que realizan una tarea específica. Pueden recibir parámetros y devolver valores usando **return**.

## 7. Programación Orientada a Objetos (POO)

Python es un lenguaje orientado a objetos. Permite modelar el mundo real mediante:

  - **Clases (class)**: El "molde" para crear objetos.

  - **Objetos**: Las instancias creadas a partir de la clase.

  - **Atributos y Métodos**: Las variables y funciones internas del objeto.

## 8. Módulos y Librerías.

No tienes que reinventar la rueda. Python permite importar código externo usando la palabra clave **import**.

  - **Biblioteca estándar**: Incluye módulos nativos como **math**, **datetime** o **random**.

  - **Ecosistema externo**: Herramientas que instalas (vía *pip*) como **Pandas** (datos), **Django** (web) o **NumPy** (ciencia).

**Dato clave**: La filosofía de Python se resume en *"Lo bonito es mejor que lo feo"* y *"Lo explícito es mejor que lo implícito"*. Es lo que se conoce como el Zen de Python.
