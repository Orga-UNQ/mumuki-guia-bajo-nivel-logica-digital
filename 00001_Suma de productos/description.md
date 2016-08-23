### Estableciendo una norma

La expresión SOP (Suma De Productos) es una **norma de escritura** para las fórmulas de verdad. Como lo dice su nombre, es una suma (disyunción, OR, '+') de términos que son productos (conjunciones, AND, '.') entre literales.

¿Y qué es un literal? Bueno, es una variable o su negación.

Por ejemplo, una SOP de dos variables `a` y `b` es algo escrito así:

```
-a.b + a.b
```
Notá que la expresión SOP anterior tiene **dos términos** y en el primero hay una negación (`-a`)

Además de ser una norma, es un mecanismo para **deducir la fórmula  a partir de una tabla de verdad**. Para hacerlo, se debe extraer el término que describe cada caso de la tabla de verdad que verifica la fórmula. Es decir, **cada fila donde la salida vale 1**. 

Por ejemplo, si tenemos la siguiente tabla de verdad:


|a|  b  | s|
|:---:|:---:|:---:|
|0    |  0  | 1|
|0    |  1  | 0|
|1    |  0  | 0|
|1    |  1  | 0|


Solamente el primer caso tiene salida 1. Su término es `-a.-b`, porque ambos valen 0.

***Ojo:*** El orden de los términos debe escribirse como aparece en la tabla!


## Poniendo a prueba
Teniendo en cuenta la siguiente tabla:

|p| q  | s|
|:---:|:---:|:---:|
|0    |  0  | 1|
|0    |  1  | 0|
|1    |  0  | 1|
|1    |  1  | 0|

Copiá la SOP en el editor:

```
-p.-q+p.-q
```