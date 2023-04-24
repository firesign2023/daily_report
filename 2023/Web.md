# はじめに

HTTP通信について、Google検索を例にまとめてみました。




HTTP（Hypertext Transfer Protocol）とはWebサーバとWebブラウザの間で情報をやりとりするためのプロトコルです。

``プロトコル``：通信するためのルール



![Google](https://github.com/firesign2023/daily_report/blob/img/image.png "Google")

Google検索するときの処理の流れです。

1. Chromeなどのブラウザで Google (URL : https://www.google.co.jp/ )にアクセスします。  
2. 検索ワード「例：おいしい店」を入力し、Googleに送信します。``リクエスト``  
3. Googleから検索結果を受け取る。``レスポンス``  

<br><br>

通信するためには相手側の``IPアドレス``、``ポート番号``が必要ですが、

``DNS(Domain Name System)``という技術でURLからIPアドレスに変換してくれます。

~~~
https://www.google.co.jp/　→→→　``IPアドレス:192.168.xxx.xxx
~~~

また、上記の場合はポート番号を省略しているので、デフォルトの値が使用されます。<br>
    

|  プロトコル  |  ポート番号  |
| ---- | ---- |
|  HTTP  |  80番  |
|  HTTPS  |  443番  |

