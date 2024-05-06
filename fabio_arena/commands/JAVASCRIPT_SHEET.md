Ecco alcuni esempi di comandi JavaScript:

- Dichiarazione di variabili:
var x = 5; // Dichiarazione di una variabile utilizzando var
let y = "Hello"; // Dichiarazione di una variabile utilizzando let
const PI = 3.14; // Dichiarazione di una costante utilizzando const

- Operazioni aritmetiche:
let a = 10;
let b = 5;
let sum = a + b; // Somma
let difference = a - b; // Differenza
let product = a * b; // Prodotto
let quotient = a / b; // Quoziente

- Condizioni:
let age = 20;
if (age >= 18) {
    console.log("Sei maggiorenne");
} else {
    console.log("Sei minorenne");
}

- Cicli:
// Ciclo while
let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}

// Ciclo for
for (let j = 0; j < 5; j++) {
    console.log(j);
}

- Funzioni:
// Dichiarazione di una funzione
function greet(name) {
    console.log("Ciao, " + name + "!");
}

// Chiamata di una funzione
greet("Mario");
Array:
javascript
let fruits = ["Mela", "Banana", "Arancia"];
console.log(fruits[0]); // Output: Mela
console.log(fruits.length); // Output: 3

// Iterazione su un array
fruits.forEach(function(fruit) {
    console.log(fruit);
});

- Manipolazione del DOM:
html
<!DOCTYPE html>
<html>
<head>
    <title>JavaScript DOM</title>
</head>
<body>
    <p id="demo">Clicca sul pulsante</p>
    <button onclick="changeText()">Clicca qui</button>

    <script>
        function changeText() {
            document.getElementById("demo").innerHTML = "Testo modificato!";
        }
    </script>
</body>
</html>



Questi sono solo alcuni esempi di comandi JavaScript che mostrano varie funzionalità come dichiarazione di variabili, operazioni aritmetiche, condizioni, cicli, funzioni, array e manipolazione del DOM.