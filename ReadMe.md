# 3/29

## 2.02 輸入html與假文

- ! + tab
- html -> set syntex
- h1 + tab 
- lorem : 產生假文

##   2.03-自訂預覽快速鍵及快速輸入class_ID方式

- keybinding : 設定 open in browser 的快速鍵
- .wrapper + tab -> div.class
- \#wrapper + tab -> div.id

## 2.04-利用emmet快速輸入html屬性

- a[href=...] + tab -> 快速設定屬性
  - target="_blank" -> 開新視窗
- input + tab-> 開一個text的文字框
- input:c + tab -> 開一個checkbox--方形文字框
- input:r + tab -> 開一個 radio--圓形文字框

## 2.05-利用emmet快速建構網頁內容文字

輸入標籤的同時也一併將內容撰寫完成

- a[href="http://google.com"]{connet to google} + tab -> 同時產生內容與標籤，大括號內放內容小括號內放屬性

## 2.06-我要一次打10行

如何快速產出多個標籤

- li*6 + tab -> 一次產出六個li
- li{title}*6 + tab -> 一次產出六個li 具有內容

##  2.07-一行鍵出父層與子層原始碼

- ul>li + tab -> 產出階層式

## 2.08-快速建構同層多種標籤的原始碼

學習加號的使用方式，讓一行建置網頁能愈加彈性方便。

- +號為css的親代選取器，為同一層

## 2.09-設定出獨立處理原始碼的群組區塊

運用+ > {} [] 快速產出網頁內容

- command + / ->註解
- (...) -> 獨立區塊，不會跟外面有任何關係

## 2.10-使用升冪符號跳至父層

使用升冪符號讓您更快建構原始碼 

- ^: .wraper>.header>.logo+.nav^.main>.sidebar+.container^.footer

##  2.11-快速產出中文假文章

- ctlorem : 產出繁體中文假文章

## 2.12-使用錢號快速產出連續數字

- ul>li{$}*10
- ul>li.A$${$$}*10

##  3.01-快速選取與修改網頁內容
