# 概要
telnetを使ってHTTPのやり取りを覗きます。

# 準備

このリポジトリを公開できる（XAMPPとか）ディレクトリに配置してください。


# GET

```
GET /get.php HTTP/1.1
```

# POST

```
POST /post.php HTTP/1.1  
Host: a-http.localhost  
Content-Type: application/x-www-form-urlencoded  
Content-Length: 6  
  
key=10  
```


# 参考URL

* [HTTP :: telnet で HTTP](http://tm.root-n.com/protocol:http:telnet_http)
* [telnetでHTTPリクエストを送ってみよう。](http://masasuzu.hatenablog.jp/entry/20110205/1296886588)
* [HTTP勉強したまとめ](http://momongahoi.hatenablog.com/entry/2014/01/18/155207)

