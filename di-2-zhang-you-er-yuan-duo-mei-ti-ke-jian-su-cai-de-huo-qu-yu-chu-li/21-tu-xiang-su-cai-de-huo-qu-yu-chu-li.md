#2.1 图像素材的获取与处理

<div align="center"><iframe frameborder="0" width="640" height="498" src="https://v.qq.com/iframe/player.html?vid=s0534swnxqt&tiny=0&auto=0" allowfullscreen></iframe></div>
<div align="center"><span style="font-size:20px">教学微视频</span></div>
===

##2.1.1图像素材简介

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一般来说，图像格式大致可以分为两大类: 位图 (Bitmap) 矢量图(Vector Graphic )。位图是以二维点阵形式来描述图像: 矢量图是在绘制线条、矩形、圆形等的基础上去创建图像，矢量图像实际上是存储了表示许多单个对象的一系列指令。一般说来，矢量类图像的表达细致、真实，缩放后的分辨率不变，同时，它所需的存储空间也比较小。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在介绍图像格式前有必要先了解几个主要指标：分辨率、色彩数、灰度。图像的分辨率包括屏幕分辨率和输出分辨率，前者用每英寸行数表示，数值越大则质量越好; 后者衡量输出设备的精度，以每英寸的像素点数表示。图像的色彩数和图像灰度用位（bit）表示，通常写成2<sup>n</sup>，代表位数。当图像达到24位时，可表现2<sup>24</sup> ≈1677 万种颜色，即真彩。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;图像素材的常用文件类型包括以下几种:

###1.BMP 格式

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BMP(Bit Map Picture)格式是Windows 使用的基本图像格式，是一种位图格式文件，用一组数据(8--24 位)来表示一个像素的色彩。大多数图像软件都支持BMP 格式。BMP 格式文件的规模比较大。

###2.PNG格式

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;采用无损压缩编码，能获得较高的压缩比，文件尺寸较小，支持多种颜色深度。

###3.JPG格式

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;JPG（Joint Photographic Expert Group)格式也称JPEG 格式是一种十分流行的图像格式，它采用了JPG方法进行压缩，因此文件可以非常小，而且可以通过降低压缩比来获得较高质量的图像资料。但JPG格式是一种有损压缩，因此不适于存储珍贵的图像资料或原始素材。

###4.TIFF格式

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;支持多种压缩方案、多种颜色深度、能提供专业级印刷质量的图像。

###5.GIF 格式

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GIF(Graphics Interchange Format )格式是目前因特网上使用最普遍的图像文件格式之一，主要用于在不同平台上进行图像交流传输。GIF 格式文件的压缩比比较高，文件规模较小，但它仅能表达256 色图像。目前的GIF 格式文件还支持图像内的小型动画，它使得因特网上的网页显得生动活泼。

## 2.1.2 图像的获取与编辑

###1.图像的获取

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;图像是多媒体课件中必不可少的素材，在课件制作中，除了自己绘制图像外，还可以使用屏幕捕捉软件、扫描仪等工具来获取现有的图像。 
 
**(1)捕捉屏幕上的图像**
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;用于屏幕捕捉的软件很多，Hyper Snap-DX、Capture Professional、SnagIt都是不错的抓取软件，功能相当强大。它们不仅可以捕捉屏幕上的静态图像，还可以捕捉动态屏幕影像和屏幕文字。  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;除了借助屏幕捕捉的软件，我们还可以利用键盘上的快捷键直接截取图像，键盘如图2-1-1（适用于使用台式键盘的电脑，而笔记本快捷键是：FN + Prtsc）。

<div align="center"><img src="/assets/2-1-1.png"><p style="text-align:center; font-size:10px; margin-top:2px">图2-1-1 键盘</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;① Print Screen功能键，直接按下即可捕捉电脑屏幕图像，截图我们所看到的显示器显示的所有界面。  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;② 使用Alt + Print Screen键实现活动截图，即可完成当前活动区域的界面截图。  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③ 同时按下Ctrl+ Alt+ A键可实现选择区域截图（该快捷键需要在登陆QQ后才可以使用）此时，我们可以任意拖动鼠标来选择区域截图。  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;以上三种方法中，我们要看到或要保存所截图像，都需要打开画板或Word或其他编辑器→【Ctrl+ V】粘贴→另存为图像。  

**(2)通过扫描仪获取图像**  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;要从书本、杂志、照片等非数码资源中获取图像，扫描仪是一类最常用的工具。扫描仪的工作原理和复印机相似。用一列光传感器电子化地捕捉图像。传感器每次把一行光转换成颜色和光强，直到整个页面被扫过。各类扫描仪的性能有很大的不同，在分辨率方面可以达到100dpi\(每英寸的点数\)至1000dpi的质量。 
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;扫描仪由软件控制，这些软件将计算机与扫描仪连接起来。由软件管理传感器的预热，控制扫描仪的机械运动，将扫描出来的图像经过转换后保存到硬盘上。该扫描软件由于扫描仪的类型不同而不同，但是无论使用哪种扫描软件，扫描图像的步骤基本上是一样的: 预扫描→设定扫描区域→扫描→保存图像。  

**(3）利用数码照相机拍摄数字图像**  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;利用数码照相机可以直接拍摄数字化图像素材。通过数码照相机获取的数字图像通常存放在存储卡内再通过数据线将其输入到计算机中使用。

**(4）通过下载**  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;有许多专门的软件用于图像搜索，搜索到需要的图像资源后可以使用下载工具，如迅雷下载下来。或者直接在网页中下载即可。 

###2.图像的编辑  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;通过上述手段获取了数字化图像以后，通常还需要对图像进行编辑或加工。图像编辑工具十分丰富，从Windows自带的“画笔”软件到功能十分强大的Photoshop软件都可选用。利用它们能完成基本的绘制图像功能，并具有对从外部文件输入的图像数据进行编辑修改的能力。 
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Adobe公司开发的Photoshop集位图和矢量图绘画、图像编辑、网页图像设计、网页动画制作、网页制作等多种功能于一体，是多媒体课件制作中不可缺少的图像素材编辑软件，Photoshop的主界面如图2-1-2所示。

<div align="center"><img src="/assets/2-1-2.png"><p style="text-align:center; font-size:10px; margin-top:2px">图2-1-2 Photoshop软件的主界面</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Photoshop的主要功能可分为图像编辑、图像合成、校色调色及特效制作等。  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;图像编辑是图像处理的基础，可以对图像做各种变换，如放大、缩小、旋转、倾斜、镜像、透视等，也可进行复制、去除斑点，修补、修饰图像的残损等处理。 
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;图像合成则是将几幅图像通过图层操作、工具应用形成完整的、意义明确的图像。Photoshop提供的绘图工具让图像可以很好地融合起来，使图像合成得天衣无缝。如图2-1-3所示，在Photoshop中打开图2-1-3、图2-1-4两张图像。

<div align="center"><img src="/assets/2-1-3.png"><p style="text-align:center; font-size:10px; margin-top:2px">图2-1-3 待合成图窗口</p></div>
===

<div align="center"><img src="/assets/2-1-4.png"><p style="text-align:center; font-size:10px; margin-top:2px">图2-1-4 待合成图企鹅</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;首先利用【选框工具】/【套索工具】在图2-1-3做出一个矩形选框，打开图2-1-4，按下【Ctrl+  A】全选图像→【Ctrl+ C】，打开图2-1-3点击菜单栏【编辑】→【选择性粘贴】→【贴入】将两图合成一张图，接着利用【移动工具】调整图像的位置。合成效果如图2-1-5所示

<div align="center"><img src="/assets/2-1-5.png"><p style="text-align:center; font-size:10px; margin-top:2px">图2-1-5 图像合成</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;色彩调色是Photoshop中深具威力的功能之一，利用它可以方便快捷地对图像的颜色进行明暗、色彩的调整和校正，也可以切换颜色以满足图像在不同多媒体作品中的应用。

<div align="center"><img src="/assets/2-1-6.png"></div>
<div align="center"><img src="/assets/2-1-7.png"><p style="text-align:center; font-size:10px; margin-top:2px">图2-1-6 处理前的图</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如图2-1-6处理前的图像所示，其利用了Photoshop对曝光不足的图像进行处理：菜单栏中【图像】→【调整】→【色阶】，此时调整色阶中的白场即可。反之，对于曝光过度的图像，调整色阶中的黑场、白场。下图2-1-7为处理后的图像。

<div align="center"><img src="/assets/2-1-8.png"><p style="text-align:center; font-size:10px; margin-top:2px">图2-1-7 处理后的图像</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;特效制作在Photoshop中主要由滤镜、通道及工具综合应用完成，包括图像的特效创意和特效字的制作，如油画、浮雕、石膏画、素描等常用的传统美术技巧可通过Photoshop特效完成。

##2.1.3图像素材的制作要求

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;图像素材的制作要求如下:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1)尽量使用容量小的图像。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2)用作教学内容的图像要准确。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(3)用作背景的图像要淡一些，不可冲淡教学内容。


