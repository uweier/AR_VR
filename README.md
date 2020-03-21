# AR_VR

## 一、虚拟现实AR/VR开发环境的搭建
软件提取：
- 链接：https://pan.baidu.com/s/1xZEa1obWH3NDkHRgIvAj6g 
- 提取码：flo5

:exclamation:注意！软件安装路径下不能有中文！

### 1、安装Unity3d
先后安装：
- UnitySetup64-5.6.2f1
- UnityStandardAssetsSetup-5.6.2f1（关闭防火干墙和其他所有窗口）
- UnitySetup-Android-Support-for-Editor-5.6.2f1.exe

安装时主要点击“下一步”即可，首次使用Unity要注册。

### 2、安装JAVA开发平台
安装：
- jdk-8u144-windows-i586_8.0.1440.1

安装参考[安装教程](https://www.cnblogs.com/maoning/p/10701349.html)

配置环境变量：
1. 变量名“JAVA_HOME”，变量值“E:\jdk”（jdk的安装路径）
2. 变量名“Path”，添加变量值“%JAVA_HOME%\bin”

（图）

验证java是否成功安装：
- 快捷键win+r，输入cmd
- 在cmd中分别输入：“java”、“java -version”、“javac”

安装成功会有以下输出：
（图）

### 3、安装android开发平台
安装sdk开发包:
- android-sdk_r24.4.1-windows

在sdk安装包内找到并安装：
- SDK Manager.exe

初次更新一下新包：
（图）


### 4、配置Unity3d的Android运行环境
