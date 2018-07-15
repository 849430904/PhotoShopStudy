### [ps6破解](https://www.jianshu.com/p/097353202b66)
---

#### 文件新建:ctrl+n 
---
![](img/001.png)

````
若有经常使用的尺寸，可以直接设置好宽度和高度，点击存储预设；
注：ctrl+alt+n  重复上次的文件尺寸大小；
若不需要此尺寸，可以直接选中并点击删除预设；

分辨率:
	若用于网页设计，网页浏览，可选择72分辨率，单位为像素
	若用于高级图像处理，可选择300分辨率，单位为像素
	若用于印刷等出版，可选择300分辨率，单位可以选择毫米或厘米
颜色模式:RGB模式、CMYK模式、位图、灰度、Lab颜色
    RGB模式：RGB模式是PS中最常用的模式，也被称之为真彩色模式，在RGB模式下显示的图像质量较高，也是PS的默认模式；RGB颜色模式主要是由R（红）、G（绿）、B（蓝）三种基本色相加进行配色，并组成了红绿蓝三种颜色通道；该模式适用于显示器、投影仪、扫描仪、数码相机等；
    CMYK模式：CMYK颜色模式是打印全彩图像的颜色系统。青色、品红、黄色、和黑色是平版印刷机和喷墨打印机使用的油墨颜色。CMYK模式主要是由C（青）、M（洋红）、Y（黄）、K（黑）4种颜色相减而配色的。因此它也组成了青、洋红、黄、黑4个通道，每个通道混合而构成了多种色彩。
  当对图像进行印刷时，必须将它的颜色模式转换为CMYK模式。由于在CMYK模式下Photoshop的许多滤镜效果无法使用，所以一般都使用RGB模式，只有在即将进行印刷时才转换成CMYK模式，这时的颜色可能会发生改变。
   位图：位图模式是用黑色和白色来表现图像的，不包含灰度和其他颜色，因此它也被称为黑白图像。
   灰度：灰度模式下的图像只有灰度，而没有其他颜色。如果将彩色图像转换成灰度模式后，所有的颜色将被不同的灰度所代替。
   Lab颜色：Lab模式既不依赖光线,也不依赖于颜料,Lab模式由三个通道组成,它的一个通道是亮度,即L.另外两个是色彩通道,用A和B来表示.A通道包括的颜色是从深绿色（底亮度值）到灰色（中亮度值）再到亮粉红色（高亮度值）；B通道则是从亮蓝色（底亮度值）到灰色（中亮度值）再到黄色（高亮度值）.因此,这种色彩混合后将产生明亮的色彩.


背景内容：
   白色：背景画布为白色单色
   背景色：背景画布的颜色为背景色设置的颜色
   透明：背景内容无颜色填充，呈现透明状态   
````

-----

##### 文件的存储

![](img/002.png)

````
常用的格式：
   PSD格式是Photoshop工具的默认格式，也是唯一支持所有图像模式的文件格式。它可以保存图像中的图层、通道、辅助线和路径等信息。一般寻找素材会选择PSD格式，文件做完或者没做完都习惯性保存PSD源文件，方便后期修改。由于PSD格式所包含的图像数据信息比较多，因此比其他格式的图像文件要大得多。
   JPEG是一种有损压缩的格式，此格式的图像通常用于图像预览和一些超文本的文档中（HTML文档），文件后辍名为“.jpg”或“.jpeg”，最大的特色是文件比较小，可以进行高倍率的压缩，是目前所有格式中压缩率比较高的格式之一，但是JPEG格式在压缩保存的过程中会以失量最小的方式丢掉一些肉眼不易察觉的数据，因而保存的图像与原图有所差别，没有原图的质量好，不适合印刷使用。
   PNG用来存储灰度图像时，灰度图像的深度可多到16位：存储彩色图像时，彩色图像的深度可多到48位，并且还可存储多到16位的通道数据。PNG在网页应用中使用较为广泛,比如在Dreamweaver中插入一张透明背景图片，就可以使用PNG格式的图片。PNG能保留完整的照片色彩，是一种非失真性压缩格式。不过唯一的缺点是文件较大，不利于网页浏览。由于PNG格式不完全支持所有浏览器，所以在网页使用要比GIF和JPEG格式使用少的多。
   GIF格式是一种图形格式，只是保存最多256色的RGB色阶数，是一种基于LZW算法的连续色调的无损压缩格式。目前几乎所有相关软件都支持它。GIF格式的另一个特点是其在一个GIF文件中可以存多幅彩色图像，如果把存于一个文件中的多幅图像数据逐幅读出并显示到屏幕上，就可构成一种最简单的动画。GIF分为静态GIF和动画GIF两种，扩展名为.gif，是一种压缩位图格式，支持透明背景图像，适用于多种操作系统，“体型”很小，网上很多小动画都是GIF格式。其实GIF是将多幅图像保存为一个图像文件，从而形成动画，所以归根到底GIF仍然是图片文件格式。
   BMP格式：它是Window操作系统中的标准图像文件格式，其不支持CMYK模式的图像。由于BMP文件格式是Windows环境中交换与图有关的数据的一种标准，因此在Windows环境中运行的图形图像软件都支持BMP图像格式。
   TIFF格式：TIFF是一种无损压缩格式，是一种非常广泛的图像格式，TIFF与JPEG和PNG一起成为流行的高位彩色图像格式。TIFF格式可以制作质量非常高的图像，因而经常用于出版印刷。如果您要在一个并非创建该图像的程序中编辑图像，则以这种格式保存将很有帮助，因为多种程序都可以识别它。TIFF用于在应用程序和计算机平台之间交换文件，是一种灵活的位图图像格式，几乎受所有的绘画、图像编辑和页面版画应用程序的支持。而且，几乎所有的桌面扫描仪都可以生成TIFF图像。

总结：psd存储了所有图像模式；
     jpeg有损压缩、文件较小；
     png非失真压缩、文件较大；
     gif:无损压缩；

````

----

#### 文件的打开与关闭
----
##### 文件的打开：
* ctrl+o
* 双击ps画面区域打开
* 直接拉拖动文件到ps当中去
* 直接双击打开psd文件

##### 文件的关闭：
![](img/003.png)

----

#### 移动工具
----

![](img/004.png) 

* 移动工具不仅可以轻松的选择每一个图层，还可以移动各个图层到自己的理想位置，还可以进行文件图像与其他文件之间的移动；
* 移动工具快捷键：V
* 移动工具属性：
![](img/005.png)

1. 自动选择：在默认情况下，移动工具的“自动选择”一项是没有勾选的。表示只能选中图层窗口中选定的固定图层，不能随意的点击选择别的图层。在这里，我们也勾选“自动选择”，可任意选择图层
2. 显示变换控件  ctrl+T ![](img/006.png)
3. 对齐方式(至少两个或者两个以上的图层); 分布（至少三个或者三个以上的图层）
  分组快捷键：CTRL+g (有时候需要将多个图层水平距离一定，我们可以垂直分组，然后选择所有组，再使用对齐)
  
````
  图层复制：ctrl+alt（option）+ 鼠标拖动
````

----

#### 选区工具组
----
![](img/007.png)
* 快捷键：M  
* 在PS中可以通过创建选区对图像进行填充、移动、复制、变换等编辑操作。在PS操作中，用选区选取范围是比较常用的方法。建立选区以后，就可以对选区内的图像进行操作。

#### 选区的运算
1. 利用选择工具建立选区，然后利用属性面板中的运算按钮。
1. 利用快捷键，如下：

* Shift:添加选区(合并选区) ![](img/008.png)
* Alt:减去选区（删减选区）  ![](img/009.png)
* shift+alt:与选区相交 ![](img/010.png)

#### 羽化
* 快捷键：shift+F6
* 选区的羽化是PS中使用频率比较高的一项功能，它可以起到融合边缘的效果，实现渐变过渡边缘。

#### 消除锯齿
* 消除图像边缘部分的锯齿状，使边缘看起来比较平滑![](img/012.png)

````
  要为选区填充颜色：新建选区-》新建图层-》填充颜色；
````
#### 样式--宽度--高度
* 可以自由绘制选区，也可以固定比例，固定大小，与宽度及高度结合使用；![](img/011.png)

----

#### 调整边缘
----

----

#### 图层
----
* 图层：学习PS的人员都知道PS作图是离不开图层的操作的；在图层里面，可以加入文本、图片等，也可以自由的修改、创新，良好的分层更是有助于设计更完美的展示及修改；
* 新建图层：可以直接点击如图所示图标，也可以使用快捷键：Ctrl+Shift+Alt+N; ![](img/013.png)

* 填充前景色:Alt+Del  填充背景色：Ctrl+Del
* 图层快捷键：Ｆ７

##### 删除图层：
1. 将图层直接拖动至删除箱
2. 右击删除图层
3. Del健直接删除

##### 复制图层：右击复制图层或者使用快捷键Ctrl+J;
##### 图层重命名：双击图层名字区域 ![](img/014.png)
##### 合并图层：Ctrl+E
##### 合并可见图层:Ctrl+Shift+E
##### 建组：Ctrl+G

----

#### 矩形选择工具
----
![](img/015.png)

* 快捷键：M/Shift+M

````
   填充前景色：Alt+Delete  必须要在图层上面
	填充背景色：Ctrl+Delete  必须要在图层上面
	取消选区：Ctrl+D
	shift 可以约束等比 （拖拽边角点）,可以画等比例的宽高（正方开）；先选择区，再按shift
	alt   约束中心点
	撤销操作：
	ctrl + Z  最后两部互相切换
	ctrl + alt + Z 一直往回撤销
	ctrl + shift + Z 重做变换选区:Alt+S+T
	复制图层：
	按着ALt+鼠标拖动

````

----

#### 椭圆选框工具

----

![](img/016.png) 

* 快捷键：M/Shift+M

````
调节图层顺序：
ctrl + [ 向下走一层  ] 向上走一层
ctrl + shift + [  or  ]   (直接一步到位到最底层或最顶层)
自由调节外框：ctrl + T  大小   或者 shift+鼠标拖动   
变化选区：Alt+S+T
shift 可以约束等比 （拖拽边角点）
alt   约束中心点
放大与缩小画面：
可按Alt+鼠标滚轮
放大：Ctrl+“+”
缩小：Ctrl+“-”
移动中心点：Alt健进行中心点的拖动，可利用shift健协助；

打开或隐藏标尺：Ctrl + R 
````
* 利用标尺确定画布的中心点; 视图->新建参考线->50% ![](img/017.png)

----

#### 单行选框工具

----
* ![](img/018.png)
 
````
复制：Ctrl+J
     Ctrl+C
粘贴：Ctrl+V
剪切：Ctrl+X－－－自动生成一个新的图层	

````

----

#### 单列选框工具

----
*  ![](img/019.png)如图所示，打开PS，在选区工具组里，第四个就是单列选框工具，其呈现出来的状态是垂直且单位为1像素的线，单击即可生成，若图片过大，需要进行放大仔细观看。

````
键盘上下左右方向键可以移动图层/选区；
变换并复制:Ctrl+Alt+T  （先要选中）
重复变换：Ctrl+Alt+Shift+T
shift+点击：加选
alt+点击：减选

````

----
#### 修改选区边界
----

* ![](img/020.png)边界：用于创建将原选区边界分别向内外扩展指定宽度后生成的区域,在原有的选区上多出一个选区，填充颜色时填充两个选区中间的部分，并且呈现出羽化状态；


````
注意:
1,边界宽度值：1-200像素之间；
2,必须是在已经有选区存在的情况下，进行修改边界。如果没有选区存在，那么修改边界命令呈灰色状不能够使用。
3,与描边的区别，使用边界命令就自动羽化了，而描边命令则不会出现羽化效果。
4,如果宽度值设置为奇数，则选区的边界由蚁行线内侧选择度大于50%的像素定义。
5、如果宽度值设置为偶数，则选区的边界由蚁行线内外两侧的像素共同定义。

````
* 未设置边界效果前：![](img/021.png)
* 修改边界后：![](img/022.png)

----
#### 选区平滑效果(可以实现圆角效果)
----
* 平滑：调节选区的平滑度，边角圆滑效果,平滑选区中的尖角和锯齿；
* 菜单--选择--修改--平滑
* 默认前景色背景色快捷键：D
* 反选：Ctrl+Shift+I
* 平滑前效果：![](img/023.png)
* 平滑后效果：![](img/024.png)

----
#### 选区的扩展
----
* 扩展：原选区沿边界向外扩大指定的宽度；
* 菜单--选择--修改--扩展
* 扩展前效果：![](img/025.png)
* 扩展后效果：![](img/026.png)
* 注意：扩展会把你的选区微变化

#### 选区的收缩
* 收缩：原选区沿边界向内缩小指定的宽度；
* 菜单--选择--修改--收缩
* 收缩前的效果：![](img/028.png)
* 收缩后的效果：![](img/029.png)
* 注意：收费也会把你的选区微变化
#### 选区的羽化（可以实现类似投影、阴影效果）
* 羽化：羽化将会使选区边缘变得柔和，有自然的过渡衔接，羽化像素的尺寸将会决定选区边缘逐渐软化的区域大小。
* 快捷键：Shift+F6
* 菜单--选择--修改--羽化
* 羽化前的效果：![](img/030.png)
* 羽化后的效果：![](img/031.png)
* 把背景层变为普通图层：按着ALt双击图层缩略图 ![](img/032.png)
* 后退：Ctrl+Z
* 连续撤销：Ctrl+Shift+Z
* 根据视觉习惯进行绘图：从上到下  从左到右
* 上下左右两边同时放大或者缩小：按Alt

----
#### 套索工具组
----
![](img/033.png) 

* 快捷键： L   可按shift+L进行切换
* 套索工具：主要是用来进行不规则形状的选取，利用鼠标拖拽制作选取范围；
	* 方法：鼠标左键点击不松手拖动，释放左键之后终点与起点将自动链接起来，且自动创建选区；
* 多边形套索工具：用于绘制直线型的选取范围；
	* 方法：单击鼠标左键确定起点，可松开鼠标，再选择下一处节点的位置，节点与节点之间将自动连接成选区线段，当终点与起点重合时，鼠标右下角将会出现圆圈，单击即可闭合生成选区，如果在绘制的过程中封闭选区，双击即可形成闭合选区；

````
技巧：
	1,按Shift键可以创建水平、垂直、45°角的线；
	2,如果在创建选区的过程中出错，可以按键盘上的delete即可删除刚创建的节点，也可以按esc键退出重新创建选区；
	3,套索工具和多边形套索工具可相互结合使用，在套索工具下按着Alt键不松开即可切换到多边形套索工具；

````
* 磁性套索工具：是一种比较智能的选择工具，可以自动吸附图像的边缘，沿着图像边缘产生选区，适合于抠图，但是需要选择边缘清晰、对比度明显的图像；
	* 方法：单击左键定义起点，松开鼠标，沿着图像边缘移动鼠标位置，当终点与起点重合时，鼠标右下角将会出现圆圈，单击即可闭合生成选区，如果在绘制的过程中封闭选区，双击即可形成闭合选区；

````
技巧：
	1，在绘制的过程中，若图像某处边缘不清晰，可单击鼠标人为确定下一个节点；
   2，如果在创建选区的过程中出错，可以按键盘上的delete即可删除刚创建的节点，也可以按esc键退出重新创建选区；
   3，磁性套索工具和多边形套索工具可相互结合使用，在磁性套索工具下按着Alt键不松开并单击即可切换到多边形套索工具，松开之后即可变回磁性套索工具；

````
##### 磁性套索工具属性栏:![](img/034.png)
* 宽度：检测的范围宽度，默认为10像素，若想更直观的看到检测宽度，可以按键盘上的的Caps lock切换到精确光标的方式，光标就会变成一个圆圈，就可以直观的看到宽度范围了，宽度的数值越小得到的选区越精确，可根据实际情况适当调节宽度值；
* 对比度：控制周围色与边缘色彩的反差程度，对比度数值设置1-100；若选取的图像与周围图像间的颜色对比度比较强，可设置一个较高的百分数值，反之，设置数值较低比较好；
* 频率：控制绘制过程中生成的节点数量，数值越大，速率越快，节点越多，最大值为100，默认值为57，当图片边缘比较复杂的时候，可以采用较大的频率值，来提高边缘的准确性；
* 钢笔压力：![](img/035.png) 用光笔绘图板的用户才会用到。

----
#### 快速选择与魔棒工具
----

* ![](img/037.png)
* 快捷键： W  
* 方法：选择快速选择工具，调节画笔大小，可按“{”“}”进行画笔大小的快速调节，点击并拖动鼠标选择需要选取的范围，选区会自动延伸；
* 快速选择工具属性栏 ![](img/038.png)
* 选择方式：
	* 新建：![](img/039.png)加选：![](img/040.png) 减选： ![](img/041.png)
	* 注意：当没有选区时，默认的选择方式时新建，当选区建立后，自动改为添加到选区，按ALt键，可以将选择方式变为从选区中减去。
* 画笔调整：包括大小、硬度、间距，对于选区边与背景颜色反差比较多的图像，可适当将画笔笔触调大，进行快速的选择，提高效率，反之调小，进行细致的范围选取；![](img/042.png)
1. 大小：鼠标拖动三角![](img/043)往右将画笔放大，往左将画笔缩小；注意：右括号“】”可增大画笔的大小，左括号“【”可减小画笔的大小，在调节时，请将自己的输入法关闭；
2. 硬度：当笔头设置的硬度值越大，选区边缘就会越生硬，数值越小，变会越柔和，但是对快速选择工具的意义不大；
3. 间距：若设置的数值比较小，选区一般是连续的，若设置的数值比较大，一般是间断的，通常情况下不做特殊调整；
4. 角度：与圆度可以配合使用，如下图，当角度设置为50°时，画笔笔触将不再是水平或者垂直展现出来；
5. 圆度：可将画笔笔触变为椭圆形，但是对于快速选择工具，角度和圆度用的几率都不是很大；![](img/044.png)
6. 需要外接手绘板才可以完成制作；![](img/045.png)

##### 对所有图层取样：
* 基于所有图层创建一个选区，而不仅仅针对当前图层。
##### 自动增强
* 减少选区边界的粗糙程度，使选区向主体的边缘进一步流动，遇到选择对象的边沿有模糊的过渡色时，会做一个自动边缘调整，扩大要选择的范围；
##### 调整边缘

-----
##### 魔棒工具
----
![](img/046.png)
* 快捷键： W  
* 魔棒工具:可以通过简单的操作创建选区，且选区范围是与鼠标落点处颜色相邻或相近的区域，对背景简单且颜色比较单一的图像可进行快速的选取；
* 方法：选择魔棒工具，通过鼠标单击图像颜色区域取样，可按Shift键加选，Alt键减选；

````
技巧：
   1、在选择图像时，要适时放大进行选择或加选，以免有漏选的现象发生，全部选择之后，请检查看选取的完整性；
   2、魔棒工具一般抠取背景色与主体色差比较大的图片，若背景比较复杂或与主体色差比较小或有融合的部分，可采取别的方式抠图；

````

* 魔棒工具属性栏![](img/047.png)
* 取样大小：默认为取样点，是取样点像素的大小。比如3×3，就是三个像素乘三个像素的大小；
* 容差：魔棒工具是利用色彩的容差来选择图像的范围，所以容差值设置对于魔棒工具起着非常重要的作用；容差越大，选取颜色时的色差范围越大，反之越小，取值范围：0-255，当容差值设置为0时，选区选取只能和取样颜色完全相同的颜色区域。
* 连续：选择位置相连且颜色相接近的区域，若处于勾选状态，魔棒只选择相邻区域，与图像中其他色块无关，该选择处于非勾选状态，则选择图像中所有颜色相接近的区域；![](img/048.png)
* 对所有图层取样：处于未勾选状态时，魔棒工具只从当前图层选取颜色范围，若勾选，在选取时会将文件中所有可见图层的相似颜色全部选取，如下图；![](img/049.png)


-----
##### 裁剪工具
----
![](img/050.png) 

* 快捷键： C  
* 裁剪工具:在PS作图的过程当中，往往会遇到图片大小不合适或者画布大小需要修改等问题，有时候拍摄出来的照片也需要调整其构图及大小，那我们就可以用裁剪工具移去部分图像也可以扩大画布范围，裁剪工具也可以修正歪斜的图片，大小及长宽比可手动任意拖动。
* 方法：选中PS裁剪工具，在图像中拖动选取范围，即可在图片的四角和四边会出现裁剪标识---8个控制点，并显示裁剪范围，且其他区域会变暗，选框可以在创建之后调整，利用控制点对框内范围进行放大、缩小、旋转等操作，调整完成之后双击鼠标或按回车（enter）键确定选取范围；若要取消裁剪，可以鼠标右击“取消”，也可以按快捷键Esc进行删除；

````
技巧：
   1，将鼠标放置在框内可移动选框；
   2，3:2、4:3、1:1是处理摄影图片常用选项；
````

-----
##### 透视裁剪工具
----
![](img/051.png) 
 
 * 透视裁剪工具:可以将裁剪区域调整为透视或者任意四边形，从而改变图像形态，也可以纠正不正确的透视变形，对倾斜的图片进行矫正。
 * 方法：
	* 选择透视裁剪工具，在图像当中任意拖动矩形，可以利用边缘框点进行边框的变形更改；
	* 选择透视裁剪工具，直接单击鼠标定出四个点画出任意四边形
	* 可以按Alt键更改画面中心点
	* 注意：任何变形都会导致画面的扭曲，所以变形的程度不能太大。
* 透视裁剪工具属性栏 ![](img/052.png)
* 设置裁剪图像的宽度、高度及分辨率 ![](img/053.png),在框中可以输入需要的尺寸大小
* 前面的图像：单击可以记录图像的大小及像素，可以使裁剪后的图像与之前记录的图像大小相同；
* 清除：单击可以清除设定好的宽高值及分辨率值；
* 显示网格：勾选状态是显示裁剪框的网格，不勾选则只显示外框；![](img/054.png)
* 选完以后，按enter键就可以确定最终图片；

-----
##### 切片工具
----

* ![](img/055.png)  
* 快捷键： C  
* 切片工具:切片工具就是用来切割图像，学习切片工具有两方面原因：
	1. 	主要用于网页设计，改善网页加载速度，让相同的网速下网页加载速度更快，给用户良好的网页浏览体验。
	2. 设计出来的Jpg图片没有办法做链接跳转，需要切片处理添加超链接做跳转。
* 方法：选择 工具箱中的“切片工具”，在想切入的地方点击并拉动鼠标，会出现四方形的切片区域，拉到合适的位置，松开鼠标后可完成创建一个用户切片，且有蓝色数字标识![](img/056.png),用户以外生成自动切片。同样的操作，可以继续操作下面的切片用户，操作错误，可以右击或者delete键删除切片或用切片选择工具进行修改编辑。

````
技巧：
   1,当鼠标放置在当前切片用户范围处，可直接切换切片选择工具，当鼠标移动至其他切片处，可按Ctrl键切换选择工具；
   2,隐藏切片：Ctrl+H   清除切片：Alt+V+C；如果不想同时隐藏辅助线，可以按完ctrl+H后再任意拉一条辅助线即可;
   3、按Shift可以加选切片并进行组合切片；

````
* 切片工具属性栏 ![](img/057.png)
* 样式：可以改变切片工具的裁切标准：
	* 正常：随意切片，切片大小和位置取决于自己画的框；
	* 固定长宽比：根据特定的长宽比设置切片框；
	* 固定大小：固定设置切片的长宽大小；
* 宽度：设置切片的宽度；
* 高度：设置切片的高度；
* 基于参考线的切片：如果我们的文件需要参考线标注可以更加准确，我们可以执行基于参考线的切片操作，使切片精准度更高；

-----
##### 切片选择工具
----
* ![](img/058.png)
* 快捷键： C 
* 切片选择工具:当我们把图片切出来之后，可以用切片选择工具删除无用的切片，也可以变化切片的大小和位置等，也可以进行切片的排列对齐，图片的超链接等;
* 方法：
	1. 点击切片，可以根据切片边或者角点随意拉伸或收缩切片，改变大小及位置，也可选中直接按delete或右击进行删除切片；
	1. 在切片位置处右击选择编辑切片选项，或双击切片，可以调出编辑框，进行网址链接等相关信息的设置；
* 切片类型：![](img/059.png)

````
	无图像；该切片输出空白无图像可以在切片中输入HTML文本；
	图像：该切片图像输出成图像；
	表：切片导出时作为嵌套表写入到HTML文本文件中；
	名称：输入切片的名称，但是如果选择无图像，则没有名称选项；
	URL：为切片设置一个超链接地址，在浏览器单击该切片图像会跳转到相对应的网址里；
	目标：指定窗口打开位置，是原窗口打开，还是在新窗口（blank）打开链接；
	信息文本：鼠标移到这个块时浏览器左下角显示的内容；
	Alt标记：图片的属性标记，鼠标移动到这块时鼠标旁的文本信息；
	尺寸定位：定位切片的坐标和长宽；
	切片背景类型：可自选背景色填充透明区域。

````
* 存储：存储方式选择“存储为Web所用格式”![](img/060.png)

````
1、保存格式选择HTML和图像，如果选择仅限图像，只输出图像。如果选择HTML，不会显示图片，设置为默认设置，切片为所有切片；
2、CMYK模式的图片在网页上是看不到的；
3、文件名改成英文，防止有电脑识别不出来。
````

* 切片工具属性栏   ![](img/061.png)
* 置为顶层：把所选薄片调到最前
*  前移一层：把所选薄片向前移动一个水平层
*  后移一层：把所选薄片向后移动一个水平层
*  置为底层： 把所选薄片调到最后
*  提升：可以将自动生成的切片提升为手动切片，对切片进行设置
*  划分：可以根据设定将切片水平垂直的继续划分成多个小切片，可以指定切片的个数或像素大小 ![](img/062.png)
*   对齐：切片过多可能会造成重叠，因此我们可以用对齐功能调整切片的次序
*  分布：可以让多个切片按照一定的分布规律进行排列（与选区类似），多选切片可以按Shift键
*  隐藏自动切片：可以将自动切片进行隐藏 ![](img/063.png)
*   设置切片选项：![](img/064.png) 也是进行切片选项的一种方法

-----
##### 吸管工具
----
* ![](img/065.png)
* 快捷键：I
* 吸管工具可以很好的帮助作图人员进行图像中颜色的吸取，以拾取点周围的平均色进行颜色取样且一次只能吸取一种颜色。
* 方法:点击吸管工具在想要吸取颜色的地方点击，前景色会变为所取颜色，然后就可以进行颜色填充，也可以通过颜色面板观察前景色背景色的变化及色值，吸取颜色作为当前的前景色。![](img/066.png)
* 技巧：

````
	1、按Alt键用吸管工具吸取颜色可定义为当前背景色；
	2、若希望填充颜色和图像上的某处颜色值一样，可直接选吸管工具点击某处进行取色，这样填充的颜色就和所取颜色相同；
	3、吸管工具也可以进行拷贝颜色的十六进制代码，可结合网页设计相关知识使用；
	如“fff6f0” “ color="#4d1980"f ”等
````
* 吸管工具属性栏  ![](img/067.png)
* 取样大小：以鼠标吸取点为中心，进行颜色运算，取样大小设置为取样点，则是准确根据鼠标定点为基准颜色，取样大小设置为3×3平均，则是吸取此点周围三个像素的平均色。![](img/068.png)
* 样本：吸取颜色的图层范围，有五个选项，选择比较多的是所有图层或当前图层；![](img/069.png)
* 注：“所有无调整图层”，是指排除掉所有调整层之后，最终叠加效果图里取样点的颜色。

-----
##### 3D材质吸管工具
----
* ![](img/070.png)
* 快捷键：I
* 3D材质吸管工具需要结合3D图像进行使用，主要可以用来查看当前3D图像所用的材质类型，也可以进行材质类型的改变；
* 方法:选择3D材质吸管工具，单击鼠标左键选取你需要的图像区域，即可在属性栏出现材质类型，也可以在属性窗口里面更换材质；
* 3D材质吸管工具属性栏   ![](img/071.png)
	* 材料油漆桶：用于材质的储存更换等
	* 载入所选材质：可以将当前所选材质存入到材料油漆桶中

-----
##### 颜色取样器工具
----
* ![](img/072.png)
* 快捷键：I
* 颜色取样器工具:可以对图像信息进行取样，帮助记录数值，可以用数值判断图片是否有颜色方面的问题，方便对比。颜色值会显示在信息面板上并自动编号，同样可以根据取样点的定义其色彩模式。
* 方法:选择颜色取样器工具在图像上所取位置单击，即可建立一个取样点，取样信息会在信息面板中保存并显示出来，图像中最多放置4个取样点，取样点位置可以按Ctrl键进行拖动，改变其位置，对于取样点可进行右击删除或者按住Alt键当鼠标变成剪刀形状点击删除或直接将其拖出画布。
* 颜色取样器工具属性栏 ![](img/073.png)
	* 清除：点击可以清除图像上所有的取样点


-----
##### 标尺工具
----
* ![](img/074.png)
* 快捷键：I
* 标尺工具:使用标尺工具可以精准的测量图像当中点或线之前的信息，也可以进行图像的修正；
* 方法:选择标尺工具在图像上单击确定一个起点，拖动出一条直线，在松开鼠标的位置确定终点，此时属性栏中会自动显示出坐标轴、宽度、高度、长度、角度等信息；双击起点可以拉出第二条标尺线，当我们的图像不是很正，可以沿着倾斜边画出一条直线，点击“拉直图层”，即可让倾斜的线变水平，同时图像角度会发生一定改变。
* 技巧：

````
1，若想修改拉出的标尺位置或长度方向，可以将鼠标放置在拉出的直线顶点或直线上进行调整；
2，按键盘上的Shift键拉动，可出现水平、垂直或45°线段；
````
* 标尺工具属性栏 ![](img/075.png)

````
	X：使用标尺工具拉出直线起点的X坐标轴数值；
	Y：使用标尺工具拉出直线起点的Y坐标轴数值；
	W：起点与终点拉出直线的宽度；
	H：起点与终点拉出直线的高度；
	A：使用标尺工具拉出的直线与水平线之间的角度；
	L1：标尺工具拉出的直线的长度；
	L2：标尺工具拉出的第二条直线的长度；
	
	使用测量比例：使用测量比例计算标尺数据，在图像中设置与比例单位数相等的指定像素数，创建之后可以记录结果；
	拉直图层：可用于修正歪图，让拉出的直线与水平线平行；
	清除：可清除标尺工具拉出的直线；

````  

-----
##### 注释工具
----
* ![](img/076.png)
* 快捷键：I
* 注释工具:在图像中添加文字注释及作者信息等内容，用于解释说明图像当中标注的位置信息，使其他人可以直观明了的看到注释信息，便于相关工作人员的修改。
* 方法:打开图像，选择注释工具，通过鼠标左键单击目标位置使其出现注释文本标志![](img/077.png)，即可在注释中添加文字加以说明，注释标志颜色可以根据属性栏设置修改，在作者栏中可以输入作者的名字，右击可进行删除注释。
注意：在保存的时候，保存PSD格式的文件，若保存JPG或者色彩文件，不会被保存；
* 注释工具属性栏![](img/078.png)

````
作者:用于输入用户或作者的名字
颜色：设置注释标志颜色
清除全部：清除图像当中的所有注释
显示或隐藏注释面板

````

-----
##### 计数工具
----
* ![](img/079.png)
* 123计数工具:可以统计图像中目标的个数，是一款数字计数工具，以数字标志的形式显示在画面当中，数目显示在属性栏的“计数”当中，用这款工具可以统计画面中一些重复使用的元素，是款不错的统计及标示工具。
* 方法:选择123计数工具，在目标位置左键单击，旁边即可出现一个数字，再下一个目标位置单击数字会自动按阿拉伯数字递增，并在上方属性栏中显示计数总数，若想改动数字点位置，可把鼠标放在数字的位置处出现三角光标提示，即可移动数字点。
* 技巧：

````
1，按Shift键移动数字点可进行水平/垂直方向的移动；
2，按Alt键左键单击数字点可删除数字段点；
3，保存计数文件保存为PSD格式；
4、键盘上下箭头可以调节标记与标签大小；

````
* 计数工具属性栏 ![](img/080.png)

````
	计数：显示计数总数；
	计数组：可以创建新的可见计数组，在计数组名称框内可以显示；
	关闭小眼睛图标可暂时隐藏数字点，删除当前所选计数组图标可删除计数组（至少有两组可以进行删除操作）； 
	清除：可以清除图像当中的所有计数点；
	拾色器：可以设置标签颜色；
	标记大小：设置标记的大小；
	标签大小 ： 设置标签的大小；

````

-----
##### 修复画笔工具组
----
* ![](img/081.png)
* 快捷键：J
* 切换方式其他方法：Shift+J/按Alt键点击修复画笔工具组
* 修复画笔工具组里的功能在PS图像处理方面发挥很大的作用，通过把图像像素的纹理、光照、阴影等与周围像素匹配，使其更好的融合在画面当中，可以很好的美化照片人物图像等，包括污点修复画笔工具、修复画笔工具、修补工具、内容感知移动工具、红眼工具；
##### 污点修复画笔工具
* 主要用于快速修复比较小的污点和瑕疵等，操作起来简单快捷，在有瑕疵的地方单击或划动即可修复；

##### 修复画笔工具
* 用于修复图像当中的缺陷，并能使修复的结果自然的与周围像素融合在一起，需要按下Alt键从图像中取样，定义一个与修复处相近的基准点，再进行修复操作；

##### 修补工具
* 先勾勒出一个需要修补的选区，会出现一个选区虚线框，移动鼠标时这个虚线框会跟着移动到适当的位置，比如与修补区相近的区域，单击即可。
#### 内容感知移动工具
* 用来移动图片中主体，可以随意放置到合适的位置。移动后的空隙位置会被智能修复。
##### 红眼工具
* 去掉照片中由于反光产生的红眼现象

* 方法：根据作图情况，选择修复画笔工具组相应的工具，结合工具属性栏相关设置进行调节不同的参数，达到不同的修复效果。
* 技巧：通常采用修图工具会影响到本来的图像效果，建议在作图前可以先复制一层进行复件的操作；


-----
##### 污点修复画笔工具
----
* ![](img/082.png)
* 快捷键：J
* 污点修复画笔工具：主要用于快速修复比较小的污点和瑕疵等，操作起来简单快捷，在有瑕疵的地方单击或划动即可修复，且PS会自动将修复区域与周围像素自然的融入到一起，不会留下特别明显的人为修复的感觉。
* 方法：选择污点修复画笔工具，调整画笔的大小及其他相关设置，在所要修复的区域单击或轻微划动即可迅速的去除小污点或瑕疵部分；
* 技巧

````
1，此工具不适合在较大面积中使用，在修复时细心的处理瑕疵部位，避免大片范围的一次性修复；
2，适当调节画笔大小，画笔越大，画面修复速率越快但是效果会越粗糙；
3、调节笔头大小可以通过键盘上的的左右中括号键【 】进行操作；

````

* 污点修复画笔工具属性栏：![](img/083.png)

````
画笔选取器：用于调整画笔的大小、硬度、间距、角度等（详解见第25节快速选择工具）；
模式：
	可以设置修复图像与源图像之间的混合方式
	替换：可以保留画笔描边边缘处的杂色、胶片颗粒和纹理。
	其他模式在讲图层混合模式时进行讲解；
类型:
	包括“近似匹配”、“创建纹理”、“内容识别”三项，
	近似匹配：在修复图像时，以画笔定位点为基准，根据周围像素内容来修复；
	创建纹理：以画笔定位点为基准创建一些相似的纹理，进行填充修复的区域；
	内容识别：软件默认类型，在修复图像时，根据修复区域的像素内容识别，并自动填充；
对所有图层取样：
	若选择该项，修复操作是从所有可见图层中进行，若不选择，则从当前图层中进行操作；


````

-----
##### 修复画笔工具
----
* ![](img/084.png)
* 快捷键：J
* 修复画笔工具:用于修复图像中的杂斑、污点等，且图像修复处将智能的与周围像素相互融合在一起，使修复后的图像看起来比较自然美观。
* 方法:选择修复画笔工具，按着Alt键配合鼠标点击从图像中取样，在需要修复的区域进行点击或者涂抹操作即可。
* 修复画笔工具属性栏:![](img/085.png)

````
	画笔选取器：调整画笔的大小样式硬度等；
	仿制源：在仿制源面板中，可以设置5个不同的仿制源，为修复比较复杂的图片；
	模式：图像的混合模式，替换--源点处图像替换修复处图像，视觉效果基本一致。
	源：选择取样，需要按Alt键在当前的图像中单击取样作为取样点修复图像；选择图案，可选择图案直接修复图像；
	对齐：未选择对齐，取样点始终不变，即使在操作过程中松开鼠标后再次修复依然会使用初始取样点修复图像；选择对齐会对图像像素连续取样，取样点位置会跟随光标的移动发生相应的变化，不会重复复制；
	样本：用于设置从指定的图层中进行数据取样。包括当前图层、当前和下方图层、所有图层;
	打开以在修复时忽略调整图层：用于忽略调整的图层，可在实际运用中尝试调整出的视觉效果;

````

-----
##### 修复工具
----
* 快捷键：J
* 方法	:修补工具在使用的过程中会创造选区，固定出一定的区域，选区可以进行加、减、交叉的运算，也可以进行填充颜色或羽化操作使修复边缘更加平滑；首先用鼠标绘制出需要修复部位的选区，之后在选区内单击拖动鼠标移动选区至目标区域，松开鼠标即可看到修复后的效果，
* 修补工具属性栏 ![](img/087.png)

````
	选区运算：新建、加、减、相交
	修补：
	正常：修复区域与目标区域混合融合在一起；
	内容识别：修复区域与周围内容混合融合在一起；
	
	源：选区内的像素会随着鼠标移动的目标位置的像素产生更改；
	目标：目标位置的图像将被更改为取样选区内的像素内容；
	透明：选区中的图像与目标位置图像产生透明叠加的效果，若不选择，被修补的区域与周围图像只在边缘上融合，内部图像纹理不变；
	使用图案：建立选区后，使用图案便可使用，否则默认灰色不可用，选定一种图像当中；

````

-----
##### 内容感知移动工具
----
* ![](img/088.png)
* 快捷键：J
* 通过内容感知移动工具，可以智能的将选区内的像素移动到目标位置，可以迅速的改变选区内容的位置，且移动后的边缘会自动的与周围环境融合在一起。
* 方法:选择内容感知移动工具，用鼠标选取需要移动的区域，可以选择属性栏中的模式：移动或扩展，将鼠标放进选区内部，即可进行移动扩展；
* 技巧:选区内部也可进行填充修复，快捷键：Shift+F5
* 内容感知移动工具属性栏![](img/089.png)

````
	选区运算:基本的选区运算，新建、加、减、相交；
	模式：包括移动和扩展；
	移动：将选区内容移动到目标位置，并智能的与周围环境融合在一起；
	扩展：将选区内容复制移动到目标位置，选区内容位置不变；
	适应：共五项可以选择，“非常严格”会严格的限定取样的周边范围，“非常松散”使取样周围的像素内容变得缓和，在更大的范围内进行取样。
	对所有图层取样:

````

-----
##### 红眼工具
----
* ![](img/090.png)
* 快捷键：J
* 红眼工具可以用于修饰数码照片的工具，可以移去用闪光灯拍摄的人物或动物照片中的红眼效果；
* 方法：选择红眼工具，可以通过鼠标直接点击需要修复的红眼区域；
* 红眼工具属性栏 ![](img/091.png)
	* 瞳孔大小：设置瞳孔指示的大小；
	* 变暗量：设置去除红眼后瞳孔变暗的程度，数值越大，则去除红眼后的瞳孔越暗；
![](img/092.png)

-----
##### 画笔工具

----

* 快捷键：B
* 画笔工具：用于绘图的工具，可以表现出多种形态的图案效果，是PS软件常用工具之一。
* 方法：选择画笔工具，可以通过属性栏调整画笔的软硬度及其他相关设置，完成后可直接通过点击，或鼠标拖动在画布中绘制；
* 安装笔刷方法：
	* 下载自己所要用的笔刷形态，打开画笔预设面板，通过齿轮设置按钮，找到“载入画笔”，载入你的笔刷文件即可，文件后缀名.abr，同样可以选择笔刷右击删除画笔；![](img/093.png)
	* 直接将下载下来的画笔拖入到PS软件当中，重新打开PS即可；
* 技巧

````
	打开画笔面板快捷键：F5
	鼠标右击也可以快速的打开画笔面板
	降低画笔的硬度：Shift+[   增大画笔的硬度：Shift+]
	按shift键绘制可绘制垂直或水平的线段
	] 放大画笔； [ 缩小画笔
   可以用画笔工具绘制立体球
````
* 画笔工具属性栏 ![](img/094.png)
	* 画笔预设选取器：可以调整画笔笔尖形态及画笔大小、软硬程度，也可以通过设置载入自己所需要的其他画笔笔刷；![](img/095.png)
	* 模式：定义绘图色与底图的混合模式；
	* 不透明度：设置画笔颜色整体的不透明度，取值范围1%-100%，1%达到完全透明的状态；
	* 流量：画笔颜色的浓度，单独笔触的不透明度；
	* 喷枪：鼠标点击不松手喷枪会不断喷出颜色，保持时间越长，颜色越深面积越大；
	画笔预设面板
* 画笔预设面板 ![](img/096.png)
* 画笔笔尖形状:包括笔尖形态，大小等；
	* 翻转X：改变画笔笔尖在X轴的方向；
	* 翻转Y：改变画笔笔尖在Y轴的方向；![](img/097.png)
	* 角度：椭圆的倾斜角度，可以通过拖动滑块或者输入数值进行调节；
	* 	圆度：椭圆的长短直径的比例设置，可以通过拖动滑块或者输入数值进行调节，100%时是正圆，0%时椭圆外形最扁平；
	* 硬度：画笔边缘的软硬程度，可以决定画笔边缘的过渡效果，数值越小，画笔边缘越模糊；
	* 间距：控制画笔笔尖之间的距离，数值越大，间距越大，反之越小；

* 形状动态![](img/098.png)
	* 大小抖动：控制画笔大小抖动的变化程度；![](img/099.png)
	* 控制:确定画笔笔迹变化的方式；![](img/100.png)
	* 渐隐：逐渐消隐，可以在后面的数值输入框中输入一个数值，以确定尺寸波动的步长值，如图所示：![](img/101.png)（“钢笔压力”、“钢笔斜度”、“光笔轮”3种方式都需要有压感笔支持） 
	* 最小直径：画笔的最小尺寸，数值越小，发生波动变化越大，反之越小；
	* 倾斜缩放比例：当选择“控制”下方的“钢笔斜度”，该项才可使用；
	* 角度抖动：控制画笔笔迹的角度变化，数值设置越大，波动的幅度也越大；![](img/102.png)
	* 圆度抖动:控制画笔笔迹圆度的变化，数值越大，波动的幅度也越大；![](img/103.png)
	* 最小圆度：圆度抖动打开之后才可使用，控制画笔笔迹的最小圆度，百分数越大，发生波动的幅度相应变小；
	* 翻转X抖动、翻转Y抖动：设置画笔笔尖在X轴、Y轴的方向；
	* 画笔投影：给画笔笔迹加轻微投影，并不明显；
* 散步 ![](img/104.png)

````
	散步：控制画笔笔迹位置分布及偏离程度，百分数也大，偏离程度越大；
	两轴：画点在X和Y两个轴向上发生分散。   
	控制：控制画笔笔迹的分散方式；
	数量：设置分散画笔笔迹的数量，数值越大，笔迹越多；
	数量抖动：分散画笔笔迹的变化程度，百分数越大，笔迹数量的波动幅度越大； 

````
* 纹理:设置画笔与图案纹理相混合的方式；![](img/105.png)

````
	纹理调板：单击纹理调板，可以选择所需要的纹理图案；
	反相：取反相纹理，图案中的颜色进行反相处理，亮区变暗，暗区变亮；
	缩放：图案的大小缩放比例；
	亮度：纹理的明暗程度；
	对比度：纹理明暗的对比度；
	为每个笔尖设置纹理：把选择的纹理单独应用于画笔的每个笔迹，而不是应用于整体，只有打开，才能设置最小深度和深度抖动；
	模式：确定纹理和画笔的混合模式；
	深度：设置纹理显示的深度，数值越大，纹理越明显；
	最小深度：控制纹理的最小深度；
	深度抖动：设定深度的变化程度； 
````
* 双重画笔

````
	可以设置两种画笔的混合效果；
	模式：设定两种画笔的混合模式；
	大小：控制叠加画笔的大小；
	间距：设定叠加画笔的间距；
	散步：设定叠加画笔笔尖的分散程度；
	数量：设定叠加画笔笔迹的数目；

````

* 颜色动态:用于设置画笔在绘制过程中颜色的动态变化；![](img/106.png)

````
	前景/背景抖动：设置画笔颜色在前景色和背景色之间的变化程度，数值越大，越接近于背景色，反之越接近于前景色；
	色相抖动：画笔笔迹颜色色相的变化程度，数值越大，越接近于背景色色相，反之越接近于前景色色相；
	饱和度抖动：设置画笔笔迹颜色的饱和度变化；
	亮度抖动：设置画笔笔迹颜色亮度的变化程度；
	纯度：控制画笔纯度；

````
* 传递：![](img/107.png)

````
	不透明度抖动：控制画笔笔迹不透明度的变化方式，随机性比较大；
	流量抖动：控制画笔颜色的浓度变化的方式，数值越大，效果越明显；
	湿度抖动、混合都懂：只有在混合器画笔工具中才能使用；
````

* 画笔笔势:毛笔笔刷效果会比较明显；![](img/108.png) ![](img/109.png)

````
	倾斜X、倾斜Y：画笔根据X、Y轴进行倾斜；
	旋转：根据画笔笔芯进行旋转；
	压力：根据压力数值设置的不同达到不同的效果；

````
* 杂色:在笔刷的边缘产生杂边，和硬度有一定关系，硬度越小，杂色越明显；![](img/110.png)
* 湿边:笔迹边缘颜色加深，有水彩效果感觉；![](img/111.png)
* 平滑:在快速绘图过程中，使绘制的图像边缘较平滑；

-----
##### 铅笔工具
----

* ![](img/112.png)
* 快捷键：B
* 铅笔工具可以绘制出的线条是硬的、有棱角的，曲线或斜线都会根据像素格子产生明显的锯齿，与硬度值的设置无关，颜色设置为前景色；
* 方法：选择铅笔工具，可直接设置笔尖的大小，快捷键：缩小【、放大】，也可以直接通过画笔面板调节，选择铅笔形态，即可绘制；
* 技巧：
	* 当画笔笔触为1像素时，会形成一个小方块，可以用小方块绘制像素图形；
	* 在绘制过程中按Alt+Shift键能迅速转换为变成颜色取样器工具，加鼠标右键不松手可以改变前景色颜色；![](img/113.png)

* 铅笔工具属性栏![](img/114.png)
	* 画笔、模式、不透明度与画笔相同，可通过画笔笔记和视频了解；
	* 自动抹除：勾选自动抹除后，当第一次使用铅笔工具绘图时，颜色直接使用前景色，接着在此前景色基础上绘制，会填充为背景色；

-----
##### 颜色替换工具
----

* ![](img/115.png)
* 快捷键：B
* 颜色替换工具:运用此工具可以很好的用前景色替换图像的颜色，并且能够保留原有的材质纹理与明暗基调；
* 方法:确定前景色后，鼠标起点的像素颜色为基准色，调整相关的属性设置，在图像中需要更改颜色的地方涂抹即可；
* 颜色替换工具属性栏![](img/116.png)

````
画笔预设
模式：用于选择混合模式
包括色相、饱和度、颜色、明度

取样：
连续：以鼠标所在的位置像素颜色为基准对颜色连续取样； 
一次：每次操作鼠标不松手只替换鼠标点击的区域目标颜色；
背景色板：替换与背景色颜色相同或相似的像素；
限制：
不连续：替换出现在鼠标点击下任何位置的样本颜色；
连续：替换与鼠标点击颜色邻近的颜色；
查找边缘：主要替换在色彩区域间的边缘部分，更好的保留形状边缘的锐化程度；
容差：设置1-100之间的整数，数值越大，选取颜色范围越广；
消除锯齿：使边缘变得平滑；
该工具不适用于“位图”“索引”“多通道”颜色模式的图像；

````

-----
##### 混合器画笔工具

----
* ![](img/117.png)
* 快捷键：B
* 混合器画笔工具可以模拟真实的绘画技术，可以混合画布上的颜色，也可以调整不同的绘画湿度，绘制出艺术画的效果；
* 方法:选择混合器画笔工具，调整画笔的笔触、颜色、潮湿度等，即可开始绘制，在绘制的过程中，可以不断的调整笔触形态，已达到更好的效果；
* 技巧
	* 按Alt键可以选取颜色并载入；
	* 按下Ctrl+Alt+Shift的同时，按下鼠标右键，也可选取颜色；
* 混合器画笔工具属性栏![](img/118.png)
	* 画笔库：调节画笔笔刷大小等；
	* 当前画笔载入：![](img/119.png)显示出前景色的颜色，点击可以改变颜色色值，也可以吸取画面当中的颜色；点击小三角，出现载入画笔、清理画笔、只载入纯色；![](img/120.png)
	* 每次描边后载入画笔：控制每一笔绘制之后画笔是否自动载入；
	* 每次描边后清理画笔：选择之后系统将之前载入的画笔清除；
	* 有用的混和画笔组合：用于设置不同混合预设效果，包括4组：干燥、湿润、潮湿、非常潮湿等，当选择其中某一种时，右边的4个数值会自动为预设值；![](img/121.png)
	* 潮湿：设置从画布拾取的油彩量，设置的值越大，画在画布上的色彩越淡；
	* 载入：设置画笔上的油彩量；
	* 混合：设置颜色混合的比例，当潮湿为0时，该选项不能用；
	* 流量：设置描边的流动速率；
	* 启用喷枪样式的建立效果：当鼠标点击画布画笔停留在某一位置时，会一直有颜色喷出来的感觉；
-----
##### 仿制图章工具

----
* ![](img/122.png)
* 快捷键：S
* 仿制图章工具也可以对图像进行修复，能够选择取样点，根据涂抹的范围复制全部或者部分到一个新的图像中，复制出来的图像与原图是完全一样的；
* 方法：选择仿制图章工具，按着Alt键，用鼠标在图像中通过点击定义取样点，在修复目标处拖动涂抹即可复制新的图像{像画笔一样也可以选择笔触形态}；
* 仿制图章工具属性栏![](img/123.png)
	* 对齐：选择对齐松开鼠标后，当前的取样点不会丢失，取样点会根据你鼠标的移动产生变化，若取消选择，则每次松开鼠标重新绘制，都将应用初始取样点；
其他属性不再做解释，可参考之前学习的内容；

-----
##### 图案图章工具

----
* ![](img/124.png)
* 快捷键：S
* 图章工具可以选用特定图案进行填充，也可以先自行定义图案进行填充；
* 方法：选择图案图章工具，设置好属性栏相关参数及图案，在画布上直接进行涂抹就可以出现设定的图案效果，绘制出的图案会重复排列。
* 图案图章工具属性栏![](img/125.png)
	* 印象派效果：勾选后，图像会产生印象派绘画效果；
	* 可以利用图案进行绘画，可以从图案库中选择图案或者自己创建图案；

-----
##### 历史记录画笔工具

----
* ![](img/126.png)
* 快捷键：Y
* 历史记录画笔工具能够记录图像中每一步的操作，还原操作图像本来的状态，也可以将部分图像恢复到被指定的某一步操作；
* 方法：在对于图像调整之后，选中历史记录画笔工具，调整合适的笔刷及其他属性，进行擦拭或者涂抹，就可恢复原来的状态；
* 历史记录画笔工具属性栏![](img/127.png)

-----
##### 历史记录艺术画笔工具认识

----
* ![](img/128.png)
* 快捷键：Y
* 历史记录艺术画笔工具能恢复被修改的图片，也可以对图像进行特殊的效果处理，创建不同的色彩和艺术风格；
* 方法:若想恢复图片本来的效果并带有艺术效果的感觉，可以选中修改过的图片，选中历史记录艺术画笔工具，调整其笔刷、模式、不透明度、样式等属性，即可在画面当中进行绘制；
* 历史记录艺术画笔工具属性栏![](img/129.png)
	* 样式：用于控制画笔绘制的形式；![](img/130.png)
	* 绷紧短效果:![](img/131.png)
	* 绷紧中效果：![](img/132.png)
	* 绷紧长效果:![](img/133.png)
	* 松散中等效果：![](img/134.png)
	* 松散长效果：![](img/135.png)
	* 轻涂效果：![](img/136.png)
	* 绷紧卷曲效果:![](img/137.png)
	* 绷紧卷曲长效果：![](img/138.png)
	* 松散卷曲：![](img/139.png)
	* 松散卷曲长：![](img/140.png)

	* 区域：指定绘画描边所覆盖的范围，数值越大，覆盖的区域越大，数量越多，数值设置范围为0-500间的整数；
	* 容差：控制绘画描边的区域，容差越低，选取的颜色范围越小；

-----
##### 橡皮擦工具
----
* ![](img/141.png)
* 快捷键：E
* 橡皮擦工具:可以用来擦除画面中不需要的区域，也可以达到修复画面图像的效果；
* 方法：选择橡皮擦工具，可直接对画面进行操作，适当的调整画笔及其他参数设置；
* 技巧：
	1. 在擦拭的过程中，按Alt键再被擦拭区域涂抹可以恢复图像（类似于历史记录画笔工具）；
	2. 若图像为背景图层，则擦去的部分会被背景色所填充，若图像为普通图层，则擦掉的部分变为透明区域；
* 橡皮擦工具属性栏![](img/142.png)
	1. 画笔：改变画笔的笔刷样式等；
	2. 模式：包括画笔、铅笔、块；![](img/143.png)
	3. 画笔：可以改变笔刷软硬样式等；
	4. 铅笔：边缘比较生硬；
	5. 块：橡皮擦擦拭的时候会显示出方块的状态，选择块模式，画笔是不能用的状态；
	6. 不透明度：定义擦除强度；
	7. 流量：指定流动速率；
	8. 喷枪：在画笔模式中，单击喷枪按钮将画笔用作喷枪；
	9. 抹到历史记录：抹除图像以存储的状态或快照，若勾选，则橡皮擦工具就有历史画笔工具的效果，能使改变后的图片恢复为原来的样子；

-----
##### 背景橡皮擦工具
----
* ![](img/144.png)
* 快捷键：E
* 背景橡皮擦工具也是擦除工具，在擦除的时候更加智能化一些；
* 方法：选择背景橡皮擦工具，在需要擦除的部位进行涂抹，注意将十字擦头放入被修改的区域，防止影响其他颜色；
* 技巧：
	1. 若擦拭的图像为背景图像，则擦拭后自动转化为普通图层；
	2. 十字圈，擦物体边缘的时候，即使画笔覆盖了物体及背景，只要圈里的十字在背景的颜色上，背景会就会被删除掉而不影响主体物；
* 背景橡皮擦工具属性栏![](img/145.png)

````
	取样：连续、一次、背景色板；
	连续：取样点随着鼠标移动连续取样抹除，如果按着鼠标不放的情况下，鼠标中心所接触的图像颜色基本都可以被擦拭；
	一次：以鼠标每一次点击取样的颜色为基准色或近似色进行抹除，在未松开鼠标之前，其他颜色将不被抹除；
	背景色板：将图像中与背景色一样或相似的颜色进行抹除；
	限制：不连续、连续、查找边缘；
	不连续：可以擦除画笔移动范围内与样本颜色相近没有连续起来的颜色；
	连续：将像素连续起来的位置可以进行擦除；
	查找边缘：保留边缘效果进行擦除颜色；
	容差：选取擦除图像的颜色精确度；值越大，擦除颜色范围越大，容差值越小，擦除颜色范围越小；
	保护前景色：勾选后，橡皮擦在擦拭的过程中可以保护与前景色相同的颜色不会被擦除，若不想删除图像中的某种颜色，把它吸取设置为前景色就可以了；

````

-----
##### 魔术橡皮擦工具
----

* ![](img/146.png)
* 快捷键：E
* 魔术橡皮擦工具可以通过设定范围将像素颜色进行区域型擦除，擦除的部分将以透明的状态呈现出来；
* 方法:魔术橡皮擦工具通过设置容差值来擦除背景，通过鼠标单击取样点，取样容差范围内的像素即成为透明。
* 技巧:
	1. 魔术橡皮擦在用于初始建立的背景时，背景会自动转为图层；
	2. 对于背景比较复杂的图像，若使用魔术橡皮擦擦除，会产生凌乱的色块效果，不建议使用；
* 魔术橡皮擦工具属性栏![](img/147.png)

````
	容差：设置颜色的取值范围，容差越大，取值范围越宽，擦除面积越大；
	消除锯齿：魔术橡皮擦擦拭之后会有明显的锯齿感觉，此功能可以在使擦除之后的主体边缘锯齿变弱变小；
	连续：勾选后，擦除在容差选择范围内连续的颜色；不勾选时，会擦除图像内所有容差值选择的范围颜色；

````

-----
##### 渐变工具
----

* ![](img/148.png)
* 快捷键：G
* 渐变工具可以创建多种颜色的混合状态，利用渐变工具可以为图像填充比较融合的过渡的颜色效果，总共包含五种不同的渐变类型：线性渐变、径向渐变、角度渐变、对称渐变、菱形渐变；
* 方法：选择渐变工具，可以调整前景色背景色，也可以直接打开渐变编辑器对色标不透明度的定位等作调整，选择渐变类型，可以在画面中利用选区固定区域，以鼠标落点为渐变起点的位置，拖移定义终点的位置，实现从一种颜色到另一种颜色的过渡变化；
* 技巧：
	* 如果在画面中没有定义固定选区，则渐变色会填充到当前整个图层上；如果有选区，则会填充到选区当中；
	* 很多比较立体的图案效果及背景效果的打造都可以借用渐变工具；
* 渐变工具属性栏：![](img/149.png)
* 渐变编辑器:![](img/150.png)
* 线性渐变：从起点到终点有直线渐变的效果；![](img/151.png)
* 径向渐变：以起点为圆心，起点到终点的距离为半径，创建圆形渐变的效果；![](img/152.png)
* 角度渐变：以起点为圆心，以拖动光标的角度线为源进行360度旋转的锥形渐变效果；![](img/153.png)
* 对称渐变：以光标落点处与拖动方向相垂直的直线为轴，进行对称渐变；![](img/154.png)
* 菱形渐变：创建以光标落点处为圆心，拖动光标的距离为半径的菱形渐变效果；![](img/155.png)
* 模式：用来设置渐变色与下面图像的混合模式；
* 不透明度：设置渐变效果的不透明度；
* 反向：颠倒渐变颜色设置的顺序；
* 仿色：使渐变颜色之间的过渡更加平滑柔和；
* 透明区域：默认勾选，勾选后“渐变编辑器”窗口中不透明度的设定才会生效，“否则，即使透明度色标设置有一定的透明度，也做不出透明的效果；
* 案例练习：![](img/156.png)
* 渐变工具可以做：立体球
* 注意：渐变工具要固定选区，否则整个画布会渐变

-----
##### 模糊工具
----

* ![](img/157.png)
* 无快捷键
* 模糊工具可以对图像进行模糊处理，降低像素之间的反差，突出主体部分，一般用于对图像的微调；
* 方法：打开图像，直接选择模糊工具，在需要进行模糊的图像位置左单击开始涂抹，根据实际情况调整画笔样式及模糊强度等属性，再图像位置涂抹次数越多越模糊；
* 技巧：
	* 模糊工具可以对人像皱纹部位进行微调；
	* 设计人员经常会使用模糊工具做场景模糊的效果；
	* 注意把握，使用过多容易使图像失真；
* 模糊工具属性栏 ![](img/158.png)
* 强度对比：![](img/159.png)
* 场景调整前：![](img/160.png)
* 场景调整后：![](img/161.png)

-----
##### 锐化工具
----
* ![](img/162.png)
* 使用锐化工具可以使模糊的图像越来越清晰，像素对比更加强烈，多用于提高图像的清晰度，与模糊工具产生相反的效果；
* 方法:选择锐化工具，在图像需要锐化部分进行涂抹；
* 技巧：锐化强度适度调节，不要太大，以免失真，出现杂点像素；
* 锐化工具属性栏：![](img/163.png)
* 强度：调节锐化的程度；![](img/164.png)

-----
##### 涂抹工具
----
* ![](img/165.png)
* 涂抹工具使画面有涂抹的效果，可根据边缘位置的颜色进行拖动涂抹，鼠标可控制涂抹的强度与方向，常用于修正物体的轮廓，制作背景、火苗、毛发丝等等；
* 方法：选择涂抹工具，调整合适的画笔样式及软硬程度，强度可在作图过程中做适当的调整，用鼠标控制涂抹的对象及方向；
* 技巧：涂抹时强度在最初不要设置的过于强烈，否则涂抹粗来的画面会比较假；
* 涂抹工具属性栏：![](img/166.png)
* 手指绘画：未勾选时，可以进行每次描边的起点处所指的颜色进行涂抹，勾选时，可使用每个描边起点处的前景色进行涂抹。
* 案例显示：![](img/167.png)
 
-----
##### 减淡工具
----
* ![](img/168.png)
* 快捷键：O
* 减淡工具可以使图片颜色减淡，画面有提亮的效果，能够增强图片的质感与美感，减淡工具的范围包括暗调、中间调、高光，在作图的过程中可以为素材图片定义三个层次，即黑白灰，对应不同的层次可以选择不同的范围进行操纵；
* 方法：将所要提亮的素材拖入到画布当中，选择减淡工具，调整好范围层及曝光度，可以进行操作；
* 技巧
	* 高光：减淡后饱和度较高；
	* 中间调：减淡后饱和度较柔和；
	* 阴影：减淡后饱和度较低，反复涂抹后，颜色会趋于白色；
* 减淡工具属性栏：![](img/169.png)
	* 曝光度:调整图像处理的曝光程度，曝光值建议设置偏小；
	* 保护色调：防止颜色产生色相的偏移；
* 案例显示：![](img/170.png)

-----
##### 加深工具
----
* ![](img/171.png)
* 快捷键：O
* 加深工具与减淡工具相反，可以将图像变暗，颜色加深；加深工具的范围包括暗调、中间调、高光，在作图的过程中可以为素材图片定义三个层次，即黑白灰，对应不同的层次可以选择不同的范围进行操纵；
* 方法:将所要修改的素材拖入到画布当中，选择加深工具，调整好范围层及曝光度，可以进行操作；
* 技巧
	* 阴影：饱和度比较高；
	* 中间调：饱和度较柔和；
	* 高光：呈灰色，饱和度较低，曝光度越高，灰色越暗；
* 加深工具属性栏![](img/172.png)
	* 曝光度:调整图像处理的曝光程度，曝光值建议设置偏小；
	* 保护色调：防止颜色产生色相的偏移；
* 案例显示：![](img/173.png)

-----
##### 海绵工具
----
* ![](img/174.png)
* 快捷键：O
* 海绵工具可以加深或降低（去除）图像的色彩饱和度，包括降低饱和度(去色)和饱和两个模式，但是海绵工具不能应用于索引颜色和位图颜色模式 ，如果在灰度模式下操作将会产生增加或减少灰度对比度的效果。    
* 方法:选择海绵工具，设置画笔选项，选择降低饱和度/饱和，调整流量大小（流量越大效果越明显）即可；
* 技巧
	* 降低饱和度和饱和可以互补，当饱和度过低，可以切换到饱和模式增加色彩饱和度（无法调整已经完全呈现灰度的像素）；
	* 色彩饱和度越高，表现越鲜明，饱和度较低，则较暗淡；
	* 开启喷枪方式可产生持续的操作效果。
* 海绵工具属性栏![](img/175.png)
* 模式：
	* 降低饱和度：稀释颜色的饱和度 
	* 饱和：增强颜色的饱和度 
* 流量：相当于颜料的流出速度
* 自然饱和度：可以默认勾选，让色彩过渡的更自然；
* 案例显示：![](img/176.png)


-----
##### 钢笔工具
----
* ![](img/177.png)
* 钢笔工具是我们最常用的工具之一，其功能也是非常强大，可以用来抠图、绘画，其可以绘制出封闭或不封闭的矢量图形，称为路径，我们使用钢笔工具可以绘制出直线也可以绘制平滑的曲线，在线段上有一定的控制节点，我们可以通过节点调节自己需要的线条。
* 方法:选择钢笔工具，在画布中可以随意确定一个点，鼠标左单击，在另外一个区域点击一个点，两点之间就会有线段相连，若在下一个位置左单击不松开鼠标继续拖动锚点将会出现平滑的曲线，如图，小节点我们可以称锚点，通过调节锚点修改平滑程度；![](img/178.png)
* 绘制封闭路径：多次绘制线段之后将鼠标末点与起点相连，在闭合时，将鼠标箭头紧挨着路径起点，当出现一个小圆圈时，单击鼠标，可以将路径闭合；![](img/179.png)
* 绘制开放路径：多次绘制将要完成时，可以直接单击工具栏中的钢笔工具按钮结束绘制，也可以按Ctrl键在画布任意位置单击；![](img/180.png)
* 技巧：
	* 在绘制过程中按Shift键可以绘制出45°、90°或水平、垂直的线段，如图；![](img/181.png)
	* 若为勾选自动添加/删除，可以在绘制中通过鼠标右击路径上某点，在弹出的菜单中选择添加或删除锚点选项； 
* 钢笔工具属性栏:![](img/182.png)
	* 路径模式
	* 建立
	* 选区：将所绘制的路径转化为选区，且可以设置羽化值；![](img/183.png)
	* 蒙版：将所绘制的路径为原来图像添加蒙版操作；![](img/184.png)
	* 形状：将所绘制的路径转化为形状，即可填充颜色等作形状的相关操作；
	* 路径操作：![](img/185.png)
	* 合并形状：可多次绘制路径，且所画路径自动合为同一图层；![](img/186.png)
	* 减去顶层形状：将再绘制的路径与原路径重叠的部分减去；![](img/187.png)
	* 与形状区域相交：将再绘制的路径与原路径相交的部分保留；![](img/188.png)
	* 排除重叠形状：将在绘制的路径与原路径重叠的部分删除；![](img/189.png)
	* 合并形状组件：可以将多条路径合并为一条路径![](img/190.png)
	* 路径对齐方式：配合路径选择工具可以进行对齐操作（详情见路径选择工具）；
	* 路径排列方式：配合路径选择工具可以进行对齐操作（详情见路径选择工具）；
	* 橡皮带：勾选此选项，可以更直观的看到下一个锚点定义出的路径线段效果；
	* 自动添加/删除：在绘制过程中通过单击线段上的任意一个位置可以对绘制出的路径上的锚点进行添加，通过单击原有的锚点可以将其删除，可以调节锚点达到我们所期望的线段效果；
* ![](img/191.png)
	* 形状模式:选择形状模式在绘制时不仅产生路径效果，同时在图层中创建了一个形状图层，我们可以通过属性改变形状的样式等；
	* 填充：可以将形状填充为所选颜色，包括颜色填充、渐变填充及图案填充；![](img/192.png)
	* 描边：描边也可以选择不一样的填充效果，包括颜色填充、渐变填充及图案填充；![](img/193.png)
	* 其次，描边可以更改粗细；![](img/194.png)
	* 描边选项：可以调节描边的类型，虚线/实线，也快以调节边角及端点的平滑程度，及虚线线段之间的间隔程度；![](img/195.png),如图：![](img/196.png)
	* 新建形状：可以在不改变原有任意一个形状的情况下，绘制一个新的形状



























 
















 











 








































  









 
	





















 

