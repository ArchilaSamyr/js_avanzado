# Tema 1: Arrays en JavaScript

## ¿Qué es un Array?

Un Array (arreglo) permite guardar varios valores dentro de una sola variable. Sus elementos tienen índices que comienzan en `0`.

```javascript
let frutas = ["Manzana", "Pera", "Uva"];

console.log(frutas[0]); // Manzana
console.log(frutas[2]); // Uva
```

## Características

- Guarda varios elementos en una variable.
- Los índices comienzan en cero.
- Los elementos se pueden consultar, modificar, agregar y eliminar.
- Puede guardar diferentes tipos de datos.

## Propiedad y métodos comunes

| Nombre | Función | Ejemplo |
|---|---|---|
| `length` | Devuelve la cantidad de elementos | `frutas.length` |
| `push()` | Agrega al final | `frutas.push("Mango")` |
| `pop()` | Elimina el último elemento | `frutas.pop()` |
| `unshift()` | Agrega al inicio | `frutas.unshift("Fresa")` |
| `shift()` | Elimina el primer elemento | `frutas.shift()` |
| `includes()` | Comprueba si existe un elemento | `frutas.includes("Pera")` |
| `indexOf()` | Devuelve la posición de un elemento | `frutas.indexOf("Uva")` |

## Ejemplo práctico

```javascript
let videojuegos = ["Minecraft", "FIFA", "Roblox"];

console.log("Lista inicial:", videojuegos);

videojuegos.push("Mario");
console.log("Después de agregar:", videojuegos);

videojuegos.pop();
console.log("Después de eliminar el último:", videojuegos);

console.log("Cantidad:", videojuegos.length);
console.log("¿Está FIFA?", videojuegos.includes("FIFA"));
```

## Ejercicio para los compañeros: Lista de videojuegos

Crea un archivo llamado `ejercicio_arrays.js` y completa las tareas:

1. Muestra la lista inicial.
2. Agrega un videojuego al final con `push()`.
3. Elimina el último videojuego con `pop()`.
4. Muestra cuántos videojuegos hay con `length`.
5. Comprueba si existe `"Roblox"` con `includes()`.
6. Muestra la posición de `"FIFA"` con `indexOf()`.

## Cómo ejecutar

Puedes ejecutar los archivos en la consola del navegador o con Node.js:

```bash
node ejemplo_arrays.js
```
