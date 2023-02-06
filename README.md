# [CW32W031](https://doc.soc.xin/CW32W031)

* [whxy](https://www.whxy.com/): [Cortex-M0](https://github.com/SoCXin/Cortex)
* [L1R2](https://github.com/SoCXin/Level): 48 MHz

## [简介](https://github.com/SoCXin/CW32W031/wiki)

[CW32W031](https://www.whxy.com/product/detail/81)基于CW32L031与PAN3028的SIP芯片，采用7.5mm×7.5mm×0.75mm超小尺寸QFN64封装，集成无线收发器。高集成度的设计大大减少了其他外部元器件，从而降低了整体BOM成本。

采用ChirpIoTTM调制解调技术，支持半双工无线通信，工作频段为370~590 MHz和740~1180MHz，具有高抗干扰性、高灵敏度、低功耗和超远距离通信等特性。最高具有-140dBm的灵敏度，22dBm的输出功率，使其成为远距离传输和对可靠性要求极高应用的最佳选择。

### 关键参数

* 48 MHz Cortex-M0
* 8KB SRAM + 64KB Flash + 128B OTP存储器
* Sub-1G 射频，支持ChirpIoT调制方式
    * 通信频段：370MHz ~ 590MHz，740MHz ~ 1180MHz
    * 发射输出功率：-7dBm ~ 22dBm
    * 最大链路预算可达：162dB
    * 接收灵敏度：-140dBm@62.5kHz
    * 深度休眠电流：400nA
    * 接收电流：12.5mA@DCDC 模式
    * 发射电流：135mA@22dBm，83mA@18dBm，25mA@0dBm
    * 支持带宽：62.5kHz、125kHz、250kHz、500kHz
    * 支持 SF 因子：7 ~ 12，支持扩频因子自动识别
    * 支持码率：4/5，4/6，4/7，4/8
    * 支持 CAD 功能
    * 支持低速率模式：0.08kbps ~ 20.4kbps
* QFN64，LDO 模式支持 1.8V - 3.6V

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/CW32W031)


## [www.SoC.xin](http://www.SoC.Xin)
