Recién vimos que las oraciones, frases o párrafos escritos en un lenguaje natural deberían cumplir ciertas reglas sintácticas. ¿Pero qué pasa cuando escribimos código, es decir, órdenes para una computadora escritas en lenguaje formal? :thinking: ¡También tendremos que cumplir sus reglas! 

Por ejemplo el siguiente código:
 
```python
def hola_mundo():
    print('hola mundo')
```

no es lo mismo que:

```python
Def Hola_mundo():
    Print('hola mundo')
```

o esto:

```python
def hola_mundo[]:
    print('hola mundo')
```

ni esto: 

```python
def hola_mundo():
print('hola mundo')
```

Si no cumplimos con estos principios, a los cuales llamaremos _sintaxis_, la computadora no podrá interpretar nuestra intención y esto llevará a que nuestros programas no funcionen como lo teníamos planeado. :thumbsdown:

> Seleccioná qué porción de código es idéntica a:
>
```python
def doble(numero):
   return numero * 2
```