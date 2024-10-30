# 1. ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?

JavaScript tiene dos tipos principales de datos: **primitivos** y **tipos de referencia**.

## Tipos de datos primitivos:
- **Boolean**: `true` y `false`.
- **null**: Un valor especial que representa la ausencia de valor.
- **undefined**: Indica que una variable ha sido declarada, pero no tiene un valor asignado.
- **Number**: Representa números, ya sea enteros o decimales (ej: `42`, `3.14`).
- **BigInt**: Representa números enteros con precisión arbitraria (ej: `9007199254740992n`).
- **String**: Una secuencia de caracteres que representa texto (ej: `"Hola"`).
- **Symbol**: Representa un valor único e inmutable.

## Tipos de datos de referencia:
Estos son mutables y se almacenan por referencia, es decir, cuando se asignan o pasan como argumento, se pasa la referencia en memoria, no el valor.

- **Object**: Colección de pares clave-valor para almacenar datos estructurados. Incluye varios subtipos:
  - **Array**: Lista ordenada de valores.
  - **Function**: Bloque de código que puede ejecutarse.
  - **Date**: Representa fechas y horas.
  - **RegExp**: Expresiones regulares para patrones de búsqueda en cadenas.
  - **Otros**: Objetos como `Map`, `Set`, `WeakMap`, `WeakSet`, etc., que permiten organizar datos de distintas maneras.


# 2. ¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa?

Explica cómo usar las estructuras `if` y `else` en JavaScript. Describe de manera simple su sintaxis y cómo funcionan para ejecutar un bloque de código si se cumple una condición. Incluye ejemplos de cómo se usa `else if` para verificar más de una condición y qué papel cumplen estas estructuras dentro de un programa, es decir, cómo ayudan a tomar decisiones y controlar el flujo de las acciones según ciertas condiciones o valores.


# 3. ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?

En JavaScript, los operadores permiten realizar operaciones sobre valores o variables. Existen varios tipos:

- **Operadores aritméticos**: Realizan cálculos básicos como suma, resta, multiplicación, división, módulo (resto), exponenciación, e incremento/decremento.
- **Operadores de asignación**: Asignan valores a las variables, como `=`, y combinan operadores aritméticos para hacer operaciones y asignar en un solo paso (ej: `+=`).
- **Operadores de comparación**: Comparan dos valores y devuelven `true` o `false`. Incluyen operadores de igualdad (débil y estricta) y operadores para mayor, menor o diferente.
- **Operadores lógicos**: Combinan expresiones y devuelven `true` o `false`. Incluyen AND (`&&`), OR (`||`), y NOT (`!`), para evaluar varias condiciones.
- **Operador ternario**: Versión compacta de `if-else`, que evalúa una condición y devuelve un valor si es verdadera y otro si es falsa.

Los **operadores aritméticos** son esenciales para realizar cálculos matemáticos y manipular valores numéricos en un programa.


# 4. ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?

- **`var`**: Tiene un alcance de función (visible en toda la función) y permite reasignación y redeclaración. Su declaración es "elevada" al principio del ámbito.
  
- **`let`**: Tiene un alcance de bloque (solo es accesible dentro del bloque `{}`). Permite reasignación, pero no redeclaración en el mismo bloque. No se puede usar antes de su declaración.

- **`const`**: También tiene un alcance de bloque y debe inicializarse al declararse. No permite reasignación, pero los datos internos de objetos o arreglos pueden modificarse.