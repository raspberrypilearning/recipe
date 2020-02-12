## Ostatnie pociągnięcia

Dodajmy nieco więcej HTML i CSS, aby ulepszyć twoją stronę internetową.

+ Możesz dodać poziomą linię na końcu twojego przepisu za pomocą znacznika `<hr>`.

![zrzut ekranu](images/recipe-hr.png)

Zauważ, że ten znacznik nie ma znacznika zamykającego, tak samo jak znacznik `<img>`.

+ Linia, którą dodałaś nie pasuje stylem do reszty twojej strony. Naprawmy to dodając trochę kodu CSS:
```
    hr {
        height: 2px;
        border: none;
        background-color: tomato;
    }
```    

![zrzut ekranu](images/recipe-hr-css.png)

+ Za pomocą tego kodu CSS możesz nawet zmienić wygląd twoich punktorów:
```
    ul {
        list-style-type: square;
    }
```    

![zrzut ekranu](images/recipe-ul-css.png)