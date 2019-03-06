## Son rötuşları

Web sayfanızı geliştirmek için biraz daha HTML ve CSS ekleyelim.

+ `<hr>` etiketini kullanarak tarifinizin sonuna yatay bir çizgi ekleyebilirsiniz.

![ekran görüntüsü](images/recipe-hr.png)

Bu etiketin, `<img>` etiketi gibi bir bitiş etiketi olmadığına dikkat edin.

+ Yeni eklediğiniz satır, web sayfanızın geri kalanıyla aynı değil. Biraz CSS kodu ekleyerek düzeltelim:

    saat {
        yükseklik: 2 piksel;
        sınır: yok;
        arka plan rengi: domates;
    }
    

![ekran görüntüsü](images/recipe-hr-css.png)

+ Madde imli noktalarınızın bu CSS koduyla nasıl göründüğünü bile değiştirebilirsiniz:

    ul {
        liste tarzı türü: kare;
    }
    

![ekran görüntüsü](images/recipe-ul-css.png)