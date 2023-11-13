# 串口调试助手
------------------
## 介绍
**一款使用 C# 及 WPF 框架编写的串口助手软件。该串口助手界面优雅、简洁，易于使用。软件实现了基本的串口通讯需要的功能，开发者可以基于此添加自定义的功能。此外，可以基于此开发出一些简单的串口控制类软件，进而与你的单片机或 Arduino 互动。**

## 项目主页
* [基于WPF开放源码的串口调试助手(https://github.com/ChrisLeeGit/SerialAssistant)](https://github.com/ChrisLeeGit/SerialAssistant)
 

## 基本功能
* 串口数据接收，可以采用多种模式显示接收到的数据：字符，十六进制等；
* 串口数据发送，可以手动/间隔自动发送；
* 保存串口接收到显示区的数据；
* 保存/加载软件配置；
* 独创的**简洁视图模式**， 便于用户专注于数据的接收和发送。


## 运行测试
### 启动初始化截图
![启动初始化截图](https://raw.githubusercontent.com/ChrisLeeGit/SerialAssistant/master/DebugPics/1.PNG)

### 打开端口并接收数据
![打开端口并接收数据](https://raw.githubusercontent.com/ChrisLeeGit/SerialAssistant/master/DebugPics/2.PNG)

### 可自由隐藏的设置面板
![可自由隐藏的设置面板1](https://raw.githubusercontent.com/ChrisLeeGit/SerialAssistant/master/DebugPics/3.PNG)
![可自由隐藏的设置面板2](https://raw.githubusercontent.com/ChrisLeeGit/SerialAssistant/master/DebugPics/4.PNG)

### 简洁无干扰的视图
![简洁无干扰的视图](https://raw.githubusercontent.com/ChrisLeeGit/SerialAssistant/master/DebugPics/5.PNG)

## 使用到的开源库
* 本软件使用的一个开源的 [Json.Net](http://www.newtonsoft.com/json) 库，可以非常方便地使用它用 Json 格式存储配置信息或者加载 Json 格式的配置文件。

## 开发
1. 请下载项目源码，并使用 Visual Studio 2013 及以上版本打开；
2. 代码中有详细注释，可以根据需要扩展功能。

## 反馈
- 如果有 Bug 或者希望增加新的功能，可在 [issues](https://github.com/ChrisLeeGit/serial-assistant/issues) 中提出；
- 如果你添加了新的有意义的功能，也欢迎向我提交 PR，多谢。

## 更新日志
更新日志请参见 [CHANGE_LOG.md](./CHANGE_LOG.md)。

## 相关开源项目
暑假同时完成了一个基于 Arduino 的太阳能自动供水系统。当然，这个系统并没有实际使用上，但是设计的功能基本都实现了。这个项目属于比较综合的了。使用了串口通信的方式与PC端的控制软件进行通信。该PC串口控制软件可以给单片机发送自定义的控制指令，并被执行。所以，便涉及到通信用的自定义的协议设计，Arduino 指令解析系统的设计和实现。如果感兴趣的话，也同样可以关注，共同学习进步！！谢谢！以下是项目托管地址：

1. Github地址：[基于 Arduino 的太阳能自动供水系统实现](https://github.com/ChrisLeeGit/water-supply-system)。

## 许可协议
采用 [MIT](./LICENSE.md) 协议进行许可。Please feel free~ :)


