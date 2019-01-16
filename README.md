这是一个bootstrapt4的练习

用到的工具：

bootstrapt的CDN：https://getbootstrap.com/
创建服务器：package

*************************************************************************************
1.搭建环境

step1.创建目录兴建index.html
打开CMD建立bootstrapt4目录
mkdir bootstrapt4

step2.在index.html头部加上cdn
写一个html5的结构
link 贴上 bootstrapt4 的css的cdn  （cdn参考位置：https://getbootstrap.com/）
添加cdn的前后次序很重要
bootstrap4.css-->jQuery.is-->popper.js-->bootstrap.js

step3.自定义的css和js
自定义的都是加在最后一行

step4.搭建项目的服务器
cmd输入
yarn init -y

安装brower-sync
yarn add browser-sync

回到package.json文件
加入
"scripts":{
    "start":"./node_modules/.bin/browser-sync start --server --no-notify --files='index.html, *.css, *.js'"
  }

回到cmd启动项目
yarn start

**************************************************************************************
2.搭建github项目

step1.新建.gitignore
在本地新建.gitignore文件，打开http://github.com/github/gitignore
找到Node.gitignore文件，把上面的代码完全复制贴到本地的.gitignore文件


step2.打开CMD进入项目建立githug
cmd 输入 $ cd 项目位置

$ cd 

