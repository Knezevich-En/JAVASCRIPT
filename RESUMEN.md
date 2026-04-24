### BIENVENIDO AL CURSO JAVASCRIPT DESDE CERO


### CAPITULO #1 🔥

#### 1. CONOCIMIENTO PREVIO
* Conocimientos previos: NO SE NECESITAN CONOCIMIENTOS PREVIOS.
* IMPORTANTE: "NO ES NECESARIO SABER PROGRAMAR", PERO ""ES RECOMENDABLE TENER CONOCIMIENTOS BASICOS DE INFORMATICA Y LOGICA".

### VARIABLES

* Las variables son contenedores para almacenar datos.
* en JS las variables se declaran con la palabra reservada "var", "let" o "const".
* var: variable global.
* let: variable local.
* const: variable constante.

## Tipos de datos

* Los tipos de datos son los siguientes:
    1. "string": texto.
    2. "number": numero.
    3. "boolean": true o false.
    4. "object": objeto.
    5. "array": array.
Casos especiales: NaN, Undefined, Null.

```js
let nombre = "Juan"
let edad = 25
let altura = 1.75
let esVerdadero = true
let esFalso = false
let esIndefinido = undefined
let esNulo = null //let es usado para declarar variables locales
var nombre = "Pedro" //var es usado para declarar variables globales
const PI = 3.1415 //const es usado para declarar variables constantes
// CONST tiene que declararse e inicializarse
variable = "Juan" //sin declarar

    * NaN (Not a Number): Es un valor numérico especial que representa un número inválido.
    * Undefined: Indica que una variable ha sido declarada pero no tiene valor asignado.
    * Null: Representa la ausencia intencional de un valor.

```

### SCOPE
* El scope es el alcance de una variable.
* La diferncia entre var, let y const es el scope.
* var: variable global
* let: variable local
* const: variable constante

### HOISTING
* El hoisting es la capacidad de una variable para ser accedida desde cualquier parte del codigo.
* var: variable global
* let: variable local
* const: variable constante

### EJEMPLO DE HOISTING
```js
console.log(nombre)
var nombre = "Juan"
```

### Diferencia entre var, let y const
La diferencia entre var, let y const es el scope.

### CREAR MULTIPLES VARIABLES
```js
let a = b = c = 10 //crea 3 variables
const a = b = c = 10 //crea 3 variables constantes
var a = b = c = 10 //crea 3 variables globales
let numero1, numero2, numero3 //crea 3 variables
let numero1 = 1, numero2 = 2, numero3 = 3 //crea 3 variables con valores iniciales

//Alert es una funcion que permite mostrar datos al usuario.
alert(numero1)
```

### PRUEBAS CON PROMPT
* Prompt es una funcion que permite obtener datos del usuario.
* Sintaxis: prompt("Ingresa el valor de la variable")
* Ejemplos:
```js
let nombre = prompt("Ingrese su nombre")
let apellido = prompt("Ingrese su apellido")
let edad = prompt("Ingrese su edad")
let altura = prompt("Ingrese su altura")
let esVerdadero = prompt("Ingrese si es verdadero o falso")
let esFalso = prompt("Ingrese si es verdadero o falso")
let esIndefinido = prompt("Ingrese si es verdadero o falso")
let esNulo = prompt("Ingrese si es verdadero o falso")

console.log(nombre)
console.log(apellido)
console.log(edad)
console.log(altura)
console.log(esVerdadero)
console.log(esFalso)
console.log(esIndefinido)
console.log(esNulo)

alert(nombre)
alert(apellido)
alert(edad)
alert(altura)
alert(esVerdadero)
alert(esFalso)
alert(esIndefinido)
alert(esNulo)
```

### OPERADORES
* Los operadores son simbolos que permiten realizar operaciones con variables.
* Operadores aritméticos: +, -, *, /, %
    * La suma (+) se puede usar para concatenar strings.
    * La resta (-) se puede usar para restar números.
    * La multiplicación (*) se puede usar para multiplicar números.
    * La división (/) se puede usar para dividir números.
    * El módulo (%) se puede usar para obtener el residuo de una división.
    - Toman valores numericos para realizar operaciones ya sean literales o variables. Retornan un valor numerico unico. 
    - Ejemplos: 
    ```js
    let numero1 = 10;
    numero += 5;
    numero -= 5;
    numero *= 5;
    numero /= 5;
    numero %= 5;

    document.write("numero: " + numero);
    console.log("numero: " + numero);
    alert("numero: " + numero);
    ```


* Operadores de asignación: =, +=, -=, *=, /=, %=
    - Toman un valor o operacion para asignar a una variable. 
    - Ejemplos:
    ```js
    let esIndefinido = undefined
    let esNulo = null
    var nombre = "Pedro"
    const PI = 3.1415
    variable = "Juan"
    let numero = 10;
    numero += 5;
    numero -= 5;
    numero *= 5;
    numero /= 5;
    numero %= 5;

    document.write("numero: " + numero);
    console.log("numero: " + numero);
    alert("numero: " + numero);
    ```
    

* Operadores de comparación: ==, !=, ===, !==, <, >, <=, >=
    - Toman valores para comparar ya sean literales o variables. Retornan un valor booleano. 
    - Ejemplos: 
    ```js
    let valor1 = "PRUEBA" 
    let valor2 = "PRUEBA"
    valor1 != valor2
    valor1 === valor2
    valor1 !== valor2
    valor1 < valor2
    valor1 > valor2
    valor1 <= valor2
    valor1 >= valor2

    document.write(valor1 != valor2)
    ```
* Operadores lógicos: &&, ||, !
    - Toman valores para comparar ya sean literales o variables. Retornan un valor booleano. 
    - Ejemplos: 
    ```js
    let nombre = "Juan"
    let edad = 25
    let altura = 1.75
    let esVerdadero = true
    let esFalso = false
    let esIndefinido = undefined
    let esNulo = null
    var nombre = "Pedro"
    const PI = 3.1415
    variable = "Juan"
    ```
* Operadores de incremento y decremento: ++, --
    - Toman valores para comparar ya sean literales o variables. Retornan un valor booleano. 
    - Ejemplos: 
    ```js
    let nombre = "Juan"
    let edad = 25
    let altura = 1.75
    let esVerdadero = true
    let esFalso = false
    let esIndefinido = undefined
    let esNulo = null
    var nombre = "Pedro"
    const PI = 3.1415
    variable = "Juan"
    ```
* Operador ternario: ? :


### CONCATENACIÓN
La concatenación es la unión de strings. 
```js
let cadena1 = "HOLA"
let cadena2 = "MUNDO"
frase = cadena1 + cadena2 + "ES UNA PRUEBA" //podemos concatenar variables y strings
document.write(frase)
console.log(frase)
alert(frase)

//AHORA LA CONCATENACIÓN DE NUMEROS

let num1 = 10
let num2 = 20
union = "" + num1 + num2
document.write(union)
console.log(union)
alert(union)
```
## USO DE CONCAT
Para usar el método concat necesitamos usar el operador "+" para concatenar y al menos tener un string para concatenar.
```js
let cadena1 = "HOLA"
let cadena2 = "MUNDO"
frase = cadena1.concat(cadena2, "ES UNA PRUEBA") //podemos concatenar variables y strings
document.write(frase)
console.log(frase)
alert(frase)
```
### TAMBIÉN SE PUEDE USAR  BACKTICK PARA LA CONCATENACIÓN Y LA VARIABLE DENTRO DE ${ }
- Se usa para concatenar strings y variables.
- La variable se escribe dentro de ${ }.
- Debe usar Backtick `` para que funcione.
- La gran ventaja es que no hay que usar el operador "+" para concatenar.

```js
let nombre = "Arturo Knezevich";
frase = `HOLA ${nombre} como estas`;

document.write(frase);
console.log(frase);
alert(frase);
```

## ESCAPE DE COMILLAS SIMPLES Y DOBLES
Para escapar una comilla simple necesitamos usar " \" " y para escapar una comilla doble necesitamos usar " \" ".

```js
let frase = "El dice que \"HOLA\" a los 25 años";
document.write(frase);
console.log(frase);
alert(frase);
```

### CAMEL CASE
- Es una forma de escribir variables en minusculas con la primera letra de cada palabra en mayusculas.
- Se usa para escribir variables que contienen mas de una palabra.
* Ejemplos: 
```js
let nombreCompleto = "Arturo Knezevich"
```


### CONDICIONALES
- Los condicionales son estructuras de control que permiten ejecutar codigo de forma condicional.

Sintaxis: 
```js
if (condicion) {
    // codigo que se ejecuta si la condicion es verdadera
}

else if (condicion) {
    // codigo que se ejecuta si la condicion es verdadera
    document.write("La condicion es verdadera")
    console.log("La condicion es verdadera")
    alert("La condicion es verdadera")
}

else {
    // codigo que se ejecuta si la condicion es verdadera
    document.write("La condicion es verdadera")
    console.log("La condicion es verdadera")
    alert("La condicion es verdadera")
}


```

### CAPITULO #2 🔥


