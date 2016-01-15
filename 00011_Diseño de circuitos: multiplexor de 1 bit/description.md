Se necesita construir un circuito que permita **seleccionar una de sus dos entradas para proyectarla en la salida**, en función de una línea de control. 

Este tipo de operaciones se denomina **multiplexación**. Si el control vale 1, se proyecta la entrada _e0_, y en caso contrario se proyecta _e1_. Es decir:

```
si c=0 entonces s=e0, si c=1 entonces s=e1
```

**Importante:** La línea de control es otra entrada mas! Pero lo interesante es que es otro dispositivo el que la setea/configura

La caja negra de un multiplexor es:

![caja negra mux](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/mux.png?raw=true "Logo Title Text 1")


## A trabajar
> Dar la fórmula de verdad de un demux de 2 entradas como el de la figura
