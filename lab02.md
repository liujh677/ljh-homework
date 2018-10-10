# ***如何制作平台游戏***

* 准备工作：安装construct2(https://www.scirra.com/tutorials/top)
* 游戏说明：通过射击怪物获取分数的游戏


<font size="4">

 
* &nbsp; 启动construct2，单击 File 按钮，然后选择 New  

![](https://www.scirra.com/images/articles/filenew.png)





* &nbsp; 您将看到“模板或示例”对话框，选择 New empty project ,点击 Open

![](https://www.scirra.com/images/articles/newprojdialog65.png)

* &nbsp; 然后会看到以下界面：

![](https://indienova.com/farm/blog/2017/07/10424-1499432374.png)

* &nbsp; 首先，让我们为游戏设置一个好看的背景，比如：

![](https://www.scirra.com/images/articles/bg.png)

请先将它保存到你电脑的某处，以待备用


* &nbsp; 然后左键双击击上图数字2部分的空白处,会跳出如下界面：

![](data:image/png;base64,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)

双击红圈中的 Tiled Background 表示将其插入，这时鼠标会变成一个“十字”，这时你只需用“十字”点击一下（Layout 1中）任意的空白部分即可

* 此时会跳出编辑页面

![](https://www.scirra.com/images/articles/loadtexturefromfile.png)

点击 Load ，随后在电脑上找到自己刚才保存的背景图，双击图片即可,然后你应该会看到以下界面：

![](https://github.com/liujh677/ljh-homework/blob/gh-pages/001.png?raw=true)

然后关闭此编辑页面（如果系统提示您，请务必保存！）

* 左键点击一下背景，然后在左边的 Properties 处设置背景的大小和位置,将其位置设置为0,0（布局的左上角），并将其大小设置为1280,1024（布局的大小）



![](https://www.scirra.com/images/articles/tiledproperties.png)

这样，背景就做好了！（你可以点击左上角的RUN图标预览一下你的背景）


* 然后，由于我们玩游戏时需要用到鼠标和键盘进行操作，所以类似于插入背景，我们需要将Input中的Mouse和Keyboard依次插入(请自己尝试一下)


* 接下来，就该添加人物，特效，道具等图案了，请先将以下图片保存到你的电脑中：

玩家：


![](https://www.scirra.com/images/articles/player.png)

怪物：

![](https://www.scirra.com/images/articles/monster.png)

子弹：

![](https://www.scirra.com/images/articles/Bullet.png)

爆炸特效：

![](https://www.scirra.com/images/articles/explode.png)


然后同样类似于插入背景，将这四个东西依次插入，只不过此次应该双击Sprite：

![](https://github.com/liujh677/ljh-homework/blob/master/002.png?raw=true)

然后同样点击Load，找到保存的图片后双击,再按X关闭即可，最终效果应如图：

![](https://github.com/liujh677/ljh-homework/blob/master/003.png?raw=true)

* 这些对象将被称为Sprite，Sprite2，Sprite3和Sprite4。这样容易将他们混淆。你可以根据需要将它们重命名为Player，Monster，Bullet和Explosion。您可以通过选择对象，然后更改属性栏中的Name属性来执行此操作：

![](https://www.scirra.com/images/articles/objectname.png)

* 然后，我们需要为这些物体添加必要的行为以让我们能够完成游戏操作


其中，Construct 2有这些行为;

- 8方向运动。这使您可以使用箭头键移动对象。它会很好地适应玩家的运动。
- 子弹运动。这只是以当前角度向前移动一个物体。它对玩家的子弹很有用。尽管有这个名字，它也可以很好地移动怪物 - 因为所有的移动都是以某种速度向前移动物体。
- 滚动到。这使得屏幕在移动时跟随对象（也称为滚动）。这对玩家有用。
- 绑定到布局。这将停止一个物体离开布局区域。这对玩家也很有用，所以他们不能在游戏区域外游荡！
- 破坏外部布局。而不是停止离开布局区域的对象，如果它停止，则会破坏它。它对我们的子弹很有用。没有它，子弹将永远飞离屏幕，总是占用一点内存和处理能力。相反，我们应该在他们离开布局后销毁子弹。
- 淡出。这逐渐使物体淡出，我们将用于爆炸。
* 等等

让我们将以上行为及其他必要行为添加到需要它们的对象中

* 如何添加行为：

1.让我们为玩家添加8方向移动行为。单击Player以选择它。在属性栏中，请注意“ 行为”类别。单击“ 添加/编辑”。播放器的“行为”对话框将打开。

![](https://www.scirra.com/images/articles/openbehaviors.png)

点击绿色加号“添加行为”，双击“八方向移动”以添加它

再次执行相同操作，这次添加Scroll To行为，使屏幕跟随播放器，以及"绑定到布局"行为，以使它们保持在布局中。行为对话框现在应如下所示：

![](https://www.scirra.com/images/articles/playerbehaviors_2.png)

这时你可以关闭行为对话框，尝试运行游戏（记得RUN键吗？）

2.我们可以通过相同的方法向其他对象添加行为 - 选择它，单击添加/编辑以打开行为对话框，并添加一些行为。让我们添加其他行为：

- 将Bullet移动和Destroy外部布局添加到Bullet对象（没有惊喜）
- 将子弹移动添加到Monster对象（因为它也向前移动）
- 将Fade行为添加到Explosion对象（因此它逐渐消失）出现后）。默认情况下，淡化行为也会在淡出淡出后破坏对象，这也使我们不必担心隐藏的爆炸对象会堵塞游戏。

3.如果你运行游戏，你可能会注意到唯一不同的是，你可以看到任何怪物突然快速射击。让我们慢慢放松一下。选择Monster对象。请注意，自从我们添加了一个行为后，属性栏中出现了一些额外的属性：

![](https://www.scirra.com/images/articles/bulletproperties.png)

这允许我们调整行为的工作方式。将速度从400更改为80（这是以每秒行进的像素数为单位）。

同样，将Bullet对象的速度更改为600，将Explosion对象的淡入淡出行为的淡出时间更改为0.5（即半秒）。

4.创造一些更多的怪物

按住控件，单击并拖动Monster对象。你会注意到它产生了另一个实例。这只是Monster 对象类型的另一个对象。

使用control + drag，创建7或8个新怪物。不要放置太靠近玩家，否则他们可能会立即死亡！如果有帮助，您可以使用控制+鼠标滚轮向下缩小，并将它们分布在整个布局上。你最终会得到类似的东西。

![](https://www.scirra.com/images/articles/severalghosts.png)




* 接下来，应该给游戏添加事件了，这一大步操作可以在上栏的Event sheet中进行：

![](https://github.com/liujh677/ljh-homework/blob/master/004.png?raw=true)

* 双击Event sheet中的任意的空白部分,你会看到跳出的Add event页面,双击system：

![](https://www.scirra.com/images/articles/newevent_2.png)

再双击“every tick”以将其插入

![](https://www.scirra.com/images/articles/everytickcnd.png)


应该会变成这样：

![](https://www.scirra.com/images/articles/everytickempty.png)

然后点击图片中的add action（注意不是add event！）

点击player

![](https://www.scirra.com/images/articles/addactiondlg.png)

与添加事件一样，我们有相同的对象列表可供选择，但这次是添加操作。尽量不要在添加条件和添加操作之间感到困惑！如图所示，双击该player的对象，因为这是我们要看看鼠标的玩家。将显示Player对象中可用的操作列表：

![](https://www.scirra.com/images/articles/playersetanglepos.png)

将跳出以下页面：

![](https://www.scirra.com/images/articles/setangleposparams.png)

construct2现在需要知道X和Y坐标以指向玩家：我们想要将角度设置为鼠标位置。Mouse对象可以提供此功能。输入Mouse.X为X，和Mouse.Y为ÿ。

* 这是你设置的第一个事件！尝试运行一下吧

* 接下来的操作也是依葫芦画瓢：

1.让玩家开枪

条件：鼠标 - > 单击 - >左键单击（默认值）
操作：播放器 - >生成另一个对象 - >对于对象，选择Bullet对象。对于Layer，放1（“Main”层是第1层 - 记住Construct 2从零开始计数）。将图像点保留为0。

您的活动现在应该如下所示：

![](https://www.scirra.com/images/articles/spawnbullet1.png)

2.让子弹杀死怪物

添加以下事件：

条件：子弹 - > 与另一个物体碰撞 - >选择怪物。
动作：怪物 - > 摧毁
动作：子弹 - >生成另一个对象 - > 爆炸，第1层
动作：子弹 - > 摧毁

3.爆炸效果

我们会发现旁边有很大的黑边，为了解决这个问题:单击右下角的对象栏中的Explosion对象，或单击项目栏（带有图层栏的选项卡）。其属性显示在左侧的属性栏中。在底部，将其Blend mode属性设置为Additive。

现在再试一次游戏。效果是否如下了：

![](https://www.scirra.com/images/articles/explosionadditive.png)

4.使怪物变得更聪明

现在，怪物只是偏离布局向右。让我们让它们变得更有趣。首先，让我们以随机的角度开始它们。

条件：系统 - > 开始布局
动作：怪物 - > 设置角度 - >随机（360）

![](https://www.scirra.com/images/articles/ghostshooterevent4.png)

当他们离开布局时，他们仍会永远徘徊，再也不会被人看到。让我们把它们留在里面。我们要做的是当他们离开布局时将他们指回玩家。这样做有两件事：它们总是留在布局中，如果玩家静止不动，怪物就会出现在他们面前！

条件：怪物 - > 外部布局
动作：怪物 - > 设置角度朝向位置 - >对于X，Player.X - 对于Y，Player.Y。

运行游戏。如果你闲逛了一会儿，你会注意到怪物也会在布局周围停留，他们会走向各种各样的方向。这不是人工智能，但它会做到！

5.改变事件
切换回活动表。现在，一旦子弹击中它们，我们就会摧毁怪物。让我们改变它从健康状况中减去1。

找到事件：Bullet - 与Monster碰撞。请注意，我们有一个“摧毁怪物”动作。让我们用“从健康中减去1”来代替它。右键单击“destroy monster”操作，然后单击“ 替换”。

![](https://www.scirra.com/images/articles/replaceaction.png)

出现相同的对话框，好像我们正在插入一个新动作，但这次它将取代我们点击的动作。选择Monster - > Subtract from（在Instance variables category中）- > Instance变量“health”，并为Value输入1。单击完成。该动作现在应该如下所示：

![](https://www.scirra.com/images/articles/sub1fromhealth.png)

现在，当我们射击怪物时，它们会失去1点生命值，子弹会爆炸，但是当它们的生命值达到零时，我们还没有杀死怪物。添加另一个事件：

条件：怪物 - >比较实例变量 - >健康，更少或相等，0 
动作：怪物 - >生成另一个对象 - >爆炸，第1层
动作：怪物 - >摧毁

![](https://www.scirra.com/images/articles/monsternohealth.png)

* 完成接触


我们差不多完成了。让我们添加一些最后的润色。

首先，让我们有一些怪物经常产卵，否则一旦你射杀了所有的怪物，就没有什么可做的了。我们将每3秒创建一个新怪物。添加新活动：

条件：系统 - > 每X秒 - > 3
动作：系统 - > 创建对象 - > 怪物，第1层，1400（对于X），随机（1024）（对于Y）

1400是紧邻布局右边缘的X坐标，随机（1024）是随机Y坐标布局的高度。

最后，让鬼魂杀死玩家。

条件：怪物 - > 与另一个物体碰撞 - > 玩家
动作：玩家 - > 摧毁

现在，恭喜你大功告成了，你可以尝试去运行你的第一个HTML5游戏啦！