## Cores!

Vamos adicionar algumas cores à página de internet de sua receita.

+ Você já aprendeu a adicionar texto colorido a uma página de internet. Adicione este código dentro do seu arquivo `style.css`, para fazer com que o texto no corpo da sua página fique azul:

```
body {
    color: blue;
}
```

![captura de tela](images/recipe-blue.png)

+ Seu navegador conhece cores como `blue`, `yellow` e até mesmo `lightgreen`, mas você sabia que seu navegador realmente conhece os **nomes** de mais de 140 cores diferentes, no idioma inglês?

Há uma lista de todos os nomes de cores que você pode usar: [jumpto.cc/colours](http://jumpto.cc/colours), que inclui nomes de cores como `tomato`, `firebrick` e `peachpuff`.

Altere a cor do texto de `blue` para `tomato`.

![captura de tela](images/recipe-tomato.png)

+ Seu navegador conhece os nomes de 140 cores em inglês, mas na verdade conhece os **valores das cores** de mais de 16 milhões de cores!

Para informar ao navegador qual cor exibir, você só precisa informar o quanto vermelho, verde e azul deve usar.

As quantidades de vermelho, verde e azul são escritas como um número entre `0` e `255`.

![captura de tela](images/recipe-rgb-img.png)

Adicione este código ao CSS para o corpo da página de internet, para exibir uma cor de fundo amarelo claro:

    background: rgb(250,250,210);
    

![captura de tela](images/recipe-rgb.png)

+ Se preferir, você pode informar ao navegador qual cor exibir usando um código hexadecimal (ou **hex code**). Isso funciona de maneira semelhante ao código `rgb()` acima, exceto pelo fato de que os códigos hexadecimais sempre começam com `#` e usam 'valores' hexadecimais entre `00` e `ff` para a quantidade de vermelho, verde e azul.

![captura de tela](images/recipe-hex-img.png)

Substitua o código `rgb()` no seu CSS com este código hexadecimal:

    background: #fafad2;
    

![captura de tela](images/recipe-hex.png)

Você deve ver o mesmo amarelo claro que tinha antes, nada mudou, só a forma de escrever o código!