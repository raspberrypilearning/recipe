## Színek!

Adjunk hozzá néhány színt a weboldalhoz.

+ Már megtanulta, hogyan kell színes szöveget hozzáadni egy weboldalhoz. Adja hozzá ezt a kódot a `style.css` fájl belsejébe, hogy a webhely teljes szövege kékké váljon:

    body {
        color: blue;
    }
    

![screenshot](images/recipe-blue.png)

+ Böngészője ismeri a `blue`, a `yellow` még a `loghtgreen`színt is, de tudta, hogy a böngésző valójában több mint 140 különböző szín **neveit** ismeri?

Itt található az összes használható színnév: [jumpto.cc/colours](http://jumpto.cc/colours), amely olyan színneveket tartalmaz, mint `tomato`, `firebrick` és `peachpuff`.

Változtassa meg a szöveg színét `blueról tomatora.`.

![képernyőkép](images/recipe-tomato.png)

+ A böngésző 140 szín nevét ismeri, de valójában több mint 16 millió szín **színértékét** fel tudja ismerni!

Ahhoz, hogy megmondja a böngészőnek melyik színt kell megjeleníteni, csak tudatnia kell vele, hogy mennyi vörös, zöld és kék színt kell használni.

A vörös, zöld és kék mennyiség `0` és `255`közötti számként van írva.

![screenshot](images/recipe-rgb-img.png)

Add hozzá ezt a kódot a CSS törzséhez, hogy világossárga háttér legyen:

    background: rgb(250,250,210);
    

![screenshot](images/recipe-rgb.png)

+ Ha úgy tetszik hexadecimális kódot is lehet használni. Ez hasonlóan működik, mint a fenti `rgb ()` kód, azzal a különbséggel, hogy a hexadecimális kódok mindig `#`mal kezdődnek, és hexadecimális „számot” használnak `00` és `ff` között a vörös, zöld és kék.

![screenshot](images/recipe-hex-img.png)

Cserélje ki a CSS-ben található `rgb ()` kódot erre a hexadecimális kódra:

    háttér: # fafad2;
    

![screenshot](images/recipe-hex.png)

Ugyanazt a sárgát kell látnia, mint korábban!