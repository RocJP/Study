
# 一、web基础
  ## 端口
1.http，超文本传输协议，端口号：80
2.https，端口号：443 
 
 ## URL
1.协议类型:[//服务器地址[:端口号]][/web服务器文件路径]文件名[?查询][#ID]

  ## HTTP包
请求信息：请求行、请求头、请求内容
响应信息：响应行、响应头、响应内容
1.HTTP请求：get，post

  1> GET 方法。 GET 方法用于获取请求页面的指定信息，我们平时浏览网页大部分用的都是GET的方法。如果我们请求的页面为动态脚本页面，则返回的结果是>
容器解析过的HTML源代码。

  2>POST 方法。 POST方法也与GET 方法类似，但是最大的区别在于。GET方法没有请求内容，但是post方法是有请求内容的。POST的请求可以向服务器发送大
量的信息。eg:文件上传。虽然GET方法也可以传送数据，但是有长度的限制，而且get请求会将发送的数据明文显示出来。而post不会,所以安全性相对高一
点。eg:账户密码登录。

   3>PUT方法 PUT方法会把http请求消息中的请求正文存储在web服务器的指定目录下。如果存在，则会替换。此方法属于极度危险的方法。
 
   4>OPTIONS方法 用于试探服务器支持的http方法。

   5>DELETE方法 用于删除指定web目录下的资源。 首先来看一下服务器上的文件
   
   6>HEAD方法。用法同get类似，唯一不同是不能在响应消息中返回主体信息。此方法可用于编写扫描工具中，因为其只探测资源是否存在，所有速度较快。4
  
   ## 响应行的状态码 
 1xx：表示请求已经被成功接受，继续处理。其范围是100-101.
 2xx：访问成功，服务器成功的处理了请求，其范围是200-206
 3xx: 重定向，告诉浏览器客户端，他们访问的资源已经被移动。并告知客户端新的资源的位置。这是浏览器重新对新资源发起请求。其范围是300-305.
 4xx: 客户端请求错误码，有时候客户端会请求一些服务器无法处理的东西。比如格式错误的请求，最常见的是请求一个不存在的url.其范围是400-415.
 5xx: 用于描述服务器内部错误。表示请求正常，但是web服务器出现问题，比如服务运行出错，或者网站挂了。其范围是500-505.
   常见的状态码如下：
 200:表示请求成功，最常见的状态码。
 302：重定向
 404：请求的资源不存在
 400：客户端请求有语法错误，不能被服务器理解。
 403：服务器收到服务，但是拒绝提供服务。
 500：服务器内部错误。
 503：服务器不能处理当前客户端请求。过一段时间恢复，一般是由于临时维护，或者服务器过载。
 
 # 二、前端基础
  ## HTML、CSS，JavaScript
  ->前端代码运行环境是浏览器，标准的前端语言只有HTML、CSS、和JavaScript。通常情况下，这些代码保存在服务端，通过http（或者https）传输到浏览器上。**html定义了要显示的内容、文档结构，可理解为骨架。css定义了显示的样式，可理解为衣服。JavaScript可实现执行动态更新样式，响应用户操作和服务端的交互**。
  
  
  
  
  
  
  
  
  
  
  
