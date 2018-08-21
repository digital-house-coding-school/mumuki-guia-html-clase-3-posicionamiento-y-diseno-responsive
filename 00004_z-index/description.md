Imaginemos ahora que contamos con una sección en nuestra página con varios articles con cajitas:

``` html
<article>
  <div class="yellow"> </div>
  <div class="red"> </div>
</article>
```
El primer `<div>` tiene fondo amarillo y mide 20px por 20px. El segundo `<div>` tiene fondo rojo y mide 100px por 100px.

Vamos a hacer que se superpongan y probar que pasa con nuestra nueva propiedad `z-index`

Para esto:

> 1. Demosle a ambos divs la propiedad `position:relative`. Sin aclarar position, no podemos utilizar z-index
> 2. Movamos el `<div class="yellow">` 10px desde arriba.
> 3. Agreguemos z-index al `<div class="red">` y cambiemos su valor a ver que pasa!


