## 嵌入式题目

### 超声波测距仪

基于STM32设计一台能够实时监测距离并具有报警功能的仪器。

### 基础要求：

1、上电后OLED显示欢迎界面，通过按动按键使设备进入工作状态；（25分）

2、利用超声波模块实现测距功能，并将实时距离与设定阈值（默认初始阈值为15cm）显示在OLED上；（25分）

3、当实时距离小于设定阈值时，蜂鸣器发出警报，通过按键操作可以关闭警报。（20分）

### 进阶要求：

1、报警阈值可在10cm，15cm，20cm，30cm之间切换；（15分）

2、新设置的阈值在断电后仍能被保留。（15分）


### 【参考资料】  
  
#### 1、 《STM32库开发实战指南》：  
<p align="center">
  <img src="https://github.com/CXCYGZF-UESTC/SME_2018/raw/master/%E5%B5%8C%E5%85%A5%E5%BC%8F%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E5%9B%BE%E4%B8%80.jpg">  
</p>
  
  
#### 2、 《电子设计从零开始》：  
<p align="center">
  <img src="https://github.com/CXCYGZF-UESTC/SME_2018/raw/master/%E5%B5%8C%E5%85%A5%E5%BC%8F%20%C2%B7%20%E5%9F%BA%E7%A1%80%E9%A2%98/picture/%E5%9B%BE%E4%BA%8C.jpg">  
</p>  
  
  
#### 3、 涉及模块：数码管，按键，EEPROM  
#### 4、 STM32开发板（学习用的板子上面很多模块都有）    
https://item.taobao.com/item.htm?id=20428448343
#### 5、 视频教程  
- 腾讯课堂下载链接：https://ke.qq.com/course/279762?tuin=1730a331  
- 腾讯课堂在线观看链接：https://ke.qq.com/course/278479  
- 百度网盘下载链接：  
  - A盘独立压缩包: http://pan.baidu.com/s/1c2zdIJQ 程序源码，手册，软件等除视频外的所有其他资料  
  - B盘独立压缩包: http://pan.baidu.com/s/1i5GwEqT 视频盘,《手把手教你学STM32-M3》视频  
  - C盘独立压缩包：http://pan.baidu.com/s/1miPJYeW 视频盘,《手把手教你学STM32-M3》视频  
  - D盘独立压缩包：http://pan.baidu.com/s/1i4UZ4Lf 视频盘,《手把手教你学STM32-M3》视频  

