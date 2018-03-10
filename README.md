# 神奇海螺

***

## 简介

是时候该结束开发板裸奔的时代了。采用堆叠设计，拥有漂亮外观及超强扩展性。一款完全开源的结构及通用硬件扩展平台，旨在大家能更欢乐的DIY。

![xconch-introduced ](https://github.com/xboot/xconch/raw/master/documents/images/xconch-introduced.png)

## 名称的由来

神奇海螺，源自网友`word天`lymz@foxmail.com(QQ928882442)的网名，只因在激烈的项目取名讨论中，一张惊天图片，高逼格的意境，贴合式奶骑，迅速定论，结束了还在`一个完全开源的，未知项目名称的，有着炫酷外观及超强堆叠扩展性的装逼DIY套件`简介中的混沌态。

![magical-conch](https://github.com/xboot/xconch/raw/master/documents/images/magical-conch.png)

在这里同样感谢如下网友参与头脑风暴，积极献计献策。排名不分先后，如有遗漏还请海涵：

| 网名         | QQ         |
| ---------- | ---------- |
| 非飞         | 6278495    |
| 挖坑侠晕哥      | 516333132  |
| 迪卡魏曼依奇君    | 932668000  |
| Val劲       | 2452013147 |
| Bumbee     | 1059270763 |
| 忽忽         | 12931577   |
| Dictionary | 179670618  |
| 怪盗Kid      | 783837037  |
| 暗╰☆╮夜      | 2819617028 |
| 已完成。 成。 成。 | 2495841298 |
| flame      | 470230832  |
| Robe       | 82796620   |
| 橘子         | 2535418266 |
| 肠子         | 553010120  |
| 〃阿慕慕ぐ      | 819876772  |
| 郑          | 158754845  |
| Mpax       | 530465617  |
| K.o.s      | 13712417   |
| ——         | 673576000  |
| Jarvis     | 390246362  |
| Fourier    | 157871537  |
| 和自己赛跑™®    | 254762059  |
| 冰水寒        | 76884682   |
| 我在做梦       | 345340585  |
| 宁以远        | 800636     |
| 火龙果Geek    | 1136632326 |

## 神奇海螺LOGO（临时放个，需要更换）

![logo](https://github.com/xboot/xconch/raw/master/documents/images/logo.png)

## 项目意义及最终目标

神奇海螺项目旨在解决现在市面上无数大大小小的开发板不仅互不兼容，而且绝大部分都还没有外壳，这对于DIY来说，实在不太友好。辛辛苦苦开发了某款功能，却只见到眼前如蜘蛛网般的各种导线，实在没了心情，你说你开发的这个功能有多先进，有多强大，在面对眼前如此景象时，我想您也少了份底气，神奇海螺要做的，就是让您能自豪的说，我开发的这个功能随时可以以产品级的形态来演示。

神奇海螺最终目标不是做各种开发板或开发平台，而是定义一套完整的标准技术规范，包括各种机械结构及电气信号。当然在神奇海螺项目中也会实现一些有典型意义的开发平台，旨在提供标准参考实现。同时，这也是一个持续性的过程，尽可能丰富基于神奇海螺标准的各种开发平台及扩展模块。

## 神奇海螺授权模式

神奇海螺采用免授权模式，官方不保留任何权利，任何组织及个人可无偿使用神奇海螺的各种成果，包括各种商业用途。神奇海螺LOGO，外观，技术规范，具体平台实现，官方都不保留任何权利，想用就用，想拿就拿，想卖就卖，如果硬是要给这种授权模式定义一个概念的话，那就叫做`真空授权`吧。

## 如何加入组织及贡献自己的一份力量

神奇海螺整个项目寄存在`github`网站，任何想加入的组织及个人可直接`fork`项目，然后`pull request`即可。欢迎各种组织及个人踊跃贡献，官方会维护一份贡献名单，任何做出贡献的组织及个人不论贡献大小，统统记录在案，并在项目显目位置展示。

## 神奇海螺项目贡献名单，定期更新

| 网名         | QQ         |
| ---------- | ---------- |
| XBOOT         | 8192542    |

## 结构总体设计

结构设计采用上下堆叠方式，层间既可通过磁吸连接，也可通过长螺杆，贯穿所有模块来永久固定。结构上主要有两种形态，一种是主控盒，带有各种非标准扩展接口的，包括`显示屏`，`触摸屏`，`USB OTG`，`HDMI`，`按键`等等，另一种是扩展盒，采用板对板连接器，层高`8mm`，实现无限堆叠。

### 主控盒设计

TBD

### 扩展盒设计

![xconch-extended-box-large-pcb](https://github.com/xboot/xconch/raw/master/documents/images/xconch-extended-box-large-pcb.png)

 ![xconch-extended-box-mini-pcb](https://github.com/xboot/xconch/raw/master/documents/images/xconch-extended-box-mini-pcb.png)

扩展盒边框`2mm`厚度，倒圆角，内有4颗`3mmx8mm`磁铁固定位，磁铁安装方向为正面北极，背面南极，底部堆叠接口开窗，面壳无盖，PCB板直接裸露。内部四周有6颗PCB板定位孔，依PCB板型可使用4颗或6颗自攻螺丝来固定，固定螺丝为`304十字圆头带垫自攻螺丝PWA1.7X5X4.5`。

- 3x8mm强磁：

![magnet-3x8](https://github.com/xboot/xconch/raw/master/documents/images/magnet-3x8.png)

- 304十字圆头带垫自攻螺丝PWA1.7X5X4.5

![PWA-1_7X5X4_5](https://github.com/xboot/xconch/raw/master/documents/images/PWA-1_7X5X4_5.png)

## 硬件总体设计

### 主控盒设计

任何一个具体的硬件平台，一定包含主控盒及通用扩展盒或专用扩展盒。任何一种堆叠方式中仅能有一个主控盒，并置于堆叠的最上方，通用扩展盒或专用扩展盒可以无限向下堆叠。主控盒上默认集成了各种非标准扩展功能，包括`显示屏`，`触摸屏`，`USB OTG`，`DEBUG UART`，`HDMI`，`按键`，`音频`等等，主控盒默认集成哪些功能，依据具体芯片的资源特点进行设计，尽可能提供出主控盒结构所扩展的各种功能接口，如果不存在某些功能，则需要将相对应的功能接口作留空处理。

### 扩展盒设计

扩展盒分通用扩展盒及专用扩展盒，通用扩展盒要求强制兼容，保证通用性。专用扩展盒依赖具体的主控盒，不保证兼容性。扩展盒板厚1.6mm，4个螺丝孔位或者6个螺丝孔位固定，正面限高1.8mm，背面限高2.6mm，器件尽可能放在背面，正面通过各种丝印尽可能清晰准确的描述该扩展盒，尽可能在不查阅文档时，了解该扩展盒的使用方法。

扩展盒有两种PCB板型，一种迷你板型，还有一种完整板型，两者在结构上时完全兼容的。因为整个堆叠扩展盒尺寸相对较大，而很多扩展功能相对单一，功能简单，所占PCB面积较小，为了有效降低成本，可用迷你板型来设计，迷你板型采用4颗螺丝固定，完整板型采用6颗螺丝固定，两种固定方式，都能有效保护堆叠扩展口。

- 扩展盒迷你板型尺寸如下:

![Mini-PCB-DXF](https://github.com/xboot/xconch/raw/master/documents/images/Mini-PCB-DXF.png)

- 扩展盒完整板型尺寸如下：

![Large-PCB-DXF](https://github.com/xboot/xconch/raw/master/documents/images/Large-PCB-DXF.png)

## 板对板连接器

板对板连接器，采用1.27间距，双排80PIN贴片排针及排母，正面采用排针，背面为排母，详细规格如下：

![PinHeader_2x40_P127mm_Vertical_SMD](https://github.com/xboot/xconch/raw/master/documents/images/PinHeader_2x40_P127mm_Vertical_SMD.png)

![PinSocket_2x40_P127mm_Vertical_SMD](https://github.com/xboot/xconch/raw/master/documents/images/PinSocket_2x40_P127mm_Vertical_SMD.png)

### 堆叠扩展口描述

堆叠扩展口采用板对板连接器，正面为排针，背面为排母，需布局在PCB的堆叠扩展位，以实现上下无限堆叠扩展。80PIN管脚，分为两个区域，一个50PIN的强制兼容区，另一个30PIN的非兼容扩展区，这样的设计既保证了堆叠的兼容性，又增强了扩展的灵活性。这也就意味着，如果需要设计一款通用扩展盒，就必须通过50PIN强制兼容区来扩展，反过来说，只要能称之为通用扩展盒的就一定是任何平台兼容的，如果一个CPU有很多特别的功能管脚需要引出，而这些信号并不在50PIN通用扩展区，这就必须通过30PIN扩展区来扩展了，扩展区不要求兼容，依据主控CPU自身的资源特点自行设计，当然基于30PIN扩展区扩展出来就是专用扩展盒了，专用扩展盒只能用于特定平台，不具有任何兼容性。通用扩展盒只能使用50PIN强制兼容区，另30PIN非兼容扩展区管脚必须需做悬空处理，专用扩展盒可以使用所有的80PIN扩展管脚。

### 强制兼容区50PIN信号定义

| 管脚 | 名字     | 管脚 | 名字      |
| ---- | -------- | ---- | --------- |
| 1    | BAT+     | 2    | BAT-      |
| 3    | VCC_5V   | 4    | VCC_5V    |
| 5    | VCC_3V3  | 6    | VCC_3V3   |
| 7    | VCC_1V8  | 8    | VCC_1V8   |
| 9    | GND      | 10   | GND       |
| 11   | UART_TX  | 12   | UART_RX   |
| 13   | I2C_SDA  | 14   | I2C_SCL   |
| 15   | SPI_MOSI | 16   | SPI_CLK   |
| 17   | SPI_MISO | 18   | SPI_CS    |
| 19   | USB_D+   | 20   | USB_D-    |
| 21   | CAN_H    | 22   | CAN_L     |
| 23   | SDIO_D0  | 24   | SDIO_D1   |
| 25   | SDIO_D2  | 26   | SDIO_D3   |
| 27   | SDIO_CMD | 28   | SDIO_CLK  |
| 29   | I2S_DI   | 30   | I2S_LRCLK |
| 31   | I2S_DO   | 32   | I2S_CLK   |
| 33   | PWM0     | 34   | PWM1      |
| 35   | ADC0     | 36   | ADC1      |
| 37   | DAC0     | 38   | DAC1      |
| 39   | GPIO0    | 40   | GPIO1     |
| 41   | GPIO2    | 42   | GPIO3     |
| 43   | GPIO4    | 44   | GPIO5     |
| 45   | GPIO6    | 46   | GPIO7     |
| 47   | GPIO8    | 48   | GPIO9     |
| 49   | GND      | 50   | GND       |

### 非兼容扩展区30PIN信号定义
| 管脚 | 名字 | 管脚 | 名字 |
| ---- | ---- | ---- | ---- |
| 51   | N/A  | 52   | N/A  |
| 53   | N/A  | 54   | N/A  |
| 55   | N/A  | 56   | N/A  |
| 57   | N/A  | 58   | N/A  |
| 59   | N/A  | 60   | N/A  |
| 61   | N/A  | 52   | N/A  |
| 63   | N/A  | 54   | N/A  |
| 65   | N/A  | 56   | N/A  |
| 67   | N/A  | 58   | N/A  |
| 69   | N/A  | 60   | N/A  |
| 71   | N/A  | 62   | N/A  |
| 73   | N/A  | 64   | N/A  |
| 75   | N/A  | 66   | N/A  |
| 77   | N/A  | 68   | N/A  |
| 79   | N/A  | 80   | N/A  |

## 结构详细设计

设计文件共享地址：

- 通用扩展盒：http://a360.co/2HdUN1z

STL格式输出文件，放置在`shell/stl`目录下：

- 通用扩展盒：https://github.com/xboot/xconch/blob/master/shell/stl/xconch-extended-box.stl


## 硬件详细设计

## 神奇海螺相关链接
- 项目首页：https://github.com/xboot/xconch

## 讨论组，大佬聚集，请踊跃加入
神奇海螺QQ群：[658250248](https://jq.qq.com/?_wv=1027&k=5BOkXYO) (2000人)
