#条件逻辑:Auto-Tab字段教程
#
##检测输入的字符数量
###步骤1:添加OnKeyUp用例
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-autotab-fields-tutorial1)

首先,打开AxureAutoTab.rp并打开“Auto-Tab”页面。
选择第一个文本字段,添加一个用例到OnKeyUp事件。在用例编辑器中,单击“添加条件”打开条件生成器。
###步骤2:构建条件
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-autotab-fields-tutorial2)

在条件构建器,设置行为“AreaCode中部件的长度值等于3”。
单击OK并关闭条件生成器。
###步骤3:设置关注在下一个字段
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-autotab-fields-tutorial3)

在用例编辑器中选择“关注”,然后单击MiddleDigits的复选框。
单击OK并关闭编辑器。
###第四步:重复步骤设置中间的文本字段
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-autotab-fields-tutorial4)

 重复步骤1到3设置中间的文本字段。而且为中间的文本字段设置同样的条件,并且把行动设置为关注最后的文本字段。
###第五步:为最后文本字段添加条件
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-autotab-fields-tutorial5)

在最后的文本字段,添加一个OnKeyUp事件,这一次把条件设为“最后的小部件的长度值等于4”。
单击OK，并关闭条件生成器。
###步骤6:添加“显示”行动
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-autotab-fields-tutorial6)

在用例编辑器中,选择“显示”行动并单击SubmitButton的复选框。
现在,当用户输入4位数在文本框中,隐藏的提交按钮将显示出来。

预览原型并测试它吧！