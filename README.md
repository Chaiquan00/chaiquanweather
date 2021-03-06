﻿# chaiquanweather

## 项目参考：《第一行代码》 第2版 项目实战练习

### 软件1932 周挺

#### 项目地址：https://github.com/Chaiquan00/chaiquanweather

---

![](https://upload-images.jianshu.io/upload_images/25581879-8951517576b3de6e.png)

项目内容：
本软件就是利用现有的网络快速获取网络上的天气信息并显示到手机终端上通过HTTPRequest、OkHttpClient、JSON抓取和解析等技术让用户在有网络的前提下可以随时随地查看天气。

本软件是一个安卓程序，启动程序后可以进行城市的选择，可以显示当前和未来的天气状况，包括温度、AQI、PM2.5、生活指数、生活建议等。这些天气数据是通过后台服务获取的，这个后台服务可以通过API提供的服务获取天气预报信息，并将天气信息保存在本地SQLite数据库中，最后通过后台服务读取后显示在界面上。

该软件的基本功能需求有：

(1) 城市选择界面：对要显示天气预报的城市进行设置；

![城市选择界面](https://upload-images.jianshu.io/upload_images/25581879-f6ffb2eec8d0ed40.png)

(2) 显示界面：通过文字和图片显示当前的天气情况，包括温度、AQI、PM2.5、生活指数、生活建议等。同时，显示界面还具有下拉刷新功能，用户每下拉一次就会触发后台更新天气数据。

![天气显示界面](https://upload-images.jianshu.io/upload_images/25581879-a9054d97064bb265.png)
