# 豆瓣电影搜索功能

## 功能介绍

* 首页（正在热映的电影，电影分类，搜索功能）
* 搜索电影列表页面（搜索关键词显示对应的结果）
* 电影详情页面（根据在列表页面的选择进入相关的电影详情页面）

## 资料及准备

* [vue]('https://cn.vuejs.org/')
* [vue-router]('https://router.vuejs.org/zh/')
* [豆瓣电影api]('https://developers.douban.com/wiki/?title=movie_v2')
* vue-cli

vue-cli不会使用请看这里（node要先安装[下载地址](http://nodejs.cn/download/)）

* 安装全局vue-cli(npm install vue-cli -g)
* 初始化，生成项目模板，demo是自己项目的名字，叫amao、agou(vue init webpack demo)
* 进入生成的项目文件夹(cd demo)
* 初始化，安装依赖(npm install)

此时请耐心等待，少则一分钟，多则大半年！初始化成功后执行npm run dev看看能不能启动了（具体其他问题找我交流）

## 效果实现

![效果](./image/gif.gif "效果")

## api的使用

* [top250]('https://developers.douban.com/wiki/?title=movie_v2#top250')
* [关键字搜索电影]('https://developers.douban.com/wiki/?title=movie_v2#search')
* [电影详情]('https://developers.douban.com/wiki/?title=movie_v2#subject')

## 静态ui图

首页
![首页](./image/1.png '首页')

详情页面
![详情页面](./image/2.png '详情页面')

## 任务

### 第一周

搭建两个前端页面，首页能显示top250热映的电影列表。

搜索功能和详情页面只需要静态页面即可。

### 第二周

处理第一周未完成的任务，遇到问题的解惑和总结。

搜索功能和详情页面功能的实现。

## 问题总结

大家遇到的问题，在群里随时提问，一些很有趣的问题，我会整理放在这里。

当然，我希望大家遇到问题，首先是自己去解决。解决的过程远比你实现这个效果来的有意义。