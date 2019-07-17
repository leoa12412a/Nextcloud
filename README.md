# Nextcloud

## Nextcloud是什麼?

Nextcloud是一款open source的雲端資料儲存庫，且支援apple和android系統的APP。

![image](https://github.com/leoa12412a/Nextcloud/blob/master/app.PNG)

## 如何安裝?

這邊我們選擇直接使用docker安裝，非常快速且便利，這也是為什麼選擇這款軟體的原因。

1.apache image
```
docker run -d -p 8080：80 nextcloud
```

2.fpm image
```
$ docker run -d nextcloud:fpm
```

## 導覽

可以在 設定=> 個人資訊 => 語言選擇 語言

![image](https://github.com/leoa12412a/Nextcloud/blob/master/1.jpg)
![image](https://github.com/leoa12412a/Nextcloud/blob/master/1.jpg)


安全性方面，可以知道每次登入是在那裡的什麼機器上

![image](https://github.com/leoa12412a/Nextcloud/blob/master/4.jpg)

活動 : 只要有任何變動都可以透過設定用mail來通知使用者

![image](https://github.com/leoa12412a/Nextcloud/blob/master/3.jpg)


