# auto-sprites
利用sass和compass自动合成图片并生成css

需要环境
1.ruby
2.sass
3.compass

1.安装ruby
windows下从官网下载安装包安装即可
地址：https://www.ruby-lang.org/en/documentation/installation/
注意安装时，有一步需要添加到系统环境变量，勾选上
打开cmd命令行  输入 ruby -v 查看是否安装成功

2.安装sass
ruby安装成功以后就可以安装sass了，
命令行输入 gem install sass
等待安装完成后 输入 sass -v查看是否安装成功

3.安装compass
安装同上，gem install compass
compass -v查看是否安装成功

4.将本demo下载到本地以后，吧images/icons中的图片换成自己需要的图片，注意图片名尽量不要以1.png等数字开头的，图片必须为png格式

5.命令行进入你的目录，如cd D:\web\zujiandemo\demo2\sprite

6.命令行输入 compass compile
就可以合成精灵图了

生成的sprite图在images文件夹下
生成的css在stylesheet下
命令行输入compass watch即可监听，文件有修改时自动生成对应的文件
