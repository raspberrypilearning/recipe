## Utolsó simítások

Adjunk hozzá még egy kicsi HTML-t és CSS-t a weboldal tökéletesítéséhez.

+ A recept végéhez vízszintes sort adhat a `<hr>` címke használatával.

![képernyőkép](images/recipe-hr.png)

Vedd figyelembe, hogy ennek a címkének nincs záró címkéje, csakúgy, mint a `<img>` címkének.

+ A hozzáadott sor nem egyezik meg a weboldal stílusával. Javítsuk ki ezt néhány CSS-kód hozzáadásával:

    hr {
        height: 2px;
        border: none;
        background-color: tomato;
    }
    

![képernyőkép](images/recipe-hr-css.png)

+ CSS kóddal a felsorolásjel kinézetét is meg lehet változtatni:

    ul {
        list-style-type: square;
    }
    

![képernyőkép](images/recipe-ul-css.png)