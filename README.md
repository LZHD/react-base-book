# React.js 小书
[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY--ND%204.0-blue.svg)](https://creativecommons.org/licenses/by-nd/4.0/legalcode)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

作者：[胡子大哈](https://www.zhihu.com/people/hu-zi-da-ha)

原文链接：[http://huziketang.com/books/react/](http://huziketang.com/books/react/)

特此申明所有文章归原作者所有

## 简介
这是一本关于 React.js 的小书。

因为工作中一直在使用 React.js，也一直以来想总结一下自己关于 React.js 的一些知识、经验。于是把一些想法慢慢整理书写下来，做成一本开源、免费、专业、简单的入门级别的小书，提供给社区。希望能够帮助到更多 React.js 刚入门朋友。

由于水平有限，编写的过程难免会有诸多错误，也希望大家在看的过程中发现了问题，可以在 Github 上给该项目发 Pull Request。衷心希望可以有更多的人参与到本书的编写当中。

（PS：因为太多人问，统一回复：本书所有的图都用 Keynote 绘制而成）

## 本书介绍

本书为有一点前端基础的并且是 React.js 零基础的同学而作，帮助他们掌握 React.js 并且灵活地把 React.js 应用到实际项目当中。如果你有一定的 HTML、CSS、JavaScript 基础并且希望学习 React.js，而又觉得 React.js 当中有些概念比难以接受和理解，希望能够从零开始学习，那么本书很适合你。但如果你已经对前端已经非常熟悉并且用过不少的前端框架和相关的组件化技术，建议你直接看官网文档。

本书并不会文档式地包含所有知识点，只会提炼实战经验中基础的、重要的、频繁的知识进行重点讲解，让你能用最少的精力深入了解实战中最需要的 React.js 知识和套路，轻装上路。如果需要更多更全面的知识点，可以参看更多的官方文档或者其他丰富的资料。

**另外，本书全书采用 ECMAScript 2015，阅读之前请确保自己已经掌握了 ECMAScript 2015 的基本语法，否则阅读起来会非常困难。**

本书初定分为三个阶段，每个阶段最后会有实战分析，把该阶段的知识点应用起来。

**第一个阶段**：希望能让读者掌握 React.js 的基本概念和基础知识。包括问题的根源：前端组件的复用性问题、数据和视图的同步问题。了解清楚问题以后再了解 React.js 的基础知识，包括 JSX、事件监听、state、props、列表渲染等。看看 React.js 是怎么解决这些问题的。这个阶段结束以后，读者就可以可以运用 React.js 构建简单的页面功能。

**第二个阶段**：让读者更进一步了解 React.js，包括组件生命周期及其含义、state 和 props 的进阶概念、props 验证及其意义、组件组合进阶、如何和 DOM 打交道、并且开始引入前端应用状态管理所存在的问题。

**第三个阶段**：让读者掌握 React.js 较为高级的概念，包括高阶组件、context。并且尝试引入 React-redux 来协助我们构建较为完整的前端应用，还会开始深入讨论前端应用状态管理的问题；关于 React-router 也会有所提及。

## 目录

**第一个阶段**

![](https://img.shields.io/badge/已完成-100%25-brightgreen.svg)

* [React.js 简介](2017-02-12-lesson1)
* [前端组件化（一）：从一个简单的例子讲起](2017-02-13-lesson2)
* [前端组件化（二）：优化 DOM 操作](2017-02-14-lesson3)
* [前端组件化（三）：抽象出公共组件类](2017-02-15-lesson4)
* [React.js 基本环境安装](2017-02-16-lesson5)
* [使用 JSX 描述 UI 信息](2017-02-17-lesson6)
* [组件的 render 方法](2017-02-18-lesson7)
* [组件的组合、嵌套和组件树](2017-02-19-lesson8)
* [事件监听](2017-02-20-lesson9)
* [组件的 state 和 setState](2017-02-21-lesson10)
* [配置组件的 props](2017-02-22-lesson11)
* [state vs props](2017-02-23-lesson12)
* [渲染列表数据](2017-02-24-lesson13)
* [实战分析：评论功能（一）](2017-02-25-lesson14)
* [实战分析：评论功能（二）](2017-02-26-lesson15)
* [实战分析：评论功能（三）](2017-02-27-lesson16)

**第二个阶段**

![](https://img.shields.io/badge/已完成-100%25-brightgreen.svg)

* [前端应用状态管理 —— 状态提升](2017-02-28-lesson17)
* [挂载阶段的组件生命周期（一）](2017-03-01-lesson18)
* [挂载阶段的组件生命周期（二）](2017-03-02-lesson19)
* [更新阶段的组件生命周期](2017-03-03-lesson20)
* [ref 和 React.js 中的 DOM 操作](2017-03-04-lesson21)
* [props.children 和容器类组件](2017-03-05-lesson22)
* [dangerouslySetHTML 和 style 属性](2017-03-06-lesson23)
* [PropTypes 和组件参数验证](2017-03-07-lesson24)
* [实战分析：评论功能（四）](2017-03-08-lesson25)
* [实战分析：评论功能（五）](2017-03-09-lesson26)
* [实战分析：评论功能（六）](2017-03-10-lesson27)

**第三个阶段**

![](https://img.shields.io/badge/已完成-90%25-brightgreen.svg)

* [高阶组件（Higher-Order Components）](2017-03-11-lesson28)
* [React.js 的 context](2017-03-12-lesson29)
* [动手实现 Redux（一）：优雅地修改共享状态](2017-03-13-lesson30)
* [动手实现 Redux（二）：抽离 store 和监控数据变化](2017-03-14-lesson31)
* [动手实现 Redux（三）：纯函数（Pure Function）简介](2017-03-15-lesson32)
* [动手实现 Redux（四）：共享结构的对象提高性能](2017-03-16-lesson33)
* [动手实现 Redux（五）：不要问为什么的 reducer](2017-03-17-lesson34)
* [动手实现 Redux（六）：Redux 总结](2017-03-18-lesson35)
* [动手实现 React-redux（一）：初始化工程](2017-03-19-lesson36)
* [动手实现 React-redux（二）：结合 context 和 store](2017-03-20-lesson37)
* [动手实现 React-redux（三）：connect 和 mapStateToProps](2017-03-21-lesson38)
* [动手实现 React-redux（四）：mapDispatchToProps](2017-03-22-lesson39)
* [动手实现 React-redux（五）：Provider](2017-03-23-lesson40)
* [动手实现 React-redux（六）：React-redux 总结](2017-03-24-lesson41)
* [使用真正的 Redux 和 React-redux](2017-03-25-lesson42)
* [Smart 组件 vs Dumb 组件](2017-03-26-lesson43)
* [实战分析：评论功能（七）](2017-03-27-lesson44)
* [实战分析：评论功能（八）](2017-03-28-lesson45)
* [实战分析：评论功能（九）](2017-03-29-lesson46)
* ...

## 特别鸣谢

特别感谢以下朋友对本书所做的审校工作，给本书提出了很多宝贵的改进意见：

* [邝伟科](https://github.com/kuangwk/) - 腾讯 Web 前端工程师
* [杨海波](https://github.com/hipoyang/) - 百度 Web 高级前端工程师
* [谢军令](https://github.com/brucexiejunling/) - 天猫 Web 前端工程师
* [戴嘉华](https://github.com/livoras/) - 前微信 Web 前端工程师

## 联系作者

* 邮箱：huzidaha@126.com
* 知乎：[@胡子大哈](https://www.zhihu.com/people/hu-zi-da-ha)
* 专栏：[@前端大哈](https://zhuanlan.zhihu.com/qianduandaha)
* 加入《React.js 小书》读者交流群，一起讨论、交流、学习前端技术。

<img width='256px' src='_images/wechat-user.jpeg' />


## License

本作品采用 [署名-禁止演绎 4.0 国际许可协议](https://creativecommons.org/licenses/by-nd/4.0/legalcode) 进行许可
