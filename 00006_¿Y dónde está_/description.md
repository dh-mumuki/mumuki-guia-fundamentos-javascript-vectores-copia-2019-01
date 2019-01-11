Otro método útil de los arrays es `indexOf`, que nos dice en que posición está un elemento dentro del array:

```javascript
var miArray = ["a", "la", "grande", "le", "puse", "cuca"]
var posicion = miArray.indexOf("grande"); //devuelve 2

var diasLaborales = ["lunes", "martes", "miercoles", "jueves", "viernes"]
var unDia = diasLaborales.indexOf("lunes"); //devuelve 0
```

Como ves, lo "raro" del método `indexOf` es que pareciera devolver siempre 1 menos de lo esperado. ¿Es que los creadores de JavaScript se equivocaron? :confused:

No, se trata de que en JavaScript, al igual que en muchos lenguajes, las posiciones de los arrays arrancan en 0: el primer elemento es la posición 0, el segundo, 1, el tercero, 2, y así.

> ¿Y qué sucede si le pasás por parámetro a `indexOf` un elemento que no tiene? ¡Averigualo vos mismo!
>
> Probá lo siguiente:
>
> ```javascript
> diasLaborales.indexOf("osvaldo")
> ```