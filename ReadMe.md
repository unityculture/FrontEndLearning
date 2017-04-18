# Todo 
 
- sublimecodeintel 無用
- 

# Course Note

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

- 用command + D 可以幫助我們：
    - 快速修改全部打錯的相同標籤

##  3.02-極速產出圍繞內容的標籤方式

way1 : control + W 選取的範圍 -> 在外層包標籤
way2 : control + W 選取的範圍 + div.nav > ul.nav -> 外層包好且產屬性

control+W 對一系列的清單，不要只有頭跟尾，可用 *
ex: control+W -> type in `li*`

## 3.03-使用外掛選取及轉換網頁色彩

了解css有關的顏色外掛工具

- install colorhilighter package
- 色馬會出現在sublime中
- 右鍵可以用choose color
- convert color 可以調整透明度

## 3.04-超好用的假圖產生器

- install package : fakeimg
- fakeimg + tab : size/img color/text color/text can be adjusted.
- div.album>ul>li*30>a[#]>fakeimg : 不可以同時共用兩個(emmet + fakeimg)外掛
- 先做 emmet + command D + fakeimg
 
## 3.05-快速設定專案資料夾

- finder > folder > 拉進來
- command + K + B : 開啟sidebar

## 3.06-如何在sublime中直接上傳網頁

不太需要 先跳過
- install package : fptsync

## 4.01-強大的snippet功能

Tools > Developer > new snippet > 把第三行取代成 程式碼 > tabtrigger 取消註解 並且命名
如果命名跟其他套件相衝(menu in emmet)，換名字，中文可

## 4.02-極重要的snippet規劃與應用方法

如果Snippet太多了話，要如何找到我們要的snippet?

重新將 snippet 取名：個人識別字-分類-用途
ex: sheng-html-menu

## 4.03-snippet極速應用技

當關鍵字衝突到怎麼辦？當忘記關鍵字怎麼辦？當片段打不出來的時候怎麼辦?

if 清單 與 導覽 是類似的東西，我們可以開一個資料夾 list 將兩個snippet放進去。
在記去改snippet的 tabtrigger。
只要打 list 在按 tab 就可以列出兩個snippet

但關鍵字要全打對才可以提示有點麻煩，因此安裝新的外掛來解決這個問題。


 ##  5.01-安裝與修改sublime主題配色

package control 輸入 material theme。看一看覺得還不錯

install package -> material theme

若 sidebar 沒有更動。可以參考官網的說明：Active the theme。複製貼上到setting - user

有時候更新sublime之後會掉，那可以到官網在複製貼上一次 Active the theme


## 5.02-package control網站應用

ok. !
