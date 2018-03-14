## Il tocco finale 

Aggiungiamo un po’ di HTML e CSS per migliorare la pagina web.

+ Puoi aggiungere una linea orizzontale al termine della ricetta utilizzando il tag `<hr>`.

![screenshot](images/recipe-hr.png)

Nota: questo tag non ha un tag di fine, proprio come il tag `<img>`.

+ La linea che hai appena aggiunto non corrisponde allo stile del resto della pagina web. Correggiamo aggiungendo un po’ di codice CSS:

```
hr {
    height: 2px;
    border: none;
    background-color: tomato;
}
```

![screenshot](images/recipe-hr-css.png)

+ Puoi anche cambiare l’aspetto dei punti elenco con il codice CSS:

```
ul {
    list-style-type: square;
}
```

![screenshot](images/recipe-ul-css.png)

