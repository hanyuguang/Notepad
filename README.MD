# 简易记事本，纯粹用于练习

基本的增删记事，支持图文混排，删除入口：长按记事item，由于模拟器分辨率过高所以图片显示可能没那么好看，实际手机上看挺可以的。

![](demo.gif)

图片存储：只保存其路径，然后SpanText显示为图片，图标的也如此，同时适当缩括图片。

另外也有个把图库获取的图片直接存数据库的demo，不过这样会很卡顿 -> [picDb分支（不更新）](https://github.com/hanyuguang/Notepad/tree/pidDb)

1. 建议将主页面和编辑记事页面的背景图片改成一致，若色差太大会看起来很晃眼
2. 编辑记事页面的UI控件是主线程加载，正文是另开线程加载的，所以会有先出界面再出文本的情况，但这样切换速度较快也不会卡UI

## License
[WTFPL](https://en.wikipedia.org/wiki/WTFPL)  
Do whatever you want.