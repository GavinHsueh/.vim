## 关于myvim
使用vim几年的时间，也总结整理了一些vim使用方法，这里主要是整理我本人使用的vim配置文档和相关插件、脚本，感兴趣的童鞋可以借鉴参考。

## Windows系统
### ctags插件安装：
将ctags.exe文件放到vim的安装目录中即可，如vim73文件夹。

### 配置文件
讲 _vimrc文件 和 vimfiles文件夹 放到vim安装目录中覆盖原文件。

### 安装插件
Vundle工具用于更方便的管理vim插件，安装方法为在终端输入如下命令(系统先安装git)

git clone https://github.com/gmarik/vundle.git d:/vim/vimfiles/bundle/vundle

:BundleList     //会显示你vimrc里面填写的所有插件名称

:BundleInstall  //会自动下载安装或更新你的插件。

如果下载安装插件速度慢，也可以考虑解压bundle.zip包，覆盖bundle文件夹。

## Linux系统
### ctags插件安装：
解压ctags-5.8.tar.gz，编译安装即可。

### 配置文件
将 _vimrc 重命名为 .vimrc，vimfiles 重命名为 .vim 放到用户主目录。

### 安装插件
Vundle工具用于更方便的管理vim插件，安装方法为在终端输入如下命令(系统先安装git)

git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

:BundleList     //会显示你vimrc里面填写的所有插件名称

:BundleInstall  //会自动下载安装或更新你的插件。

如果下载安装插件速度慢，也可以考虑解压bundle.zip包，覆盖bundle文件夹。

## 其他
VIM中文社区： http://www.osvim.org

VIMqq交流群：475392251
