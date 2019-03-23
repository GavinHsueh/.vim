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
