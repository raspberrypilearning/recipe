## Der letzte Schliff

Lass uns noch mehr HTML und CSS hinzufügen, um deine Webseite zu verbessern.

+ Du kannst eine horizontale Linie am Ende deines Rezeptes hinzufügen, wenn du das `<hr>` Tag benützt.

![Screenshot](images/recipe-hr.png)

Beachte, dass dieses Tag kein End-Tag hat, genau wie das `<img>` Tag.

+ Die Linie, du du gerade hinzugefügt hast, passt nicht so recht zum Rest deiner Webseite. Lass uns das mit etwas CSS Code beheben:

```
hr {
    height: 2px;
    border: none;
    background-color: tomato;
}
```  

![Screenshot](images/recipe-hr-css.png)

+ Du kannst sogar das Aussehen der Listenpunkte mit diesem CSS Code verändern:

```
ul {
    list-style-type: square;
}
``` 

![Screenshot](images/recipe-ul-css.png)