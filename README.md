#アメブロ画像ゲッター
田中美保ちゃんの画像を収集したかったので、ブックマークレットを作ってみた。  
###使い方
適当なブックマークレットのURLを編集して使います。ブックマークを右クリック→編集...→URL:に下記を入れます。   


```
javascript:url=document.getElementById('imgEncircle').firstChild.getAttribute('src');url_list=url.split("/");console.log(url_list);name=url_list[url_list.length-1];function download(url,filename){var elem=document.createElement("a");elem.download=filename;elem.href=url;elem.click();}download(url,name);  
```

![my image](public/bookmark.png)

アメブロにアクセスし、ブックマークをクリックすればダウンロードできます。  

###使用例
![my image](public/before.png)

美保ちゃん可愛いですね。天使みたい。ここで先ほどのブックマークをクリックしてみてください。  

![my image](public/after.png)
このようにダウンロードできます。

GoogleChrome 32.0.17で動作確認。使用は自己責任でお願いします。  

###連絡先
質問等があれば  
<endotakashi1992@icloud.com>  
[@kyouzyuuuuuuuu1](https://twitter.com/kyouzyuuuuuuuu1)  
まで。お気軽にどうぞ。  
![my image](public/face.png)  
author:遠藤孝志  