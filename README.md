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
可直接应用工作的13个基础组件
> 
* [x] confirm：确认对话框组件 
* [x] listview：通讯录列表组件
* [x] loading：加载态组件
* [x] no-result：无结果展示组件
* [x] progress-bar：进度条组件 
* [x] progress-circle：圆形进度条组件
* [x] scroll：移动端滚动组件
* [x] search-box：搜索框组件
* [x] search-list：搜索列表组件
* [x] slider：轮播图组件
* [x] switches：开关切换组件
* [x] top-tip：顶部消息提示组件
* [x] song-list：歌曲列表组件

15个业务组件
>
* [x] add-song：添加歌曲到列表组件 
* [x] disc：歌单详情页组件
* [x] m-header：页面头部组件
* [x] music-list：歌曲列表页面组件
* [x] player：播放器内核组件 
* [x] playlist：播放列表组件
* [x] rank：排行榜页面组件
* [x] recommend：推荐页面组件
* [x] search：搜索页面组件
* [x] singer：歌手页面组件
* [x] singer-detail：歌手详情页组件
* [x] suggest：搜索提示列表组件
* [x] tab：顶部导航栏组件
* [x] top-list：排行榜详情页组件
* [x] user-center：用户中心页组件

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
