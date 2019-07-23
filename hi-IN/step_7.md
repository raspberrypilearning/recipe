## रंग!

चलिए आपकी रेसिपी के वेबपेज को रंगीन बनाते हैं।

+ आपने पहले से सिख रखा हैं कैसे अपने वेबपेज में रंगीन शब्द जोड़ा जाता हैं। आपकी वेबपेज कि शब्दों को नीला करने के लिए, अपने `style.css` फाइल में यह कोड जोड़ दीजिये:

    body {
        color: blue;
    }
    

![screenshot](images/recipe-blue.png)

+ आपका ब्राउज़र `blue`, `yellow` और यहाँ तक कि `lightgreen` जैसे रंगों के बारे में जानता है, लेकिन क्या आपको पताथा कि आपका ब्राउज़र वास्तव में 140 से ज़्यादा रंगों के **नाम** जानता है?

आपके लिए उपयोग करने के लिए सभी रंगों की सूची आपको यहाँ मिलेंगी: [jumpto.cc/colours](http://jumpto.cc/colours), जिसमें `tomato`, `firebrick` और `peachpuff` जैसे रंगों के नाम शामिल हैं।

क्स्ट के रंग को `blue` से `tomato` में बदलें।

![स्क्रीनशॉट](images/recipe-tomato.png)

+ आपका ब्राउज़र 140 रंगों के नाम जानता है, लेकिन वास्तव में यह 1.6 करोड़ से ज़्यादा रंगों के ** रंग मूल्य ** जानता है!

To tell the browser which colour to display, you just need to let it know how much red, green and blue to use.

The amounts of red, green and blue are written as a number between `0` and `255`.

![स्क्रीनशॉट](images/recipe-rgb-img.png)

Add this code to the CSS for the body of the webpage, to display a light yellow background:

    background: rgb(250,250,210);
    

![स्क्रीनशॉट](images/recipe-rgb.png)

+ If you prefer, you can tell the browser which colour to display by using a hexadecimal code (or **hex code**). This works in a similar way to the `rgb()` code above, except that hex codes always start with a `#`, and use hexadecimal ‘numbers’ between `00` and `ff` for the amount of red, green and blue.

![स्क्रीनशॉट](images/recipe-hex-img.png)

Replace the `rgb()` code in your CSS with this hex code:

    background: #fafad2;
    

![स्क्रीनशॉट](images/recipe-hex.png)

You should see the same light yellow as before!