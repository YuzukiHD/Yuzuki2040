# Yuzuki2040
A dev board based on RaspberryPi RP2040 MCU
## 基于树莓派RP2040 MCU设计的开发板。

RP2040是树莓派基金会的一款基于Arm Cortex-M0+ 设计的MCU。

![RP2040-1-800x559.jpg](//image.lceda.cn/pullimage/s1Rj4InVgqJDEsvgTq7Isydo1CpuYM1Q7wG668Wf.jpeg)

* 双核 Arm Cortex-M0+ @ 133MHz
* 264KB 片内RAM，内部6个独立的RAM块， 在总线中心进行交换，可以让内核和DMA并行运行而无冲突
* 通过专用的QSPI总线可以支持最高16MB的片外Flash存储器
* DMA控制器
* 2 × UARTs, 2 × SPI控制器, 和2 × I2C控制器
* 16 × PWM通道
* 1 × USB 1.1控制器和PHY，支持Host和Device
* 8 × 树莓派可编程I/O状态机
* USB存储启动模式并支持UF2, 可以通过拖拽进行编程
* 芯片售价1美元~~~~

![RP2040内部图](//image.lceda.cn/pullimage/n42uW7miEMWgMLQqMTpqCo9BH7uv7T59UN1TrIlG.png)

### 更新日志

* 1.4 - 验证成功
    * 修复Type C接口CC错误
    * 增加GPIO引出
    * 删除孤岛
    * 优化布线结构
* 1.3 - 验证成功
    * 增加RESET按钮
* 1.2 - 验证成功
    * 增加CH340N作为板载UART转换芯片，方便MicroPython等开发
    * 增加电源保护反接保护
    * 增加Micro USB接口作为串口输出
* 1.1 - 验证成功
    * 修复3V3与1V1电路绘制错误导致芯片烧毁问题
    * 增加测试脚位
* 1.0 - 验证失败
    * 增加Arduino风格板型
    * 完成电路图绘制
    * 完成PCB绘制

### 成品图片

#### V1.3 Sakura

![IMG_1222.JPG](//image.lceda.cn/pullimage/uQ6uSdaTAuntJBxch3L7fOp56V9hhGKobj7esiuj.jpeg)
![IMG_1223\(20210904-161226\).JPG](//image.lceda.cn/pullimage/Xv0WoCqKAe7bCLldG9F6DoCBA7yLsMkrMwaV42Pg.jpeg)

#### V1.2

![2 \(2\).jpg](//image.lceda.cn/pullimage/QGfd70gA2T1vHH69MOTCtHOMqQLqYNY97axnhEVJ.jpeg)
![2 \(1\).jpg](//image.lceda.cn/pullimage/WDrEiRsDmOHassNaLoboFDd0oVrxsVx4YBk0L13o.jpeg)

#### V1.1

![IMG_0549.JPG](//image.lceda.cn/pullimage/5ni7cypuAHDDlbFX8355LGAqzVVri0VC8eY9JL0y.jpeg)
![IMG_0551.JPG](//image.lceda.cn/pullimage/3r3pMisPCVPenIQldu9sgFaxiEpcQRwVq15fnarp.jpeg)
![IMG_0550.JPG](//image.lceda.cn/pullimage/yZFJicej25AuHusfS2gtfh2XtHLDMN4plmb4S4ko.jpeg)

### 官方资料与文档

* [https://www.raspberrypi.org/products/raspberry-pi-pico/](https://www.raspberrypi.org/products/raspberry-pi-pico/)
* [https://www.raspberrypi.org/documentation/rp2040/getting-started/](https://www.raspberrypi.org/documentation/rp2040/getting-started/)

##### USB已验证

![读取资料](//image.lceda.cn/pullimage/m5HSzUajAkfYlbJHsxoKQJqKZ4jwWUXh6cOULlqZ.png)
