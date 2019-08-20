## Der letzte Schliff

Lass uns noch mehr HTML und CSS hinzufügen, um deine Webseite zu verbessern.

+ Du kannst eine horizontale Linie am Ende deines Rezeptes hinzufügen, wenn du das `<hr>` Tag benützt.

![Screenshot](images/recipe-hr.png)

Beachte, dass dieses Tag kein End-Tag hat, genau wie das `<img>` Tag.

+ The line you’ve just added doesn’t match the style of the rest of your webpage. Let’s fix that by adding some CSS code:

    hr {
        height: 2px;
        border: none;
        background-color: tomato;
    }
    

![screenshot](images/recipe-hr-css.png)

+ You can even change how your bullet points look with this CSS code:

    ul {
        list-style-type: square;
    }
    

![Screenshot](images/recipe-ul-css.png)