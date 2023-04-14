# Markdownをひたすら試すページ

# 見出し @ シャープ#

# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6

# Block段落 @ 空白行

段落1

段落2

# Br改行 @ space2つ
hoge
fuga  
piyo

# Blockquotes 引用@ >

> 引用
> 引用
>> 多重引用

# Code コード@バッククォート3つで囲む
```print 'hoge'```

# インラインコード@バッククォートで単語を囲む
`インラインコード`

# pre 整形済みテキスト @ 半角スペース4個もしくはタブで、コードブロックをpre表示
    aaa

# Hr 水平線 @ アンダースコア、アスタリスク、ハイフンなどを3つ以上連続して記述
***
aaa
___

# UI箇条書きリスト @ ハイフン、プラス、アスタリスクのいずれかを先頭に記述
* 111
+ 222
- 333

# OI番号付きリスト @ 番号.を先頭に記述（ネストはタブで表現）
1. aaa
2. bbb
3. ccc

# Link リンク @ [表示文字](URL)でリンクに変換
[Google](https://www.google.co.jp/)

# 外部参照リンク
URLが長くて読みづらくなる場合や同じリンクを何度も使用する場合は、リンク先への参照を定義できます。
[Yahooを見る][Yahoo]

[Yahoo]: http://www.yahoo.co.jp

# 強調
em  
*aaa*  
_aaa_  
  
strong  
**aaa**  
__aaa__  

em+strong  
***aaa***  
___aaa___  

# Images 画像 @ 先頭の!で画像と認識される。大きさ指定はimgタグ
![alt]([画像URL]([https://github.com/firesign2023](https://github.com/firesign2023/Progate/blob/main/top.png)))
![代替文字列](URL "タイトル")

<img src="[attach:cat.jpg]([https://github.com/firesign2023](https://github.com/))" alt="attach:cat" title="attach:cat" width="200" height="200">

# Table 表 @ - と |

| TH1 | TH2 |
----|---- 
| TD1 | TD3 |
| TD2 | TD4 |

| 左揃え | 中央揃え | 右揃え |
|:---|:---:|---:|
|1 |2 |3 |
|4 |5 |6 |
