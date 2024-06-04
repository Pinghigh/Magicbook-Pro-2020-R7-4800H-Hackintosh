# Magicbook-Pro-2020-R7-4800H-Hackintosh

学业问题，可能更新暂缓  
issues and PRs welcome

严禁一切形式售卖，包括“会员免费”“收手工费”等。（某些网站，不想点名了）

荣耀 Magicbook Pro 2020 R7-4800H (aka. HLYL-WXX9) 的 OpenCore Hackintosh 配置

## 硬件变动

- 网卡更换为 Intel AX210

## 目前状态

| 设备   | 状态                                                                                         |
| -------- | ---------------------------------------------------------------------------------------------- |
| GPU      | Metal 正常，Firefox 可能（基本上不）崩溃，Chromium/Electron 应用建议禁用显卡加速（QQNT 打开图片会花屏）（详见 [NootedRed 项目](https://github.com/ChefKissInc/NootedRed)） |
| CPU      | AMD Hackintosh 通病，不赘述                                                              |
| 硬盘   | 原装西数盘，没有问题                                                                 |
| USB      | 右侧 USB 控制器偶尔抽风，重启解决，待优化（似乎问题不存在了）                                    |
| 蓝牙   | 未测试，理论完美                                                                       |
| 无线网卡 | 需要借助 Heliport 进行联网                                                             |
| 声音   | 有线耳机没有高频~~待定制 Codec~~，可以进入 MIDI 设备管理里面，扬声器有两个输出，把一个拉低点就行（但是会有点失真，待解决）；扬声器正常。                                   |
| 电池   | 可充电，没细看                                                                          |

## TODO

- [x] 声卡驱动定制（无效）
- [ ] 精简 EFI

## Credits

借助了挺多东西的，回头有时间了整理。

黑苹果就是站在无数前人的肩膀上看到的远处的风景。

~~大部分 Kext 都是常用的，实在没精力挨个整理了，只写几个少见的~~

- [GUX-RyzenXHCIFix](https://github.com/RattletraPM/GUX-RyzenXHCIFix) 修复了两边 USB 只能用一边的问题
- [NootedRed](https://github.com/ChefKissInc/NootedRed) 为 AMD 部分核显提供显卡加速

参考的教程：

- [Noot Hackintosh Guide](https://chefkissinc.github.io/guide)
- [国光的黑苹果教程](https://apple.sqlsec.com/)

在定制声卡的过程中参考了：

- [黑果小兵的博客](https://blog.daliansky.net/Use-AppleALC-sound-card-to-drive-the-correct-posture-of-AppleHDA.html)
- [林慕凡的笔记](https://byjc.gitee.io/alcdingzhi.html)
