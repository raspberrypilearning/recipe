## अंतिम रूप देना

चलिए आपके वेबपेज को सुधरने के लिए थोड़े और HTML और CSS जोड़ें।

+ आप `<hr>` टैग का उपयोग करके अपनी रेसिपी के अंत में क्षैतिज लाइन जोड़ सकते हैं।

![screenshot](images/recipe-hr.png)

ध्यान दें कि `<img>` टैग की तरह, इस टैग का कोई अंत टैग नहीं है।

+ आपने अभी जो लाइन जोड़ा, वह आपके वेबपेज के स्टाइल के साथ मिल नहीं रहा हैं। चलिए कुछ CSS कोड जोड़कर इसे ठीक करें:

    hr {
        height: 2px;
        border: none;
        background-color: tomato;
    }
    

![screenshot](images/recipe-hr-css.png)

+ आप CSS कोड द्वारा अपने बुलेट पॉइंट्स का स्वरूप भी बदल सकते हैं:

    ul {
        list-style-type: square;
    }
    

![screenshot](images/recipe-ul-css.png)