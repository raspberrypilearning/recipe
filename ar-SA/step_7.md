## الألوان!

دعونا نقوم بإضافة بعض الالوان الى صفحتك.

+ لقد تعلمت كيف تضيف نص ملوّن في صفحتك. قم بإضافة هذه الكود داخل ملف `style.css`، لجعل كل النص داخل الصغحة أزرق اللون:

    body {
        color: blue;
    }
    

![لقطة شاشة](images/recipe-blue.png)

+ إن متصفح الانترنيت لديك يعرف اللون `الازرق` و `الاصفر` وحتى `الاخضر الفاتح`، ولكن هل كنت تعرف حقيقة أن متصفحك يعرف **الاسماء** الخاصة باكثر من ١٤٠ لون مختلف؟

هناك قائمة بأسماء جميع الاوان، يمكنك أن تستخدم الموقع:[jumpto.cc/colours](http://jumpto.cc/colours), والذي يحوي اسماء الالوان مثل ` tomato`، و` firebrick` و ` peachpuff`.

غيّر لون الخط من `الازرق` الى `tomato`.

![لقطة الشاشة](images/recipe-tomato.png)

+ Your browser knows the names of 140 colours, but actually knows the **colour values** of more than 16 million colours!

To tell the browser which colour to display, you just need to let it know how much red, green and blue to use.

The amounts of red, green and blue are written as a number between `0` and `255`.

![لقطة الشاشة](images/recipe-rgb-img.png)

Add this code to the CSS for the body of the webpage, to display a light yellow background:

    background: rgb(250,250,210);
    

![لقطة الشاشة](images/recipe-rgb.png)

+ If you prefer, you can tell the browser which colour to display by using a hexadecimal code (or **hex code**). This works in a similar way to the `rgb()` code above, except that hex codes always start with a `#`, and use hexadecimal ‘numbers’ between `00` and `ff` for the amount of red, green and blue.

![لقطة الشاشة](images/recipe-hex-img.png)

Replace the `rgb()` code in your CSS with this hex code:

    background: #fafad2;
    

![لقطة الشاشة](images/recipe-hex.png)

You should see the same light yellow as before!