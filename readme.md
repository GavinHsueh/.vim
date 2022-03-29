## 关于.vim
本项目主要是整理自己平时使用的 Vim 配置文档和相关插件、脚本，感兴趣的童鞋可以参考使用。
注：适合自己的，才是最好的！

## Windows系统

### 配置文件
将本项目 clone 到 C:\Users\Administrator\ 下，并重命名为 vimfiles。配置文件 vimrc 存放在 vimfiles 文件夹中。

### ctags插件安装：
将 ctags.exe 文件放到vim的安装目录中即可，如 D:/vim/vim82/ 文件夹。

### 安装插件
Vundle 工具用于更方便的管理 Vim 插件，安装方法为在终端输入如下命令(系统先安装 Git)

git clone https://github.com/gmarik/vundle.git C:/Users/Administrator/vimfiles/bundle/vundle

:BundleList     //会显示你 vimrc 里面填写的所有插件名称

:BundleInstall  //会自动下载安装或更新你的插件。

如果下载安装插件速度慢，也可以考虑解压 bundle.zip 包，覆盖 bundle 文件夹。

## Linux系统
### ctags插件安装：
解压 ctags-5.8.tar.gz，编译安装即可。

### 配置文件
将本项目 clone 到 ~/ 下即可。配置文件 vimrc 存放在 .vim 文件夹中。

### 安装插件
Vundle 工具用于更方便的管理 Vim 插件，安装方法为在终端输入如下命令(系统先安装 Git)

git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

:BundleList     //会显示你vimrc里面填写的所有插件名称

:BundleInstall  //会自动下载安装或更新你的插件。

如果下载安装插件速度慢，也可以考虑解压 bundle.zip 包，覆盖 bundle 文件夹。

## 其他
VIM中文社区： https://www.osvim.com

VIMqq交流群：475392251
