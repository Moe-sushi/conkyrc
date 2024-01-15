### Thanks：
[auroot/conkyrc](https://gitee.com/auroot/conkyrc)
### Screenshot：
![](https://github.com/Moe-sushi/conkyrc/raw/main/screenshot.jpg)
### Installation：
You should install conky with lua support(conky-all in Debian,conky-lua in Archlinux) first.      
Then:
```
git clone https://github.com/Moe-sushi/conkyrc
cd conkyrc
```
If you are using KDE:
```sh
cp kde/conkyrc ~/.conkyrc
```
If you are using Xfce4      
```sh
cp xfce4/conkyrc ~/.conkyrc
```
For other desktop environments,please test it yourself.  
Finally:  
If your cpu has 4 cores：      
```
cp 4cpus/clock.lua ~/.clock.lua
```
If your cpu has 8 cores：      
```
cp 8cpus/clock.lua ~/.clock.lua
```
If your cpu has 12 cores：  
```
cp 12cpus/clock.lua ~/.clock.lua
```
If your cpu has 6 cores:      
Write it yourself please. I've wrote 12cpus myself.
