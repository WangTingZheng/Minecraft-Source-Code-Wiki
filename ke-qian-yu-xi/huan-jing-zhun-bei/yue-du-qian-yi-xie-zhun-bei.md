---
description: 准备好刀叉好上菜
---

# 阅读前一些准备

### 教材

在阅读代码的过程中，总会遇到一些工程性问题，我们需要有一些参考书来解答我们的疑惑，一本讲解Java语法的参考书是必不可少的，我们的对它的要求是，第一，必须全面，即我们遇到什么Java语法方面的问题，都能在这本书上找到详细的解答；第二是最好是电子版的，带可跳转的目录，可搜索。除了基础的编程以外，我们还需要懂得如何设计代码结构，解决一些实际的问题，提升应用程序的性能和可扩展性，所以我们要学习设计模式，由于我们没有基础，所以我们对设计模式教材的要求是简单易懂而且全面。基于以上需求，我们选择了这两本作为我们的教材：

* 设计模式：[《head first：设计模式中文版》](https://detail.tmall.com/item.htm?id=526535264904)
* Java：[《Java核心技术卷1：基础知识第10版》](https://detail.tmall.com/item.htm?id=539422857815)

### 资料

在探索Minecraft的源码的过程中，前人总结的智慧是必不可少的，它能帮助我们节省很多时间，可惜放眼全世界，较为系统的讲解minecraft源代码的文章/书基本上没有，我只能找到一些比较零散简单的博客：

* [从编程的角度来看，Minecraft 是怎么样设计的？ - 王远的回答 - 知乎](%20https://www.zhihu.com/question/24459078/answer/133609241)
* [ProcedualGeneration - 拳四郎的博客 - CSDN](https://blog.csdn.net/qp120291570/category_6203791.html)
* [白玉楼之梦 - szszss' blog](http://blog.hakugyokurou.net/)
* [Minecraft Modding](https://greyminecraftcoder.blogspot.com/)
* [wiki.vg:Minecraft](https://wiki.vg/Main_Page)

### 视频

看文字学习未免有些枯燥，所以我收集了一些技术视频，目前只有讲设计模式的，主要是有一个youbuter叫Christopher Okhravi，讲设计模式讲得太好了，一点也不枯燥，关键是有人在b站搬运并翻译了大部分视频，看英文有些吃力的我感觉非常方便。

* [Design Patterns in Object Oriented Programming - Christopher Okhravi - Youtube](https://www.youtube.com/playlist?list=PLrhzvIcii6GNjpARdnO4ueTUAVR9eMBpc)
* [设计模式\(中文字幕\) - 懒癌正患者 - BiliBili](https://space.bilibili.com/4706388/channel/detail?cid=90274)

### 工具

Minecraft非常庞大，我们需要有一些工具帮助我们阅读、执行、测试、注释Minecraft的源码，我们使用业界领先的Java IDE—— Intellij IDEA来完成这些任务，除此之外，我们使用typora作为我们的主力markdown编辑器，用来编写源码阅读文档。

* Java IDE：[IntelliJ IDEA: The Java IDE for Professional Developers by JetBrains](https://www.jetbrains.com/idea/)
* markdown编辑器：[Typora](https://typora.io/)
* SSR客户端：[SSTap](https://github.com/mayunbaba2/SSTap-beta-setup)
* SSR云服务商：[cordcloud](https://cordcloud.site/)
* Github的DNS配置：由于Github的DNS地址被污染，导致GitHub长的图片无法在线查看，可以阅读这篇[博客](https://www.cnblogs.com/zuoanfengxi/p/12724698.html)解决这个问题

### 目标

我们希望我们不仅了解Minecraft内部是如何运作的，我们还希望我们能利用我们所学的知识解决一些实际问题，以此来检验我们知识的掌握程度。

* 看懂地图生成，制作一个基于latex的minecraft渲染器，帮助红石爱好者们更好地在论文里展示自己的机器，促进学术交流

