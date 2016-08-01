
###三、Source

用于查看和调试当前页面所加载的所有源文件。

![console](./md/source2.png)

![console](./md/source1.png)


* 格式化JavaScript

	选择你想要格式化的脚本文件，点击按钮pretty就可以了。

*  调试XHR

	打开Source面板的debugger，在“XHR Breakpoints”下指定XHR的URL或URL部分，当发生XHR请求时会开启断点调试。

* SourceMap

	点击设置->通用里的“Enable javascript source maps”或“Enable css source maps”可以调试
JavaScipt源代码、CoffeeScript，甚至Sass，只需要在你的源码加入类似 //@ sourceMappingURL=/path/to/file.js.map 即可。


* Workspace

想让本地的文件夹在Source面板下可以编辑，右键单击Source面板选择“Add Folder to Workspace”，之后就可以直接编辑该目录下的任何文件，把Chrome当做一个编辑器来用。

* Snippets

	有时你想保存小段的脚本、书签或是你在浏览器中调试时经常用到的，都可以使用Snippets，你可以在Source面板里创建、存储和运行这些Snippets.


在Source中有用的快捷键有：

* Ctrl+F 根据关键词查找你想要的请求
* Ctrl+Shift+F 在所有加载的文件下查找
* ctrl+o 打开一个js文件
* ctrl+p 同ctrl+o
* ctrl+f 查找当前js文件中的关键字
* ctrl+shift+f 全局查找关键字
* ctrl+shift+e 在控制台运行当前选中的代码片段

>延伸阅读:[面板详解](http://zodiac-xl.github.io/chrome-dev/%E9%9D%A2%E6%9D%BF%E8%AF%A6%E8%A7%A3.html#/)