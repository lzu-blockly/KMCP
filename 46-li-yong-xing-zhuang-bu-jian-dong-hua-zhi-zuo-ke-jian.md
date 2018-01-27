#4.6 利用形状补间动画制作课件

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;许多简单的动画都是通过补间完成的，在时间轴上的某一帧定义一个对象的位置、大小和旋转等属性，然后在另一个关键帧上改变该对象的属性。通过设置，F1ash会自动补间帧，形成补间动画。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F1ash中的补间动画有两种：一种是形状补间动画，另一种是动作补间动画。两者之间最大的区别是形状补间动画适用于不是元件而未组合的对象，而动作补间动画针对组合对象或元件操作。本节主要介绍形状补间动画。通过学习，可以掌握用F1ash形状补间动画制作动态演示课件的方法和技巧。

###1．形状补间的原理

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在Flash 的【时间轴】面板上，在一个关键帧绘制一个形状，然后在另一个关键帧更改该形状或绘制另一个形状， Flash 根据二者之间帧的值或形状来创建的动画被称为形状补间动画。形状补间动画可以实现两个图形之间颜色、形状、大小、位置的相互变化，其变形的灵活性介于逐帧动画和动作补间动画之间，使用的元素多为用鼠标或压感笔绘制出的形状，如果使用图形元件、按钮、文字，则必先“打散”再变形。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;为了使Flash在计算变形过渡时依一定的规则进行，进而有效地控制变形过程，下面介绍添加【形状提示】，运用这个功能能极大改善变形的规范性。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;【形状提示】会标识起始形状和结束形状中的相对应的点，它为Flash 的形状渐变效果指示了变化的趋势，有利于形状补间按照制作者的意图变化。形状提示可以连续添加，最多能添加26个。分别用字母a-z表示，按逆时针顺序从形状的左上角开始放置形状提示，它们的工作放果最好。拖动开始帧和结束帧上的形状提示圆圈，在形状边缘的适当位置放置，可看到开始帧上的【提示圆圈】变为黄色，结束帧上的【提示圆圈】变为绿色。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;【形状提示】要在形状的边缘才能起作用，如果调整后相对应的形状提示不在一条曲线上时【提示圆圈】颜色不变，不能起到调整形状的作用。在调整形状提示位置前，单击【工具】面板中的【紧贴至对象】按钮，能自动把形状提示吸附到边缘上，如果形状提示仍然无效，则可以用放大镜工具放大到2000倍，以确保形状提示位于图形边缘上。另外，要删除所有的形状提示，可选择【修改】→【形状】→【删除所有提示】命令。删除单个形状提示，可在此形状提示上右击，在快捷菜单中选择【删除提示】命令。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;形状补间的操作方法如下：

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（1）新建一个文档，“大小”设置为“550×400像素”，“帧频”为30fps。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（2）在舞台绘制一个圆形，如图4-6-1所示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（3）在时间轴上第30帧处击右键选择【插入空白帧】，绘制一个正方形。如图4-6-2所示。

<div align="center"><img src="/assets/4-6-1.png"></div>
<div align="center"><span style="font-size:10px">图4-6-1 圆的绘制</span></div>
===


<div align="center"><img src="/assets/4-6-2.png"></div>
<div align="center"><span style="font-size:10px">图4-6-2 正方形的绘制</span></div>
===


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（4）右击1-30帧的任意帧，在弹出的快捷菜单中选择【创建补间形状】命令，创建形状补间动画。如图4-6-3所示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（5）这样一个从圆形到正方形的形状补间动画就完成了，效果如图4-6-4所示。

<div align="center"><img src="/assets/4-6-3.png"></div>
<div align="center"><span style="font-size:10px">图4-6-3 创建补间动画</span></div>
===


<div align="center"><img src="/assets/4-6-4.png"></div>
<div align="center"><span style="font-size:10px">图4-6-4 运行效果</span></div>
===


###2．实例：内吞

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;该例是中学生物“内吞”动画模拟演示课件，它通过形状补间动画演示了液体吞入细胞的过程。充分显现出F1ash课件在展示生物微观现象时的优势，学生通过观看形象的内吞动画演示过程，形成科学、规范的概念。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（1）新建一个Flash文件，舞台大小设置为“550×400像素”，设置背景色为淡绿色，其他参数保持默认值。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（2）新建一个名称为“物质”的图形元件，在此元件的编辑场景中，用绘图工具绘制一个填充色为黑色的圆形。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（3）创建“图标”影片剪辑元件

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①新建一个名称为“图标”的影片剪辑元件，在这个元件的编辑场景中，将“图层1” 重命名为“圆形”运用绘图工具 (虚线边框没有填充)，如图4-6-5所示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②新建一个图层，重命名为“变形”在此图层中，调整方向如图4-6-6所示。

<div align="center"><img src="/assets/4-6-5.png"></div>
<div align="center"><span style="font-size:10px">图4-6-5 绘制一个圆形</span></div>
===


<div align="center"><img src="/assets/4-6-6.png"></div>
<div align="center"><span style="font-size:10px">图4-6-6 绘制矩形</span></div>
===


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;此时“图标”影片剪辑元件的图层结构和场景效果如图4-6-7所示。

<div align="center"><img src="/assets/4-6-7.png"></div>
<div align="center"><span style="font-size:10px">图4-6-7 图层结构和场景效果</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（4）为“图标”影片剪辑元件添加动画帧

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①同时选中两个图层的第30帧，按【F5】键，在第30帧插入帧，此时的图层结构如图4-6-8所示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②锁定“圆形”图层，选中“变形”图层的第25帧，按F6键插入关键帧。接着选中“变形”图层的第10帧，按【F7】键插入空白关键帧，如图4-6-9所示。


<div align="center"><img src="/assets/4-6-8.png"></div>
<div align="center"><span style="font-size:10px">图4-6-8 图层结构</span></div>
===


<div align="center"><img src="/assets/4-6-9.png"></div>
<div align="center"><span style="font-size:10px">图4-6-9 第10帧插入空白关键帧</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③在“变形”图层的第10帧上绘制一个三角形。右击第15帧，在弹出的快捷菜单中选择【插入关键帧】命令插入关键帧，此时的图层结构如图4-6-10所示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（5）定义形状补间动画

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①选中“变形”图层的第1帧，击右键选择【创建补间形状】，“变形”图层的第1-10帧间出现了一条带箭头的实线，并且帧格变为绿色，说明己经实现了“变形”图层第1-10帧的形状补间动画。使用同样的方法在第15-25帧创建形状补间动画，如图4-6-12所示。此时图层结构，拖动播放头或按【Enter】键就能看到形状补间动画的效果了。

<div align="center"><img src="/assets/4-6-10.png"></div>
<div align="center"><span style="font-size:10px">图4-6-10 图层结构</span></div>
===

<div align="center"><img src="/assets/4-6-11.png"></div>
<div align="center"><span style="font-size:10px">图4-6-11 创建形状补间动画</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（6）添加形状提示

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①选中“变形”图层的第1帧，选择【修改】 →【形状】→【 添加形状提示】命令，该帧的矩形上增加了一个带字母的红色圆圈，同样设置第10帧。 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②拖动开始帧和结束帧上的形状提示圆圈，在形状边缘的适当位置放置，可看到开始帧上的“提示圆圈”变为黄色，结束帧上的“提示圆圈”变为绿色，如图4-6-12和图4-6-13所示。

<div align="center"><img src="/assets/4-6-12.png"></div>
<div align="center"><span style="font-size:10px">图4-6-12</span></div>
===

<div align="center"><img src="/assets/4-6-13.png"></div>
<div align="center"><span style="font-size:10px">图4-6-13</span></div>
===
                     
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③依次为第1-10帧的形状补间添加4个形状提示，调整它们的位置，如图4-6-14和图4-6-15所示。

<div align="center"><img src="/assets/4-6-14.png"></div>
<div align="center"><span style="font-size:10px">图4-6-14</span></div>
===

<div align="center"><img src="/assets/4-6-15.png"></div>
<div align="center"><span style="font-size:10px">图4-6-15</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;④用同样的方法为第15-25帧添加形状提示。添加了形状提示后，形状补间动画效果更自然。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（7）布局背景和标题

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①从元件编辑场景返回到主场景，插入3个图层，重新命名图层。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②选择“背景”图层，在舞台上输入课件标题，添加滤镜效果。接着使用【刷子工具】绘制细长形装饰条，并将【库】面板中的【图标】影片剪辑元件拖放到场景中，调整好大小和位置，如图4-6-16所示。

<div align="center"><img src="/assets/4-6-16.png"></div>
<div align="center"><span style="font-size:10px">图4-6-16 将【图标】影片剪辑元件拖放到场景</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（8）创建内吞过程补间动画

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①锁定“背景”图层。选中“细胞膜”图层，绘制一个无填充的圆形。在圆形的左上方用【选择工具】拖动选择二段圆弧，选择【编辑】→【剪切】命令，选中“运动”图层，选择【编辑】→【粘贴到当前位置】命令，把这段圆弧移动到“运动”图层。从【库】面板中把“物质”图形元件拖放在场景的“物质”图层。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②同时选中4个图层的第55帧，按【F5】键，在第55帧插入帧。在“细胞膜”图层的第20 、35 和36 帧分别插入关键帧。在“运动”图层的第20 、35 、36 和55帧插入关键帧，在“物质”图层的第20 、36 和55帧插入关键帧。此时的图层结构如图4-6-17所示。

<div align="center"><img src="/assets/4-6-17.png"></div>
<div align="center"><span style="font-size:10px">图4-6-17 图层结构</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当由几个图层共同构成补间动画时，关键帧的添加一定要同步进行，使它们彼此之间能协同变化，求得一致的效果。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（9）创建内吞过程补间动画

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①按照前面介绍的方法在“细胞膜”图层的第20-35 帧“运动”图层的第1-20帧、第20-35帧、第36-55帧添加形状补间动画。在“物质”图层的第1-20帧、第20-36帧、第36-55帧添加动作补间动画，如图4-6-18所示。

<div align="center"><img src="/assets/4-6-18.png"></div>
<div align="center"><span style="font-size:10px">图4-6-18 图层结构</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;注意：添加形状补间动画只能在【属性】面板的【补间】下拉列表框中选择【形状】。判断形状补间动画添加是否成功，可以观察时间轴上的关键帧之间是否有绿色背景和连续的带箭头的实线，如果表现为虚线则说明某个关键帧中的对象不是形状，这时可以按Ctrl+B键将对象分离为形状。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②运用【选择工具】调整“细胞膜”图层第20 、35 帧上的形状。如图4-6-19、图4-6-20所示。

<div align="center"><img src="/assets/4-6-19.png"></div>
<div align="center"><span style="font-size:10px">图4-6-19 第20帧上的形状</span></div>
===

<div align="center"><img src="/assets/4-6-20.png"></div>
<div align="center"><span style="font-size:10px">图4-6-20 第35帧上的形状</span></div>
===
       
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③编辑修改“运动”图层第1 、20 、35 、36 帧上的形状，如图4-6-21所示。

<div align="center"><img src="/assets/4-6-21.png"></div>
<div align="center"><span style="font-size:10px">图4-6-21 “运动”图层第1 、20 、35 、36 帧上的形状</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;④调整移动“物质”图层第20 、35 、36 、55 帧上“物质”元件的位置，如图4-6-23所示。

<div align="center"><img src="/assets/4-6-22.png"></div>

<div align="center"><img src="/assets/4-6-23.png"></div>

<div align="center"><img src="/assets/4-6-24.png"></div>

<div align="center"><img src="/assets/4-6-25.png"></div>
<div align="center"><span style="font-size:10px">图4-6-22 “物质”图层第20 、35 、36 、55 帧上“物质”元件的位置</span></div>
===

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;注意：调整对象形状或位置时要相互兼顾，方能使动画形象逼真。另外，多使用锁定和隐藏图层进行调整，能方便制作。

