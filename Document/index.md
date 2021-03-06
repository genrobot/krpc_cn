#kRPC V0.2.2 中文文档 

原始出处:<http://krpc.github.io/krpc/index.html>  
本项目地址:<https://github.com/gc313/krpc_cn>

kRPC允许你通过游戏外运行的脚本操作坎巴拉太空计划（Kerbal Space Program）。它自带了许多可为流行语言使用的客户端库，包括C++、C #，java，Lua和Python。


+ [入门指南](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_1/1.1.md)
+ [教程和实例](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_2/2.1.md)
+ [客户端、服务器和其他的工具]


The mod exposes most of KSPs API and includes support for Kerbal Alarm Clock and Infernal Robotics. This functionality is provided to client programs via a Remote Procedure Call server, using protocol buffers for serialization. The server component sets up a TCP/IP server that remote scripts can connect to. This communication could be on the local machine only, over a local network, or even over the wider internet if configured correctly. The server is also extensible. Additional remote procedures (grouped into “services”) can be added to the server using the “Service API”.  

该MOD公开调用大部分KSPs API接口并包含了对Kerbal Alarm Clock和Infernal Robotics的支持。该功能通过使用Protocol Buffers将结构数据序列化来远程调用服务器。服务器组件设置了一个远程脚本可以连接的TCP/IP服务器。这种通信可以只在本地机器进行，也可以在局域网中，如果进行正确的配置甚至可以在互联网中进行通信。服务器也可以拓展。额外的远程程序（分组为“services”）可以用“Service API”添加到服务器。


###目录

+ [开始](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_1/1.1.md)

    - [服务器插件](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_1/1.1.md)
    - [Python客户端](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_1/1.2.md)
    - [“Hello World”脚本](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_1/1.3.md) 
    - [更进一步...](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_1/1.4.md) 

+ [教程和实例](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_2/2.1.md)

    - [亚轨道飞行](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_2/2.1.md)
    - [参考系](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_2/2.2.md)
    - [发射入轨](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_2/2.3.md)
    - [俯仰、航向和滚动](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_2/2.4.md)
    - [零件交互控制](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_2/2.5.md)
    - [对接指南](https://github.com/gc313/krpc_cn/blob/master/Document/chapter_2/2.6.md)

+ C#

    - C# Client
    - SpaceCenter API
    - InfernalRobotics API
    - Kerbal Alarm Clock API

+ C++

    - C++ Client
    - SpaceCenter API
    - InfernalRobotics API
    - Kerbal Alarm Clock API

+ Java
    - Java Client
    - SpaceCenter API
    - InfernalRobotics API
    - Kerbal Alarm Clock API

+ Lua
    - Lua Client
    - SpaceCenter API
    - InfernalRobotics API
    - Kerbal Alarm Clock API

+ Python
    - Python Client
    - SpaceCenter API
    - InfernalRobotics API
    - Kerbal Alarm Clock API

+ Other Clients, Services and Scripts
    - Clients

+ Compiling kRPC
    - Install Dependencies
    - Setup your Environment
    - Building using Bazel
    - Building the C# projects using an IDE

+ Extending kRPC
    - The kRPC Architecture
    - Service API
    - Documentation
    - Further Examples
    - Generating Service Code for Static Clients
    
+ Communication Protocol
    - Establishing a Connection
    - Remote Procedures
    - Protocol Buffer Encoding
    - Streams
    - KRPC Service
    - Service Description Message

+ Internals of kRPC
    - Server Performance Settings