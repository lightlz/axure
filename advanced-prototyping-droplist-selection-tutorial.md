#条件逻辑：下拉列表选择教程
##下拉列表交互
###步骤1:添加OnSelectionChange案例
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial1.png)

首先,打开AxureDroplistSelection。rp和开放“Droplist选择”页面。
选择droplist并添加OnSelectionChange事件。在编辑器中,单击Add条件开放条件生成器。
***
###第二步:构建“没有条件”
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial2.png)

条件构建器默认值恰好是我们所需要的。条件应该读<如果所选选项的AnimalDroplist等于"没有" >。
单击OK关闭条件生成器。
***
###步骤3:添加动作设置面板的状态
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial3.png)

在编辑器中,单击“设置面板状态”并检查AnimalPanel复选框。
“没有”状态将被默认选中。单击OK关闭编辑器。
***
###第四步:重复小狗和小猫的州
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial4.png)

重复步骤1到3只小狗和小猫droplist物品。
第二个和第三个案件应该有条件“小狗”和“猫”,并相应地设置面板的状态。
###第五步:添加最后的“其他”
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial5.png)

双击OnChange添加4例,但这一次不添加一个条件。我们已经设置可用droplist 3的4项条件所以最后将如果以上3个条件已经满足。
添加一个动作,第四例设置AnimalPanel状态金鱼。
###步骤6:预览的原型
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-droplist-selection-tutorial6.png)

这是它!预览原型和测试。