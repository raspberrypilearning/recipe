## Finpuss

La oss legge til litt mer HTML og CSS for å forbedre websiden din.

+ Du kan legge til en horisontal linje på slutten av oppskriften, ved å bruke `<hr>` taggen.

![skjermbilde](images/recipe-hr.png)

Legg merke til at denne taggen ikke har en sluttkode, akkurat som `<img>` taggen.

+ Linjen du nettopp har lagt til, samsvarer ikke med stilen til resten av nettsiden din. La oss fikse det ved å legge til noen CSS-kode:

    hr {
        høyde: 2px;
        kantlinje: ingen;
        bakgrunnsfarge: tomat;
    }
    

![skjermbilde](images/recipe-hr-css.png)

+ Du kan til og med endre hvordan kulepoengene dine ser ut med denne CSS-koden:

    ul {
        liste-stil-type: square;
    }
    

![skjermbilde](images/recipe-ul-css.png)