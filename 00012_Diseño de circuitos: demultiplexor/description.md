### Idea

Así como la unidad de control necesita [multiplexores](http://orga-unq.mumuki.io/exercises/2175-bajo-nivel-logica-digital-diseno-multiplexador-de-1-bit), son necesarios circuitos que permitan derivar **una única entrada en una determinada salida** en función de líneas de control. 

Retomando la metáfora de los trenes: esto puede pensarse como cuando un tren llega a la estación terminal y se le debe dar un anden para detenerse.

![demux amarillo](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/demux-tren-amarillo.png?raw=true "Tren derivado al andén amarillo")


![demux azul](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/demux-tren-azul.png?raw=true "Tren derivado al andén amarillo")



¿Este circuito te parece útil para algo? Te damos una pista... el comportamiento puede describirse así:



¡Es una **estructura condicional**!


```
si c=0 entonces s0=e, si c=1 entonces s1=e
```

En términos generales, el demultiplexor tiene la siguiente estructura


![caja negra demux](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/demux.png?raw=true "Demultiplexor")



## A trabajar
> Dar la fórmula de verdad de un multiplexor de dos salidas (como el que se describió)

| e  |  c1 | c2 | s 
|:---:|:---:|:---:|:---:|
|0|0    |  0  | ?|
|0|0    |  1  | ?|
|0|1    |  0  | ?|
|0|1    |  1  | ?|
|1|0    |  0  | ?|
|1|0    |  1  | ?|
|1|1    |  0  | ?|
|1|1    |  1  | ?|
