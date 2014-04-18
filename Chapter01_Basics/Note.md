
#1.2 基于Android SDK 的IDE开发环境

需要以下内容：

1. JDK环境
2. Eclipse继承开发环境
3. ADT插件
4. Android SDk

目前Google 在android.com提供了打包好的开发工具。

###1.2.2Windows上的开发环境安装。
1. 下载安装jdk
2. 下载安装Eclipse
3. 安装Android sdk 
4. 安装ADT Android Development Tools

###1.2.3 Linux 上的开发环境安装
* 安装jdk Ubuntu环境 

```
sudo apt-get install sun-java6-sdk
```
其他雷同windows

###1.2.4 Android中运行仿真器环境
1. 建立虚拟设备
通过Eclipse的Android AVD manger可以创建
2. 运行虚拟设备

###1.2.5
1、建立工程
2、各个文件 AndroidManifest.xml中的Instrumentation标签用来测试。
3、运行工程  可以Run as 或则 Debug As 在Run As的时候可以通过Run Configurations进行更多配置比如，配置启动活动，配置启动设备等等。 

###1.2.6 在Ide中使用各种Android工具

1. Device工具
2. Heap工具，导出hprof文件 可以借助MAT Memory Analyzer Tool 内存分析工具  分析当前京城内存泄露情况 
3. Logcat
4. 仿真器控制工具 Emulator Control工具
5. 文件浏览器工具
6. Windows给你工具 查看当前系统窗口情况。 
7. 属性查看工具  View properties工具
8. Pixel Perfect工具
9. Tree Overview 和 Tree View工具
10. Layout View工具

###1.2.7 其他android工具
* adb 工具
* ddms工具
* hierarchyviewer工具
* mksdcard工具


##1.3 Android应用程序的结构
###1.3.1  Android应用程序的代码组成

四大组件 Component

* Activity
* Service
* BroadcastReceiver
* ContentProvider

res  src   asset  


###1.3.2 android应用示例

1. 源代码工程结构
2. Sdk环境中的编译结构
3. Apk包的结构


###1.3.3 

