Install kinect_for_Windows_sdk using Openni and NiTE 
===========================================================

 This tutorial will  introduce how to install kinect for windows sdk(v1.8) (Openni and Nite)
 
1.	Details：
============================ 

The Kinect for Windows SDK includes the following:

•	Drivers for using Kinect for Windows sensors on a computer running Windows 7, Windows 8, Windows 8.1, and Windows Embedded Standard 7

•	Application programming interfaces (APIs) and device interfaces

•	Note: Samples, tools, and other valuable development resources are available in the [Kinect for Windows Developer Toolkit](http://go.microsoft.com/fwlink/?LinkID=323589).

•	However, if you want to know more about Kinect for Windows Sensor and SDK please click [here](http://www.microsoft.com/en-us/kinectforwindowsdev/start.aspx).

•
![alt tag](https://raw.githubusercontent.com/timlentse/-Installing--kinect-for-windows-sdk--using-Openni-and-NiTE-/master/kinect.png)

2.	Requirements
==========================

Supported OS：
Windows 7, Windows 8, Windows 8.1, Windows Embedded Standard 7

•	Hardware requirements：

•	 Kinect for Windows sensors and a PC with the following minimum capabilities：

•	32 bit (x86) or 64 bit (x64) processor

•	Dedicated USB 2.0 bus

•	2 GB RAM

•	A Microsoft Kinect for Windows sensor

•	To get your Kinect for windows sensor started you must need the following softwares:

•	[KinectSDK-v1.8-Setup.exe](http://download.microsoft.com/download/E/1/D/E1DEC243-0389-4A23-87BF-F47DE869FC1A/KinectSDK-v1.8-Setup.exe)

•	[SimpleOpenNI-1.96.zip](https://code.google.com/p/simple-openni/downloads/list)

•	[NiTE2-Windows-x64(x86)-2.21.zip](http://www.openni.org/files/nite/)

•	[OpenNI-Windows-x64(x86)-2.2.0.33.zip](http://www.openni.org/openni-sdk/)

•	[Processing-2.1.2-windows-x64(x86).zip](https://www.processing.org/download/?processing)

3.	Install SDK Instructions:
==============================

a)	Make sure the Kinect sensor is not plugged into any of the USB ports on the computer.

b)	double-click on [KinectSDK-v1.8-Setup.exe](http://download.microsoft.com/download/E/1/D/E1DEC243-0389-4A23-87BF-F47DE869FC1A/KinectSDK-v1.8-Setup.exe)，开始安装Kinect for Windows SDK
Installing Kinect for windows SDK ：

 ![alt tag](https://raw.githubusercontent.com/timlentse/-Installing--kinect-for-windows-sdk--using-Openni-and-NiTE-/master/screenshot1.png)　
 
Installation finished and close the windows！

c)	After installing KinectSDK-v1.8-Setup.exe sucessfully，ensure the Kinect sensor is plugged into an external power source and then plug the Kinect sensor into the PC's USB port. The drivers will load automatically.

 ![alt tag](https://raw.githubusercontent.com/timlentse/-Installing--kinect-for-windows-sdk--using-Openni-and-NiTE-/master/screenshot2.png)
 
The installing winzard will disappear when finished installing driver and we can check it in the device manager：

![alt tag](https://raw.githubusercontent.com/timlentse/-Installing--kinect-for-windows-sdk--using-Openni-and-NiTE-/master/screenshot3.png)
 
d)	Install OpenNI2（how to? --just click “next”button，You can also customize the installation directory）

e)	Install NITE2 。

f)	Unzip the Processing-2.1.2-Windows-x64(x86).zip and put it to wherever you want,double click processing.exe and you will enter the processing IDE。

Processing一个开源的程序语言及开发环境，提供给那些想要对影像、动画、声音进行程序编辑的工作者。如果有兴趣的话，不妨在editor里面输入ellipse(50,50,80,80);点击运行，在绘制窗口里面会出现一个椭圆，如下图： processing相关的tutorials, click [here](http://www.processing.org/tutorials/).

![alt tag](https://raw.githubusercontent.com/timlentse/-Installing--kinect-for-windows-sdk--using-Openni-and-NiTE-/master/screenshot4.png)
![alt tag](https://raw.githubusercontent.com/timlentse/-Installing--kinect-for-windows-sdk--using-Openni-and-NiTE-/master/screenshot5.png)

   
g)	最后一步解压SimpleOpenNI-1.96.zip(对于windows用户来说解压目录一定要是C:\Users\Administrator\Documents\Processing\libraries，否则运行案例程序会报错no librares found)，SimpleOpenNI为一些在processing里面编写的OpenNI的例程，我们可以SimpleOpenNI\examples\OpenNI里面找到相关的程序。

4.	Test：
================

安装好以上的软件后，我们到了测试阶段，以检测我们的kinect是否可以正常使用了，不妨使用OpenNI自带的程序来作为测试工具。

1.先把kinect传感器电源线插上，usb线接在电脑usb端口上，我们会发现kinect传感器的指示灯为绿色，kinect传感器正常工作，

2.打开OpenNI2\Samples\Bin，双击其中一个.exe文件（如ClosestPointViewer.exe）会出现扫描窗口：
![alt tag](https://raw.githubusercontent.com/timlentse/-Installing--kinect-for-windows-sdk--using-Openni-and-NiTE-/master/screenshot6.png)
 
Done！

