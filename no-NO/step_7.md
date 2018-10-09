## Farger!

La oss legge til litt farge på oppskriftswebsiden din.

+ Du har allerede lært hvordan du legger til farget tekst på en nettside. Legg til denne koden i din `style.css` fil, for å gjøre hele teksten i nettstedet kroppsblå:

    kropp {
        farge: blå;
    }
    

![skjermbilde](images/recipe-blue.png)

+ Nettleseren din kjenner farger som `blå`, `gul` og til og med `lysegrønn`, men visste du at nettleseren din faktisk kjenner de **navnene** med over 140 forskjellige farger?

Det er en liste over alle farge navnene du kan bruke: [jumpto.cc/colours](http://jumpto.cc/colours), som inkluderer farge navn som `tomat`, `firebrick` og `ferskenpuff`.

Endre tekstfargen fra `blå` til `tomat`.

![skjermbilde](images/recipe-tomato.png)

+ Nettleseren din vet navnene på 140 farger, men vet faktisk **farger verdier** av mer enn 16 millioner farger!

For å fortelle nettleseren hvilken farge som skal vises, trenger du bare å fortelle den hvor mye rød, grønn og blå som skal brukes.

Mengden rød, grønn og blå er skrevet som et tall mellom `0` og `255`.

![skjermbilde](images/recipe-rgb-img.png)

Legg denne koden til CSS for websiden, for å vise en lys gul bakgrunn:

    bakgrunn: rgb (250.250.210);
    

![skjermbilde](images/recipe-rgb.png)

+ Hvis du foretrekker det, kan du fortelle nettleseren hvilken farge som skal vises ved hjelp av en heksadesimal kode (eller **heksekode**). Dette fungerer på samme måte som `rgb ()` koden ovenfor, bortsett fra at heksekoder alltid starter med en `#`, og bruk heksadesimale tall mellom `00` og `ff` for mengden rød, grønn og blå.

![skjermbilde](images/recipe-hex-img.png)

Erstatt `rgb ()` koden i ditt CSS med denne heksekoden:

    bakgrunn: # fafad2;
    

![skjermbilde](images/recipe-hex.png)

Du bør se den samme lysegul som før!