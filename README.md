# Magicbook-Pro-2020-R7-4800H-Hackintosh

严禁一切形式售卖，包括“会员免费”“收手工费”等。（某些网站，不想点名了）

荣耀 Magicbook Pro 2020 R7-4800H (aka. HLYL-WXX9) 的 OpenCore Hackintosh 配置

## 硬件变动

- 网卡更换为 Intel AX210

## 目前状态

| 设备   | 状态                                                                                         |
| -------- | ---------------------------------------------------------------------------------------------- |
| GPU      | Metal 正常，Firefox 等一些 OpenGL 加速应用会使系统崩溃，Chromium/Electron 应用建议禁用显卡加速（详见 [NootedRed 项目](https://github.com/ChefKissInc/NootedRed)） |
| CPU      | AMD Hackintosh 通病，不赘述                                                              |
| 硬盘   | 原装西数盘，没有问题                                                                 |
| USB      | 右侧 USB 控制器偶尔抽风，重启解决，待优化                                    |
| 蓝牙   | 未测试，理论完美                                                                       |
| 无线网卡 | 需要借助 Heliport 进行联网                                                             |
| 声音   | 有线耳机没有高频，待定制 Codec，扬声器正常                                   |
| 电池   | 可充电，没细看                                                                          |

## TODO

- [ ] 声卡驱动定制
- [ ] 精简 EFI

## Credits

借助了挺多东西的，回头有时间了整理。

黑苹果就是站在无数前人的肩膀上看到的远处的风景。
