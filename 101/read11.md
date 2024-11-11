# Responde

## 1. ¿Qué es el DOM?
Es una interfaz de programación para los documentos HTML y XML. Facilita una representación estructurada del documento y define de qué manera los programas pueden acceder, al fin de modificar, tanto su estructura, estilo y contenido.

## 2. Relación entre DOM y JavaScript
El DOM y JavaScript tienen una conexión cercana, ya que:
* El DOM define la estructura de una página web como un árbol de nodos
* JavaScript es el lenguaje que permite interactuar con esa estructura

A través de JavaScript, los desarrolladores pueden:
* Acceder
* Modificar
* Crear
* Eliminar elementos y contenido en el DOM de manera dinámica

Esto hace posible agregar interactividad y ajustar el aspecto y comportamiento de la página en respuesta a eventos como clics del usuario o entradas de teclado.

## 3. ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?
Para seleccionar un elemento del DOM por su ID, se usa el método `getElementById` de JavaScript.

### Sintaxis
```javascript
document.getElementById("idDelElemento");

Ejemplo
HTML:
<h1 id="titulo">Hola, Mundo</h1>

JavaScript:
const elemento = document.getElementById("titulo");
elemento.innerText = "¡Hola, DOM!";

## 4. Cambiar el color de fondo
Para cambiar el color de fondo de un elemento en el DOM, se utiliza el método style.backgroundColor de JavaScript.
Ejemplo

HTML:
<div id="miElemento">Este es un div</div>
JavaScript:
const elemento = document.getElementById("miElemento");
elemento.style.backgroundColor = "blue";

Notas sobre colores
Se pueden usar diferentes formatos de color:

Nombres de color: "red"
Valores hexadecimales: "#ff0000"
Valores RGB: "rgb(255, 0, 0)"

