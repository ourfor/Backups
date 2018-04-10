---
title: MIUI Theme
date: 2018-04-07 10:10:34
tags: [Theme,MIUI]
---
最近闲的没事，改了改手机上的主题。虽然主题商店里面有不少精美的主题的，但是这些主题都不够完美，有些图标精致，有些锁屏强大，所以总能勾起修改的欲望。接触主题制作这么久了，***主题商店***还仅仅上架过一款主题，说实话我PS弄得一般般，所以这款唯一上架的主题也仅仅分成了10多块大洋，设计不太会，代码还是懂一点的，主题描述文件是遵循` xml `语法的，所以就借用其他主题的素材，修改部分代码，东拼西凑了一下，最后效果还不错。（仅限自用，请勿上传到主题商店）

<!--more-->
### 效果预览
![主屏](http://p5culcl8r.bkt.clouddn.com/autojump_0.png)
这个` AT&T `是在手机的` 设置-状态栏-运营商 `这里修改。而这个` Love you %d days `是修改了主题的状态栏描述文件，这个数字就是电池实时电量的百分比。

![Time](http://p5culcl8r.bkt.clouddn.com/autojump_1.png)

时间设置成` 星期+日期|时间 `也在主题的描述文件里面设置的，图标则是使用了***H2SO***的图标。

![Tips](http://p5culcl8r.bkt.clouddn.com/autojump_2.png)

### 时间居中
状态栏时间居中是在解锁System后使用` MiUI Statusbar Pro `设置的，当然你也可以反编译` system/priv-app/miuisystemui `里的` miuisystemui.apk `,这同样需要*root*权限。

相关教程[下载](http://p5culcl8r.bkt.clouddn.com/%E7%8A%B6%E6%80%81%E6%A0%8F%E5%B8%83%E5%B1%80%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%EF%BC%88%E4%BF%AE%E8%AE%A2%E7%89%88%EF%BC%89.pdf)

### 应用主题
[主题下载](http://p5culcl8r.bkt.clouddn.com/H2OS.mtz)(仅限自用，请勿上传到主题商店)
[MIUI Theme Editor](http://p5culcl8r.bkt.clouddn.com/com.mixapplications.miuithemeeditor.apk)

我使用的是星空的官改rom，由于这手机平时用得着，所以就退出体验版内测了，估计大部分人用的是官方的开发版或者稳定版，没更新过系统的话，用` MIUI Theme Editor `（不需要root）注入主题，就可以在主题里面应用，只不过这个软件第一次使用需要下载大概60m的数据文件，需要翻墙下载。
