Se necesita diseñar un restador con carry de 1 bit, con las siguiente caracteristicas:

* tiene 3 entradas: 
  - los numeros a restar (A y B que son cadenas del sistema BSS(1))
  - el borrow de entrada (el anterior pidio 1)
* Tiene 2 salidas:
  - el resultado de la resta 
  - el borrow.

De nuevo, es util usar la idea del [**Full Adder**](http://orga-unq.mumuki.io/exercises/2179-bajo-nivel-logica-digital-circuitos-arimeticos-full-adder) y comenzar completando una tabla como la siguiente: 


| A   |   B |  Ce |   R |  Cs |
|:---:|:---:|:---:|:---:|:---:|
|0    |0    |0    | ?|?|
|0    |0    |1    | ?|?|
|0    |1    |0    | ?|?|
|0    |1    |1    | ?|?|
|1    |0    |0    | ?|?|
|1    |0    |1    | ?|?|
|1    |1    |0    | ?|?|
|1    |1    |1    | ?|?|

Luego escribi la formula de verdad de **la salida Cs** en el editor 
