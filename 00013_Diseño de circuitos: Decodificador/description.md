### Idea

Un decodificador traduce una cadena de bits en un pulso para una determinada salida. Podemos pensalo como una traduccion de una cadena en bss a un valor numérico

![alt text](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/deco.png?raw=true "cajanegra, deco")

Por ejemplo, los siguientes son dos de los cuatro casos del deco:

![alt text](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/caso1-deco.png?raw=true "caso, deco")


![alt text](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/caso2-deco.png?raw=true "caso, deco")

### Multiples salidas

Quizás ya lo notaste: el decodificador tiene muchas salidas! Es importante aclarar que cada salida es una [función](https://en.wikipedia.org/wiki/Function_(mathematics)) de las entradas y por lo tanto, debemos dar **una funcion de verdad para cada una**.

La tabla de verdad del decodificador es entonces:

| e1  |  e2 | s1|s2|s3|s4
|:---:|:---:|:---:|:---:|:---:|:---:|
|0    |  0  | 1|0|0|0|
|0    |  1  | 0|1|0|0|
|1    |  0  | 0|0|1|0|
|1    |  1  | 0|0|0|1|



## A trabajar

> Escribí la función de verdad para la salida s1, consuderando la tabla de verdad descripta arriba

