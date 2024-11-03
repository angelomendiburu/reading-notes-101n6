## 1. ¿Qué es “Control Flow” (Control de Flujo)?

El **control de flujo** se refiere a cómo se dirige la ejecución de un programa, es decir, la manera en que el código toma decisiones y se ejecuta en distintos caminos, dependiendo de condiciones y valores. Es esencial para hacer que el programa actúe de manera dinámica y responda a diferentes situaciones.

---

## 2. ¿Qué es una “function” (Función) de JavaScript?

Una **función** es un "subprograma" que puede ser llamado por código externo (o interno en caso de recursión) a la función. Al igual que el programa en sí mismo, una función se compone de una secuencia de declaraciones, que conforman el llamado **cuerpo de la función**. Se pueden pasar valores a una función, y la función puede devolver un valor.

En JavaScript, las funciones son **objetos de primera clase**, es decir, son objetos y se pueden manipular y transmitir al igual que cualquier otro objeto. Concretamente son objetos `Function`.

---

## 3. ¿Cuántas veces se ejecutará un bucle “while”?

La cantidad de veces que se ejecuta un bucle `while` depende de la condición:

- Si la condición es `true` al principio y se vuelve `false` en algún momento, el bucle se ejecutará hasta que eso ocurra.
- Si la condición es siempre `true`, habrá un **bucle infinito**.
- Si la condición es `false` al inicio, el bucle **no se ejecutará**.

Es importante tener un cambio en el valor que se evalúa en la condición para que el bucle eventualmente se detenga y evitar bucles infinitos no deseados.

---

## 4. ¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?

Para agregar un elemento al final de un array, puedes usar el método **`push()`**. Este método agrega uno o más elementos al final del array y devuelve la nueva longitud del array.

### Sintaxis

elemento1, elemento2, ..., elementoN: Los elementos que deseas agregar al final del array. Puedes agregar uno o más elementos.

let frutas = ["manzana", "naranja", "plátano"];

frutas.push("uva");

console.log(frutas); // Resultado: ["manzana", "naranja", "plátano", "uva"]

En este caso:

La función push() agrega "uva" al final del array frutas.
El array frutas ahora tiene cuatro elementos, con "uva" como el último elemento.
Agregar múltiples elementos
También puedes agregar varios elementos al mismo tiempo:

let frutas = ["manzana", "naranja", "plátano"];

frutas.push("uva", "mango");

console.log(frutas); // Resultado: ["manzana", "naranja", "plátano", "uva", "mango"]

En este caso, tanto "uva" como "mango" se agregan al final del array frutas.

Retorno del método push()
El método push() devuelve la nueva longitud del array después de agregar los elementos:

let frutas = ["manzana", "naranja"];
let nuevaLongitud = frutas.push("plátano");

console.log(nuevaLongitud); // Resultado: 3
console.log(frutas);        // Resultado: ["manzana", "naranja", "plátano"]

Este método es una forma sencilla y eficiente de agregar elementos al final de un array en JavaScript.