# Remote_BMS
# 前言
  本软件包含安卓端、苹果端、PC端、iPAD端。移动端采用BS架构，使用web网页的方式进行呈现，因此需要使用浏览器进行系统访问。PC端、iPAD端为应用程序。
  系统：安卓、IOS、windows7+

  浏览器：Google Chrome或者 Edge 等现代浏览器
 # 启动软件
 ## 移动端
 打开Google chrome 浏览器或者微软Edge浏览器后，输入系统网址，例如演示用的地址为：http://39.98.134.152:81/start/index.html#/user/login ，输入系统地址后，会自动跳转到登录界面，如下图2.1_1 所示。在登录界面输入用户名和密码，然后点击【登录】按钮即可。
 
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture1.png)
## PC端、iPAD端
点击RMBMS.exe(IPAD端点击RMBMS)启动远程管理系统
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture2.png)
# 功能模块
## 设备连接
点击连接设备在下拉框中选择需要连接的设备。如图3.1-1所示，在下拉列表中会同步显示设备的上线时间。
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture3.png)
## 参数查看
选择完设备后点击参数查看便可进入设备的参数查看界面。如图所示。用户可点击左侧的选项卡进入对于的界面
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture4.png)
### BMS主机
该模块会实时显示BMS主机的相关参数，包括预计电量、功率、电量、总电压、最高电芯电压、最低电芯电压、最高电芯温度、最低电芯温度、充电控制、放点控制、最高BIC温度、BMC温度和BIC采用总线通信质量。通信周期为1S。
### BMS从机
该模块可查看BMS从机（BIC）的实时数据，用户通过下拉选择BIC编号来查看实时数据。实时数据包括BIC模块温度、电芯序号、电芯电压、电芯均衡、温度传感器编号、电芯温度。如图3.2.2-1所示。通信周期为1S。
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture5.png)
### 运行参数
该模块可查看设备的运行参数，包括充电限制电压、均衡开启电压、启动充电电压、启动放电电压、放电限制电压、电芯高温保护、电芯低温保护、是否监测总电压总电流、BIC数量、BIC采样检测周期、标定电池容量、总电压检测量程、电流检测量程、单体过量保护电压、均衡压差、是否自动开启放电。
### 容量测试
该模块可设定初始值和读取容量测试信息。如图所示。
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture6.png)
### 系统报警
该模块可对设备出现故障时进行报警。报警信息包括：单体电压、单体温度、通信质量。
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture7.png)
## 参数设定
选择完设备后点击参数设定便可进入设备的参数设定界面。如图3.3-1所示。用户可点击左侧的选项卡进入对于的界面
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture8.png)
### BMS主机
该模块用户可通过点击读取参数查看BMS主机的相关参数，包括：充电限制电压、均衡开启电压、启动充电电压、启动放点电压、放电限制电压。用户重新设置设定值后点击设定参数便可完成参数的设定工作。
### BMS从机
该模块用户可通过点击读取参数查看BMS从机的相关参数，包括：从机地址、单体电芯数量、温度传感器数量。用户重新设置设定值后点击设定参数便可完成参数的设定工作。如图3.3.2-1所示。
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture9.png)
### 总电压总电量设定
该模块用户可设定电池组容量、匹配电流、匹配电压。用户可点击查询按钮获取电池组容量信息，用户设定是否检测总电压，用户可点击读取量程来获取当前设备的电压量程和电流量程。如图
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture10.png)
### 网络参数
该模块可设定网络参数，用户点击网络参数选项卡后会弹出提示框，提示框内容为设定网络参数的注意事项。如图3.3.4-1，用户可指定wifi 的名称和密码。设置界面如图3.3.4-2。
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture11.png)
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture12.png)
## 调试模式
该模块可对设备进行指令调试，方便后期开发新的功能。界面如图3.4-1所示。用户首先选择需要调试的设备编号，在CMD中输入发送给设备的指令、设备返回的信息会返回到RES中。用户可点击情况接收区来情况接收区的信息。
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture13.png)
## 多语言切换
用户可点击右上角的语言切换按钮随时切换系统语言，目前该系统支持中文、英文。英文界面如图
![image](https://github.com/liangzhikai2013/Remote_BMS/blob/main/img/Picture14.png)
## 消息中心
消息中心可显示软件升级、软件使用手册、产品推广、广告等信息。

# 商业合作
欢迎各大BMS厂商洽谈合作
lianzhikai@126.com





