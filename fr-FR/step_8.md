## Touches finales

Et si on ajoutais encore un peu plus d'HTML et CSS pour améliorer notre page.

+ Tu peux ajouter une ligne horizontal à la fin de ta recette, en utilisant le tag <hr />.

![screenshot](images/recipe-hr.png)

Tu remarqueras que ce tag n'a pas besoin d'un tag de fin, tout comme le tag `<img>`.

+ La ligne que tu viens d'ajouter n'est pas en phase avec le reste de ta page. Règlons ce problème en ajoutant un peu de code CSS:

```
hr {
    height: 2px;
    border: none;
    background-color: tomato;
}
```

![screenshot](images/recipe-hr-css.png)

+ Tu peux même changer le style des puces avec ce code CSS:

```
ul {
    list-style-type: square;
}
```

![screenshot](images/recipe-ul-css.png)
