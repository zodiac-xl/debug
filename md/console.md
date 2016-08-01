
###一、Console

用于显示脚本中所输出的调试信息，或运行测试脚本等
![console](./md/console.png)


基础：

* console.info() 输出提示信息
* console.debug() 输出调试信息
* console.warn() 输出警示信息
* console.error() 输出错误信息


console.log() 是 printf 打印风格，因此你可以这么做：

	console.log("%s is %d years old.", "Bob", 42)。
	
console自定义

	console.log("%cThis is green text on a yellow background.", "color:green; background-color:yellow");

你可以输出多个值，用逗号隔开即可，方便在同一行输出对象和数组，例如：

	console.log('Kings: ', 'kings');

>不赞成使用 console.debug() ，因此没有图标标识，赞成用 console.log() 代替。


其他有用的快捷键有：

1. 重新运行命令：点一下“上”箭头即可翻看原先的命令列表。

2. 改变框架焦点：切换document  （iframe等 插件document等）

3. 引用当前和前一个元素

    如果你的“Elements”标签选择了一个元素，你可以用 $0 调用它
    在 Chrome 和 Safari，你可以通过 $1 - $4 选择更靠前的元素。

4. $_：获取先前表达式的结果


5. 使用$(选择器)可以选择元素，等价于document.querySelector(),$$(选择器)等价document.querySelectorAll()，
6.  Ctrl+` 控制台获得焦点
7.  Ctrl+L 清除控制台
8. Shift+Enter 多行输入
9. command+alt+f 全文件查找

>延伸阅读:[consoleApi](http://zodiac-xl.github.io/chrome-dev/consoleApi.html#/);
[面板详解](http://zodiac-xl.github.io/chrome-dev/%E9%9D%A2%E6%9D%BF%E8%AF%A6%E8%A7%A3.html#/)