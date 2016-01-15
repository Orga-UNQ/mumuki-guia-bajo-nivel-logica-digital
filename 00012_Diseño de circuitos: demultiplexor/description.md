Así como la unidad de control necesita multiplexores, son necesarios circuitos que permitan derivar **una única entrada en una determinada salida** en función de líneas de control. 

Esto puede pensarse como cuando un tren llega a la estación terminal y se le debe dar un anden para detenerse.

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

> Dar la fórmula de verdad de un multiplexor de dos salidas