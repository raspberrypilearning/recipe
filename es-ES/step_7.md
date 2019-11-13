## ¡Colores!

Vamos a añadir algo de color a la página web de tu receta.

+ Ya has aprendido a añadir color al texto de tu página web. Añade este código dentro de tu archivo `style.css`, para hacer que todo el texto del cuerpo de tu página web sea azul:

    body {
        color: blue;
    }
    

![screenshot](images/recipe-blue.png)

+ Tu navegador conoce los colores como `blue` (azul), `yellow` (amarillo) y hasta `lightgreen` (verde claro), pero ¿sabías que tu navegador sabe los **nombres** de más de 140 colores?

Hay una lista de todos los nombres de colores que puedes usar: [ jumpto.cc/colours ](http://jumpto.cc/colours), que incluye nombres de colores como ` tomato` (tomate), ` firebrick ` (ladrillo) y ` peachpuff` (melocotón).

Cambia el color del texto de `blue` (azul) a `tomato` (tomate).

![screenshot](images/recipe-tomato.png)

+ Tu navegador sabe los nombres de 140 colores, pero de hecho sabe los **códigos de color** de ¡más de 16 millones de colores!

Para decirle al navegador el color que debe mostrar, sólo debes decirle cuánto rojo, verde y azul debe usar.

Las cantidades de rojo, verde y azul se escriben como números entre `0` y`255`.

![screenshot](images/recipe-rgb-img.png)

Añade este código CSS para el cuerpo de la página web, para mostrar un color verde claro de fondo:

    background: rgb(250,250,210);
    

![screenshot](images/recipe-rgb.png)

+ Si lo prefieres, puedes decirle al navegador qué color mostrar usando el código hexadecimal (or **hex code**). Esto funciona de forma similar al código `rgb()` de arriba, excepto que el código hex siempre empieza con `#`, y usa números hexadecimales entre `00` y `ff` para la cantidad de rojo, verde y azul.

![screenshot](images/recipe-hex-img.png)

Sustituye el código `rgb()` con este código hex:

    background: #fafad2;
    

![screenshot](images/recipe-hex.png)

¡Deberías ver el mismo verde claro de antes!