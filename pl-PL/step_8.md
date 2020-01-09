## Ostatnie pociągnięcia

Dodajmy nieco więcej HTML i CSS, aby ulepszyć twoją stronę internetową.

+ Możesz dodać poziomą linię na końcu twojego przepisu za pomocą znacznika `<hr>`.

![zrzut ekranu](images/recipe-hr.png)

Zauważ, że ten znacznik nie ma znacznika zamykającego, tak samo jak znacznik `<img>`.

+ The line you’ve just added doesn’t match the style of the rest of your webpage. Let’s fix that by adding some CSS code:

    hr {
        height: 2px;
        border: none;
        background-color: tomato;
    }
    

![zrzut ekranu](images/recipe-hr-css.png)

+ You can even change how your bullet points look with this CSS code:

    ul {
        list-style-type: square;
    }
    

![zrzut ekranu](images/recipe-ul-css.png)