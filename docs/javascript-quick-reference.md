1. Declarar variables
Constante (no cambia)
const nombre = "Roberto";

Cuándo usarla:
Cuando el valor no debe cambiar.

Variable (puede cambiar)
let puntos = 10;

Cuándo usarla:
Cuando el valor cambiará durante el programa.

2. Mostrar información
console.log("Hola");

o

console.log(nombre);

o

console.log("Hola", nombre);

3. Operadores matemáticos
+   suma

-   resta

*   multiplicación

/   división

4. Reasignación

Forma larga

puntos = puntos + 5;

Forma corta

puntos += 5;

También:

puntos -= 3;

5. Incrementar y disminuir
puntos++;

puntos--;

6. Comparaciones

Mayor

>

Menor

<

Mayor o igual

>=

Menor o igual

<=

7. if
if (condicion) {

}

La estructura básica es:

if (condicion) {

    instrucciones

}

8. if / else
if (condicion) {

    instrucciones

} else {

    instrucciones

}

9. Paréntesis ()

Los usamos cuando un comando necesita recibir información.

Ejemplos:

console.log("Hola");

El comando console.log recibe un dato.

10. Llaves {}

Las llaves indican un bloque de instrucciones.

Ejemplo:

if (saldo > 0) {

    console.log("Compra realizada");
    console.log("Descontando saldo");
    console.log("Actualizando inventario");

}

Todo eso pertenece al mismo bloque.

11. Punto y coma ;

En JavaScript moderno muchas veces es opcional.

Nosotros lo usaremos siempre.

Es una buena práctica mientras aprendes.

12. Comillas

Texto

"Roberto"

Número

51

Boolean

true

13. Anatomía de una línea

Observa:

let saldo = 100;

Cada parte tiene un significado.

Parte   	Significado
let	        Declara una variable
saldo	    Nombre de la variable
=	        Asigna un valor
100	        Valor
;	        Fin de la instrucción


## Comparadores

```javascript
>
<
>=
<=
===
!==

&&    // AND
||    // OR
!     // NOT