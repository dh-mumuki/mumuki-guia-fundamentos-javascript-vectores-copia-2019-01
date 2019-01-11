Al reves que con `indexOf` (que nos dice la posicion de un elemento particular) existe un operador para averiguar qué elemento hay en una posición dada:

```javascript
ム mesesDelAnio[0]
"enero"
ム ["ese", "perro", "tiene", "la", "cola", "peluda"][1]
"perro"
```

¡Ojo! El índice que le pasás debe ser menor a la longitud del array, o cosas malas pueden suceder.

> Probalo vos mismo en la consola: ¿qué sucede si le pedís el elemento 0 a una lista vacía? ¿O si le pedís el elemento 48 a una lista de 2 elementos?