# 3.7 Netty源码学习 
Netty is an asynchronous event-driven network application framework for rapid development of maintainable high performance protocol servers & clients.

#### 1.netty包结构
org.boss.netty
 ├── bootstrap 配置并启动服务的类
 ├── buffer 缓冲相关类，对NIO Buffer做了一些封装
 ├── channel 核心部分，处理连接
 ├── container 连接其他容器的代码
 ├── example 使用示例
 ├── handler 基于handler的扩展部分，实现协议编解码等附加功能
 ├── logging 日志
 └── util 工具类

