
#条件逻辑：下拉列表选择教程
##下拉列表交互
###步骤1:添加 OnSelectionChange 用例
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial1.png)

首先,打开 AxureDroplistSelection.rp 和打开“下拉列表选择”页面。
选择下拉列表并添加 OnSelectionChange 用例。在编用例辑器中,单击添加条件打开条件生成器。

###步骤2:构建“没有条件”
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial2.png)

条件生成器的默认值恰好是我们所需要的。条件应该读为<如果所选选项的动态面板的值为"没有" >。  
单击OK，并关闭条件生成器。

###步骤3:添加动作来设置面板的状态
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial3.png)

在用例编辑器中,单击“设置面板状态”并勾选动态面板复选框。
“没有”状态将被默认选中。  
单击OK，并关闭用例编辑器。

###步骤4:重复步骤为小狗和小猫设置状态
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial4.png)

重复步骤1到3为小狗和小猫设置下拉列表物品。
第二个和第三个用例应该为“小狗”和“猫”设置条件,并相应地设置面板的状态。
###步骤5:添加最后的“如果其他”用例
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial5.png)

双击 OnChange 添加第四个4用例,但这一次不添加任何条件。我们已经为4个有用的下拉列表项目设置了3个条件，所以如果以上3个条件都没有满足最后一个用例的条件将会自动生成.添加一个动作到第四个用例，来为金鱼设置动态面板的状态。
###步骤6:预览的原型
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial6.png)

就是它了!预览原型和测试它吧。
##总结
现在你可以执行操作了，当一个图片在下拉列表中被选中的时候。
还需要其他帮助吗？查看[论坛](http://www.axure.com/c/forum.php)或联系我们 **support@axure.com**
