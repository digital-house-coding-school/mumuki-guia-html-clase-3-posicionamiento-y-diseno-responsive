Imaginemos ahora que contamos con un article que tiene adentro dos divs. El primero tiene fondo amarillo y mide 20px por 20px. El segundo tiene fondo rojo y mide 100px por 100px.

``` html
<article>
  <div class="yellow"> </div>
  <div class="red"> </div>
</article>
```

Vamos a hacer que estas cajas se superpongan para empezar a probar qué pasa con la propiedad z-index.

> Primero, asignemosle a cada div la propiedad position:relative. Sin declarar esto, no podemos utilizar z-index.

> Después, movamos el div con clase yellow 10px desde arriba.

> Por último, declaremos la propiedad z-index al div con clase red y cambiemos su valor para ver que pasa y comparar distintos resultados!

Te dejamos una imagen de referencia de como se ve el sitio antes de que vos agregues código:

<img src="https://raw.githubusercontent.com/digital-house-coding-school/mumuki-guia-html-clase-3-posicionamiento-y-diseno-responsive/master/assets/Ejercicio-4_1562088050609.PNG" alt="Ejercicio-4_1562088050609.PNG" width="100%" height="auto">
