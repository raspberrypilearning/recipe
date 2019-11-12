## 最后一步

让我们再添加一点HTML和CSS来改进你的网页。

+ 你可以使用`<hr>`标签在食谱的末尾添加一条水平线。

![截屏](images/recipe-hr.png)

注意，这个标签没有结束标签，就像`<img>`标记一样。

+ The line you’ve just added doesn’t match the style of the rest of your webpage. Let’s fix that by adding some CSS code:

    hr {
        height: 2px;
        border: none;
        background-color: tomato;
    }
    

![截屏](images/recipe-hr-css.png)

+ You can even change how your bullet points look with this CSS code:

    ul {
        list-style-type: square;
    }
    

![截图](images/recipe-ul-css.png)