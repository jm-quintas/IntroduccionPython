# Introducción.

**Python** es un *lenguaje de programación de alto nivel, interpretado, de propósito general y multiparadigma*. Fue creado a finales de los años 80 por Guido van Rossum en los Países Bajos y lanzado públicamente en 1991. Su nombre no proviene del reptil, sino de la admiración de su creador por el grupo cómico británico Monty Python. La esencia del lenguaje está resumida en un conjunto de 19 principios de software conocidos como "The Zen of Python" (escritos por Tim Peters). Si abres una terminal de Python y escribes **import this**, los verás. Los pilares más célebres son:

- Bello es mejor que feo.

- Explícito es mejor que implícito.

- Simple es mejor que complejo.

- La legibilidad cuenta.

A diferencia de otros lenguajes que permiten escribir código de formas muy oscuras, Python obliga (mediante su sintaxis) a que el código sea limpio y legible.

## Características Técnicas Principales.

Para entender por qué es tan popular, debemos mirar bajo el capó:

- **Lenguaje Interpretado**: El código fuente se traduce a un código intermedio (bytecode) y es ejecutado por la Máquina Virtual de Python (PyVM) sin necesidad de una compilación previa a lenguaje máquina (como en C o C++). Esto facilita el desarrollo multiplataforma.

- **Tipado Dinámico y Fuerte**:
  - *Dinámico*: No necesitas declarar el tipo de una variable (como **int** o **string**) al crearla; Python lo infiere en tiempo de ejecución.

  - *Fuerte*: Python no realiza conversiones de tipo implícitas y locas. Si intentas sumar un texto con un número ("5" + 2), el sistema arrojará un error en lugar de inventar un resultado.

- **Multiparadigma**: Soporta de forma nativa la *Programación Orientada a Objetos* (POO), la *Programación Estructurada* (Funcional) y la *programación imperativa*. Te da la libertad de elegir el enfoque que mejor se adapte a tu problema.

- **Sintaxis Basada en Indentación**: En Python no existen las llaves {} para definir bloques de código (como en Java o JavaScript). Los bloques se definen mediante espacios en blanco o tabulaciones. Esto garantiza que todo el código escrito en Python comparta un estilo visual uniforme.

