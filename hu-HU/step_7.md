## Színek!

Adjunk hozzá néhány színt a recept weboldalához.

+ Már megtanulta, hogyan kell színes szöveget hozzáadni egy weboldalhoz. Adja hozzá ezt a kódot a `style.css` fájl belsejébe, hogy a webhely teljes szövege kékké váljon:

    test {
        szín: kék;
    }
    

![screenshot](images/recipe-blue.png)

+ Böngészője ismeri a `kék`, a `sárga` és a `halványzöld`színt, de tudta, hogy a böngésző valójában ismeri a 140 különböző színből **nevet**?

Itt található az összes használható színnév: [jumpto.cc/colours](http://jumpto.cc/colours), amely olyan színneveket tartalmaz, mint `paradicsom`, `firebrick` és `barackpuff`.

Változtassa meg a szöveg színét `kék` ről ``paradicsomra.

![képernyőkép](images/recipe-tomato.png)

+ Az Ön böngészője ismeri a 140 szín nevét, de valójában ismeri a több mint 16 millió szín **színértékét**!

Ahhoz, hogy megmondja a böngészőnek, melyik színt kell megjeleníteni, csak tudatnia kell vele, hogy mennyi vörös, zöld és kék színt kell használni.

A vörös, zöld és kék mennyiség `0` és `255`közötti számként van írva.

![screenshot](images/recipe-rgb-img.png)

Adja hozzá ezt a kódot a weboldal törzsének CSS-hez, hogy világossárga háttér legyen:

    háttér: rgb (250 250 210);
    

![screenshot](images/recipe-rgb.png)

+ Ha úgy tetszik, akkor lehet mondani a böngészőt, amely színt kijelző használatával hexadecimális kód (vagy **hexa**). Ez hasonlóan működik, mint a fenti `rgb ()` kód, azzal a különbséggel, hogy a hexadecimális kódok mindig `#`mal kezdődnek, és hexadecimális „számot” használnak `00` és `ff` között a vörös, zöld és kék.

![screenshot](images/recipe-hex-img.png)

Cserélje ki a CSS-ben található `rgb ()` kódot erre a hexadecimális kódra:

    háttér: # fafad2;
    

![screenshot](images/recipe-hex.png)

Ugyanazt a sárgát kell látnia, mint korábban!