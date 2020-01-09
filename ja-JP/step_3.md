## 材料

レシピに必要な材料をリストしましょう。

+ 次のTrinketのテンプレートを開きます：jumpto.cc/html-template。
    
    プロジェクトはこのようになります。
    
    ![スクリーンショット](images/recipe-starter.png)

+ 材料のリストには、
    
    タグを使用して、順序付けられていないリストを使用します。 Go to line 8 of the template and add this HTML, replacing the text in the `<h1>` title with the name of your own recipe:</p></li> 
    
        <h1>Banana Milkshake</h1>
        
        <h3>Ingredients:</h3>
        
        <ul>
        
        </ul>
        
    
    + View your webpage, and you should see your two headings.
    
    ![スクリーンショット](images/recipe-headings.png)
    
    You won’t see your list yet though, because you haven’t added any list items to it!
    
    + The next step is to add list items into your list, by using the `<li>` tag. Add the following code inside your `<ul>` tag:
    
        <li>1 banana</li>
        
    
    ![スクリーンショット](images/recipe-ul.png)
    
    As your list is unordered, there are no numbers next to the list items, just bullet points.