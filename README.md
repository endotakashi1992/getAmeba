#アメブロ画像ゲッター
田中美保ちゃんの画像を収集したかったので、ブックマークレットを作ってみた。  
###使い方
下のリンクをブックマークバーにドラックアンドドロップしてください。  
[画像ゲッター](javascript:url=document.getElementById('imgEncircle').firstChild.getAttribute('src');url_list=url.split("/");console.log(url_list);name=url_list[url_list.length-1];function download(url,filename){var elem=document.createElement("a");elem.download=filename;elem.href=url;elem.click();}download(url,name);)  

アメブロにアクセスし、ブックマークをクリックすればダウンロードできます。

###例


image

このページでブックマークレットをクリックすれば、ダウンロードできます。  

image

GoogleChrome 32.0.17で動作確認。  