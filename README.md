#bitchttpd
----

`bitchttpd` 是一个简单高效的http server，纯C语言开发，目前主要用在本人个人的网站。

###功能
* 支持文件，目录的访问
* 支持sendfile, tcp_cock等高效操作
* 支持404， 500
* 支持异步的日志：
    * 支持零点自动切换日志文件
    * 完善清晰的格式
    * 多线程支持
* 支持epoll


###待续...
* 急需支持304 not modified


###想法
   可以把图片之类的公用的资源fang在另一个端口