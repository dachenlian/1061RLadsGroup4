# 看看Facebook使用者在Apple和Microsoft的粉絲專業都留些什麼留言

## 我們怎麼擠出結果

1. 用Rfacebook的getPage()抓Apple和Microsoft的粉專上的post ID，粉專各抓300 posts
2. 有了post ID 之後，我們用了getPost()抓每一個post的comments然後存到一個vector
3. 接下來就是cleaning 和 lemmatization
4. 現在就做出一個詞頻表
5. 最後根據詞頻表做出wordcloud~
6. 詳細內容請看Rmd檔

## 資料夾的內容

1. 抓 Microsoft 和 Apple 留言的程式碼.Rmd跟html版本
