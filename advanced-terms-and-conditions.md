#条件逻辑:条款和条件的教程
##动态启动和禁用
###步骤1:禁用文本字段和按钮
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-terms-and-conditions-tutorial1.png)

首先,打开 AxureTermsAndConditions.rp 并打开“条款和条件”页面。
让我们通过禁用的签名的文本字段和继续按钮开始吧。选择文本字段和按钮,在 properties 选项卡中勾选复“禁用”。一定要禁用形状和文本字段。
###步骤2:添加 OnClick 交互到复选框
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-terms-and-conditions-tutorial2.png)

选择复选框并添加一个用例到 OnClick 事件。在用例编辑器中,单击“更多事件> 中的 OnClick ”来打开条件构建器。
###步骤3:添加条件
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-terms-and-conditions-tutorial3.png)

条件生成最好能猜测到你会想要的条件。在这种情况下,初始化条件“ AgreeCheckbox 是值为真”。  
在这里我们不需要再改变任何东西了,单击 OK 并关闭条件生成器。
###步骤4:启用标志文本
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-terms-and-conditions-tutorial4.png)

既然我们已经明确的条件了,我们可以设置动作，当条件满足时来执行它了。点击“启用”并勾选“标志文本”复选框。  
单击 OK，并关闭用例编辑器。
###第五步:添加“其他”用例
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-terms-and-conditions-tutorial5.png)

当 AgreeCheckbox 被选中时,再次双击 OnClick ,添加第二个用例。这是“如果这是真的”用例。点击“禁用”并勾选 SignatureField 复选框。  
单击OK，并关闭用例编辑器。
###步骤6:添加 OnKeyUp 用例到文本字段
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-terms-and-conditions-tutorial6.png)

接下来,当用户输入文本字段时我们将启动继续按钮,。选择文本字段并添加一个用例到 OnKeyUp 事件。在用例编辑器中,单击“添加条件”打开条件生成器。
###第七步:构建条件
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-terms-and-conditions-tutorial7.png)

条件将自动设置为使用文本字段上的文字,但我们想改为中间下拉菜单中的的“不平等”。条件为“文本小部件中的签名文本不能为空”。这意味着,如果有任何文本在文本字段中,这个动作在这个用例中会被执行。  
单击OK，并返回用例编辑器。
###第八步:添加动作到启用按钮
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-conditional-logic-terms-and-conditions-tutorial8.png)

现在点击“启用”并勾选“继续按钮”复选框。完成交互翻译为“如果有签名文本,就启用继续按钮”。如果文本为空白您还可以添加第二个用例来禁用使用继续按钮。

预览原型和测试它吧！
##总结
现在你可以使用限制了，在复选框或类似onkeyup的事件中。明白了吧！
还需要其他帮助吗？查看[论坛](http://www.axure.com/c/forum.php)或联系我们 **support@axure.com**