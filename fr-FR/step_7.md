## Couleurs!

Il est temps d'ajouter un peu de couleur a notre page de recette.

+ Tu sais maintenant comment ajouter de la couleur au texte de ta page. Ajoute ce code dans ton fichier `style.css`, pour rendre tout le texte de ta page bleu:

```
body {
    color: blue;
}
```

![screenshot](images/recipe-blue.png)

+ Ton navigateur connais plein de couleurs comme `blue`, `yellow` (jaune) et même `lightgreen` (vert clair), mais sais tu que ton navigateur connais en faite les __noms__ de 500 couleurs différentes ?

Il existe une liste de toutes les couleurs que tu peux utiliser: [jumpto.cc/web-colours](http://jumpto.cc/web-colours), qui comprend des noms de couleurs comme `tomato`, `firebrick` et `peachpuff`.

Change la couleur de ton texte de `blue` à `tomato`.

![screenshot](images/recipe-tomato.png)

+ Ton navigateur connais enormément de couleurs, mais en faite il connais les __valeurs de couleurs__ de plus de 16 millions de couleurs!

Peut etre le sais tu deja, mais toutes les couleurs sont fabriqués a partir de trois couleurs primaire: rouge, vert et bleu. Pour indiquer à ton navigateur quelle couleur tu veux afficher, tu dois juste lui définir la quantité de chaque couleurs primaire que tu veux utiliser.

La quantité de rouge, vert et bleu peuvent s'écrirent en chiffres compris entre `0` et `255`.

![screenshot](images/recipe-rgb-img.png)

Ajoute ce code à ton CSS, sur le selecteur body de ta page, pour afficher un fond jaune léger.

```
background: rgb(250,250,210);
```

![screenshot](images/recipe-rgb.png)

+ Si tu préfères, tu peux aussi indiquer à ton navigateur quelle couleur afficher en utilisant un code héxadécimal (plus connue sous le nom de __hex code__). Cela fonctionne de façon similaire à la méthode `rgb()`, à l'exception que le hex code commence toujours par `#`, et un 'nombre' hexadecimal se défini entre `00` et `ff` pour la quantité de rouge, vert et bleu.

![screenshot](recipe-hex-img.png)

Remplace ton code `rgb()` dans ton CSS par ce hex code:

```
background: #fafad2;
```

![screenshot](images/recipe-hex.png)

Tu devrais voir la même couleur de fond qu'avant!
