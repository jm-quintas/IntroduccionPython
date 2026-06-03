# Programación en Python Fase I.

La Fase de Principiante está diseñada como el cimiento fundamental de todo camino como programador. Su objetivo principal es que **domines la sintaxis elemental de Python** y **comprendas con total claridad cómo la computadora almacena, procesa y altera el flujo de la información**.  A lo largo de esta etapa, nos enfocaremos en la lógica de programación lineal a través de tres grandes bloques informativos:

  - **Fundamentos del lenguaje**: Aprenderás a configurar tu entorno de trabajo profesional y a comunicarte con la computadora utilizando variables y tipos de datos primitivos como números y texto.
  
  - **Control de flujo**: Descubrirás cómo hacer que tus programas tomen decisiones de forma autónoma mediante condicionales y cómo automatizar tareas repetitivas utilizando bucles.
  
  - **Estructuras lineales y funciones**: Empezarás a agrupar información eficientemente en colecciones y a escribir bloques de código reutilizables para resolver problemas prácticos.
  

# Comentarios en Python.

Los comentarios son una de las herramientas más importantes en la programación. Son **anotaciones en texto** plano que incluyes dentro del código para explicar cómo funciona, detallar el porqué de una decisión de diseño o dejar recordatorios. Lo más importante que debes saber es que el **intérprete de Python ignora por completo los comentarios** al ejecutar el programa; están ahí exclusivamente para los seres humanos (tú mismo en el futuro o tus compañeros de equipo). En Python existen diferentes formas de estructurar y utilizar los comentarios:

## 1. Comentarios de una sola línea (#).

Es la forma más común. Se utiliza el **símbolo de almohadilla o numeral (#)**. Todo lo que escribas a la derecha de este símbolo en la misma línea será tratado como un comentario.

```Python
# Esto es un comentario de una sola línea.
``` 

Se pueden usar de dos formas:

  - **En su propia línea**: Ideales para explicar bloques de código complejos justo antes de que ocurran.
  - **En la misma línea del código (Inline comments)**: Se colocan al final de una instrucción. Se recomienda dejar al menos dos espacios de separación después del código para mantener la legibilidad.

## 2. Comentarios multilínea o de bloque.

Si colocas un texto entre triples comillas (""" o ''') y no lo asignas a ninguna variable, Python lo leerá pero lo descartará inmediatamente al ejecutarlo.

```Python
''' Hola esto es un comentario
multilínea en Python.
``` 
