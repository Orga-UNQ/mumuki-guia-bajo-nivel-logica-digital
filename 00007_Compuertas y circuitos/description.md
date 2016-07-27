Existen muchas formas de diseñar o construir los circuitos. Un mecanismo que ejercitaremos es el siguiente

1. Pensar la **tabla de verdad**: enumerar los casos y pensar como debe ser la salida
2. Derivar la **fórmula de verdad** a partir de la tabla, usando [SoP](http://orga-unq.mumuki.io/exercises/2165-bajo-nivel-logica-digital-suma-de-productos) o PoS
3. _Cablear_ el **circuito** a partir de la fórmula, usando las compuertas básicas.


Este último paso puede incluir compuertas complejas (como el Nand, Nor, XOR) o incluso otros circuitos (que ya diseñaste o pensas diseñar después). Esto refleja la **escencia del reuso y la modularización** que se pone en práctica también a la hora de programar.

Las compuertas que usaremos se grafican como sigue:

![alt text](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/referencias.png?raw=true "Logo Title Text 1")

Para poder ejercitar, usaremos la siguiente notación:


|compuerta    | símbolo|
|:---:|:---:|
|xor   |  #   |
|nand  |  &   |
|nor   |  $   |


> Entremos en calor: copiá y pegá en el editor la expresión (a#b)+a