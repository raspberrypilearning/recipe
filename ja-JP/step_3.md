## 材料

レシピに必要な材料をリストしましょう。

+ 次のTrinketのテンプレートを開きます：[jumpto.cc/html-template](http://jumpto.cc/html-template){:target="_blank"}。
    
    プロジェクトはこのようになります。
    
    ![スクリーンショット](images/recipe-starter.png)

+ 材料のリストには、
    
    タグを使用して、順序付けられていないリストを使用します。 テンプレートの8行目に移動し、このHTMLを追加して、`<h1>`タイトルのテキストを独自のレシピの名前に置き換えます。</p></li> 
    
        <h1>Banana Milkshake</h1>
        
        <h3>Ingredients:</h3>
        
        <ul>
        
        </ul>
        
    
    + Webページを表示すると、2つの見出しが表示されます。
    
    ![スクリーンショット](images/recipe-headings.png)
    
    ただし、リスト項目はまだリストに追加されていないため、リストはまだ表示されません。 
    
    + 次のステップは、`<li>`タグを使用してリストにリストアイテムを追加することです。 `<ul>`タグ内に次のコードを追加します。
    
        <li>1 banana</li>
        
    
    ![スクリーンショット](images/recipe-ul.png)
    
    リストは順序付けられていないため、リスト項目の横に数字はなく、箇条書きだけです。