<div align="center">
  <h1>:movie_camera: AR_VR :eyeglasses:</h1>
</div>

## 一、虚拟现实AR/VR开发环境的搭建
软件提取（资源由老师提供）：
- 链接：https://pan.baidu.com/s/1xZEa1obWH3NDkHRgIvAj6g 
- 提取码：flo5

<div align="center">
  <p>:heavy_exclamation_mark: 注意！软件安装路径下不能有中文！ :heavy_exclamation_mark:</p>
</div>

### 1、安装Unity3d
先后安装：
- UnitySetup64-5.6.2f1
- UnityStandardAssetsSetup-5.6.2f1（安装时关闭防火墙和Unity）
- UnitySetup-Android-Support-for-Editor-5.6.2f1.exe

安装时主要点击“下一步”即可，首次使用Unity需注册。

![UnitySetup.png](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/UnitySetup.png)

![UnityStandardAssetsSetup.png](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/UnityStandardAssetsSetup.png)

![UnitySetup-Android.png](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/UnitySetup-Android.png)

### 2、安装JAVA开发平台
安装：
- jdk-8u144-windows-i586_8.0.1440.1

安装参考[安装教程](https://www.cnblogs.com/maoning/p/10701349.html)

配置环境变量：
1. 变量名“JAVA_HOME”，变量值“E:\jdk”（jdk的安装路径）
2. 变量名“Path”，添加变量值“%JAVA_HOME%\bin”

![java_0](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/java_path_0.png)

![java_1](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/java_path_1.png)

验证java是否成功安装：
- 快捷键win+r，输入cmd
- 在cmd中分别输入：“java”、“java -version”、“javac”

安装成功会有以下输出。

![java_install_0](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/java_install_0.png)

![java_install_1](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/java_install_1.png)

### 3、安装android开发平台
安装sdk开发包:
- android-sdk_r24.4.1-windows

在sdk安装包内找到并打开：
- SDK Manager.exe

初次打开要更新一下新包：

![sdk_0](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/sdk_0.png)


### 4、配置Unity3d的Android运行环境
(1)进入Unity3d，新建项目

(2)打开 edit --> preferences --> External Tools，点击Browse，选择sdk和jdk路径文件夹

![unity_android_hj_0](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/unity_android_hj_0.png)

(3)新建场景/打开已有场景，打开 File --> Build Settings，切换至Android，点击“Switch Platform”，点击“Add Open Scenes”。

![unity_android_hj_1](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/unity_android_hj_1.png)

点击“Player Settings”，修改Company Name，“Other Settings”中，修改Identification-Package Name，例如：com.yuhui.sj

![unity_android_hj_2](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/unity_android_hj_2.png)

修改完成后，点击Build。保存打包为.apk文件。

将.apk文件安装到手机即可使用。

![unity_android_hj_3](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/unity_android_hj_3.png)

### 5、导入、导出项目

![export_package](https://github.com/uweier/AR_VR/blob/master/AR_VR_image/export_package.png)

### 项目成功安装效果

[游戏在手机上的效果录屏](https://github.com/uweier/AR_VR/blob/master/AR_VR_video/ar_vr_class_1.mp4)
