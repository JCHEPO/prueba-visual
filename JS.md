## diferencias entre === 

🔑 Diferencia entre == y ===

== ( igualdad débil ): compara los valores conversión automática de tipos (coerción).
Ejemplo: el número 5 y el string "5" los considera iguales.

=== ( igualdad estricta ): compara tanto el valor como el tipo de dato.
Ejemplo: 5 (number) y "5" (string) los considera diferentes.
<h2>Ejemplos</h2>
// Igualdad débil (==)
console.log(5 == "5");  // true -> convierte "5" a número antes de comparar
console.log(true == 1); // true -> convierte true a 1
console.log(false == 0); // true -> convierte false a 0

// Igualdad estricta (===)
console.log(5 === "5");  // false -> uno es number, el otro string
console.log(5 === 5);    // true -> mismo valor y mismo tipo
console.log(true === 1); // false -> boolean vs number
console.log(false === 0); // false -> boolean vs number
