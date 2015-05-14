# 条件，值和变量
创建“条件”,以检查一个文本字段中的文本是否是空白,基于输入链接到相应的页面。 使用一个变量来存储文本框输入的文本。然后,使用变量设置部件在下一个页面上的文本上。

## 添加一个文本框和一个按钮形状
![image](https://raw.githubusercontent.com/ClearChan/axure/master/images/conditionsvv1.png)
### 1 添加文本框和按钮
放置一个文本框部件和一个按钮形状部件到设计区域。
### 2 命名文本框
将文本框命名为“UserNameTextField”。
### 3 编辑文本和命名按钮
编辑按钮形状文本读作“Log In”。然后标注它为“LogInButton”。
### 4 为按钮形状编辑 OnClick 
选择“LogInButton”，双击它的 OnClick 事件打开“编辑器”

## 添加一个条件去检查文本框是否为不空
![image](https://raw.githubusercontent.com/ClearChan/axure/master/images/conditionsvv2.png)
### 1 点击添加条件选项
点击“添加条件”右边的“名称”字段来打开“条件生成器”。
### 2 设置条件的值
匹配每个字段的值：
  
“length of widget value”  
“UserNameTextField”
“does not equal”  
“value”  
最后字段保留空白。
### 3 点击 OK 
点击“OK”按钮返回“编辑器”。


## 将文本框的值设置为 ONLOADVARIABLE 
![image](https://raw.githubusercontent.com/ClearChan/axure/master/images/conditionsvv3.png)
### 1 添加设置变量动作
在“编辑器”中，添加动作到“设置变量值”。
### 2 选择 OnLoad Variable
勾选 OnLoadVariable 的复选框。
### 3 设置 OnLoad Variable
匹配每个字段的值：  
“text on widget”  
“UserNameTextField”  
### 4 不要点击 OK 
我们还没完成这个案件。我们将在下一步添加第二个动作。


## 打开页面 1 添加动作 
![image](https://raw.githubusercontent.com/ClearChan/axure/master/images/conditionsvv4.png)
### 1 为 Open Link 添加动作
同一案件中通过点击“打开链接”添加另一个动作。
### 2 选择“页面 1”
选择“页面 1”，作为链接的目的地
### 3 点击 OK 
点击“OK”按钮确认这个案件的所有改变。


## 当文本框为空时添加第二个案件 
![image](https://raw.githubusercontent.com/ClearChan/axure/master/images/conditionsvv5-1.png)
![image](https://raw.githubusercontent.com/ClearChan/axure/master/images/conditionsvv5-2.png)
### 1 添加第二个案件
选择“LogInButton”再一次双击 OnClick 事件。这个将打开“编辑器”的“案例 2”。
### 2 为 Open Link 添加动作
为“打开链接”添加动作。
### 3 指定页面 2
选择“页面 2”，作为链接的目的地。
### 4 点击 OK
点击“OK”按钮确认这个案件的所有改变。


## 添加一个矩形到页面 1
![image](https://raw.githubusercontent.com/ClearChan/axure/master/images/conditionsvv6.png)
### 1 打开页面 1
双击站点地图中的“页面 1”在设计区域打开它。
### 2 添加矩形部件
在页面 1 中添加一个矩形部件
### 3 标注矩形
标注矩形为“WelcomeMessage”。
### 4 添加一个案件到 OnPageLoad 
双击“页面交互”选项卡中的 OnPageLoad 事件。


## 当页面加载时设置矩形的文本
![image](https://raw.githubusercontent.com/ClearChan/axure/master/images/conditionsvv7.png)
### 1 添加设置文本动作
选择“设置文本”动作。
### 2 选择 WelcomeMessage
选择 WelcomeMessage 部件。
### 3 点击函数按钮
点击“fx”按钮打开“编辑文本”对话框。


## 将 ONLOADVARIABLE 放进欢迎信息中
![image](https://raw.githubusercontent.com/ClearChan/axure/master/images/conditionsvv8.png)
### 1 输入欢迎文本
输入文本“Welcome， ”。包括逗号和空格。
### 2 在下拉列表框中选择 OnLoadVariable 
点击“插入变量或函数...”打开下拉列表框。选择“OnLoadVariable”在文本中插入“[[OnLoadVariable]]”.
### 3 点击所有的 OK 按钮
点击所有打开的对话框中的“OK”按钮。

## 预览原型
导航回到主页和预览你的原型。首先文本框保留空白，然后点击“登陆”按钮。因为文本框是空白的，所以你会链接页面 2。使用站点地图回到主页。这一次，在空白的文本框中输入你的名字然后点击“登陆”按钮。你将链接到页面 1 然后会看到你的名字在欢迎信息里面。