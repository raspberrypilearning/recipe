## Színek!

Adjunk hozzá néhány színt a weboldalhoz.

+ Már megtanultad, hogyan kell színes szöveget hozzáadni egy weboldalhoz. Add hozzá ezt a kódot a `style.css` fájl belsejébe, hogy a weboldal teljes szövege kékké váljon:

    body {
        color: blue;
    }
    

![képernyőkép](images/recipe-blue.png)

+ A böngésződ ismeri a `blue` (kék), a `yellow` (sárga), sőt még a `lightgreen` (világoszöld), színt is, de tudtad, hogy a böngésző valójában több mint 140 különböző szín **neveit** ismeri?

Itt található az összes használható színnév: [jumpto.cc/colours](http://jumpto.cc/colours), amely olyan színneveket tartalmaz, mint `tomato`, `firebrick` és `peachpuff`.

Változtasd meg a szöveg színát `blue`-ról `tomato`-ra.

![képernyőkép](images/recipe-tomato.png)

+ A böngésző 140 szín nevét ismeri, de valójában több mint 16 millió szín **színértékét** fel tudja ismerni!

Ahhoz, hogy megmondd a böngészőnek, melyik színt kell megjeleníteni, csak tudatnod kell vele, hogy mennyi vörös, zöld és kék színt kell használni.

A vörös, zöld és kék mennyisége `0` és `255` közötti számként van leírva.

![képernyőkép](images/recipe-rgb-img.png)

Add hozzá a CSS-ben a body elemhez tartozó részhez ezt a kódot, hogy a weboldal háttere világossárga legyen:

    background: rgb(250,250,210);
    

![képernyőkép](images/recipe-rgb.png)

+ Ha jobban szereted, megmondhatod a böngészőnek, melyik színt kell megjelenítenie, tizenhatos számrendszerbeli kóddal (vagy **hex kóddal**). Ez hasonlóan működik a fenti `rgb()` kódhoz, azonban a hex kódok mindig a `#` jellel kezdődnek, és tizenhatos számrendszerbeli számokat használnak `00`-tól `ff`-ig a vörös, zöld és kék szín erősségére.

![képernyőkép](images/recipe-hex-img.png)

Cseréld ki a CSS-ben az `rgb()` kódot erre a hex kódra:

    background: #fafad2;
    

![képernyőkép](images/recipe-hex.png)

Ugyanazt a világossárgát kell látnod, mint korábban!