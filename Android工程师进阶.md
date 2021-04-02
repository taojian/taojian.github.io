# Android工程师进阶

## JVM运行时内存结构

![JVM内存结构示意图](.\Ciqah157GD2AYLFtAADxheNgCA0454.png)





## Java内存模型与线程

> * Java 内存模型的来源：主要是因为 CPU 缓存和指令重排等优化会造成多线程程序结果不可控。
>
> * Java 内存模型是什么：本质上它就是一套规范，在这套规范中有一条最重要的 happens-before 原则。
>
> * 最后介绍了 Java 内存模型的使用，其中简单介绍了两种方式：volatile 和 synchronized。其实除了这两种方式，Java 还提供了很多关键字来实现 happens-before 原则，后续课时中将会详细介绍。 

