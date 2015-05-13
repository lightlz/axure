#变量
#将文本传递给下一个页面教程
##通过从页面输入的值
###步骤1:添加OnClick案件提交按钮
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-pass-text-next-page-tutorial1.png)

首先,打开AxurePassTextToNextPage。rp并打开“文本传递给下一个页面”页面。
在设计区域中选择Submit按钮,并添加一个OnClick事件。这将打开编辑器对话框。
###步骤2:NameField文本存储在一个变量中
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-pass-text-next-page-tutorial2.png)

在编辑器中,添加一个行动,并选择OnLoadVariable设置变量值。
在droplist选择“文本小部件”,选择NameField。这将NameField文本字段中输入的值存储在变量OnLoadVariable。
###步骤3:添加动作打开第一页
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-pass-text-next-page-tutorial3.png)

还在营业的情况下编辑,添加一个行动,现有的情况下,以“开放链接”,选择第1页。是很重要的,此操作需要注意到这里来设置变量的价值后,我们打开了第一页,变量值永远不会设置。单击OK关闭案例编辑器对话框。
单击提交按钮将该变量设置为任何用户输入文本字段,并打开第1页。
###步骤4:添加OnPageLoad第1页
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-pass-text-next-page-tutorial4.png)

接下来,打开第一页的站点地图面板。在这里,我们想要插入文本值存储在OnLoadVariable进入欢迎页面上的文本。
在底部的页面交互选项卡窗格中,添加一个OnPageLoad事件。
###第五步:设置文本欢迎文本面板部件
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-pass-text-next-page-tutorial5.png)

在编辑器中,添加一个“设置文本”的行动,选择“欢迎文本面板”并单击“外汇”按钮。
###第六步:插入变量值为文本
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-pass-text-next-page-tutorial6.png)
在对话框中,输入文本光标
“欢迎”文本。点击“插入变量
或函数……”,选择OnLoadVariable。这个文本插入[[OnLoadVariable]]。无论值存储在OnLoadVariable将取代这个文本。
单击OK关闭打开的对话框。
###第七步:预览的原型
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-pass-text-next-page-tutorial7.png)
预览您的原型和测试。单击提交按钮设置变量的值,打开下一个页面,并将值插入文本的欢迎。