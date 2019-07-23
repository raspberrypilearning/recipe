## अंतिम रूप देना

चलिए आपके वेबपेज को सुधरने के लिए थोड़े और HTML और CSS जोड़ें।

+ You can add a horizontal line at the end of your recipe, by using the `<hr>` tag.

![screenshot](images/recipe-hr.png)

Notice that this tag doesn’t have an end tag, just like the `<img>` tag.

+ The line you’ve just added doesn’t match the style of the rest of your webpage. Let’s fix that by adding some CSS code:

    hr {
        height: 2px;
        border: none;
        background-color: tomato;
    }
    

![स्क्रीनशॉट](images/recipe-hr-css.png)

+ You can even change how your bullet points look with this CSS code:

    ul {
        list-style-type: square;
    }
    

![स्क्रीनशॉट](images/recipe-ul-css.png)