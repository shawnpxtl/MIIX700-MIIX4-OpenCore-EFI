# Miix700-Hackintosh-Monterey-OpenCore

本套EFI可以保证启动并且适应macOS Monterey系统，并且除了不工作的硬件之外没有太大毛病

## 配置信息（这是本人配置，仅供参考）

| CPU    | Intel Core m5-6y54                       |
|:------:|:----------------------------------------:|
| 核芯显卡   | HD515                                    |
| RAM    | 8GB DDR3                                 |
| 键盘&触摸板 | Miix700 USB keyboard                     |
| 触摸屏    | ELAN222F                                 |
| 声卡     | ALC236                                   |
| 屏幕     | 三星12英寸 2160x1440                      |
| 硬盘     | 128GB SATA m.2 SSD                       |
| 网卡&蓝牙  | Intel 8260ac(实测只有173Mbps)           |

## 正常工作

1. CPU变频（其他CPU型号使用[one-key-cpufriend](https://github.com/stevezhengshiqi/one-key-cpufriend)生成对应的kext）

2. 键盘&触摸板（键盘映射按照需要手动调整，触摸板模拟鼠标工作）

3. 外放耳机正常

4. 麦克风

5. 触摸屏

6. 电量显示（显示需要维修，问题不大）

7. 盒盖关屏（休眠不太理想）

8. 亮度按键、音量按键（包括机身上的音量按键）  

9. HiDPI，使用一键[HiDPI](https://github.com/xzhih/one-key-hidpi)脚本。

10. WiFI

11. 蓝牙 


## 不工作&小毛病

1. I2C摄像头、重力感应、光线感应

2. 读卡器

3. 休眠

4. 压感笔和触摸屏冲突，在使用压感笔后导致触屏的点击动作失效

5. 手写笔的压感

6. HDMI

7. 休眠唤醒后键盘有一定几率失灵,重新插拔键盘可以解决 

8. CPU过热(可能是跟我改造散热把热量导到后盖有关系)

9. 可能还有未提到的问题... 
