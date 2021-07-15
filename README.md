# iTerm-mac
此库主要是Mac上配置iTerm的简易教程



iTerm配置说明

这是一个很智能的配置，不论你电脑里面有没有安装iTerm，不管你有没有.zshrc配置文件，

git配置文件，git忽略文件，以及git的默认编辑器都已经更改为vim，等等这些。此配置文件

都已经做好，你需要做的就是以下步骤哦

只需要操作以下橙色标记的几步，即可配置成功??

1 把localConfig.tgz localConfig.tgz拷⻉到家⺫录下 （也可以拷贝到别的目录下，以下操作是

以家目录下为准）

2 每台Mac电脑都有自带的终端，打开 Mac Mac⾃带终端 （这是对于没有安装iTerm

的情况下，如果已经安装，那么可以在iTerm里面操作也行）

3 在终端里面进入家目录下执行以下操作

4 tar xfvz localConfig.tgz tar xfvz localConfig.tgz (解压)（也可双击此文件解压）

5 然后 cd lolocalConfig cd lolocalConfig (进入解压完的localConfifig目录，必须进入

lolocalConfifig里面，因为运行此脚本是基于这个脚本所在的目录)

6 lsls 此时看到有两个目录，一个脚本文件 分别为 dotfifiles tools install.sh

7 注意： dotfifiles 里面很多隐藏文件，所以打开这个文件的时候看不到，不

要删除。lolocalConfifig里面也有很多隐藏文件

8 执行 ./install.sh ./install.sh 回车 ，输入密码 出现 [Info]: Success! [Info]: Success! 即可成功

9 重新打开iTerm，你就会看到已经配置好的iTerm。

附加条： 更改操作git的用户名和邮箱

1. 方法一：在家目录下， vi .gitconfig 直接更改里面的name，email，然后保存退

出。

2. 方法二：执行以下两步

1. git config --global user.name "XXXX"

2. git config --global user.email XXXXXXX@163.com

