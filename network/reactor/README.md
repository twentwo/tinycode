## Reactor

依据 Doug Lea 的 [Scalable IO in Java](http://gee.cs.oswego.edu/dl/cpjslides/nio.pdf) 基于 NIO 实现的 Reacotr 模式的回显服务器

- BasicHandler: 单线程处理器
- MultiReactor: 主从 Reactor
- MultithreadHandler: 线程池处理器
- Reactor: 接收连接，I/O 读写

## Getting started

**编译**

```java
javac -encoding utf-8 *.java
```

**运行**

```java
java Reactor
java MultiReactor
```

**测试**

使用 telnet 命令进行测试，在 windows 下记得打开回显（ctrl+] -> set localecho -> Enter）

```bash
D:\>telnet 127.0.0.1 10393
```
