# DIYkeyboard

## 产品定位

cpu选型:

满血版:
全功能
* AT32F435(QSPI flash) + esp32-c3

残血版:
砍去 蓝牙 和 智慧旋钮底座
* AT32F435

# MCU

## esp32			

* 集成蓝牙

  

* 性能溢出

* 贵

* 功耗高

* 没有USB

* 有没用的功能 

* GPIO少
## atmega32u4
* 生态完善

* 有USB

  

* 性能太低

* 贵

* GPIO少
## STM32L433
* 低功耗

* 有USB

* 性能优

  

* 贵

* GPIO少


## CH583 risc-v  
* 低功耗

* 集成蓝牙

* 可编程

* 有USB

* 性能优

  

* 新芯片，生态差

* QFN封装 焊接困难

* 40 GPIO

## CH32V208WBU6 ON
* QFN68封装
* 53 GPIO



* 功能过于强大
* 没有低功耗

## STM32F407ZGxx

* LQFP 144
* 资料全
* 生态好
* 适配microPython
* 方便开发
* 功能强大



* 功耗30~40mA
* 贵
* 可能GPIO过多
* 不集成蓝牙

**注意功耗计算**

带蓝牙的单片机引脚都少

# 外观
透明亚克力板铜螺柱支撑
四层：
  亚克力上板
  亚克力保护板
  PCB
  亚克力底板
  

# 硬件
* AT32F435 288Mhz DSP FPU
* ~[smartknob](https://github.com/scottbez1/smartknob)旋钮~
* tft-lcd屏 *1
* 编码器 *6
* 拨码器 *2
* 0.45oled 键帽
* 蓝牙模块 esp系列
* 手势触摸条？

# 软件
* RT-Thread
* ~openHarmony 有js可编程框架~
* ~lua~
* microPython RTT内有移植
* ~[pikascript](https://github.com/pikastech/pikascript/)~
* ~集成鼠标控制~
* ~光标控制~
* 自定义组合键
* 键位录制
* 对应软件功能切换
* 快速切换蓝牙连接设备
* ~参考使用稚晖的固件~

# 问题
* ~钱~
* ~先开发smartknob项目~
* ~3D打印机~
