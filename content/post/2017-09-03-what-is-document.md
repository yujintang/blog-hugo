---
title: 文档是什么？
date: '2017-09-03'
categories:
  - 感想
draft: false
---

> 在软件行业，文档无处不在，可是是否想过文档书写该注意什么呢？

## 给谁看？

这个应该是首先应该去想的，文档是给谁看的？客户还是同事？对方是什么职业？

比如，对方是客户可能不懂代码，你写的文档应该注重介绍，类比和展示，而不是怎么实现；

对方如果是库的使用者，那么应该从用法深入到专业方面的实现；

如果是合作者，那么你应当注重介绍如何开发和依赖还有设计思路方面的。

这才是我们始终关注的主线，时刻要记住！

<!--more-->

## 什么是最重要的？

### 开发者最关注什么？

当然是怎么快速接手然后干活了。

所以书写文档时，首先应该告诉开发者怎么搭建开发环境，或者开发环境应该注意什么，而不是一上来就展示自己的技术栈。

因为技术栈可以从依赖中看出来，而开发环境因人而异，如果不写清楚则会花费很多时间让开发者去试，或者去问，增加了交流成本。

其次，介绍技术栈，让开发者心中有数。如果你使用的是某些很灵活的框架，你甚至可以把目录结构简单注释一下，方便开发者快速定位需要改动的文件。

如果你的应用是可扩展的，你应该给出插件开发文档，最好能够给出例子，因为你对自己的设计最熟悉。

如果项目很多，命名体现不出项目在整体架构中的位置，应当在文档头写出此项目对应整个项目的位置，这点比任何东西都重要。

### 库使用者最关心什么？

首先就是 demo，最好自己做一个 demo 网站展示效果，好让使用者一开始就知道自己需要的这个库能不能满足。

其次就是怎么使用，简短的快速开始，能够让程序运行起来。

接着，你可以详细介绍配置中的每一项是什么。

### 客户最关心什么？

客户最关心的是能做什么事情？怎么做事情？能解决什么问题？和同类产品比较有什么优势？

注意，考虑到客户很有可能不懂代码，所以你应该用通俗易懂的语言，避免使用专业词汇，最好通过类比现实中常见的场景来说明。

---

文档写的不好会浪费每一个开发者的时间，所以团队应该共同维护文档，主动完善修正文档，这样才会提升大家的开发效率，不要把时间浪费在一个文档就能解决的事情上面。
