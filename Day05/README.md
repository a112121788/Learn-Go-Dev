# 学习要点
- Go Web开发（只用标准库）

## Go Web开发（只用标准库）
- <https://go-zh.org/doc/articles/wiki/>
见 goweb

- [Go Web编程](http://www.duokan.com/book/168958) 【新加坡】郑兆雄

Web应用通常需要具备的特质
1. 可扩展
2. 模块化
3. 可维护
4. 高性能

> 前三个其他语言&框架都能做到， Go在高性能上有优势。

如何实现可扩展
1. 垂直扩展 (单机性能)
2. 水平扩展 （多机性能）

静态类型语言+接口机制+函数类型+函数式编程 实现模块化

良好的工程实践+简洁的语法+清晰的包管理+优秀的工具&文档&测试 实现可维护性

编译型+goroutine 实现高性能


Web服务器 Web应用 Http
GET HEAD POST PUT DELETE OPTIONS CONNECT PATCH

请求 响应 状态码

URI HTTP/2  MVC 

模板引擎 
