## ¡Colores!

Vamos a añadir algo de color a la página web de tu receta.

+ Ya has aprendido a añadir color al texto de tu página web. Añade este código dentro de tu archivo `style.css`, para hacer que todo el texto del cuerpo de tu página web sea azul:

    body {
        color: blue;
    }
    

![captura de pantalla](images/recipe-blue.png)

+ Tu navegador conoce los colores como `blue` (azul), `yellow` (amarillo) y hasta `lightgreen` (verde claro), pero ¿sabías que tu navegador sabe los **nombres** de más de 140 colores?

Hay una lista de todos los nombres de colores que puedes usar: [ jumpto.cc/colours ](http://jumpto.cc/colours), que incluye nombres de colores como ` tomato` (tomate), ` firebrick ` (ladrillo) y ` peachpuff` (melocotón).

Cambia el color del texto de `blue` (azul) a `tomato` (tomate).

![captura de pantalla](images/recipe-tomato.png)

+ ¡Tu navegador sabe los nombres de 140 colores, pero de hecho sabe los **códigos de color** de más de 16 millones de colores!

Para decirle al navegador el color que debe mostrar, sólo debes decirle cuánto rojo, verde y azul debe usar.

The amounts of red, green and blue are written as a number between `0` and `255`.

![captura de pantalla](images/recipe-rgb-img.png)

Add this code to the CSS for the body of the webpage, to display a light yellow background:

    background: rgb(250,250,210);
    

![captura de pantalla](images/recipe-rgb.png)

+ If you prefer, you can tell the browser which colour to display by using a hexadecimal code (or **hex code**). This works in a similar way to the `rgb()` code above, except that hex codes always start with a `#`, and use hexadecimal ‘numbers’ between `00` and `ff` for the amount of red, green and blue.

![captura de pantalla](images/recipe-hex-img.png)

Replace the `rgb()` code in your CSS with this hex code:

    background: #fafad2;
    

![captura de pantalla](images/recipe-hex.png)

You should see the same light yellow as before!