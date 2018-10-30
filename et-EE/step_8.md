## Viimistlus puudutab

Lisage veebisaidi parandamiseks natuke rohkem HTML-i ja CSS-i.

+ Teie retsepti lõpus saate lisada horisontaalse jooni, kasutades märgist `<hr>`.

![ekraanipilt](images/recipe-hr.png)

Pidage meeles, et sellel sildil pole lõppsilti, nagu silt `<img>`.

+ Liin, mille olete just lisanud, ei ühti ülejäänud veebisaidi stiiliga. Lahendage see, lisades mõne CSS-koodi:

    hr {
        kõrgus: 2px;
        piir: puudub;
        taustavärvi: tomati;
    }
    

![ekraanipilt](images/recipe-hr-css.png)

+ Võite isegi muuta seda, kuidas teie kuuli punktid välja näevad, kasutades seda CSS-koodi:

    ul {
        list-style-type: square;
    }
    

![ekraanipilt](images/recipe-ul-css.png)