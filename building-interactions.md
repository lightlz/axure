# 建立交互
点击启用一个按钮形状，使用编辑器设置关注文本框。然后，当页面加载的时，使用页面的 OnPageLoad 事件把焦点放到文本框上。

## 添加一个按钮形状和两个文本框
![images](https://raw.githubusercontent.com/ClearChan/axure/master/images/buildinginteractions1.png)

### 1 添加一个按钮，两个文本框
拖放一个按钮形状部件和两个文本框部件到设计区域上。

### 2 在按钮上编辑文本
在按钮形状部件上编辑输入两个单词“Swap Focus”。

### 3 为按钮命名
仍然选择按钮形状部件，在“部件交互和注释”窗口将它命名为“Button1”。

### 4 编辑提示文本
选择第一个文本框， 在“属性”选项卡中编辑提示文本读作“Text Field 1”。

### 5 命名为 TextField1
将文本框命名为“TextField1”。

## 禁用第二个文本框
![images](https://raw.githubusercontent.com/ClearChan/axure/master/images/buildinginteractions2.png)  

### 1 编辑提示文本
将第二个文本框部件编辑提示文本读作“Text Field 2”。

### 2 禁用 Text Field 2
在“属性”选项卡，单击“禁用”。

### 3 命名为 TextField2
继续选择文本框并命名为“Textfield2”。

## 单击按钮禁用第一个文本框
![images](https://raw.githubusercontent.com/ClearChan/axure/master/images/buildinginteractions3-1.png)  
![images](https://raw.githubusercontent.com/ClearChan/axure/master/images/buildinginteractions3-2.png)  

### 1 选择 Button1
单击选择“Swap Focus”部件。
 
### 2 编辑 OnClick 事件
在“交互”选项卡双击“OnClick”事件。

### 3 添加动作到禁用
在最左侧的列表上选择动作“禁用”选项。

### 4 指定 TextField1
在最右侧的列表上勾选“TextField1”复选框。

### 还不能点击（“OK” 按钮）。
我们在下一步将在同一案例中继续添加另一个动作。

## 启用第二个文本框
![images](https://raw.githubusercontent.com/ClearChan/axure/master/images/buildinginteractions4.png)

### 1 添加启用部件动作
同一案件中通过点击“启用”添加另一个动作。

### 2 指定 TextField2
勾选“TextField2”复选框。

### 3 不要点击 OK 
我们还没完全完成这个案件。下一步，我们将添加第三个动作。

## 第二个文本框设置关注
![images](https://raw.githubusercontent.com/ClearChan/axure/master/images/buildinginteractions5.png)

### 1 添加设置关注动作
在同一案件下通过点击“关注”添加另一个动作。

### 2 指定 TextField2
勾选“TextField2”复选框。

### 3 复查所有动作
确定的所有动作如上图所示正确的显示出来。

### 4 点击 OK 
点击“OK”按钮确认所有的改变。

## 当页面下载时设置关注 Text Field 1
![images](https://raw.githubusercontent.com/ClearChan/axure/master/images/buildinginteractions6-1.png)  
![images](https://raw.githubusercontent.com/ClearChan/axure/master/images/buildinginteractions6-2.png)

### 1 添加一个 Case "OnPageLoad"
在下方“页面交互”选项双击“OnPageLoad”事件。

### 2 添加设置关注动作
在最左侧列表选择动作“关注”。

### 3 指定 TextField1
在最右侧列表勾选“TextField1”复选框。

### 4 点击 OK
点击“OK”按钮确认所有改变。

## 预览原型
预览你的原型。注意当页面加载时第一个文本框已经关注。点击“Swap Focus”按钮禁用“Text Field 1”然后启用关注“Text Field 2”。在浏览器中刷新页面将会重置一切。
