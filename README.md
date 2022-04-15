<p align="center">
    <a href="https://dunwu.github.io/javacore/#/" target="_blank" rel="noopener noreferrer">
        <img src="https://raw.githubusercontent.com/dunwu/images/master/common/dunwu-logo-200.png" alt="logo" width="150px"/>
    </a>
</p>

<p align="center">
    <img src="https://badgen.net/github/license/dunwu/blog" alt="license">
    <img src="https://travis-ci.com/dunwu/blog.svg?branch=master" alt="build">
</p>

<h1 align="center">BLOG</h1>

## 1. 编程语言

> 作为程序员，职业生涯的第一步，当然是掌握并精通至少一门编程语言。
>
> 本人是一名 Java 后端程序员，刚毕业时做过两年 C/C++ 程序员，此外，还略懂几门其他编程语言。

### 1.1. Java

> Java 领域的知识点非常庞杂，我整理成了多个教程项目，每个项目都包含大量文档和代码。

- [Java 教程](https://dunwu.github.io/java-tutorial/) 📚 - 本人作为一名 Java 程序员，十年的技术积累，汇总与此。
- [JavaCore 教程](https://dunwu.github.io/javacore/) 📚 - Java 核心技术教程。内容包含：Java 语法基础特性、Java 语法高级特性、Java 并发、JVM、Java IO/NIO 、Java 容器等。
- [JavaWeb 教程](https://dunwu.github.io/javaweb/) 📚 - 内容包含：JavaEE（Servlet、Jsp 等）、JavaWeb 主流技术及框架（Mybatis、Ehcache、Shiro、Quartz 等）。
- [Spring 教程](https://dunwu.github.io/spring-tutorial/) 📚 - Spring 框架实战教程。
- [Spring Boot 教程](https://dunwu.github.io/spring-boot-tutorial/) 📚 - Spring Boot 框架实战教程。
- Spring Cloud 教程 [TODO]

### 1.2. 其他语言

- [如何学习编程语言](https://github.com/dunwu/blog/blob/master/source/_posts/coding/programming-guide.md)
- [Python Cheat Sheet](https://github.com/dunwu/blog/blob/master/source/_posts/coding/python.md)
- [Shell Cheat Sheet](https://github.com/dunwu/blog/blob/master/source/_posts/coding/shell.md)
- [Scala Cheat Sheet](https://github.com/dunwu/blog/blob/master/source/_posts/coding/shell.md)

## 2. 数据结构和算法

> 如果说编程语言好比是武功招式，那么数据结构和算法就相当于是内功。要想成为编程高手，必须具备一定的数据结构和算法功底。
>
> 要想学好数据结构和算法，在我看来，就是多刷题。

[数据结构和算法教程](https://dunwu.github.io/algorithm-tutorial/) 📚 - 包含基本数据结构和算法的讲解和示例，以及平时在 leetcode 上刷题的代码。

## 3. 数据库

> 数据库大体上可以分为关系型数据库和 Nosql 数据库。
>
> 关系型数据库的特性和原理，基本上大同小异。
>
> Nosql 数据库就真的是各有各的不同了。

[数据库教程](https://dunwu.github.io/db-tutorial/) 📚 - 本人接触的最多的数据库就是 Mysql、Redis，本教程内对于这两种数据库的特性和原理讲解比较细致，其他数据库内容没那么细致。

## 4. 操作系统

- 教程
  - [Linux 教程 📚](https://dunwu.github.io/linux-tutorial/)
- 文章
  - [Windows 常用技巧总结](https://github.com/dunwu/blog/blob/master/source/_posts/os/windows.md)
  - [Mac 常用技巧总结](https://github.com/dunwu/blog/blob/master/source/_posts/os/mac.md)

## 5. 分布式

### 分布式综合

- [分布式面试总结](source/_posts/分布式/01.分布式综合/01.分布式面试总结.md)

### 分布式理论

- [分布式理论](source/_posts/分布式/02.分布式理论/01.分布式理论.md) - 关键词：`拜占庭将军`、`CAP`、`BASE`、`错误的分布式假设`
- [分布式算法 Paxos](source/_posts/分布式/02.分布式理论/02.分布式算法Paxos.md) - 关键词：`共识性算法`
- [分布式算法 Raft](source/_posts/分布式/02.分布式理论/03.分布式算法Raft.md) - 关键词：`共识性算法`
- [分布式算法 Gossip](source/_posts/分布式/02.分布式理论/04.分布式算法Gossip.md) - 关键词：`数据传播`

### 分布式关键技术

- 集群
- 复制
- 分区
- 选主

#### 流量调度

- [负载均衡](source/_posts/分布式/03.分布式关键技术/01.流量调度/01.负载均衡.md) - 关键词：`轮询`、`随机`、`最少连接`、`源地址哈希`、`一致性哈希`、`虚拟 hash 槽`
- [流量控制](source/_posts/分布式/03.分布式关键技术/01.流量调度/02.流量控制.md) - 关键词：`限流`、`熔断`、`降级`、`计数器法`、`时间窗口法`、`令牌桶法`、`漏桶法`
- 网关
- [分布式会话](source/_posts/分布式/03.分布式关键技术/01.流量调度/03.分布式会话.md) - 关键词：`粘性 Session`、`Session 复制共享`、`基于缓存的 session 共享`

#### 数据调度

- [数据缓存](source/_posts/分布式/03.分布式关键技术/02.数据调度/01.数据缓存.md) - 关键词：`进程内缓存`、`分布式缓存`、`缓存雪崩`、`缓存穿透`、`缓存击穿`、`缓存更新`、`缓存预热`、`缓存降级`
- [读写分离](source/_posts/分布式/03.分布式关键技术/02.数据调度/02.读写分离.md)
- [分库分表](source/_posts/分布式/03.分布式关键技术/02.数据调度/03.分库分表.md) - 关键词：`分片`、`路由`、`迁移`、`扩容`、`双写`、`聚合`
- [分布式 ID](source/_posts/分布式/03.分布式关键技术/02.数据调度/04.分布式ID.md) - 关键词：`UUID`、`自增序列`、`雪花算法`、`Leaf`
- [分布式事务](source/_posts/分布式/03.分布式关键技术/02.数据调度/05.分布式事务.md) - 关键词：`2PC`、`3PC`、`TCC`、`本地消息表`、`MQ 消息`、`SAGA`
- [分布式锁](source/_posts/分布式/03.分布式关键技术/02.数据调度/06.分布式锁.md) - 关键词：`数据库`、`Redis`、`ZooKeeper`、`互斥`、`可重入`、`死锁`、`容错`、`自旋尝试`

#### 资源调度

- 弹性伸缩

#### 通信

- [消息队列](source/_posts/分布式/03.分布式关键技术/04.通信/01.消息队列.md) - 关键词：`重复消费`、`消息丢失`、`消息顺序性`、`消息积压`

### 分布式应用

#### 微服务

- [微服务简介](source/_posts/分布式/04.分布式应用/01.微服务/01.微服务简介.md)
- 注册中心
- 服务发现
- 服务调用
- 服务调用链
- 服务依赖
- 服务编排
- 服务版本管理

## 6. 计算机网络

> 如果你是做通信领域的开发，或者是 Web 应用的开发，那就或多或少需要了解一些计算机网络的知识 。

> 如果你是做通信领域的开发，或者是 Web 应用的开发，那就或多或少需要了解一些计算机网络的知识 。

- [计算机网络面试总结](source/_posts/网络/01.计算机网络面试总结.md)
- [计算机网络指南](source/_posts/网络/02.计算机网络指南.md) - 关键词：核心概念、拓扑结构、作用范围、性能指标、体系结构

### 网络分层

> 理解计算机网络，首先需要从宏观层面了解计算机网络通信的分层结构。最有代表性的是 OSI 七层结构模型，但现实中更流行的是五层结构模型。
>
> 了解网络分层结构，需要了解每个网络层级在网络通信中的定位，以及这个层级主要的通信设备、通信协议。

- [计算机网络之物理层](source/_posts/网络/01.网络分层/01.物理层.md) - 关键词：调制、解调、数字信号、模拟信号、通信媒介、信道复用
- [计算机网络之数据链路层](source/_posts/网络/01.网络分层/02.数据链路层.md) - 关键词：点对点信道、广播信道、`PPP`、`CSMA/CD`、局域网、以太网、`MAC`、适配器、集线器、网桥、交换机
- [计算机网络之网络层](source/_posts/网络/01.网络分层/03.网络层.md) - 关键词：`IP`、`ICMP`、`ARP`、路由
- [计算机网络之传输层](source/_posts/网络/01.网络分层/04.传输层.md) - 关键词：`UDP`、`TCP`、滑动窗口、拥塞控制、三次握手
- [计算机网络之应用层](source/_posts/网络/01.网络分层/05.应用层.md) - 关键词：`HTTP`、`DNS`、`FTP`、`TELNET`、`DHCP`

### 网络协议

- [超文本传输协议 HTTP](source/_posts/网络/02.网络协议/01.HTTP.md)
- [域名系统协议 DNS](source/_posts/网络/02.网络协议/02.DNS)
- [传输控制协议 TCP](source/_posts/网络/02.网络协议/03.TCP.md)
- [用户数据报协议 UDP](source/_posts/网络/02.网络协议/04.UDP.md)
- [ICMP](source/_posts/网络/02.网络协议/05.ICMP.md)

### 网络技术

- [WebSocket](source/_posts/网络/03.网络技术/01.WebSocket.md)
- [CDN](source/_posts/网络/03.网络技术/02.CDN.md)
- [VPN](source/_posts/网络/03.网络技术/03.VPN.md)

## 7. 大数据

> [大数据教程](https://github.com/dunwu/bigdata-tutorial) 📚

- [Hive 教程](https://dunwu.github.io/bigdata-tutorial/hive/) 📚
- [Hdfs 教程](https://dunwu.github.io/bigdata-tutorial/hdfs/) 📚
- [Hbase 教程](https://dunwu.github.io/bigdata-tutorial/hbase/) 📚
- [Zookeeper 教程](https://dunwu.github.io/bigdata-tutorial/zookeeper/) 📚
- [Kafka 教程](https://dunwu.github.io/bigdata-tutorial/kafka/) 📚

## 8. 计算机安全和密码学

> TODO：有待完善，不断补充。。。

## 9. 计算机体系结构

> TODO：有待完善，不断补充。。。

## 10. 架构

> 如果把软件开发工作比作是一场战争，那么系统架构无疑是战略层面的工作。众所周知，万丈高楼平地起，系统架构就像是软件的地基，如果一开始就歪了，那么代码写得再漂亮，软件也难以成功。
>
> 软件整体结构与组件的抽象描述，用于指导大型软件系统各个方面的设计。重点是分而治之，先将大型系统抽象为各个组件或模块；然后逐一解决各组件、各模块的功能、性能问题；最后将这些组件、模块整合成对外服务的一个整体。

- [系统架构面试题](source/_posts/架构/01.系统架构面试.md)
- [系统架构概述](source/_posts/架构/02.系统架构概述.md)
- [系统高性能架构](source/_posts/架构/03.系统高性能架构.md)
- [系统高可用架构](source/_posts/架构/04.系统高可用架构.md)
- [系统伸缩性架构](source/_posts/架构/05.系统伸缩性架构.md)
- [系统扩展性架构](source/_posts/架构/06.系统扩展性架构.md)
- [系统安全性架构](source/_posts/架构/07.系统安全性架构.md)
- [大型系统核心技术](source/_posts/架构/08.大型系统核心技术.md)
- [领域驱动设计](source/_posts/架构/09.领域驱动设计.md)

## 11. 设计

### 11.1. [UML](source/_posts/设计/01.UML)

> 统一建模语言（英语 - Unified Modeling Language，缩写 UML）是非专利的第三代建模和规约语言。UML 是一种开放的方法，用于说明、可视化、构建和编写一个正在开发的、面向对象的、软件密集系统的制品的开放方法。UML 展现了一系列最佳工程实践，这些最佳实践在对大规模，复杂系统进行建模方面，特别是在软件架构层次已经被验证有效。

- [UML 快速入门](source/_posts/设计/01.UML/01.UML快速入门.md)
- [UML 结构建模图](source/_posts/设计/01.UML/02.UML结构建模图.md)
- [UML 行为建模图](source/_posts/设计/01.UML/03.UML行为建模图.md)

### 11.2. [设计模式](source/_posts/设计/02.设计模式)

> 设计模式（Design pattern）代表了最佳的实践，通常被有经验的面向对象的软件开发人员所采用。设计模式是软件开发人员在软件开发过程中面临的一般问题的解决方案。这些解决方案是众多软件开发人员经过相当长的一段时间的试验和错误总结出来的。

#### 11.2.1. 创建型模式

- [简单工厂模式 (Simple Factory)](source/_posts/设计/02.设计模式/01.简单工厂模式.md)
- [工厂方法模式 (Factory Method)](source/_posts/设计/02.设计模式/02.工厂方法模式.md)
- [抽象工厂模式 (Abstract Factory)](source/_posts/设计/02.设计模式/03.抽象工厂模式.md)
- [建造者模式 (Builder)](source/_posts/设计/02.设计模式/04.建造者模式.md)
- [原型模式 (Prototype)](source/_posts/设计/02.设计模式/05.原型模式.md)
- [单例模式 (Singleton)](source/_posts/设计/02.设计模式/06.单例模式.md)

#### 11.2.2. 结构型模式

- [适配器模式 (Adapter)](source/_posts/设计/02.设计模式/07.适配器模式.md)
- [桥接模式 (Bridge)](source/_posts/设计/02.设计模式/08.桥接模式.md)
- [组合模式 (Composite)](source/_posts/设计/02.设计模式/09.组合模式.md)
- [装饰模式 (Decorator)](source/_posts/设计/02.设计模式/10.装饰模式.md)
- [外观模式 (Facade)](source/_posts/设计/02.设计模式/11.外观模式.md)
- [享元模式 (Flyweight)](source/_posts/设计/02.设计模式/12.享元模式.md)
- [代理模式 (Proxy)](source/_posts/设计/02.设计模式/13.代理模式.md)

#### 11.2.3. 行为型模式

- [模板方法模式 (Template Method)](source/_posts/设计/02.设计模式/14.模板方法模式.md)
- [命令模式 (Command)](source/_posts/设计/02.设计模式/15.命令模式.md)
- [迭代器模式 (Iterator)](source/_posts/设计/02.设计模式/16.迭代器模式.md)
- [观察者模式 (Observer)](source/_posts/设计/02.设计模式/17.观察者模式.md)
- [解释器模式 (Interpreter)](source/_posts/设计/02.设计模式/18.解释器模式.md)
- [中介者模式 (Mediator)](source/_posts/设计/02.设计模式/19.中介者模式.md)
- [职责链模式 (Chain of Responsibility)](source/_posts/设计/02.设计模式/20.职责链模式.md)
- [备忘录模式 (Memento)](source/_posts/设计/02.设计模式/21.备忘录模式.md)
- [策略模式 (Strategy)](source/_posts/设计/02.设计模式/22.策略模式.md)
- [访问者模式 (Visitor)](source/_posts/设计/02.设计模式/23.访问者模式.md)
- [状态模式 (State)](source/_posts/设计/02.设计模式/24.状态模式.md)

### 11.3. [重构](source/_posts/设计/03.重构)

> **改善既有代码的设计**。
>
> 关键词：过长函数、过大的类、基本类型偏执、过长参数列、数据泥团、switch 声明、临时字段、被拒绝的馈赠、异曲同工的类、发散式变化、霰弹式修改、平行继承体系、过多的注释、重复代码、冗余类、纯稚的数据类、夸夸其谈未来性、依恋情结、狎昵关系、过度耦合的消息链、中间人、不完美的库类

- [代码的坏味道和重构](source/_posts/设计/03.重构/01.代码的坏味道和重构.md)
- [代码坏味道之代码臃肿](source/_posts/设计/03.重构/02.代码坏味道之代码臃肿.md)
- [代码坏味道之滥用面向对象](source/_posts/设计/03.重构/03.代码坏味道之滥用面向对象.md)
- [代码坏味道之变革的障碍](source/_posts/设计/03.重构/04.代码坏味道之变革的障碍.md)
- [代码坏味道之非必要的](source/_posts/设计/03.重构/05.代码坏味道之非必要的.md)
- [代码坏味道之耦合](source/_posts/设计/03.重构/06.代码坏味道之耦合.md)

## 12. 前端技术

> [前端编程教程](https://dunwu.github.io/frontend-tutorial/) 📚 - 不会前端的后端不是好后端，这里是二手前端技术的总结。

## 13. 工具

> 工欲善其事，必先利其器

- [Git](https://github.com/dunwu/dunwu.github.io/blob/master/tools/git/README.md)
  - [如何优雅的玩转 Git](https://github.com/dunwu/dunwu.github.io/blob/master/tools/git/如何优雅的玩转Git.md)
  - [Git 帮助手册](https://github.com/dunwu/dunwu.github.io/blob/master/tools/git/Git帮助手册.md)
- [正则表达式极简教程](https://github.com/dunwu/dunwu.github.io/blob/master/tools/正则表达式极简教程.md) - 全面介绍正则表达式，也适合作为速查手册。
- [Markdown 极简教程](https://github.com/dunwu/dunwu.github.io/blob/master/tools/Markdown极简教程.md) - 全面介绍 Markdown 语义。
- [Travis CI 极简教程](https://github.com/dunwu/dunwu.github.io/blob/master/tools/travis-ci极简教程.md)
- 电子书生成器
  - [Gitbook 教程](https://github.com/dunwu/gitbook-templates) 📚 - Gitbook 可以根据 Markdown 生成电子书。我整理了一个教程，并包含了几个常用模板。
  - [Docsify](https://github.com/docsifyjs/docsify) - 类似 Gitbook，可以根据 Markdown 生成电子书。比 Gitbook 更方便，官方手册很详尽。

## 14. 效率提升

> 方法论，是人们认识世界、改造世界的方法的理论。同样，项目管理、编程、写文档都应该有一定的方式方法，帮助我们合理、高效、快速的达成目标。

- [软件工程与项目管理](https://github.com/dunwu/blog/blob/master/source/_posts/efficiency/software-engineering.md)
- [合理规划项目](https://github.com/dunwu/blog/blob/master/source/_posts/efficiency/style/project-style.md)
- [合理对文档进行归类](https://github.com/dunwu/blog/blob/master/source/_posts/efficiency/style/dir-style.md)
- [合理编排技术文档](https://github.com/dunwu/blog/blob/master/source/_posts/efficiency/style/doc-style.md)
- [Markdown Cheat Sheet](https://github.com/dunwu/blog/blob/master/source/_posts/efficiency/style/markdown-cheatsheet.md)

## 15. License

本博客所有文章除特别声明外，均采用 [![License: CC BY-NC-SA 4.0](https://camo.githubusercontent.com/68b1d40ecc7a83ac2c1e691be14ce4be95cec195/68747470733a2f2f6c6963656e7365627574746f6e732e6e65742f6c2f62792d6e632d73612f342e302f38307831352e706e67)](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可协议。
