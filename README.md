<h1 style="text-align:center"> Front-end programming Final<br>踩地雷Minesweeper<br>地質三 李彥均 b03204032</h1>

## 1. 題目名稱:
* minesweeper踩地雷

## 2. 一句話描述這個 project 在做什麼:
* 模仿與window一模一樣的踩地雷遊戲

## 3. Deployed 連結:
* https://aabb15768.github.io/final

## 4.1 程式使用方式:
* 如果以下方法不能在local端呈現網頁內容，我有將整個react app架在github上面，網址是https://aabb15768.github.io/final
* 作業開啟方式如下（在terminal執行），作業環境為maOS，npm start之後在網頁打http://localhost:3000/
```
cd b03204032_final (or cd final)
sudo npm install
sudo npm start
//如果有跳出錯誤訊息
//sudo npm install fsevents@1.2.7
//sudo npm start
```


## 4.2 遊戲操作方式:
* 右鍵放置旗子標示你認為為地雷的地方
* 左鍵點擊你認為不是地雷的地方
* 上面兩個計時器中間的笑臉/哭臉，可以重置遊戲
* 最下方的bar可以選擇難度，跟window一樣共有三種
* 當標示出全部的地雷時，遊戲為win
* 當左鍵點擊到地雷時，game over

## 5.使用與參考之框架/模組/原始碼
* https://github.com/nickarocho/minesweeper/tree/master/images
* react
## 6.我的貢獻
* 除了圖片與CSS，全部都是自己寫的程式碼。

## 7.使用的技術
* 使用facebook研發的react技術，現在求職前端，也常常被要求要會react，現在業界、全球幾乎所有的前端程式都是用react來做的，整個react coding的架構是以component為基礎，好處是encapsulation，以及最大的優點，網站改變內容時不用整個刷新，只會刷新改變的部分，還有很多的好處。
* 使用react生態系的react router，因此只需要一個html頁面即可做到很多頁面，每個不同頁面（不同url）再切換時，只會更改網頁內容改變的部分。
