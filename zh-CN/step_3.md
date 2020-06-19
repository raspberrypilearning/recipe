## 原料

让我们一起来列出你的食谱所需要的原料。

+ 打开这个示例 trinket： [jumpto.cc/html-template](http://jumpto.cc/html-template){:target="_blank"}.
    
    效果应该是这样：
    
    ![screenshot](images/recipe-starter.png)

+ 对于你的原料列表，你将使用**无序列表**，用`<ul>`标签表示。 转到模板的第8行，添加这个HTML，将`<h1>`标题中的文本替换为你的食谱的名称：

    <h1>香蕉奶昔</h1>
    
    <h3>原料：</h3>
    
    <ul>
    
    </ul>
    

+ 查看你的网页，你应该看到你的两个标题。

![screenshot](images/recipe-headings.png)

你现在看不到你的列表，因为你还没有添加任何列表项！

+ 下一步是使用`<li>`标签将列表项添加到列表中。 在你的`<ul>`标签中添加以下代码：

    <li>1个香蕉</li>
    

![screenshot](images/recipe-ul.png)

由于列表是无序的，所以列表项旁边没有数字，只有项目符号。