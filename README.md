# Real-Url

## 说明

这个仓库存放的是：获取一些直播平台真实流媒体地址（直播源）的 Python 代码实现。获取的地址均可在 PotPlayer、VLC 播放器中播放，部分可在 flv.js 中播放。

目前整理了 **26** 个直播平台：斗鱼直播、虎牙直播、哔哩哔哩直播、战旗直播、网易 CC 直播、火猫直播、企鹅电竞、YY 直播、一直播、快手直播、花椒直播、映客直播、西瓜直播、触手直播、NOW 直播、抖音直播，爱奇艺直播、酷狗直播、龙珠直播、PPS 奇秀直播、六间房、17 直播、来疯直播、优酷轮播台、网易 look 直播、千帆直播。

## 运行

1. 项目使用了很简单的 Python 代码，仅在 Python 3 环境运行测试。
2. 具体所需模块请查看代码中的 import。
3. 爱奇艺直播里有个参数是加盐的 MD5，使用仓库中的 iqiyi.js。

## 反馈

有直播平台失效或新增其他平台解析的，可发 [issue](https://github.com/wbt5/real-url/issues/new)。

## 更新

### 2020.05.23：更新17直播、虎牙直播

2020.05.19：更新火猫、快手、酷狗、PPS

2020.05.08：新增优酷轮播台、look 直播、千帆直播；

- 新增优酷轮播台：优酷轮播台是优酷直播下的一个子栏目，轮播一些经典电影电视剧，个人感觉要比其他直播平台影视区的画质要好，而且没有平台水印和主播自己贴的乱七八糟的字幕遮挡。
- 新增 LOOK 直播：LOOK 直播是网易云音乐旗下的直播平台。
- 新增千帆直播：千帆直播是搜狐旗下的直播平台。

2020.05.01：新增优酷的来疯直播。

2020.04.30：新增17直播。

2020.04.24：修复虎牙、哔哩哔哩、快手、爱奇艺。

2020.02.26：更新一直播。

2020.01.18：更新抖音直播。

2020.01.10：新增酷狗直播、龙珠直播、PPS奇秀直播、六间房。

2020.01.09：新增爱奇艺直播。

2020.01.07：新增抖音直播；删除一个直播平台。

2020.01.03：修复快手直播，请求移动网页版。 

2019.12.31：修复快手直播。 

2019.12.07：修复哔哩哔哩直播。

2019.12.04：更新斗鱼直播，新增一种获取方式。

2019.11.24：新增收米直播。

2019.11.18：新增西瓜直播；触手直播；NOW直播。

2019.11.18：新增一直播；快手直播；花椒直播；映客直播。

2019.11.17：新增火猫直播；新增企鹅电竞；新增YY直播。

2019.11.16：新增战旗tv直播源；新增网易CC直播。

2019.11.09：新增哔哩哔哩直播源。

2019.11.03：新增虎牙直播源。

2019.11.02：修复斗鱼预览地址获取的方法；新增未开播房间的判断。

