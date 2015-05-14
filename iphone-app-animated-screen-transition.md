#iPhone 应用程序教程&培训的文章
#动画屏幕过渡教程
##动画屏幕过渡概述
设计 iPhone 应用程序时,从一个屏幕过渡到另一个屏幕使用动画就像滑动条那样是很普遍的。在 Axure RP 中,屏幕可以设计在一个动态面板里面和设置面板状态行动用于从一个屏幕滑动过渡到下一个。这个 iPhone 应用程序教程向您展示如何做到这一点。

从一个方面说明,构建你的 iPhone 应用程序原型在动态面板是一个不错的方式来把你的整个应用程序放在一个页面。但为了防止过载的动态面板可能会很难控制在一个页面上,考虑将它分解成多个页面是值得考虑的。
##IPHONE应用程序导航与动态面板
###步骤1:添加热点
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial1.png)

首先,打开  AxureiPhoneApp.zip  并打开 iPhoneApp-StateChangeNavigationTutorial.rp 文件。添加热点在后退按钮和现在播放按钮的上面。我们这样做是因为这些按钮是由多个部件组成的,和我们想要添加一个交互到整个区域。
###步骤2:将第一个转换为动态面板
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial2.png)

接下来,我们将把这两个屏幕放在一个动态面板里面。选择第一个屏幕的所有部件包含灰色背景,右键单击并将其转化为一个动态面板。标签这个面板为交互面板。
###步骤3:添加"暂停"状态
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial3.png)

添加一个额外的状态面板通过在动态面板管理器右键单击面板并选择添加状态。
标签状态1为"现在播放"和状态2为“暂停”。
###四步:粘贴小部件到"暂停"状态
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial4.png)

选择站列表屏幕小部件,剪切和粘贴成站状态。将粘贴小部件移动到位置0,0。
###第五步:添加 OnClick 到热点
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial5.png)

选择"现在播放"热点,并双击 OnClick 事件打开事件编辑器。
###第六步:设置面板状态为“现在播放”
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial6.png)

为交互面板添加控制面板状态行动并勾选复选框。“现在播放”状态将被默认选中。选择并单击 OK关闭事件编辑器。
单击 OK 关闭编辑器。
###第七步:打开播放状态,添加到 OnClick
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial7.png)

导航到现在播放状态,选择后退按钮热点,并双击 OnClick 打开事件编辑器。
###第八步:设置面板状态“暂停”
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial8.png)

选择“设置面板状态”和勾选交互面板复选框。从下拉目录中选择暂停状态,并为“动画进时”和“动画出时”选择“向右滑”然后单击 OK。 
    
现在可以在你的桌面上生成和测试它或者把它放在你的苹果手机上看看效果了。
##总结
现在你有能力为你的苹果手机应用原型设置动态面板了，合理地使用它吧！还需要其他帮助吗？查看[论坛](http://www.axure.com/c/forum.php)或联系我们 **support@axure.com**
