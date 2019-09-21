# vue

## 搭建vue环境，且安装element-ui

（1）安装nodejs      https://nodejs.org

注：下载nodejs，安装的时候，点击同意，一路next就可以，会自带一个npm（npm是个包管理器，有啥用？是个仓库，需要用到啥 直接npm install packageName就可以了）

（2）安装cnpm

方法一：npm install -g cnpm --registry=https://registry.npm.taobao.org

方法二：npm install -g cnpm

（3）安装vue-cli（安装脚手架：（注：只安装一次））

方法：npm install vue-cli -g

（4）基于webpack生成模板项目: vue init webpack 项目名字

注：安装过程中的解释

（1）project name （项目名称）可以选择y 或者自己起一个

（2）Project descrption （项目描述） 可以直接选择回车或者添加描述

（3）Author （作者）可以直接选择回车或者添加作者

（4）运行施加编译的安装包（回车）

（5）Install vue-router  (是否安装路由)  回车

（6）Use ESLint to your code  （是否进行代码检查或规范）

最后两步是否安装测试环境（直接选择no）

（7）安装package.json里的依赖:npm install

（8）运行:npm run dev

 ## 目录结构介绍
（1）index.html: 首页入口文件，你可以添加一些 meta 信息或统计代码。

（2）package.json:项目配置文件。

（3）.gitignore  忽略的文件

（4）static:静态资源目录，如图片、字体等。

（5）config:	配置目录，包括端口号等。我们初学可以使用默认的。

![Image text](https://github.com/15234477664/new-vue/blob/master/1.png)

（6）build:最终发布的代码存放位置。

（7）node_modules:	npm 加载的项目依赖模块

（8）src:这里是我们要开发的目录，基本上要做的事情都在这个目录里。里面包含了几个目录及文件：assets: 放置一些图片，如logo等。

components: 目录里面放了一个组件文件，可以不用。

App.vue: 项目入口文件，我们也可以直接将组件写这里，而不使用 components 目录。

main.js: 项目的核心文件。

## 为什么选Vue进行项目开发

Vue是一个以数据驱动为核心的渐进式MVVM模式框架。采用了虚拟DOM，在页面的渲染上性能要好一些。同时他还是一个高性能，轻巧，可组件化的库，并且拥有非常易用上手的API库。

## vue的两个核心是什么？

数据驱动和组件化
