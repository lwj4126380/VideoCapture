# VideoCapture
Windows Video Audio Capture, Save BMP file

by QQ:39539883   2016-12-04

VideoCapture 是使用 DirectShow 开发的 windows视频、音频捕获demo。
重点是视频捕获截图功能。

build目录提供了vs2005 vs2008 vs2010 vs2012 vs2013 vs2015 的项目文件

提供了 ISampleGrabberCB接口，ISampleGrabber接口的定义头文件 qedit.h。

在win10下，win32/x64的各个版本测试通过，截图文件保存在%temp%\CaptureBmp\目录下面。

因为DirectShow需要对应的sdk，所以vs2010(含以下)需要正确安装sdk。我使用的vs2005的sdk。
vs2015是不需要单独安装sdk的。直接可以编译调试。

