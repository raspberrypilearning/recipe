## Mettons de la couleur !

Ajoutons de la couleur à ta page Web.

+ Tu as déjà appris comment ajouter du texte coloré à une page Web. Ajoute ce code dans le fichier `style.css` , pour que tout le texte de la page soit bleu :

    body {
        color: blue;
    }
    

![capture d'écran](images/recipe-blue.png)

+ Ton navigateur connaît des couleurs telles que `bleu`, `jaune` et même `lightgreen`, mais sais-tu qu'il connaît aussi les **noms** de plus de 140 autres couleurs ?

Voici une liste de tous les noms de couleurs que tu peux utiliser: [jumpto.cc/colours](http://jumpto.cc/colours) , qui inclut des noms de couleur tels que `tomato` , `firebrick` et `peachpuff` .

Essaie de changer la couleur du texte de `bleu` à `tomato` :

![capture d'écran](images/recipe-tomato.png)

+ Ton navigateur connaît les noms de 140 couleurs, mais connaît surtout les **valeurs numériques** de plus de 16 millions de couleurs!

Pour indiquer au navigateur quelle couleur afficher, il suffit de lui indiquer la quantité de rouge, de vert et de bleu à utiliser.

Les quantités de rouge, de vert et de bleu s’écrivent sous la forme d’un nombre compris entre `0` et `255`.

![screenshot](images/recipe-rgb-img.png)

Ajoute ce code au CSS de la page Web pour afficher un arrière-plan jaune clair :

    background: rgb(250,250,210);
    

![capture d'écran](images/recipe-rgb.png)

+ On peut aussi indiquer au navigateur la couleur à afficher en utilisant un code hexadécimal (ou **hex code**). Cela fonctionne de la même manière que le code `rgb ()` ci-dessus, à la différence que les codes hexadécimaux commencent toujours par un `#` et utilisent des "nombres hexadécimaux" compris entre `00` et `ff` pour la quantité de rouge, de vert et de bleu.

![capture d'écran](images/recipe-hex-img.png)

Tu peux remplacer le code `rgb ()` dans le CSS par ce code hexadécimal :

    arrière-plan: # fafad2;
    

![capture d'écran](images/recipe-hex.png)

Vous devriez voir le même jaune clair qu'auparavant!