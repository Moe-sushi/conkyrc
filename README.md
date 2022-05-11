魔改自gitee@auroot  
原项目地址：https://gitee.com/auroot/conkyrc
### 截图：
![](https://github.com/Moe-hacker/conkyrc/raw/main/screenshot.jpg)
右下角是绿色的cpu监控，左下角是紫红色的那一条是内存监控，上面蓝色的是电池监控，两个小细条分别是/和/home磁盘用量监控
⚠️在手机中chroot安装的linux也可使用conky，但电池不会显示，可以在lua文件中把baterry_percent改成swapperc，BAT0改成swap这样可以改成zram/swap监控
### 安装：
arch系用户使用aur助手安装conky-lua  
debian系用户安装conky-all  
其他系统自己想办法安装带有lua支持的conky  
然后：  
```
git clone https://github.com/Moe-hacker/conkyrc
cd conkyrc
```
然后:  
如果你是kde桌面:
```sh
cp kde/conkyrc ~/.conkyrc
```
如果你是xfce4桌面:
```sh
cp xfce4/conkyrc ~/.conkyrc
```
最后:  
如果你的cpu有4个核心：
```
cp 4cpus/clock.lua ~/.clock.lua
```
如果你的cpu有8个核心：
```
cp 8cpus/clock.lua ~/.clock.lua
```
如果你的cpu有6个核心：  
自己写lua文件去吧，我又不会lua，原项目又没有6核心的。。。  
