## iOS TRTC Demo
> [APPStore 体验地址](https://itunes.apple.com/cn/app/id1400663224?mt=8)

![](https://main.qcloudimg.com/raw/fa84e7c632b74483e9dc91dc04a8255e.jpg)

## Android TRTC Demo
> [应用宝体验地址](https://android.myapp.com/myapp/detail.htm?apkName=com.tencent.trtc&ADTAG=mobile)

![](https://main.qcloudimg.com/raw/41cbcff8ec2a64b6e76c2573abbb8acf.jpg)

## Mac TRTC Demo
> [下载后解压体验](http://trtc-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_Mac_Demo.tar.bz2)

![](https://main.qcloudimg.com/raw/8d146afb3b2dd07d5b5f1ca4432a9411.jpg)

## Windows TRTC Demo
> [下载后安装体验](http://trtc-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_Win_Demo.exe)

![](https://main.qcloudimg.com/raw/00ec3ebc86902044c51a5487c18dcd0c.jpg)

## 微信小程序

![](https://main.qcloudimg.com/raw/81662cce932b2500addac28baf6a83b3.jpg)

## Chrome浏览器

> [谷歌浏览器打开体验](https://sxb.qcloud.com/miniApp/?from=qcloud.com)

![](https://main.qcloudimg.com/raw/56e2bbc928a11bac85e5b78ac171b3bc.jpg)


## 符号冲突（Symbol Duplicate）

如果您的项目中已经使用过腾讯视频云 LiteAV 体系的相关产品，可能会出现符号冲突的问题（symbol duplicate）的问题。

这是由于以上 SDK 均是基于腾讯视频云 LiteAV 架构开发的，它们共同复用了相同的采集模块、编解码器、降噪模块、前处理等底层基础模块，所以才会出现符号重复。

![](https://main.qcloudimg.com/raw/05468b96b5df3c5c77f680356080f755.png)

您可以下载腾讯视频 LiteAV_Professional 版本，该版本集成了以上 SDK 的全部功能，而且由于 60% 以上的底层模块是复用的，所以产生的安装包体积增量远远小于集成两个独立的 SDK（音视频 SDK 中的主要体积增量源于编解码等各种基础模块）。

| 专业版（iOS）| 专业版（Android） | 
|:-------:|:-------:|
| [**LiteAV_Professional_iOS_6.0.6400**](http://liteavsdk-1252463788.cosgz.myqcloud.com/6.0/TXLiteAVSDK_Professional_iOS_6.0.6400.zip) | [**LiteAV_Professional_Adroid_6.0.6400**](http://liteavsdk-1252463788.cosgz.myqcloud.com/6.0/LiteAVSDK_Professional_Android_6.0.6400.zip)|
