# 2
2.0
##  git 上每个用户有自己专属的邮箱和用户名，在安装完git后首先要确定自己要使用的邮箱和用户名；
## 创建仓库;
$ mkdir learngit
$ cd learngit
$ pwd
## pwd 命令会在当前目录下建立一个仓库，在Windows环境下位于/Users/xh/Desktop,也可以在其他位置但是注意储存路径中不要有中文；
$ git init
## git init 这个命令会把这个仓库变为可管理;
##  git add ，git commit 这是将文件添加到仓库的命令,比如说先创建一个test.txt文本在learngit下,文本内容为git is the best language.然后
$ git add test
$ git commit -m"the test"
## -m是对添加的文件进行说明，是很有必要的，执行完commit命令后会出现 1 file changed,1 insertions(一个文件被改动，插入了一行内容);
## 需要注意的是commit一次可以提交多个文件，所以在commit之前可以多次使用add；


xh@DESKTOP-HO0HI6U MINGW64 ~/Desktop
$ mkdir learngit

xh@DESKTOP-HO0HI6U MINGW64 ~/Desktop
$ cd learngit

xh@DESKTOP-HO0HI6U MINGW64 ~/Desktop/learngit
$ pwd
/c/Users/xh/Desktop/learngit

xh@DESKTOP-HO0HI6U MINGW64 ~/Desktop/learngit
$ git init
Initialized empty Git repository in C:/Users/xh/Desktop/learngit/.git/

xh@DESKTOP-HO0HI6U MINGW64 ~/Desktop/learngit (master)
$ git config --global user.email "1959565006@qq.com"

xh@DESKTOP-HO0HI6U MINGW64 ~/Desktop/learngit (master)
$ git config --global user.name "huotuichaodan"

xh@DESKTOP-HO0HI6U MINGW64 ~/Desktop/learngit (master)
$ git add test

xh@DESKTOP-HO0HI6U MINGW64 ~/Desktop/learngit (master)
$ git commit -m "the test"
[master (root-commit) d047e3a] wrote a readme file
 1 file changed, 1 insertions(+)
 create mode 100644 readme

