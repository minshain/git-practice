# 關於 Makedown 語法筆記
## 基本
1. 井字號 \# ，為標題大小。
1. 星字號 \* ，改變字體，一星為斜體，二星為粗體，例如 *斜體* **
粗體** 。
1. 數字加點加空格 \1. ，做清單，使用同數字，會自動編號。
1. *, +, -, 表示無序號清單。
1. 反斜線 // 可使忽略後面的語法
1. 大於\> ，用於文字引用，須放置在最前面。例如 
>引用自國家地理頻道

代辦事項清單，可以用/-[]及/-[x]，例如
- [] 吃飯
- [x] 洗澡

## 連結
\[描述](http://somewhere) ，例如
[google](http://google.com)
\<RUL> ，直接轉超連結，例如 
<minshain@gmail.com>



## 程式碼
要插入一段程式碼，可以用\``` 三個反引號包圍起來，並且標註使用的語言，就能接高亮標示。例如:
```python
# This program says hello and asks for my name.
print("Hello world!")
print('What is your name?')
myName = input()
print('It is good to meet you, ' + myName)
```
+ 用一個反引號\'來包起一個小區塊。
` test for good ! `

## 圖片
Markdown使用一種和連結很相似的語法來標記圖片，使用方法為如下：

一個驚嘆號!
接著一個方括號，裡面放上圖片的替代文字
接著一個普通括號，裡面放上圖片的網址，最後還可以用引號包住並加上 選擇性的’title’文字。

行內圖片的語法看起來像是：
```markdown
![Alt text](/path/to/image.jpg "Option title")
```
## 表格
最初的 Markdown 規格並沒有包含表格，但 GFM 與 Markdown Here 都有支援。這個撰寫語法也常出現在電子郵件中。
```makedown
冒號（Colons）是用來對齊的（擺左齊左、擺右齊右，都擺就置中）。

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

最外圍的豎線（|）不是絕對需要，在原始文檔中你可以不要太在意美觀，實際轉成網頁或電子書時會呈現得很好。你也可以在表格內使用行內格式。

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```
結果:
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## 水平分隔線
```makedown
三個或三個以上的符號，必須在獨立的一行，前後不能有其他文字。

---
短橫線（Hyphens）

***
半形星號（Asterisks）

___
下底線（Underscores）
```

