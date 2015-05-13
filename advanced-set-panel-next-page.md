#变量
#下一个页面上设置面板教程
##在链接页面动态面板状态改变
###步骤1:添加提交按钮的OnClick
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-set-panel-next-page-tutorial1.png)

首先,打开AxureSetPanelOnNextPage。rp,打开“设置面板在下一页”页面。
选择OpenState1按钮设计区域并添加一个OnClick事件。这将打开编辑器对话框。
###步骤2:droplist选择存储在一个变量中
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-set-panel-next-page-tutorial2.png)

在本例中,我们想要存储变量和开放的花朵页面。所以,我们选择行动“设置变量值”行动,为OnPageLoad变量选择的复选框。
下拉,选择“选择选项”和“花Droplist”将自动被选中。
###步骤3:添加动作打开第一页
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-set-panel-next-page-tutorial3.png)

添加一个动作“开放链接”并指定页面“花”。是很重要的,此操作需要注意到这里来设置变量值之后,如果我们打开了第一页,变量值永远不会设置。单击OK关闭案例编辑器对话框。
###步骤4:添加OnPageLoad案例页1
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-set-panel-next-page-tutorial4.png)

接下来,打开花页面的站点地图面板。在这里,我们要��查变量值设置在前一页,并设置相应的动态面板的状态。
在底部的页面交互选项卡窗格中,添加一个OnPageLoad事件。
###第五步:添加条件检查变量值
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-set-panel-next-page-tutorial5.png)

添加一个条件在编辑器中。这将打开条件生成器对话框。
将其设置为检查变量OnLoadVariable等于价值的“价值”,然后进入“罂粟”价值。变量值是区分大小写的,所以一定要确保这droplist中的匹配项前面的页面。单击OK关闭条件生成器对话框。
###第六步:设置状态花板
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-set-panel-next-page-tutorial6.png)

如果OnLoadVariable值“罂粟”,我们想要展示的形象罂粟在页面上的动态面板。所以,我们添加行动“设置面板状态”,选择花面板,并选择从下拉菜单中“罂粟”状态。
单击OK关闭案例编辑器对话框。
###第七步:添加OnPageLoad每个选项
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-set-panel-next-page-tutorial7.png)

OnPageLoad事件,添加3更多病例。在每种情况下,增加一个条件检查OnLoadVariable价值为每个数字(1、2和3)并设置花面板动态面板到适当的状态。最后OnPageLoad情况下应该像一个在上面的截图。
###第八步:预览的原型
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-variables-set-panel-next-page-tutorial8.png)

预览您的原型和测试。选择一个按钮将你下面的页面并显示相关状态。
现在你知道如何使用变量小部件通信值从一个页面到另一个地方。
##总结
