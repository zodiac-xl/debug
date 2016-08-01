###二、Elements

Elements面板让你可以看到DOM树中所有的东西，并可以让你实时编辑DOM树。


**dom查看**

![dom查看](./md/element1.png)


1. 移动元素

	你可以直接拖拽元素来放置到DOM树中

2. 删除元素

	直接选择元素然后按delete键

3. 滚动到视图内

	想要把页面滚动到视图内，右键点击元素，选择”Scroll into View”
	
4. 查看dom 有text和html 2种模式 （使用text编辑 然后查看html 即可得到字符实体） 


![console](./md/element4.png)

5. 设置DOM断点
	
	DOM断点和Source面板的断点类似，当指定的DOM属性、子元素发生变化时可以触发断点，在Elements面板的扩展面板里的DOM Breakpoints里可以看到设置断点的元素。


**style**

可以查看CSS属性源代码的位置，还可以添加和触发伪类如鼠标滑过时的CSS。

![console](./md/element2.png)
![console](./md/element5.png)


**Event Listeners**

Elements面板的扩展面板里的Event Listeners里可以查看绑定在DOM节点的JavaScript事件监听器。查看jquery绑定的事件：$(ele).data("events").click
![console](./md/element3.png)


**其他**

1. 通过CSS选择器搜索DOM元素

    CMD + F / CTRL + F和输入你需要的类名或ID名，可以搜索到相应的选择器。

2. dom css js修改实时生效

    sourcemao的文件是根据源文件映射出来的（规则映射 或 文件映射）
    记得sourcemap的文件修改是不支持反向修改的  修改sourcemap文件并不会修改源文件 所以不会生效   

![console](./md/element6.png)    


**在Elements中有用的快捷键有**：

* F2 以HTML格式来编辑切换
* Esc 停止修改DOM
* Ctrl+Z 撤销上一个操作
* Up/Down CSS属性值增加1/-1
* Alt + Up/Down CSS属性值增加0.1/-0.1
* Shift+Up/Down CSS属性值增加10/-10
* Shift+PageUp/PageDown CSS属性值增加100/-100

>延伸阅读:[面板详解](http://zodiac-xl.github.io/chrome-dev/%E9%9D%A2%E6%9D%BF%E8%AF%A6%E8%A7%A3.html#/)