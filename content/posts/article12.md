---
title: "我的Windows配置"
date: 2026-08-21T22:02:44+08:00
#lastmod: 2026-08-21T22:02:44+08:00
draft: false
summary: "万一那天有钱了换新电脑了呢"
tags: 
- 
categories: 
- 计算机
author: "万全"
---
人可以没有梦想，不过有梦想的生活还是要好过没有梦想的。不过看现在个人PC的报价，我是不太想换了。无他，穷逼。把自己电脑最基础的需要留个底，下次重装或者换电脑的时候，就可以把其他的冗余抛弃掉了，就好像自己定期抛弃掉一些小姐姐视频、电影、电视剧以及游戏存货一样。大概不抛弃一点什么，就无法前进吧。

## 各种Office
- Microsoft Office全家桶，毕竟充了钱。我还是很认可office 全家桶的，毕竟实际上我是面向文档工作。
- libreOffice
- voleOffice  放在自己U盘上面。不过libreoffice也有portable版本欸。

## 文档处理
- [calibre](https://calibre-ebook.com/zh_CN/download)
- [obsidian](https://obsidian.md/download)  自己的库在OneDrive里面，并且nutshare插件同步到坚果云上面。
- Adobe acrobat
- [freeplane](https://github.com/freeplane/freeplane) 思维导图工具
- [Anki](https://apps.ankiweb.net/#downloads)
- [marktext](https://marktext.me/)  免费软件，可以作为typora的替代，不过我都是直接用obsidian。

## 软件管理
- scoop
  - ffmpeg  最好还是配一个 ffmpeg desktop
  - hugo  博客搭建工具
  - openlist 网盘管理
  - git
  - tortoisegit 要安装中文的language pack


## 专业和科研
- Mimics
- ProPlan
- [3Dslicer](https://www.slicer.org/)  开源工具
- Geomagic
- Radiant Dicom 医学图像查看软件
- [zotero](https://www.zotero.org/) 文献管理，神TM一年三次大版本更新，插件还不一定跟得上，不能随便升级
  - add on market 
  - 茉莉花
  - style
  - scihub
  

## 微软商店下载
- OneQuick
- Watt Toolkit  相当于steam，origin，github的翻墙。
- Potplayer

## 个人博客相关
- [PicGo](https://picgo.app/)  图床软件，配合cloudflare r2
- [Visual Studio Code](https://code.visualstudio.com/download)
- Github Desktip 注意使用ssh
- cloudflare one client

## 娱乐
- [steam](https://store.steampowered.com/)  网上还有很多家的网点，是我没有想到的。
- battlenet 暴雪战网，除了暗黑三 我基本没怎么玩过。
- uplay
- [老男人游戏网](oldmanemu.net) 模拟器游戏rom，喜欢玩模拟器游戏，大概是童年经历影响一生的证据。
  - [Visualboy Advance](https://visualboyadvance.org/) GBA模拟器
  - [PPSSPP](https://www.ppsspp.org/)   PSP模拟器
  - [DeSmuME](https://desmume.org/)  NDS模拟器
  - [Citra](https://citraemulator.org/download/)   3DS模拟器

## 系统
- [win11debloat](https://github.com/Raphire/Win11Debloat) Windows 系统冗余组件清理 别人推荐但是我还用过。
- [everythingtoolbar](https://github.com/srwi/EverythingToolbar) 将everything搜索放到资源管理器上。不过我用了directoryOpus 就已经是整合的了。
- Powertoys 
- foxmail 基本上只用来挂QQ邮箱，不过自己用网页端用惯了
- SSRdog
- Everything
- bandizip 压缩包处理 
- 7zip
- ditto 剪贴板
- freefilesync  文件同步工具
- [localsend](https://localsend.org/)   局域网文件传输
- 百度网盘
- Internet Download Manager
- [Geek Uninstaller](https://geekuninstaller.com/download) 软件卸载
- Faststone capture 录屏软件
- Bigpic 图片放大，有网页端口，有API


## 系统进一步处理

打开Windows Terminal，输入
```
winget uninstall "Windows web experience Pack"
```
这条指令会删除Windows的一个废案组件，现在你完全不需要用到
它。这么做可以有效减少内存开销。
