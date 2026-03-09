这个主要是我自己用的，哈哈
，只要运行创建一些连接后，然后，下载米哈游启动器，最好下载两个，一个用来更新国际服，一个用来更新国服，创建连接完成后，
for /d %i in ("G:\software\HoYoPlay\games\Genshin Impact game\GenshinImpact_Data\*") do mklink /J  "G:\software\genshin_impactCN\YuanShen_Data\%~nxi" "%i"
删除Managed Native Plugins 。 然后StreamingAssets里面会有20527480.blk 2KB的不一样，每次启动好像要下载2KB
随便下载一个https://www.homuhomu.cn/ 原神替换包，能让启动器定位游戏就行
然后用米哈游启动器修复游戏完事了，

更新就改config.ini里面的版本号，改成最新的，先更新一个服务器，再修复另一个。
config.ini
国服内容大概如下
```
channel=1
cps=mihoyo
sub_channel=0
[General]
sub_channel=0
uapc={"hk4e_cn":{"uapc":""},"hyp":{"uapc":""}}
downloading_mode=ldiff
game_version=6.1.0
wpf_version=6.1.0.38654915
```
国际服如下
```
channel=1
cps=mihoyo
sub_channel=0
[General]
uapc={"hk4e_global":{"uapc":"d38e36928ae7_"},"hyp":{"uapc":""}}
sub_channel=0
downloading_mode=
game_version=6.1.0
wpf_version=6.1.0.38654915
```
