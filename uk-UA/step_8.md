## Останні штрихи

Давай додамо трохи більше HTML- та CSS-коду для покращення твоєї вебсторінки.

+ Ти можеш додати горизонтальну лінію в кінці свого рецепта за допомогою тега `<hr>`.

![знімок екрана](images/recipe-hr.png)

Зверни увагу, що цей тег не має кінцевого тегу, як і `<img>`.

+ Щойно додана тобою лінія не відповідає стилю решти вебсторінки. Давай це виправимо за допомогою такого коду CSS:

```
hr {
    height: 2px;
    border: none;
    background-color: tomato;
}
```

![знімок екрана](images/recipe-hr-css.png)

+ Ти навіть можеш змінити вигляд маркування за допомогою такого коду CSS:

```
ul {
    list-style-type: square;
}
```

![знімок екрана](images/recipe-ul-css.png)