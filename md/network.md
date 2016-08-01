
###四、Network
用于查看 HTTP 请求的详细信息，如请求头、响应头及返回内容等。


* 所有请求的详细日志request response 和各阶段的时间
* 模拟网络
* 禁用cache
![console](./md/network1.png)


* timeline

![console](./md/network2.png)


	* 排队时间发指令
	* 挂起时间 浏览器得到要发出这个请求的指令，到请求可以发出的等待时间，一般是代理协商、以及等待可复用的TCP连接释放的时间，不包括DNS查询、建立TCP连接等时间
	* Request sent 请求第一个字节发出前到最后一个字节发出后的时间，也就是上传时间
	* Waiting 请求发出后，到收到响应的第一个字节所花费的时间(Time To First Byte)
	* Content Download 收到响应的第一个字节，到接受完最后一个字节的时间，就是下载时间


* 网络时间轴导出为 HAR 文件 qa测试等;重发请求等
![console](./md/network3.png)


* 录制页面快照等
![console](./md/network4.png)

白屏时间 和 完全加载时间 清晰可见


在Network中有用的快捷键有：

* Ctrl+F 根据关键词查找你想要的请求
* chrome://net-internals/ 可以查看所以网络的详细

![console](./md/network5.png)
>延伸阅读:[面板详解](http://zodiac-xl.github.io/chrome-dev/%E9%9D%A2%E6%9D%BF%E8%AF%A6%E8%A7%A3.html#/)