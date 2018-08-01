# jy-music

## 概述
项目是基于Vue.js，成品是一个移动端的音乐播放器，来源于imooc的实战课程 

## 效果图
![image](https://github.com/Davisjy/Vue-music/blob/master/images/first.jpeg)
![image](https://github.com/Davisjy/Vue-music/blob/master/images/second.jpeg)
![image](https://github.com/Davisjy/Vue-music/blob/master/images/third.jpeg)
![image](https://github.com/Davisjy/Vue-music/blob/master/images/four.jpeg)

### 数据来源
所有数据都来自于QQ音乐，抓取自QQ的接口，大部分接口都是JSONP，抓取比较容易，其中一些接口限制了host，不能直接抓取，采用的方法是用axios代理，设置header，以此绕过host的限制

## 技术栈
![image](https://github.com/Davisjy/Vue-music/blob/master/images/vendor.jpeg)

#### 从本项目能学到什么
可直接应用工作的13个基础组件，15个业务组件
1. confirm：确认对话框组件              2. listview：通讯录列表组件
3.loading：加载态组件                   4.no-result：无结果展示组件
5.progress-bar：进度条组件              6.progress-circle：圆形进度条组件
7.scroll：移动端滚动组件                8.search-box：搜索框组件
9.search-list：搜索列表组件             10.slider：轮播图组件
11.switches：开关切换组件               12.top-tip：顶部消息提示组件
13. song-list：歌曲列表组件


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
