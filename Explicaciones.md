# Explicaciones

VARIABLES
Las variables seran el lugar donde guardaremos información para usarla después. Puede ser un nombre, numero, etc.

Por ejemplo si ponemos:
let nombre = "Juan";
Aquí, nombre es el lugar donde guardamos la información que en este caso es ¨Juan'.

STRING
Un String es una cadena de texto o mejor dicho,  solo un pedazo de texto que siempre ira entre comillas.

Por ejmplo si ponemos:
let saludo = "Hola";
El Srting seria "Hola"

FUNCIONES (argumentos, return)
Una función es como una máquina a la cual le damos algo de entrada, hace algo con eso, y nos devuelve una salida.
Por ejemplo si ponemos:
function sumar(a, b) {
  return a + b;
}
Aquí, a y b son los ingredientes (argumentos), y return nos da el resultado. Si llamamos sumar(3, 4), nos devuelve 7.

DECLARACIONES (if)
En este caso el 'if' ('si' en ingles) se utiliza en entornos decisivos, para tomar una decision. El if es como tomar decisiones en la vida real. Si pasa algo, hacemos una cosa; si no, hacemos otra.
Por ejmplo:
let edad = 15;

if (edad >= 18) {
  console.log("Puedes conducir.");
} else {
  console.log("Aún no puedes conducir.");
}
En este caso si 'edad' es 18 o más, se mostrara un mensaje, si no, se mostrara otro.

VALORES Boolean (true, false)
Estos se utilizan para indicar si algo es verdadera o es falso.