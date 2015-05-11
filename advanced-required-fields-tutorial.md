#条件逻辑：必填字段教程
#
##切换IF / ELSE IF
###步骤1:添加条件OnClick案件
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-required-fields-tutorial1.png）

首先,打开AxureRequiredFields。rp并打开“必填字段”页面。
选择提交按钮,并添加一个OnClick事件。在编辑器中,单击Add。
在条件构建器,设置条件“文本小部件UsernameTextField等于价值(空白)“离开价值文本字段空白。单击OK关闭条件生成器。
###步骤2:添加一个行动来显示
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/
在编辑器中,单击“显示”,为UsernameErrorMessage选择复选框。单击OK关闭编辑器。
生成原型和测试。如果你离开UsernameTextField空白并单击Submit,将显示错误消息。
###步骤3:添加第二个案例隐藏
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/
添加第二个案例通过双击鼠标单击Submit按钮。点击“隐藏”并检查UsernameErrorMessage的复选框。单击OK关闭编��器。
使用工具栏中的“预览”和在浏览器中刷新原型来测试新病例。如果你把用户名文本字段留空,然后点击提交错误面板将显示。如果你然后再进去输入文本并单击Submit,错误消息将被隐藏。
###步骤4:添加第三个案例检查密码字段
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/
添加第三个案例通过双击OnClick。这一次,“如果文本小部件添加条件PasswordTextField等于(空白)”和文本字段值为空。单击OK关闭条件生成器。
在编辑器中选择“显示”,然后单击“PasswordErrorMessage”复选框。然后,单击OK关闭编辑器。
###第五步:切换IF / ELSE IF案例3
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/
案例3上单击右键并选择切换IF / ELSE IF。这将改变“其他”一个“如果”。现在3可能发生,即使案件1或2执行。
重新生成原型和测试。离开这两个文本字段空白应两个面板显示错误。
###步骤6:添加第四例隐藏
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/
现在我们可以添加第四个情况下隐藏的错误消息,如果一个值已经进入密码文本字段。
双击创建案例4 OnClick。选择“隐藏”并选择PasswordErrorPanel。单击OK关闭编辑器
###第七步:添加最后的案例与“成功”的条件
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/advanced-required-fields-tutorial7.png）

最后一例将包含成功登录和操作条件。
通过双击添加案例5 OnClick。
单击Add条件和第一行设置
条件说的“能见度小部件UsernameMessage等于价值的错误”。
然后,单击+图标以添加第二个行。设置这行说“能见度小部件PasswordMessage等于价值的错误”。
单击OK关闭条件生成器。
###第八步:添加动作链接到第1页
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/
在编辑器中,单击在当前窗口中打开链接,选择第1页。
单击OK关闭编辑器。
###步骤9:IF / ELSE IF切换
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/
我们想要成功的案例是一个IF语句,它总是不管上面的情况下进行评估。右键单击例5和选择切换IF / ELSE IF。
###第十步:预览的原型
![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/
这是它!预览原型和测试。
##总结
一个有点棘手。如果你沿着很容易,你可以安全地说你条件逻辑专家。