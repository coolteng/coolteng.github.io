README《機械手臂展示說明檔》
====
# [《互動式機械臂示範教材展示》](https://coolteng.github.io/)[coolteng.github.io](https://coolteng.github.io/)

此<<互動式機械臂示範教材網站>>https://coolteng.github.io/ 乃由鄧崇林從零奇巧搭建GitHub個人網站所建成，由於會用到筆者過去製作的互動式 Applet 小程式，然而谷歌Chrome 及微軟Edge 瀏覽器不再支援此小程式，因此必須①用 Internet Explorer 瀏覽器以及②設定例外網站清才能正常執行。
[機械手臂展示](https://coolteng.github.io/)
****
### Author:果冻虾仁
### E-mail:Jelly.K.Wang@qq.com
****
## 目錄
* [線上驗證 Java 版本](#clteng)
* [設定例外網站清單](#設定例外網站清單)
* [機械臂互動式示範教學](#機械臂互動式示範教學)
* [機械臂互動式示範內容概要](#機械臂互動式示範內容概要)


| 選單號 | 居中  |
| ------ |:---------------:|
| 4.5.1 | 思考題：控制這台機械手臂是採什麼樣的運動學| 
| 4.5.2 | 思考題：鐵達尼號深海探險是採什麼樣機械手臂| 
| 4.5.3 | 思考題：這張您所看到的圖是描寫什麼樣的情境| 
| 4.5.4 | 隆中對：2D模擬機械臂之後是要迎接什麼樣的挑戰| 
| 4.5.5 | 構想對：3D模擬七軸機械臂是要達到什麼樣的境界| 


<h3 id="clteng">1.線上驗證 Java 版本</h3> 
------
<1<線上驗證 Java 版本>>https://java.com/zh_TW/download/installed8.jsp
+>Chrome 及Edge 瀏覽器不支援 NPAPI 外掛程式，因此將不會執行所有 Java 內容。請切換為其他瀏覽器 (Internet Explorer 或是 Safari (Mac)) 以執行 Java 外掛程式。
+>若本地機器無 Java執行環境，也請先安裝 Java。

##2.# 設定例外網站清單
<2<設定例外網站清單>>https://www.java.com/zh_TW/download/faq/exception_sitelist.xml
+>從 Java 7 Update 11 版開始，Java 已經預設在高安全性設定中封鎖自行簽署和未簽署的 Applet 應用程式
+>從 Java 7 Update 51 版本開始導入了例外網站清單功能
+>由於Java不允許調降安全規格(Java不允許使用者執行未經簽署 (未簽署)、自行簽署 (不是由信任授權單位簽署) 或是遺漏權限屬性的應用程式)，將網站加入例外網站是唯一解法
2.1 [啟動 Java 控制面板]
2.1.1 啟動 Java 控制面板之法一：控制台 > 程式集 > Java(32位元)
2.1.2 啟動 Java 控制面板之法二：開始 > Java > 設定 Java

2.2 [編輯網站清單]例外網站清單會在 Java 控制面板的"安全"頁籤中管理。清單會顯示在該頁籤中。若要新增、編輯或移除清單中的 URL，請按一下【編輯網站清單】按鈕。
2.3 接著按一下「例外網站清單」視窗中的【新增】按鈕。
2.4 按一下「位置」欄位下空白的欄位，分別新增輸入下列兩個 URL：
2.4.1 URL：https://coolteng.github.io/
2.4.2 URL：http://robotics.ee.uwa.edu.au

2.5 按一下【確定】按鈕以儲存您輸入的 URL。如果按一下【取消】按鈕，則不會儲存 URL。
![IEsetting](https://coolteng.github.io/myPage/gif/JavaSafedUrlSetting.PNG "")
2.6 按一下「安全性警告」對話方塊中的【繼續】按鈕。

### 機械臂互動式示範教學
<3[機械臂互動式示範教學]>
+>開啟 Internet Explorer 瀏覽器並輸入網址：https://coolteng.github.io/


### 機械臂互動式示範內容概要

4[機械臂互動式示範教材概要]>
- 4.1 👍🏽 看機械手臂如何延伸我們疆界且帶出無限想像力

| 選單號 | 選單名稱與解釋  |
| ------------ |:---------------:|
| 4.1.1 | 機械手臂有探險：助人進行危險環境探索示範| 
| 4.1.2 | 機械手臂有頭腦：與人進行井字遊戲下棋示範| 
| 4.1.3 | 機械手臂有遊戲：讓人融入競技遊戲臨場示範| 
| 4.1.4 | 機械手臂有醫療：幫人進行輔助開刀手術示範| 
| 4.1.5 | 機械手臂有藝術：請人進行素人畫像描繪示範| 
| 4.1.6 | 機械手臂有舞姿：藝人樣機械人曼妙舞蹈秀場| 
| 4.1.7 | 機械手臂有包裝：無人生產線上的無隱手示範| 
| 4.1.8 | 機械手臂有異形：奇人巧思創並聯式機械手臂| 
| 4.1.9 | 機械手臂有不了：猿人意念控機械臂隔空抓物| 

- 4.2 👍🏽 從發展電腦2D模擬機械手臂中掌握它是如何運動的

| 選單號 |  選單名稱與解釋  |
| ------ |:---------------:|
| 4.2.1 | 機械手臂運動學原理簡易介紹以及應用類型概要| 
| 4.2.2 | 運動學沒搞好參數的致命慘劇所幸無損機械手臂| 
| 4.2.3 | 正向運動學（Forward Kinematics）自動展示機| 
| 4.2.4 | 逆向運動學（Inverse Kinematics）自動展示機| 
| 4.2.5 | 正向運動學模擬：機械手臂三連桿角度互動示範| 
| 4.2.6 | 逆向運動學模擬：文字選單設手掌角度互動示範| 
| 4.2.7 | 逆向運動學模擬：垂直滑桿設手掌角度互動示範| 
| 4.2.8 | 逆向運動學模擬：水平滑桿設手掌角度互動示範| 
| 4.2.9 | 水平滑桿調值與三個垂直滑桿顯示各角度出狀況| 
| 4.2.A | 修正前一版三垂直滑桿各顯示不同角度比例問題| 

- 4.3 👍🏽 進一步實際做出六軸機械手臂還需要什麼知識

| 選單號 |   選單名稱與解釋  |
| ------ | :---------------:|
| 4.3.1 | 六軸機械手臂之機構選材以及伺服馬達等等組裝| 
| 4.3.2 | 六軸機械手臂所用伺服馬達控制理論分析與應用| 
| 4.3.3 | 六軸機械手臂之伺服馬達控制校正以及操作限定| 

- 4.4 👍🏽 本次模擬2D機械手臂所採用電腦程式語言特色

| 選單號 |   選單名稱與解釋  |
| ------ | :---------------:|
| 4.4.1 | Processing 語言可以很有創意：靈感鳥驚艷現身| 
| 4.4.2 | Processing 語言可以很有手感：網狀彈性絲布料| 
| 4.4.3 | Processing 語言可以很有層次：3D空間立體走秀| 
| 4.4.4 | Processing 語言可以很有激情：模擬煙火般燦爛| 
| 4.4.5 | Processing 語言可以很有契合：開放及各種整合| 

- 4.5 👍🏽堂課自己看到了什麼又學到了什麼‧那接下來呢

| 選單號 | 選單名稱與解釋  |
| ------ |:---------------:|
| 4.5.1 | 思考題：控制這台機械手臂是採什麼樣的運動學| 
| 4.5.2 | 思考題：鐵達尼號深海探險是採什麼樣機械手臂| 
| 4.5.3 | 思考題：這張您所看到的圖是描寫什麼樣的情境| 
| 4.5.4 | 隆中對：2D模擬機械臂之後是要迎接什麼樣的挑戰| 
| 4.5.5 | 構想對：3D模擬七軸機械臂是要達到什麼樣的境界| 

----
