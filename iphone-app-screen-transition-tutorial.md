#IPHONE应用程序教程&培训的文章
#动画屏幕过渡教程
##动画屏幕过渡概述
设计iPhone应用程序时,从一个屏幕过渡到另一个屏幕使用动画就像滑动条那样是很普遍的。在Axure RP中,屏幕可以设计在一个动态面板里面和设置面板状态行动用于从一个屏幕滑动过渡到下一个。这个iPhone应用程序教程向您展示如何做到这一点。

从一个方面说明,构建你的iPhone应用程序原型在动态面板是一个不错的方式来把你的整个应用程序放在一个页面。但为了防止过载的动态面板可能会很难控制在一个页面上,考虑将它分解成多个页面是值得考虑的。
##IPHONE应用程序导航与动态面板
###步骤1:添加热点
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial1.png)

首先,打开 AxureiPhoneApp.zip 并打开iPhoneApp-StateChangeNavigationTutorial.rp文件。
添加热点在后退按钮和现在播放按钮的上面。我们这样做是因为这些按钮是由多个部件组成的,和我们想要添加一个交互到整个区域。
###步骤2:将第一个转换为动态面板
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial2.png)

接下来,我们将把这两个屏幕放在一个动态面板里面。
选择第一个屏幕的所有部件包含灰色背景,右键单击并将其转化为一个动态面板。标签这个面板为InterfacePanel。
###步骤3:添加"Station"状态
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial3.png)

添加一个额外的状态面板通过在动态面板管理器右键单击面板并选择Add状态。
标签State1为"Now Playing"和State2为“Stations”。
###四步:粘贴小部件到"Stations"状态
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial4.png)

选择站列表屏幕小部件,剪切和粘贴成站状态。将粘贴小部件移动到位置0,0。
###第五步:添加OnClick到热点
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial5.png)

选择"Now Playing"热点,并双击OnClick事件打开事件编辑器。
###第六步:设置面板状态为“Now Playing”
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial6.png)

为InterfacePanel添加控制面板状态行动并检查复选框。“Now Playing”状态将被默认选中。选择并单击 OK关闭事件编辑器。
单击OK关闭编辑器。
###第七步:打开播放状态,添加OnClick
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial7.png)

导航到现在玩状态,选择后退按钮热点,并双击OnClick打开事件编辑器。
###第八步:设置面板状态“站”
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/iphone-app-screen-transition-tutorial8.png)

选择“Set Panel State”和检查InterfacePanel复选框。从droplist选择站状态,并为“Animate In”和“Animate Out”选择“slide right”后单击OK。
在你的桌面或生成和测试它或者把它放在你的苹果手机上看看效果。
