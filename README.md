魔改自gitee@auroot  
原项目地址：https://gitee.com/auroot/conkyrc
### 截图：
![](https://github.com/Moe-hacker/conkyrc/raw/main/screenshot.jpg)
右下角绿色的是cpu监控，左下角紫红色的是内存监控，上面蓝色的是电池监控，中间是时间，外圈两个小细条分别是/和/home磁盘用量监控。  
⚠️在手机中chroot安装的linux也可使用conky，但电池不会显示，可以在lua文件中把baterry_percent改成swapperc，BAT0改成swap这样可以将电池监控改成zram/swap监控
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
其他桌面自己测试   
最后:  
如果你的cpu有4个线程：      
```
cp 4cpus/clock.lua ~/.clock.lua
```
如果你的cpu有8个线程：      
```
cp 8cpus/clock.lua ~/.clock.lua
```
如果你的cpu有12个线程：  
```
cp 12cpus/clock.lua ~/.clock.lua
```
如果你的cpu有6个线程。。。。      
这边建议您自己写，12线程是我改的，也是我目前的配置，就当备份了，6线程等我有了相关设备再说吧咕咕咕。。。
