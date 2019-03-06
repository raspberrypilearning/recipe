## Završne finese

Dodajmo još malo HTML i CSS koda kako bi poboljšali stranicu.

+ Dodajte horizontalnu liniju na kraj vašeg recepta, koristeći `<hr>` tag.

![screenshot](images/recipe-hr.png)

Uočite da ovaj tag nema završni tag, kao i `<img>` tag.

+ Linija koju ste dodali ne podudara se sa stulom ostatka vaše stranice. Ispravimo to dodajući malo CSS koda:

    hr {
        height: 2px;
        border: none;
        background-color: tomato;
    }
    

![screenshot](images/recipe-hr-css.png)

+ Možete čak i promijeniti izgled vaših bulet oznaka sa ovim CSS kodom:

    ul {
        list-style-type: square;
    }
    

![screenshot](images/recipe-ul-css.png)