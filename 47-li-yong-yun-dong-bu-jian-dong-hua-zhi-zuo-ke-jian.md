#4.7 利用运动补间动画制作课件

<div align="center"><iframe frameborder="0" width="640" height="498" src="https://v.qq.com/iframe/player.html?vid=f055140pkcz&tiny=0&auto=0" allowfullscreen></iframe></div>
<div align="center"><span style="font-size:20px">教学微视频</span></div>
===

###1．认识运动补间动画

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;利用补间动画来制作课件，是实现一个对象从一个位置上到另外一个位置上的过渡。动作补间动画的基本制作方法是，在一个关键帧上创建一个对象，然后在另一个关键帧改变这个对象的大小、位置、颜色、透明度、旋转、倾斜、滤镜等属性。定义好补间动画后，Flash自动补上中间的动画过程。构成动作补间动画的对象包括元件(影片剪辑元件、图形元件、按钮元件)、文字、位图、组、绘制对象等，但不能是形状，只有把形状组合成“组”或者转换成“元件”后才可以成为补间动画中的“演员”。

###2．制作运动补间动画

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来制作一个“流星”的例子来展示动作补间动画的制作过程。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;制作动作补间动画的方法如下：

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（1）新建一个Flash文档，将舞台大小设置为“500×400”，帧频设置成12fps，背景为“深蓝色”，如图4-7-1所示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（2）选择【插入】→【新建元件】命令，弹出【创建新元件】对话框。在【类型】中选中【影片剪辑】单选按钮，名称设置为“星星”，如图4-7-2所示。

<div align="center"><img src="/assets/4-7-1.png"><p style="text-align:center; font-size:10px; margin-top:2px">图4-7-1设置舞台属性</p></div>
===

<div align="center"><img src="/assets/4-7-2.png"><p style="text-align:center; font-size:10px; margin-top:2px">图4-7-2【创建新元件】对话框</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（3）在“星星”元件编辑区内绘制“星星”图形，如图4-7-3所示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（4）单击时间轴上方【场景1】按钮，返回主场景如图4-7-4所示。

<div align="center"><img src="/assets/4-7-3.png"><p style="text-align:center; font-size:10px; margin-top:2px">图4-7-3绘制“星星”图形</p></div>
===

<div align="center"><img src="/assets/4-7-4.png"><p style="text-align:center; font-size:10px; margin-top:2px"> 图4-7-4返回主场景</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（5）在【库】面板中选择“星星”元件并拖入到舞台中，调整位置和大小，如图4-7-5所示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（6）在第50帧处插入关键帧，并调整“星星”的大小和位置，如图4-7-6所示。

<div align="center"><img src="/assets/4-7-5.png"><p style="text-align:center; font-size:10px; margin-top:2px">图4-7-5 将“星星”元件拖入到舞台中</p></div>
===

<div align="center"><img src="/assets/4-7-6.png"><p style="text-align:center; font-size:10px; margin-top:2px">图4-7-6 调整“星星”第50帧处大小和位置</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（7）右击第1—49帧之间的任意帧，在弹出的快捷菜单中选择“创建传统补间” 命令，创建动作补间动画。如图4-7-7所示。

<div align="center"><img src="/assets/4-7-7.png"><p style="text-align:center; font-size:10px; margin-top:2px">图4-7-7创建动作补间动画</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（8）这样一个星星从右往左飞得动画就制作好了，但是效果并不好。这时可以选中补间，通过属性面板对动作补间进行设置，在属性面板中设置缓动为“100”，让星星减速飞行。在属性面板中设置旋转为“顺时针”、“1”次。使星星在运行时，有一个旋转的效果。如图4-7-8所示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（9）选中第50帧上的“星星”元件，通过【属性】面板对元件实例的属性进行设置，调整【颜色】项目中的Alpha值为“0%”，使星星在运行到最后时完全变透明至消失，如图4-7-9所示。

<div align="center"><img src="/assets/4-7-8.png"><p style="text-align:center; font-size:10px; margin-top:2px">图4-7-8 动作补间【属性】设置</p></div>
===

<div align="center"><img src="/assets/4-7-9.png"><p style="text-align:center; font-size:10px; margin-top:2px">图4-7-9调整颜色项目中的Alpha值为“0%”</p></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（10）测试并保存影片。