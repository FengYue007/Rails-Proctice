###### tags: `Rails`、`安裝`、`開新專案`

# Rails 安裝

## 先看一下Rails 版本

下指令 `$ rails -v`，應該會看到 Rails 6.1.3

## 如果沒有用gem安裝

下指令 `$ gem install rails`

## 建立一個新的專案

下指令 `$ rails new hello-world`

在終端機，在你找的到的地方下，rails new hello-world，這只是一個練習測試專案，沒有要做什麼事情。我們只是在確認環境是否安裝完成。

rails new 下去之後，它就會跑這些東西…
![](https://i.imgur.com/vhNzYfX.png)

跑、跑、跑，最，最終應該會看到一個蛋糕或拉炮的畫面，你看到了，代表你的環境是沒問題的。這些過程要全部跑完成，才會有拉炮跟蛋糕。
![](https://i.imgur.com/QVpqnAD.png)

如果有拉炮跟蛋糕，測試完這個專案就可以丟掉了，因為這只是要測試環境是否有正確安裝完成。

如果沒看到的話，要想辦法解決它，代表中間有缺了東西，可能是Nodejs或可能缺其它的東西，那就要想辮法補。

![](https://i.imgur.com/PqbDLUI.png)

## 執行專案內容
在終端機下指令` $ cd hello-world` 切回剛建立的專案
在終端機下指令` $ rails s `

## 開瀏覽器輸入網址
![新專案啟動畫面](https://i.imgur.com/z13fTYN.png)

在瀏覽器輸入網址`127.0.0.1:3000`

有成功出現小人的頁面，就代表成功！
