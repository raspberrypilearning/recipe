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

+ إن متصفح الانترنيت خاصتك يعرف الاسماء لـ١٤٠ لون، ولكن في الحقيقة فهو يعرف **قيم الالوان** لاكثر من ١٦ مليون لون!

حتى تخبر المتصفح أي لون يعرضه، عليك أن تخبره كم هو مقدار اللون الاحمر، والاخضر والازرق المستخدم.

إن مقدار اللون الاحمر والاخضر والازرق مكتوب بشكل رقم بين `0` و `255`.

![لقطة الشاشة](images/recipe-rgb-img.png)

أضف هذه الكود الى متن CSS لصفحة الويب، حتى تعرض خلفية بلون أصفر فاتح:

    background: rgb(250,250,210);
    

![لقطة الشاشة](images/recipe-rgb.png)

+ أذا كنت تفضل، يمكنك أن تخبر المتصفح أي لون ليعرضه وذلك باستخدام كود hexadecimal أو (**كود hex**). This works in a similar way to the `rgb()` code above, except that hex codes always start with a `#`, and use hexadecimal ‘numbers’ between `00` and `ff` for the amount of red, green and blue.

![لقطة الشاشة](images/recipe-hex-img.png)

Replace the `rgb()` code in your CSS with this hex code:

    background: #fafad2;
    

![لقطة الشاشة](images/recipe-hex.png)

يجب أن ترى الاصفر الفاتح كما في السابق!