README《機械手臂展示說明檔》
====
# [《互動式機械臂示範教材展示》](https://coolteng.github.io/)[coolteng.github.io](https://coolteng.github.io/)

此<<互動式機械臂示範教材網站>>https://coolteng.github.io/ 乃由鄧崇林從零奇巧搭建GitHub個人網站所建成，由於會用到筆者過去製作的互動式 Applet 小程式，然而谷歌Chrome 及微軟Edge 瀏覽器不再支援此小程式，因此必須①用 Internet Explorer 瀏覽器以及②設定例外網站清才能正常執行。
[機械手臂展示](https://coolteng.github.io/)
****
### Author:鄧崇林
### E-mail:coolteng@gmail.com
### 建置本網站的用意
1. 製作客戶端的 JavaScript 動態網頁設計，重點放在動態啟動互動式 Applet 小程式。
2. 不用熟悉git命令，沒錯，這一項可以完全忽略，單純透過網頁操作，就能制霸部署 GitHub 網站。
3. 從零奇巧搭建 GitHub 個人網站，先新建《GitHub 個人網站》，後建《網頁倉庫》，再加以整合而成。
4. 製作由 StrapDown.js 封裝 Markdown 文檔，進而動態轉成 HTML 格式的應用技巧，線上說明就是這樣製作而成的。
5. 提供有關機械手臂在各重點領域方方面面的應用側寫，以及相關的基本設計與製作，從而建立由外到裡的通盤認知。
6. 支持線上互動學習機械手臂其背後的正向運動學（Forward Kinematics），以及逆向運動學（Inverse Kinematics）。
****
## 🏁 目錄
* [👍建置本網站的用意](#建置本網站的用意)
* [👍線上驗證 Java 版本](#clteng)
* [👍設定例外網站清單](#設定例外網站清單)
* [👍機械臂互動式示範教學](#機械臂互動式示範教學)
* [👍機械臂互動式示範內容概要](#機械臂互動式示範內容概要)
------

<h3 id="clteng">線上驗證 Java 版本</h3> 

- Oracle's [線上驗證 Java 版本](
https://java.com/zh_TW/download/installed8.jsp
)
- 由於Chrome 及Edge 瀏覽器不支援 NPAPI 外掛程式，因此將不會執行所有 Java 內容。請切換為其他瀏覽器 (Internet Explorer 或是 Safari (Mac)) 以執行 Java 外掛程式。
- 若本地機器無 Java執行環境，也請先安裝 Java。

------

### 設定例外網站清單
- [設定例外網站清單說明](https://www.java.com/zh_TW/download/faq/exception_sitelist.xml)
- 從 Java 7 Update 11 版開始，Java 已經預設在高安全性設定中封鎖自行簽署和未簽署的 Applet 應用程式
- 從 Java 7 Update 51 版本開始導入了例外網站清單功能
- 由於Java不允許調降安全規格(Java不允許使用者執行未經簽署 (未簽署)、自行簽署 (不是由信任授權單位簽署) 或是遺漏權限屬性的應用程式)，將網站加入例外網站是唯一解法
* 2.1.[啟動 Java 控制面板]
  * 2.1.1.啟動 Java 控制面板之法一：控制台 > 程式集 > Java(32位元)
  * 2.1.2.啟動 Java 控制面板之法二：開始 > Java > 設定 Java

* 2.2.[編輯網站清單]例外網站清單會在 Java 控制面板的"安全"頁籤中管理。清單會顯示在該頁籤中。若要新增、編輯或移除清單中的 URL，請按一下【編輯網站清單】按鈕。
* 2.3.接著按一下「例外網站清單」視窗中的【新增】按鈕。
* 2.4.按一下「位置」欄位下空白的欄位，分別新增輸入下列兩個 URL：
  * 2.4.1.URL：https://coolteng.github.io/
  * 2.4.2.URL：http://robotics.ee.uwa.edu.au
* 2.5.按一下【確定】按鈕以儲存您輸入的 URL，如下圖所示。如果按一下【取消】按鈕，則不會儲存 URL。
>![clt01](https://coolteng.github.io/myPage/armMenu/JavaSafedUrlSetting.PNG "")

* 2.6.按一下前述新生「安全性警告」對話方塊中的【繼續】按鈕。

------
### 機械臂互動式示範教學
- 機械臂互動式示範教學，開啟 Internet Explorer 瀏覽器並輸入網址：https://coolteng.github.io/
- 成功開啟後的畫面如下圖所示(會與瀏覽器不同而有差異)，若點擊畫面左下角大拇指選項，也能線上閱讀說明：
>![clt02](https://coolteng.github.io/myPage/armMenu/擷取m00.PNG "")

- 如用微軟 Edge 瀏覽器時，請依下圖切換成 IE 瀏覽器：
>![clt03](https://coolteng.github.io/myPage/armMenu/擷取m001由Edge切換IE.PNG "")

- 當微軟 IE 瀏覽器初次執行本機械臂互動網頁時會出現下圖警示，請續按【稍後詢問我】即可
>![clt04](https://coolteng.github.io/myPage/armMenu/擷取m002續按稍後詢問我.PNG "")

- 當執行互動式 Applet 小程式時會出現下圖警示，請續按【執行】即可
>![clt05](https://coolteng.github.io/myPage/armMenu/擷取003執行Java的安全警告續按執行即可.PNG "")

--------------
### 機械臂互動式示範內容概要
- 4.1 👍🏽 看機械手臂如何延伸我們疆界且帶出無限想像力

|選單號| 選單名稱與解釋  |
| ------------ |:---------------:|
| 4.1.1 | [機械手臂有探險：助人進行危險環境探索示範](#arm11)| 
| 4.1.2 | [機械手臂有頭腦：與人進行井字遊戲下棋示範](#arm12)| 
| 4.1.3 | [機械手臂有遊戲：讓人融入競技遊戲臨場示範](#arm13)| 
| 4.1.4 | [機械手臂有醫療：幫人進行輔助開刀手術示範](#arm14)| 
| 4.1.5 | [機械手臂有藝術：請人進行素人畫像描繪示範](#arm15)| 
| 4.1.6 | [機械手臂有舞姿：藝人樣機械人曼妙舞蹈秀場](#arm16)| 
| 4.1.7 | [機械手臂有包裝：無人生產線上的無隱手示範](#arm17)| 
| 4.1.8 | [機械手臂有異形：奇人巧思創並聯式機械手臂](#arm18)| 
| 4.1.9 | [機械手臂有不了：猿人意念控機械臂隔空抓物](#arm19)| 

 [回單元](#機械臂互動式示範內容概要)

- 4.2 👍🏽 從發展電腦2D模擬機械手臂中掌握它是如何運動的

|選單號|  選單名稱與解釋  |
| ------ |:---------------:|
| 4.2.1 | [機械手臂運動學原理簡易介紹以及應用類型概要](#arm21)| 
| 4.2.2 | [運動學沒搞好參數的致命慘劇所幸無損機械手臂](#arm22)| 
| 4.2.3 | [正向運動學（Forward Kinematics）自動展示機](#arm23)| 
| 4.2.4 | [逆向運動學（Inverse Kinematics）自動展示機](#arm24)| 
| 4.2.5 | [正向運動學模擬：機械手臂三連桿角度互動示範](#arm25)| 
| 4.2.6 | [逆向運動學模擬：文字選單設手掌角度互動示範](#arm26)| 
| 4.2.7 | [逆向運動學模擬：垂直滑桿設手掌角度互動示範](#arm27)| 
| 4.2.8 | [逆向運動學模擬：水平滑桿設手掌角度互動示範](#arm28)| 
| 4.2.9 | [水平滑桿調值與三個垂直滑桿顯示各角度出狀況](#arm29)| 
| 4.2.A | [修正前一版三垂直滑桿各顯示不同角度比例問題](#arm2A)| 

 [回單元](#機械臂互動式示範內容概要)

- 4.3 👍🏽 進一步實際做出六軸機械手臂還需要什麼知識

|選單號|   選單名稱與解釋  |
| ------ | :---------------:|
| 4.3.1 | [六軸機械手臂之機構選材以及伺服馬達等等組裝](#arm31)| 
| 4.3.2 | [六軸機械手臂所用伺服馬達控制理論分析與應用](#arm32)| 
| 4.3.3 | [六軸機械手臂之伺服馬達控制校正以及操作限定](#arm33)|

 [回單元](#機械臂互動式示範內容概要)

- 4.4 👍🏽 本次模擬2D機械手臂所採用電腦程式語言特色

|選單號|   選單名稱與解釋  |
| ------ | :---------------:|
| 4.4.1 | [Processing 語言可以很有創意：靈感鳥驚艷現身](#arm41)| 
| 4.4.2 | [Processing 語言可以很有手感：網狀彈性絲布料](#arm42)| 
| 4.4.3 | [Processing 語言可以很有層次：3D空間立體走秀](#arm43)| 
| 4.4.4 | [Processing 語言可以很有激情：模擬煙火般燦爛](#arm44)| 
| 4.4.5 | [Processing 語言可以很有契合：開放及各種整合](#arm45)| 

 [回單元](#機械臂互動式示範內容概要)
 
- 4.5 👍🏽堂課自己看到了什麼又學到了什麼‧那接下來呢

|選單號| 選單名稱與解釋  |
| ------ |:---------------:|
| 4.5.1 | [思考題：控制這台機械手臂是採什麼樣的運動學](#arm51)| 
| 4.5.2 | [思考題：鐵達尼號深海探險是採什麼樣機械手臂](#arm52)| 
| 4.5.3 | [思考題：這張您所看到的圖是描寫什麼樣的情境](#arm53)| 
| 4.5.4 | [隆中對：2D模擬機械臂之後是要迎接什麼樣的挑戰](#arm54)| 
| 4.5.5 | [構想對：3D模擬七軸機械臂是要達到什麼樣的境界](#arm55)| 

 [回單元](#機械臂互動式示範內容概要)
 
----

### arm11

* 機械手臂有探險：助人進行危險環境探索示範
>![arm11](https://coolteng.github.io/myPage/armMenu/擷取m11.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm12

* 機械手臂有頭腦：與人進行井字遊戲下棋示範
>![arm12](https://coolteng.github.io/myPage/armMenu/擷取m12.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm13

* 機械手臂有遊戲：讓人融入競技遊戲臨場示範
>![arm13](https://coolteng.github.io/myPage/armMenu/擷取m13.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm14

* 機械手臂有醫療：幫人進行輔助開刀手術示範
>![arm14](https://coolteng.github.io/myPage/armMenu/擷取m14.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm15

* 機械手臂有藝術：請人進行素人畫像描繪示範
>![arm15](https://coolteng.github.io/myPage/armMenu/擷取m15.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm16

* 機械手臂有舞姿：藝人樣機械人曼妙舞蹈秀場
>![arm16](https://coolteng.github.io/myPage/armMenu/擷取m16.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm17

* 機械手臂有包裝：無人生產線上的無隱手示範
>![arm17](https://coolteng.github.io/myPage/armMenu/擷取m17.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----
### arm18

* 機械手臂有異形：奇人巧思創並聯式機械手臂
>![arm18](https://coolteng.github.io/myPage/armMenu/擷取m18.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm19

* 機械手臂有不了：猿人意念控機械臂隔空抓物
>![arm19](https://coolteng.github.io/myPage/armMenu/擷取m19.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm21

* 機械手臂運動學原理簡易介紹以及應用類型概要
>![arm21](https://coolteng.github.io/myPage/armMenu/擷取m21.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm22

* 運動學沒搞好參數的致命慘劇所幸無損機械手臂
* 此為互動式 Applet 小程式
>![arm22](https://coolteng.github.io/myPage/armMenu/擷取m22.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm23

* 正向運動學（Forward Kinematics）自動展示機
* 此為互動式 Applet 小程式
>![arm23](https://coolteng.github.io/myPage/armMenu/擷取m23.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm24

* 逆向運動學（Inverse Kinematics）自動展示機
* 此為互動式 Applet 小程式
>![arm24](https://coolteng.github.io/myPage/armMenu/擷取m24.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm25

* 正向運動學模擬：機械手臂三連桿角度互動示範
* 此為互動式 Applet 小程式，拉動左側垂直滑桿可對應控制同色系的手臂部位
>![arm25](https://coolteng.github.io/myPage/armMenu/擷取m25拉動左側垂直滑桿可對應控制同色系的手臂部位.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm26

* 逆向運動學模擬：文字選單設手掌角度互動示範
* 此為互動式 Applet 小程式，左右拉動下方水平角度數值可控制手爪俯仰角的運動設定
>![arm26](
https://coolteng.github.io/myPage/armMenu/擷取m26左右拉動下方水平角度數值可控制手爪俯仰角的運動設定.PNG ""
)

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm27

* 逆向運動學模擬：垂直滑桿設手掌角度互動示範
* 此為互動式 Applet 小程式，上下拉動左側垂直滑桿之角度數值可控制手爪俯仰角的運動設定
>![arm27](
https://coolteng.github.io/myPage/armMenu/擷取m27上下拉動左側垂直滑桿之角度數值可控制手爪俯仰角的運動設定.PNG ""
)

* [回單元](#機械臂互動式示範內容概要)
 
----
### arm28

* 逆向運動學模擬：水平滑桿設手掌角度互動示範
* 此為互動式 Applet 小程式，左右拉動下方水平滑桿可控制手爪俯仰角的運動設定
>![arm28](
https://coolteng.github.io/myPage/armMenu/擷取m28左右拉動下方水平滑桿可控制手爪俯仰角的運動設定.PNG ""
)

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm29

* 水平滑桿調值與三個垂直滑桿顯示各角度出狀況
 * 此為互動式 Applet 小程式，左右拉動下方水平滑桿可控制手爪俯仰角的運動設定
>![arm29](https://coolteng.github.io/myPage/armMenu/擷取m29左右拉動下方水平滑桿可控制手爪俯仰角的運動設定.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm2A

* 修正前一版三垂直滑桿各顯示不同角度比例問題
 * 此為互動式 Applet 小程式，左右拉動下方水平滑桿可控制手爪俯仰角的運動設定
>![arm2A](
https://coolteng.github.io/myPage/armMenu/擷取m2A左右拉動下方水平滑桿可控制手爪俯仰角的運動設定.PNG ""
)

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm31

* 六軸機械手臂之機構選材以及伺服馬達等等組裝
>![arm31](https://coolteng.github.io/myPage/armMenu/擷取m31.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----
### arm32

* 六軸機械手臂所用伺服馬達控制理論分析與應用
>![arm32](https://coolteng.github.io/myPage/armMenu/擷取m32.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm33

* 六軸機械手臂之伺服馬達控制校正以及操作限定
>![arm33](https://coolteng.github.io/myPage/armMenu/擷取m33.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm41

* Processing 語言可以很有創意：靈感鳥驚艷現身
* 此為互動式 Applet 小程式，靜靜地觀賞飛躍的書本，有如拍動著扉頁的靈感鳥，在無限空間中釋放出非凡創意
>![arm41](https://coolteng.github.io/myPage/armMenu/擷取m41.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm42

* Processing 語言可以很有手感：網狀彈性絲布料
* 此為互動式 Applet 小程式，用滑鼠點按網線托拉移位後再放下後有動態現象發生
>![arm42](https://coolteng.github.io/myPage/armMenu/擷取m42滑鼠點按網線托拉移位後再放下後有動態現象發生.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm43

* Processing 語言可以很有層次：3D空間立體走秀
* 此為互動式 Applet 小程式，在畫面中上下移動滑鼠會有動態現象發生
>![arm43](https://coolteng.github.io/myPage/armMenu/擷取m43在畫面中上下移動滑鼠會有動態現象發生.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm44

* Processing 語言可以很有激情：模擬煙火般燦爛
* 此為互動式 Applet 小程式，在畫面中上下隨處點按滑鼠會有動態現象發生
>![arm44](https://coolteng.github.io/myPage/armMenu/擷取m44在畫面中上下隨處點按滑鼠會有動態現象發生.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm45

* Processing 語言可以很有契合：開放及各種整合
* 只能在IE中有條件顯示，這是克意布置的作業，需要指出為什麼會這樣？(Hint: HTML安全議題)
>![arm45](https://coolteng.github.io/myPage/armMenu/擷取m45只能在IE中有條件顯示.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm51

* 思考題：控制這台機械手臂是採什麼樣的運動學
>![arm51](https://coolteng.github.io/myPage/armMenu/擷取m51.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm52

* 思考題：鐵達尼號深海探險是採什麼樣機械手
>![arm52](https://coolteng.github.io/myPage/armMenu/擷取m52.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm53

* 思考題：這張您所看到的圖是描寫什麼樣的情境
>![arm53](https://coolteng.github.io/myPage/armMenu/擷取m53.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm54

* 隆中對：2D模擬機械臂之後是要迎接什麼樣的挑戰
>![arm54](https://coolteng.github.io/myPage/armMenu/擷取m54.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----

### arm55

* 構想對：3D模擬七軸機械臂是要達到什麼樣的境界
* 此為互動式 Applet 小程式，在執行畫面中能拉動各種滑桿，或直接拖曳機械臂，會有動態現象發生
>![arm55](https://coolteng.github.io/myPage/armMenu/擷取m55.PNG "")

* [回單元](#機械臂互動式示範內容概要)
 
----
