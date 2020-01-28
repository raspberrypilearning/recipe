## Kolory!

Dodajmy trochę koloru do twojej strony internetowej z przepisem.

+ Już dowiedziałeś się jak dodawać kolorowy tekst do strony internetowej. Dodaj ten kod wewnątrz twojego pliku `style.css`, aby sprawić, że cały tekst na stronie stanie się niebieski:

    body {
        color: blue;
    }
    

![zrzut ekranu](images/recipe-blue.png)

+ Twoja przeglądarka zna kolory takie jak `blue` (niebieski), `yellow` (żółty), a nawet `lightgreen` (jasnozielony), ale czy wiedziałaś, że twoja przeglądarka zna **nazwy** ponad 140 różnych barw?

Tutaj znajdziesz listę ze wszystkimi nazwami kolorów, których możesz użyć: [jumpto.cc/colours](http://jumpto.cc/colours) np. `tomato`, `firebrick`, `peachpuff`.

Zmień kolor tekstu z `blue`(niebieski) na `tomato` (pomidorowy).

![zrzut ekranu](images/recipe-tomato.png)

+ Twoja przeglądarka zna nazwy ponad 140 kolorów, ale w rzeczywistości zna ponad 16 milionów **wartości różnych kolorów**!

Żeby powiedzieć przeglądarce, który kolor ma wyświetlić, musisz jej wskazać ile ma użyć czerwonego, zielonego i niebieskiego.

Ilości czerwonego, zielonego i niebieskiego są zapisywane jako liczba pomiędzy `0`, a `255`.

![zrzut ekranu](images/recipe-rgb-img.png)

Dodaj ten kod CSS dla treści strony internetowej, aby wyświetlić jasnożółte tło:

    background: rgb(250,250,210);
    

![zrzut ekranu](images/recipe-rgb.png)

+ Jeżeli wolisz, możesz powiedzieć przeglądarce jaki kolor ma wyświetlać za pomocą kodu heksadecymalnego (albo **kodu szesnastkowego**). Działa on w podobny sposób jak kod `rgb()` powyżej, oprócz tego, że kody szesnastkowe zawsze zaczynają się od `#`, i używają "liczb" szesnastkowych pomiędzy `00`, a `ff` dla określenia ilości czerwonego, zielonego i niebieskiego.

![zrzut ekranu](images/recipe-hex-img.png)

Zastąp kod `rgb()` w twoim CSS tym kodem szesnastkowym:

    background: #fafad2;
    

![zrzut ekranu](images/recipe-hex.png)

Powinieneś zobaczyć taki sam jasnożółty jak poprzednio!