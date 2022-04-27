Recién vimos que las oraciones, frases o párrafos escritos en un lenguaje natural deberían cumplir ciertas reglas sintácticas. ¿Pero qué pasa cuando escribimos código, es decir, órdenes para una computadora escritas en lenguaje formal? :thinking: ¡También tendremos que cumplir sus reglas! 

Por ejemplo el siguiente código:
 
```javascript
function holaMundo(){
  console.log('hola mundo');
}
```

no es lo mismo que:

```javascript
Function HolaMundo(){
  console.log('hola mundo');
}
```

o esto:

```javascript
function holaMundo[]:{
  console.log('hola mundo');
}
```

ni esto: 

```javascript
function holaMundo()
  console.log('hola mundo');
```

Si no cumplimos con estos principios, a los cuales llamaremos _sintaxis_, la computadora no podrá interpretar nuestra intención y esto llevará a que nuestros programas no funcionen como lo teníamos planeado. :thumbsdown:

> Seleccioná qué porción de código es idéntica a:
>
```javascript
function doble(numero){
  return numero * 2;
}
```