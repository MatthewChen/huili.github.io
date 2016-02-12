# 什么是VDBE
注：这两个文件由于与VDBE有较为密切的联系，所以弄清楚VDBE是什么以及它的大致运行流程的源码的分析十分有必要。在此部分会对VDBE作一大致介绍后再对源码进行分析。

VDBE全称为虚拟数据库引擎(virtual database engine)，它是对真实计算机资源环境的一个抽象。它的原理类似于Java中的JVM（java虚拟机）和.NET平台的CLR（公共语言运行库），它们实现了这两种语言跨平台性。