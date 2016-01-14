La expresión SOP (Suma De Productos) es, como lo dice su nombre, una suma (disyunción, OR, '+') de términos que son productos (conjunciones, AND, '.') entre literales.

¿Y qué es un literal? Bueno, es una variable o su negación.

Por ejemplo, una SOP de dos variables `a` y `b` es algo escrito así:

```
-a.b + a.b
```
Notá que la expresión SOP anterior tiene **dos términos** y en el primero hay una negación (`-a`)

Deduzca la formula de la siguiente tabla usando **Suma De Productos** (SOP)
```
p  q  | s
---------
0  0  | 1
0  1  | 1
1  0  | 1
1  1  | 0
```