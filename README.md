# Zqian.github.io

如何搭建个人博客

前期准备：安装node.js（需要用到node.js的npm管理模块） 、 git 、git账号（将博客托管到GitHub上）

node.js安装步骤:http://www.cnblogs.com/Zqian/p/8034562.html

github：如果已经拥有github账号，需要创建一个仓库，仓库命名格式为username.github.io(其中username为你的GitHub用户名)

正题：hexo安装（以下命令在git 中完成）

安装hexo

npm install hexo -g //-g表示全局安装, npm默认为当前项目安装

建立一个hexo博客文件夹

hexo init //执行init命令初始化hexo到你指定的目录

执行命令

hexo generate //自动根据当前目录下文件,生成静态网页

安装 hexo-server插件，输入命令：

$ npm install hexo-server --save

执行命令

hexo server //运行本地服务

然后。。。。

浏览器输入：

http://localhost:4000 就可以看到效果了

ctrl+c 可以结束服务
