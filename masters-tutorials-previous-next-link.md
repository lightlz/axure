# 触发事件教程 之 上一页/下一页链接（Previous/Next Links） master

## 在同一 master 上的不同交互

### 第一步：打开上一页/下一页链接 master
![](/images/masters-tutorials-previous-next-link-1.png)

首先，打开 [AxurePreviousNextButtons.rp](/downloads/AxurePreviousNextButtons.rp) ，然后在 Masters 面板内打开 Previous/Next Link（上一页/下一页链接）master 。

此操作会在设计器区域打开该 master 以供编辑。 

### 第二步：为上一页链接添加 OnClick case

![](/images/masters-tutorials-previous-next-link-2.png)

在设计区域中选择 “<< PREVIOUS” 小部件，然后为其 OnClick event 添加一个 case。此操作会打开 Case Editor 对话框。

### 第三步：为 Raise Event 添加 action

![](/images/masters-tutorials-previous-next-link-3.png)

在 Case Editor 中，为 Raise Event（触发事件）添加 action，Raise Event 选项在 actions 列表底部。

### 第四步：选择在 OnPreviousClick 上的触发事件

![](/images/masters-tutorials-previous-next-link-4.png)

在最右边的面板中，把 OnPreviousClick 事件旁边的盒子打上勾。

### 第五步：打开 Page 2，为 OnPreviousClick 添加一个 case

![](/images/masters-tutorials-previous-next-link-5.png)

从 Sitemap 面板中打开 Page 2。我们已经为页面添加好上一页/下一页链接 master 了，所以你只要在设计区域中选择该 master 。此时你会注意到 OnPreviousClick 会在 Interactions 标签页中出现，和所有别的互动事件一样。

为 OnPreviousClick 事件添加一个 case ，让其 Open Link（打开链接）并将目标设为 Page 1 .

### 第六步：为下一页链接添加 OnClick case

![](/images/masters-tutorials-previous-next-link-6.png)

回到 master，对下一页链接做和我们对上一页链接一样的事情。添加一个 OnClick case，添加触发事件 action 并且选择名为 OnNextClick 的事件。

### 第七步：打开 Page 2，为 OnNextClick 添加 case

![](/images/masters-tutorials-previous-next-link-7.png)

回到 Page 2，选择在设计区域内的 master，然后为 OnNextClick 添加一个 case，让其 Open Page 3 in Current Window（在当前窗口打开 Page 3）。

如果把这个 master 添加到别的页面，你就会发现可以为 OnPreviousClick 和 OnNextClick 事件添加不同的 case 。如果你想为链接的外观进行变更，或者重命名 Previous 为 Back ，只需要在 master 对其进行一次编辑即可！

I