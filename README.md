#webpack-error-summary

初使化使用webpack的记录

环境：win7,node;

步骤:
1.npm init
*
*输入这个命令后，终端会问你一系列诸如项目名称，项目描述，作者等信息，不过不用担心，
*如果你不准备在npm中发布你的模块，这些问题的答案都不重要，回车默认即可。
*

2.npm install webpack -g
*
*//全局安装
*

3.npm install webpack --save-dev
*
*//安装到你的项目目录
*


问题是：
执行webpack app/main.js public/bundle.js ,一直报错。

this is solve way:win7 一直报错说找不到路径，用cmd模式进入到你的项目的根目录下，运行webpack app/main.js public/bundle.js可解决问题，
但是在git shell 下直接webpack app/main.js public/bundle.js就是error!!
