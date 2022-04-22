## 注意事項
-某些語法的外觀樣式如：引用、分隔線、項目符號等，會因為使用者套用的 Hexo 主題而有不同。

-圖片可以放在 Hexo 資料夾一併上傳到 GitHub，例如圖片 123.jpg 放到 myblog/source/images 路徑下，然後圖片語法連結的地方輸入 /images/123.jpg ，就會顯示該圖片。
-不過這種方法筆者不建議(也就是不建議把 GitHub 當作圖床用)，因為當文章一多，會有機會達到 GitHub Pages 的使用限制；因此可以搜尋各大免費圖床來使用，如 Imgur, Upload.cc 等。

-HTML 語法盡量包在 Markdown 語法裡面，否則可能會造成一些顯示上的錯誤，舉例如下：

```   
語法撰寫範例一：將「今天天氣真好。」顯示粗體並更改為紅色
**<font color=#FF0000>今天天氣真好。</font>**

語法撰寫範例二：將「Title」設定成等級一標題並更改為藍色
# <font color=#0000FF>Title</font>
```  
-呈上，因為 HTML 語法和 Markdown 語法交錯使用，在 hexo-admin 文章後台的編輯區和預覽區可能會有顯示問題，請先 publish 後，以 localhost 的文章頁面顯示為準。
