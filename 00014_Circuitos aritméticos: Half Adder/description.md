## Idea
La ALU debe poder realizar operaciones entre cadenas de un determinado sistema binario, supongamos de 16 bits. 

¿Cómo sería un sumador de dos cadenas BSS(16)?

```
Caja negra del FA(16)
```

Vamos a construirlo, pero empecemos por algo mas simple, un sumador de dos cadenas de 1 bit.

## Primero lo primero

Lo mínimo que necesitamos en sumar dos cadenas BSS(1), o sea dos bits (A y B). Gráficamente se necesita:

![alt text](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/ha1.png?raw=true "texto")

Para resolverlo, debemos tener en mente [los 4 casos de la suma de 1 bit](http://orga-unq.mumuki.io/exercises/2189-bajo-nivel-sistemas-de-numeracion-aritmetica-binaria-sumando-en-bss1):

|a|b|s|
|:---:|:---:|:---:|
|0| 0 | 0|
|0| 1 | 1|
|0| 1 | 1|
|1| 1 | 0, c=1|


Es importante notar el ultimo caso, donde hay un acarreo! esto puede pensarse como **dos salidas**:


|a| b | s | c
|:---:|:---:|:---:|:---:|
|0| 0 | 0 | 0|
|0| 1 | 1 | 0 |
|1| 0 | 1 | 0|
|1| 1 | 0 | 1|

## A trabajar
> Escribir la fórmula de verdad para la salida S