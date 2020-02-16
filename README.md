# Energy-Sensor-for-STM32F4
![主控和显示](http://photogz.photo.store.qq.com/psc?/V10NjlLt3vJzWw/jATfUCBWQtBBaj8LJRaWBVAbTLqwEL.RaWOMCLxHG3YN6wecZpiHnGg.VsVf4x4OFZF8L.M*v3lbKrabitCLoA!!/b&ek=1&kp=1&pt=0&bo=fAWwA3wFsAMRADc!&tl=1&tm=1581822000&sce=0-12-12&rf=viewer_311)
![供电模块](http://a1.qpic.cn/psc?/V10NjlLt3vJzWw/jATfUCBWQtBBaj8LJRaWBT9UEnfJce6qsocDQIMfdJ5ns0bs6btO20Wa1X52lAQbxph1WsJ76lnLKqhN9PVvcg!!/b&ek=1&kp=1&pt=0&bo=oAU4BKAFOAQRADc!&tl=1&vuin=2142004747&tm=1581822000&sce=50-1-1&rf=viewer_311)

针对2018年全国大学生电子设计竞赛设计的交流电探测以及负载分析程序，适用于STM32F407

1. 通过交流互感器采集交流电网电流电压信息并做FFT分析，其中解决了频谱泄露的问题。
2. 通过频谱的指纹效应判断接入负载的数量和性质。
3. 计算市电信号的属性如失真度等信息。
4. 需要搭配硬件使用，PCB工程和COM文件一并上传

## 说明

- 需要搭配硬件使用，代码只提供参考，主要针对频谱泄露问题的解决和上位机协同学习过程。
- 指纹效应的模糊匹配过程可以简单的实现。
- 如对软件使用存在疑问，或发现软件存在问题（程序问题或计算问题）请联系作者：[xinchuandu97@gmail.com](mailto:xinchuandu97@gmail.com)

## 协作开发

本工程通过C在KEIL环境下开发，采用ST-LINK烧录测试，源文件已压缩，目前作者以停止维护，如对该工程感兴趣可以右键联系作者。
