_Ahora que ya sabemos qué es lo que queremos (`gananciaTotal`), razonemos cómo hacerlo...._

Vamos de a poquito: si el array no tuviera elementos, ¿cuanto debería ser la sumatoria? ¡0!

```javascript
function gananciaTotal0(unPeriodo) {
  var sumatoria = 0;
  return sumatoria;
}
```

¿Y si tuviera exactamente 1 elemento? Estem... 0.... ¿más ese elemento? ¡Exacto!

```javascript
function gananciaTotal1(unPeriodo) {
  var sumatoria = 0;
  sumatoria = sumatoria + unPeriodo[0];
  return sumatoria;
}
```

¿Y si tuviera 2 elementos?

```javascript
function gananciaTotal2(unPeriodo) {
  var sumatoria = 0;
  sumatoria = sumatoria + unPeriodo[0];
  sumatoria = sumatoria + unPeriodo[1];
  return sumatoria;
}
```

¿Y si tuviera 3 elementos?

```javascript
function gananciaTotal3(unPeriodo) {
  var sumatoria = 0;
  sumatoria = sumatoria + unPeriodo[0];
  sumatoria = sumatoria + unPeriodo[1];
  sumatoria = sumatoria + unPeriodo[2];
  return sumatoria;
}
```

> ¿Empezas a ver un patrón? Tratá de escribir `gananciaTotal4` que funcione para 4 elementos.

