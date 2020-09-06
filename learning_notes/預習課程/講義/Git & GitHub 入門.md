# Git & GitHub 入門

## 下一堂

* 遠端伺服器管理與操作
* 常見指令教學 (還原、查看歷史紀錄)

## 為什麼要學 Git ？

* Git 是程式碼版本控制軟體
* 用網頁版型介紹用了 Git 的差異

## 軟體與服務安裝

* [Git 軟體安裝](https://git-scm.com/) - 首頁 Download
* [Github 會員註冊](https://github.com/)
* [SourceTree 軟體安裝](https://www.sourcetreeapp.com/)

## 終端機

* Win：**Git Bash**
    * 開始 > 搜尋輸入 > Git Bash
* Mac：**終端機**
    * 輸入「control + 空白」，關鍵字輸入「終端機」

## 終端機指令學習

* 練習：前往到某資料夾，觀看內容
* 練習：嘗試用指令開一個新資料夾或檔案

|Windows	|MacOS / Linux	|說明	|
|---	|---	|---	|
|cd [路徑]	|cd [路徑]	|前往資料夾路徑	|
|---	|---	|---	|
|cd	|pwd	|取得目前所在的位置	|
|dir	|ls	|顯示資料夾裡的檔案	|
|mkdir	|mkdir	|新增資料夾	|
|無指令	|touch	|開新檔案	|
|copy	|cp	|複製檔案	|
|move	|mv	|移動檔案	|
|del	|rm	|刪除檔案	|
|cls	|clear	|清除畫面上的內容	|

## 嘗試 Git 是否有安裝成功

* 在終端機裡面輸入：git --version

[Image: 螢幕截圖 2019-10-16 11.20.49.png]
## 設定個人資料

* 輸入姓名：`git config --global user.name "gon"`
* 輸入個人的 email：`git config --global user.email "gonsakon@gmail.com"`
* 查詢 git 設定內容：`git config --list`




## 基本指令架構

[Image: 72316309_2739111376108490_535994150261096448_n.jpg]

## Git 常用指令

* 初始化數據庫： `git init`
* [開啟 .git 隱藏檔方案](https://helpx.adobe.com/tw/x-productkb/global/show-hidden-files-folders-extensions.html)
* 查詢當前狀態：`git status`
* 將檔案加入到索引：`git add .`
* 將索引檔案變成一個更新(commit)：`git commit -m "修改內容"`
* 觀察 commit 歷史紀錄： `git log`
* 下載遠端數據庫： `git clone 數據庫網址`
* 更新遠端數據庫： `git push origin master`

