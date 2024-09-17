# west2-online Android考核指南

这里是西二在线工作室安卓方向的考核指南，旨在为初学者提供一个循序渐进的安卓学习路线。

*其实已经不只是安卓了，在Kotlin Multiplatform与Compose的加持下，Kotlin已经成了一门万能语言，可以用在iOS、桌面端、网页端……*

## 版权

本项目遵循 GPL-3.0 License，转载请注明本项目仓库地址。

## 概览

| 阶段                                                                            | 学习内容                                                     | 预期时长     | 是否需要答辩 |
|-------------------------------------------------------------------------------|----------------------------------------------------------|----------|--------|
| [Java基础](https://github.com/west2-online/learn-java/blob/main/docs/1-基础语法.md) | JavaSE基础语法、类与对象                                          | 30天（1个月） | ×      |
| [环境配置，Kotlin语法学习与简单应用](docs/2-环境配置，语法学习与简单应用.md)                            | Kotlin语法，RecyclerView                              | 30天（1个月） | √      |
| [日记本](docs/3-日记本.md)                                                         | Room 数据库，Glide 图片框架，Retrofit2 网络请求框架，RecyclerView 的进一步使用 | 30天（1个月） | √      |
| [自定义View和Compose](docs/4-自定义View和Compose.md)                                     | 自定义View、Compose、动画                                       | 30天（1个月） | √      |
| [KMP](docs/5-KMP.md)                                                             | 基于 Kotlin Multiplatform 的跨平台应用开发                                 | 30天（1个月） | √      |
| [底层源码实现](docs/6.2-底层源码实现.md)                                                    | 一些常用库源码的简单实现                                             | 60天（2个月） | √      |
| [合作或其他](docs/6.1-合作或其他.md)                                | 与后端、美术等进行合作开发第一款相对成熟的产品，了解项目的对接、开发、测试；进行底层源码的学习          | 60天（2个月） | √      |

预期时长以一名零基础为参考，如果已经对其他语言有一定的了解，可以适当缩短。


## 时间安排

| 时间   | 完成内容                      |
|------|---------------------------|
| 第一学期 | Java基础、特性；Kotlin语法与安卓特性学习 |
| 寒假   | 小型综合APP开发                 |
| 第二学期 | Compose与KMP学习             |
| 暑假   | 合作轮综合考察/底层代码实现              |

## 考核设计

| 名称    | 解释                      |
|-------|-------------------------|
| 参考资料  | 供给同学们进行参考学习的部分学习资料      |
| 知识点   | 本轮要求掌握的知识内容             |
| 背景    | （部分阶段有）增加部分趣味性的故事       |
| 任务    | 任务的具体描述                 |
| Bonus | 在完成任务的基础上进行实现更加深入的功能/特性 |
| 提示    | （部分阶段有）对考核，或者对语言学习的一些提示 |

## 考核目标

我们的目标是快速为初学者构建一套**较为完整的安卓开发知识体系**。也就是经过完整的考核过程后，你将会有**独立开发一款APP**的能力，这意味着你可以通过这个赚取你的第一桶金了(指接外包)。

但是很明显，这样快速的学习并**不能满足现代企业对安卓开发工程师的需求**。这要求我们在学习过程中更加注重对原理、源码的掌握，同时这也能在面试等方面提供更多的帮助。并且我们的考核更加**偏向业务**，因此需要自己学习更加深入的内容，我们只是提供一条学习道路并培养你一定的**源码阅读、文档阅读、独立学习**的能力。

如果你有意将安卓开发作为你将来学习或工作的主要方向，我们建议认真负责的完成每一轮的**全部内容**，并能够简单了解一些框架的底层原理与设计模式、增强创造创新的能力。

## 项目结构

~~~shell
.
├─docs		// 考核文档
├─etc		// 杂项文档
│  └─blog	// 优质文章/笔记
├─img		// 文档图片
├─LICENSE
└─README.md
~~~



## 其他

由于Android开发特性原因(需要学习Java语言基本特性)，第一轮考核与Java考核同时进行。
