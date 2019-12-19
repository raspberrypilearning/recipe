## Culori!

Hai să adaugăm niște culoare la pagina web a rețetei tale.

+ Ai învățat deja cum să adaugi text colorat într-o pagină web. Adaugă acest cod în fișierul tău `style.css` pentru a face tot textul din corpul paginii web albastru:

    body {
        color: blue;
    }
    

![captură de ecran](images/recipe-blue.png)

+ Browser-ul tău știe nume de culori precum `blue`, `yellow` și chiar `lightgreen`, dar știai că browser-ul tău știe de fapt **numele** a peste 140 de culori diferite?

Există o listă a tuturor numelor de culori pe care le poți folosi aici: [jumpto.cc/colours](http://jumpto.cc/colours) care include nume de culori precum `tomato`, `firebrick` și `peachpuff`.

Schimbă culoarea textului din `blue` în `tomato`.

![captură de ecran](images/recipe-tomato.png)

+ Browser-ul tău știe numele a 140 de culori, dar de fapt știe **valoarea culorilor** pentru peste 16 milioane de culori!

Pentru a-i spune browser-ului ce culoare să afișeze, trebuie doar să îi spunem cât roșu, verde și albastru să folosească.

Cantitatea de roșu, verde și albastru este scrisă sub forma unui număr între `0` și `255`.

![captură de ecran](images/recipe-rgb-img.png)

Adaugă acest cod în partea CSS a corpului paginii web, pentru a afișa un fundal de culoare galben deschis:

    background: rgb(250,250,210);
    

![captură de ecran](images/recipe-rgb.png)

+ Dacă preferi, poți să îi spui browser-ului ce culoare să afișeze folosind un cod hexazecimal (sau **cod hex**). Acesta funcționează asemănător cu codul `rgb()` de mai sus, cu excepția faptului că codurile hex încep întotdeauna cu un `#` și folosesc „numere” între `00` și `ff` pentru cantitatea de roșu, verde și albastru.

![captură de ecran](images/recipe-hex-img.png)

Înlocuiește codul `rgb()` în CSS cu acest cod hex:

    background: #fafad2;
    

![captură de ecran](images/recipe-hex.png)

Ar trebui să vezi același galben deschis ca și cel de dinainte!