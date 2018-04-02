socketio

### 步骤：
npm install socket.io

### websocket：

WebScoket是一种让客户端和服务器之间能进行双向实时通信的技术。它是HTML最新标准HTML5的一个协议规范。WebSocket和HTTP都属于应用层协议，且都是基于TCP的。WebSocket在建立握手连接时，数据是通过HTTP协议传输的（这个请求和通常的 HTTP 请求不同，包含了一些附加头信息，其中附加头信息”Upgrade:WebSocket”表明这是一个申请协议升级的HTTP请求）,但是在连接建立后，真正的数据传输阶段则不需要HTTP协议的参与。这个连接会持续存在直到客户端或者服务器端的某一方主动的关闭连接。

![image](https://images2017.cnblogs.com/blog/1247371/201711/1247371-20171120120707258-353166864.gif)

参考：https://www.cnblogs.com/foupwang/p/7865694.html

### socket.io:

WebSocket是HTML5最新提出的规范，虽然主流浏览器都已经支持，但仍然可能有不兼容的情况，为了兼容所有浏览器，给程序员提供一致的编程体验，SocketIO将WebSocket、AJAX和其它的通信方式全部封装成了统一的通信接口，也就是说，我们在使用SocketIO时，不用担心兼容问题，底层会自动选用最佳的通信方式。因此说，WebSocket是SocketIO的一个子集。

Socket.io将Websocket和轮询（Polling）机制以及其它的实时通信方式封装成了通用的接口，其中Socket.io都实现了Polling中的那些通信机制呢？

* Adobe® Flash® Socket

* AJAX long polling

* AJAX multipart streaming

* Forever Iframe

* JSONP Polling

具体解释参考：http://www.cnblogs.com/xiezhengcai/p/3957314.html


### 优势：

* 直接存在对象形式，不用像websocket，要通过json字符串转换

* 可以自定义消息类型，不像websocket繁琐

socketio官方网站：https://socket.io/
