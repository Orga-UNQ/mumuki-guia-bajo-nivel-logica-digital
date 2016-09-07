## Idea
Al igual que sumamos en un papel, procesando las cadenas en el orden de las columnas, es posible construir un circuito que sume columna por columna, usando en cuenta el circuito que acabamos de construir: **Half Adder**.

La idea, gráficamente, es como sigue:

![alt text](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/fa2.png?raw=true "Full Adder de 2 bit")

La única limitación del half adder es que **solo** tiene en cuenta los bits de la columna que le corresponde, y **no considera el acarreo entre columnas**. 

## Full Adder: Half Adder reloaded

Para tener en cuenta el acarreo, debemos pensar una entrada mas, algo así como lo que se ve en la siguiente imagen:


![alt text](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/fa1.png?raw=true "Full Adder de 1 bit")


## Componiendo las partes

Si contáramos con un HA y un FA ya sería posible resolver el problema de la suma en BSS(2):

![alt text](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/fa2-circuito.png?raw=true "Implementacion del Full Adder de 2 bit")

## A trabajar

Dar la fórmula de verdad del resultado *FA de un bit*, pero no te olvides de pensar primero la siguiente tabla de verdad:

E0 | E1 | Ce | R | Cs
|:---:|:---:|:---:|:---:|:---:|
|0    |0    |0    | ?|?|
|0    |0    |1    | ?|?|
|0    |1    |0    | ?|?|
|0    |1    |1    | ?|?|
|1    |0    |0    | ?|?|
|1    |0    |1    | ?|?|
|1    |1    |0    | ?|?|
|1    |1    |1    | ?|?|



