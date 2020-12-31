---
title: hexo使用教程
date: 2020-12.31
type: "categories"
---
# 使用hexo需要的环境

1.安装Node.js

2.安装Git

# 安装hexo

1.在本地新建一个文件夹,用于存放hexo项目

2.npm install -g hexo-cli  安装全局hexo

3.安装完成之后，执行hexo -v，来查看当前安装的 版本，如果能显示出来就说明hexo安装成功了。

4.hexo init 【hexo项目名】，初始化hexo项目。

5.初始化完成之后，通过cd+hexo项目名的命令进入hexo项目，会在所在文件夹下面看到生成的nodeModules文件夹，说明初始化完成。

6.执行npm install，安装所需要的依赖问价。

7.安装完成之后执行hexo server命令，通过服务器启动项目，默认使用本地的4000端口，如果能在本地浏览器上通过localhost：4000，访问到hexo的首页说明hexo项目已经创建成功。