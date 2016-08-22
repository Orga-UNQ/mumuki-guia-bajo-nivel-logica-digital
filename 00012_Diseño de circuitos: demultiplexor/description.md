### Idea

Así como la unidad de control necesita [multiplexores](http://orga-unq.mumuki.io/exercises/2175-bajo-nivel-logica-digital-diseno-multiplexador-de-1-bit), son necesarios circuitos que permitan derivar **una única entrada en una determinada salida** en función de líneas de control. 

Retomando la metáfora de los trenes: esto puede pensarse como cuando un tren llega a la estación terminal y se le debe dar un anden para detenerse.

![demux amarillo](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/demux-tren-amarillo.png?raw=true "Tren derivado al andén amarillo")


![demux azul](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/demux-tren-azul.png?raw=true "Tren derivado al andén amarillo")

![caja negra demux](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/demux.png?raw=true "Demultiplexor")


¿Este circuito te parece útil para algo? Te damos una pista... el comportamiento puede describirse así:

```
si c=0 entonces s0=e, si c=1 entonces s1=e
```

¡Es una **estructura condicional**!



```
 Acá va un caso del deco, donde la entrada vale 0 y debe salir por s0
```


```
 Acá va un caso del deco, donde la entrada vale 1 y debe salir por s1
```

## A trabajar
> Dar la fórmula de verdad de un multiplexor de dos salidas