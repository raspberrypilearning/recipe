## ¡Colores!

Vamos a añadir algo de color a la página web de tu receta.

+ Ya has aprendido a añadir color al texto de tu página web. Añade este código dentro de tu fichero `style.css`, para hacer que todo el texto del cuerpo de tu página web sea azul:

    body {
        color: blue;
    }
    

![captura de pantalla](images/recipe-blue.png)

+ Tu navegador conoce los colores como `azul`, `amarillo` y hasta `verde claro`, pero ¿sabías que tu navegador sabe los **nombres** de más de 140 colores?

Hay una lista de todos los nombres de colores que puedes usar: [ jumpto.cc/colours ](http://jumpto.cc/colours), que incluye nombres de colores como ` tomato`, ` firebrick ` y ` peachpuff`.

Cambia el color del texto de `azul` a `tomate`.

![screenshot](images/recipe-tomato.png)

+ Tu navegador sabe los nombres de 140 colores, pero de hecho sabe los ** códigos de color ** de ¡más de 16 millones de colores!

Para decirle al navegador el color que debe mostrar, sólo debes hacerle saber cuánto rojo, verde y azul debe usar.

Las cantidades de rojo, verde y azul se escriben entre `0` y`255`.

![captura de pantalla](images/recipe-rgb-img.png)

Añade este código de CSS para el cuerpo de la página web, para mostrar el verde claro del fondo:

    background: rgb(250,250,210);
    

![screenshot](images/recipe-rgb.png)

+ Si lo prefieres, puedes decirle al navegador qué color mostrar usando el código hexadecimal (or **hex code**). This works in a similar way to the `rgb()` code above, except that hex codes always start with a `#`, and use hexadecimal ‘numbers’ between `00` and `ff` for the amount of red, green and blue.

![captura de pantalla](images/recipe-hex-img.png)

Replace the `rgb()` code in your CSS with this hex code:

    background: #fafad2;
    

![captura de pantalla](images/recipe-hex.png)

You should see the same light yellow as before!