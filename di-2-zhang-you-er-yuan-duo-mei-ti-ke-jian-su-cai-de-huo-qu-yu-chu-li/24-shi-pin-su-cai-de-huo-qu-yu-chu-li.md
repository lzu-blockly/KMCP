#2.4 视频素材的获取与处理

##2.4.1视频素材简介

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;视频素材也称影像素材，它是指在多媒体课件中所播放的一种既有活动画面又有声音的文件，一般来说，视频画面的质量要比动画要差一些。因此他不可能完全取代动画素材。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;视频素材的常用文件类型包括以下几种：

###1.AVI视频文件

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AVI(Audio Video Interleaved)是Windows使用的标准视频文件，它将视频和音频信号交错在一起储存，兼容性好，条用方便，图像质量好，缺点是文件体积过于庞大。AVI视频文件的扩展名为AVI。

###2.MPG视频文件

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MPG(Motion Picture Experts Group)文件家族中包括了MPEG-1，MPEG-2，和MPEG-4在内的多种视频格式，通过MPEG方法进行压缩，具有极佳的视听效果。就像条内容的视频数据来说，MPG文件比AVI文件文件规模要小得多。

###3.MOV格式

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MOV格式有较高的压缩比和较完美的视频清晰度，主要用来作为视频流媒体的存储格式。

###4.RMVB格式

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RMVB(RealMedia Variable Bitrate) 是可变的采样压缩方式，在保证静止画面质量的前提下，大幅度提高运动图像的画面质量。

## 2.4.2视频信息的采集与编辑

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;多媒体计算机的视频采集\(捕捉\)系统由计算机、视频采集卡，以及外部视频设备如录像机、摄像机等组成，如图2-4-1所示。视频采集卡的作用是将录像带、光盘等视频源上的模拟视频信息转换成数字视频信息。在视频采集卡中，模数转换器负责把从视频源传来的模拟视频流转换成数字视频流，音频捕捉线路所捕捉的数字音频信息可以和数字视频信息结合在一起，通过硬件压缩芯片执行某种压缩算法，输出的便是经过压缩的视频数据文件。也有的视频采集卡不带硬件压缩芯片，而通过压缩软件对视频数据进行压缩。

<div align="center"><img src="/assets/2-4-1.jpg"></div>
===
<div align="center"><span style="font-size:10px">图2-4-1 多媒体计算机的视频采集系统</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一般来说，视频采集卡提供了连续采集、单帧采集和视频图像的数字化播放等功能。为了对数字化视频信息进行编辑加工，可以采用专门的视频编辑软件。例如，Adobe公司的Premiere软件。  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Premiere是一个基于非线性编辑的视音频编辑软件，被广泛应用于电视编辑、广告制作、电影剪辑等领域，是PC机平台上应用最为广泛的视频编辑软件。非线性编辑系统实现了将传统的电视节目后期制作系统中的切换机、录像机、录音机、编辑机、调音台、字幕机、图形创作系统等设备集成于一台计算机内，用计算机来处理、编辑图像和声音等，再将编辑好的视音频素材输出成各种格式的文件或通过录像机录制在磁带上。Premiere就是一个优秀的非线性编辑软件。

###1.Premiere软件的主界面

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当启动Premiere cc 2017时，就会出现如图2-4-2所示的程序界面，其中【源监视器窗口】用于源素材的播放和预剪辑；【节目监视器窗口】用于播放时间线上的内容；【时间线窗口】是进行视音频编辑的工作区域；【工程项目窗口】是用于管理素材源的工作面板；【工具面板】提供了如选择工具，剃刀工具，比率拉伸工具等多种在非线性编辑中所用到的剪辑工具；【效果面板】提供了Premiere的几十种视频效果，音频效果及音视频过渡效果；【效果控件面板】用于时间线上素材效果的精确编辑。

<div align="center"><img src="/assets/2-4-2.jpg"></div>
===
<div align="center"><span style="font-size:10px">图2-4-2 Premiere程序界面</span></div>
===

###2.素材的采集和导入

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如图2-4-3所示，通过【文件】--【捕捉】命令，借助编辑平台上的视音频捕捉卡，可以采集来自各种介质的上的视音频素材；或者通过【文件】-【导入】命令，直接导入计算机硬盘中各种格式的视音频素材，包括AVI，MP4格式的视频文件，WAV，MP3格式的音频数据文件，动画FLC格式文件，PTL格式字幕文件，BMP，JPG，PNG，JIF格式的图像文件等。所有采集和导入都出现在工程项目窗口中。

<div align="center"><img src="/assets/2-4-3.png"></div>
===
<div align="center"><span style="font-size:10px">图2-4-3</span></div>
===

###3.素材的加载

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;时间线窗口有多个轨道放置视频和音频素材，是用于把素材汇编成影视作品的，用鼠标选取工程项目中的想要素材，然后拖到时间线的相应音视频轨上，即实现了素材的加载。如图2-4-4。

<div align="center"><img src="/assets/2-4-4.jpg"></div>
===
<div align="center"><span style="font-size:10px">图2-4-4</span></div>
===

###4.素材的剪辑

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;利用时间线窗口中的剪辑工具，根据分镜头稿本，剪除掉不需要的音视频素材，并进行整理，使素材很好地组接在一起。

###5.特效的加入

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在Premiere中，所有音视频效果及过渡效果都在【效果面板】中，加入效果的方法就是直接将【效果面板】中所用的效果拖入所要编辑的素材中或两段素材间。如图2-4-5。

<div align="center"><img src="/assets/2-4-5.jpg"></div>
===
<div align="center"><span style="font-size:10px">图2-4-5</span></div>
===

###6.字幕的制作

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如图2-4-6所示，通过【文件】→【新建】→【字幕】命令，可以制作标题字幕，新闻，唱词，片头字幕，片尾字幕等，并生成PTL字幕文件，同时会出现在工程项目库中，然后将字幕文件拖到时间线上，叠加到相应的视频素材上。

<div align="center"><img src="/assets/2-4-6.jpg"></div>
===
<div align="center"><span style="font-size:10px">图2-4-6</span></div>
===

###7.作品的预览

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在【节目监视器窗口】中单击播放按钮，对节目反复预览并进行修改，直到符合要求。

###8.作品的输出

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当在时间线窗口中完成了素材的剪辑，并对预览结果感到满意后，便可以输出可单独播放的影视文件。如图2-4-7所示，通过【文件】→【导出】→【媒体】命令，Premiere可以输出很多类型的文件，包括AVI文件，MOV文件，MP4文件，也可以是位图序列，动画文件FLC，还可以通过录像机录制在磁带上，使其作品可以在各种平台以及网络中很好的传播。

<div align="center"><img src="/assets/2-4-7.jpg"></div>
===
<div align="center"><span style="font-size:10px">图2-4-7 Premiere输出媒体面板</span></div>
===

##2.4.3视频素材的制作要求

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;视频素材的设计要求与动画素材的设计要求基本相同。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;首先视频素材要具备科学性。多媒体课件中的视频在表达教学内容的同时应符合生活常识和自然规律，尽量避免对学生的认知产生错误引导。其次视频素材要具备教学性。制作多媒体课件的目的是优化教学结构，提高课堂教学的教学效率，既要有利于教师的教，又要有利于学生的学。然后视频素材要具备艺术性。视频制作应尽量美观，适当运用一些视听语言，使其在承载教学功能的同时富有艺术表现力，引导学生在学习新知识的同时提升影视鉴赏能力。


