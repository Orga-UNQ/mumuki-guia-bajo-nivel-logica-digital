Se necesita construir un circuito que permita **seleccionar una de sus dos entradas para proyectarla en la salida**, en función de una línea de control. 


Imaginemos un ejemplo. Supongamos que tenemos dos vias de entrada a la terminal de trenes, pero un solo anden. Entonces necesitamos un *semáforo* que permita dar paso a una via u otra para que el tren avance hasta el andén. Gráficamente:

![Mux trenes](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/mux-tren.png?raw=true "Mux")

Este tipo de operaciones se denomina **multiplexación**. Si el control vale 1, se proyecta la entrada _e0_, y en caso contrario se proyecta _e1_. Es decir que el gráfico mas general (o caja negra) sería: 

![caja negra mux](https://github.com/Orga-UNQ/mumuki-guia-bajo-nivel-logica-digital/blob/master/assets/mux.png?raw=true "Logo Title Text 1")


```
si c=0 entonces s=e0, si c=1 entonces s=e1
```

**Importante:** La línea de control es otra entrada mas! Pero lo interesante es que es otro dispositivo el que la setea/configura


## A trabajar
> Dar la fórmula de verdad de un mux de 2 entradas como el de la figura, considerando una estructura de tabla de verdad  como la que sigue


|c    | e1   | e2 | s |
|:---:|:---:|:---:|:---:|
| 0  | 0    |  0  | ?|
| 0  | 0    |  1  | ?|
| 0  | 1    |  0  | ?|
| 0  | 1    |  1  | ?|
| 1  | 0    |  0  | ?|
| 1  | 0    |  1  | ?|
| 1  | 1    |  0  | ?|
| 1  | 1    |  1  | ?|
