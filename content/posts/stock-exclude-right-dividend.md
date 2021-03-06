+++
title = "除權息、現金及股票股利"
date = 2021-03-18T00:45:06+08:00
tags = ["股市"]
categories = ["股市"]
draft = false
description = "股市菜鳥的筆記，方便自己快速查閱。"
+++

<!--more-->
---

## 用途
快速了解除權息股利對應股價，方便快速比較各股股利配發情況。

---
## 配股、配息

* 配息：配發`現金股利`
* 配股：配發`股票股利`，也稱盈餘轉增資，將使股本增加

股本增加 ↑| 股本減少 ↓
:-----|:---------
現金增資| 減資
`發放股票股利`| 實施庫藏股買回
可轉換公司債的股權轉換|
員工認股權執行 

---
## 除權、除息
除權息日期集中於六月中旬至八月底

除權息的概念是發放股利之後，股價將向下調整，發放多少股息，公司市值將會降低多少。

---
### 除息：配發現金股利
計算方式：
```
除息後股價 = 除息前股價 - 現金股利(元)
```

範例：
> 華南金股價20元，每股配1元現金股利。除息後股價為`20 - 1 = 19元`。
> 除息完後一張華南金將為`19`元並加上`1`元的現金股利，實際整體價值還是為`20`元。

---
### 除權：配發股票股利，股價扣除相應市值
概念：

股本增長一倍，股價就減少一倍。
```
1000(股數) * 30(股價) = 30000(總價值)
```
當股數成長一倍，總價值固定。
```
2000(股數) * 15(股價) = 30000(總價值) 股價將更動為15元。
```

- 補充：

台灣股本為每股`10`元，當出現配股`1`元時，代表意義為配`1/10`股股票股利，也就是`0.1`股。

計算公式：
```
除權後股價 = 除權前股價 / ( 1 + 股票股利(元) / 10)
```
範例：
> 華南金股價20元，要配發2元的股票股利，相當於每股要配發0.2股股票股利。
> 除權後價格為 = 20 / (1 + 2 / 10) = 

---
## 同時配發現金股利和股票股利
公式：
```
除權息後股價 = ( 除權除息前股價 - 現金股利 ) / ( 1 + 股票股利(元) / 10 )
```

---
## 參考
[Mr.Market市場先生](https://rich01.com/blog-post_76/)

[Blog](https://davidhuang1219.pixnet.net/blog/post/325433772-%E9%99%A4%E6%AC%8A%E6%81%AF%E5%8F%83%E8%80%83%E5%83%B9%E5%A6%82%E4%BD%95%E8%A8%88%E7%AE%97%EF%BC%9F-%E5%A6%82%E4%BD%95%E8%A8%88%E7%AE%97%E5%90%8C%E6%99%82%E5%90%AB%E3%80%8C)