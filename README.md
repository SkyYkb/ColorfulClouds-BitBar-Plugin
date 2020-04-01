# ColorfulClouds-BitBar-Plugin
<img src="https://github.com/SkyYkb/ColorfulClouds-BitBar-Plugin/raw/master/src/screenshot.png" alt="运行界面" width="500">

## 简介
彩云天气BitBar插件。通过BitBar实现把天气显示到macOS菜单栏。

## 系统需求
- macOS
- 安装了 Bitbar
- 安装了 Python

## 什么是BitBar？
此插件和BitBar都托管在GitHub上，这是BitBar的项目地址，作者给出了比较详细的介绍：https://github.com/matryer/bitbar。

## 使用说明
使用此插件，你需要拥有OpenCage API Key（https://opencagedata.com/api）来获取你的位置信息（当然你可以手动指定经纬度和城市），彩云天气API Key（http://caiyunapp.com/api/pricing.html）来获取天气信息（必要）。
目前程序还没有加入BitBar Repository，所以你暂时只能通过下载脚本并导入你的BitBar插件目录来使用此插件。具体方法：
- 下载本repo中的`weather.15m.py`，并将其放入BitBar的插件目录中
- 在状态栏选中任意一个BitBar图标，进行刷新操作

## 其他
本插件已经达到稳定版所需了，若有bug或建议欢迎提issue。
如果你想了解更多类似的BitBar插件，可以查看少数派的这篇文章：https://sspai.com/post/58683
