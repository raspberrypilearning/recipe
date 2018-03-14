## ¡Colores!

Vamos a añadir algo de color a tu página web.

+ Ya habíamos aprendido como añadir color al texto de la página web. Añade el siguiente código dentro del fichero `style.css` para que el color de todo el texto del la página web sea azul:

```
body {
    color: blue;
}
```

![screenshot](images/recipe-blue.png)

+ El navegador conoce colores como `blue` (azul), `yellow` (amarillo) e incluso `lightgreen` (verde claro), pero, ¿sabías que los navegadores actuales conocen más de 500 __nombres__ de colores distintos?

Existe una lista con todos los nombres de color que puedes usar: [jumpto.cc/web-colours](http://jumpto.cc/web-colours), que incluye nombres de colores como `tomato` (tomate), `firebrick` (ladrillo refractario) y `peachpuff` (melocotón pocho).

Cambia el color del texto de `blue` (azul) to `tomato` (tomate).

![screenshot](images/recipe-tomato.png)

+ Tu navegador conoce el nombre de 140 colores, pero, ¡conoce los __valores__ de más de 16 millones de colores!


Así como debes saber, todos los colores se pueden obtener a partir de los colores primarios: rojo, verde y azul. Para indicarle al navegador que color mostrar tan solo necesitas saber que cantidad de cada color primario emplear.

La cantidad de color rojo, verde y azul que se usará puede ser escrito como un número entre `0` y `255`.

![screenshot](images/recipe-rgb-img.png)

Añade este código al CSS para cambiar el color del cuerpo de la página web, se mostrará un color amarillo claro en el fondo:

```
background: rgb(250,250,210);
```

![screenshot](images/recipe-rgb.png)

+ Si lo prefieres puedes decirle al navegador que color mostrar mediante código hexadecimal (o __hex code__). Esto funciona de una manera similar al código `rgb()` de arriba, excepto que los códigos hexadecimales empiezan con el símbolo `#`, y usan ‘números’ hexadecimales entre `00` y `ff` para la cantidad de rojo, verde y azul.

![screenshot](images/recipe-hex-img.png)

Sustituye el código `rgb()` en la CSS con este código hexadecimal:

```
background: #fafad2;
```

![screenshot](images/recipe-hex.png)

Deberías ver el mismo tono de amarillo claro que antes
