## Farben!

Lass uns Farben zu deiner Rezept-Webseite hinzufügen.

+ Du hast bereits gelernt, wie man farbigen Text zu einer Webseite hinzufügt. Füge den unten stehenden Code in deine `style.css` Datei, um den gesamten Text in deinem Webseite body blau zu machen:

    body {
        color: blue;
    }
    

![Screenshot](images/recipe-blue.png)

+ Dein Browser kennt Farben wie `blue`, `yellow` und sogar `lightgreen`, aber hast du gewusst, dass dein Browser tatsächlich die **Namen** von 140 verschiedenen Farben kennt?

Es gibt eine List von allen Farbnamen, die du benützen kannst: [umpto.cc/colours](http://jumpto.cc/colours), welche Farbnamen wie `tomato`, `firebrick` und `peachpuff`.

Verändere die Textfarbe von `blue` zu `tomato`.

![Screenshot](images/recipe-tomato.png)

+ Dein Browser kennt die Namen von 140 Farben, aber kennt eigentlich die **Farbwerte** von mehr als 16 Millionen Farben!

Um dem Browser zu sagen, welche Farbe er darstellen soll, musst du ihn nur wissen lassen, wie viel rot, grün und blau er verwenden soll.

Die Mengen an rot, grün und blau werden als eine Nummer zwischen `0` und `255` geschrieben.

![Screenshot](images/recipe-rgb-img.png)

Füge diesen Code zu deinem CSS für den body der Webseite, um einen gelben Hintergrund darzustellen:

    background: rgb(250,250,210);
    

![Screenshot](images/recipe-rgb.png)

+ If you prefer, you can tell the browser which colour to display by using a hexadecimal code (or **hex code**). This works in a similar way to the `rgb()` code above, except that hex codes always start with a `#`, and use hexadecimal ‘numbers’ between `00` and `ff` for the amount of red, green and blue.

![Screenshot](images/recipe-hex-img.png)

Replace the `rgb()` code in your CSS with this hex code:

    background: #fafad2;
    

![Screenshot](images/recipe-hex.png)

You should see the same light yellow as before!