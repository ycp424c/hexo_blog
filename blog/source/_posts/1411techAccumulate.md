title: 技术积累2014/11
date: 2014-11-20 10:00:27
tags:
- tech
---

> 厚积而薄发，try anything worth trying
> ——海丁·卡特 2014.11.20

入职两三个月，技术上没什么进步的，但是终究在流程上和设计流畅度上也顺了不少，但终究要整理一下才能更顺利地总结一下才能更流畅地开发和技术研究。

####项目管理

先是公司的需求项目，关键在估期和项目关键节点上，而估期也要根据项目关键节点来估计。
项目关键节点有以下几个点

1. 开始预估时间
1. 技术预研时间
1. 关键节点确认
1. 代码开始时间
1. 代码完成时间
1. 自测+体验时间
1. 提测时间
1. 发布时间

关键节点确认后，之后没一步所要用到的时间都应该确认了，另外，如果有技术预研时间就应该在技术预研时间内把开发时需要的素材（包括重构稿和测试素材，技术方案对重构稿结构有要求的也要在此阶段提出，给重构足够的时间去修改方案

####技术细节

业务上的逻辑其实都是挺简单的，优化上可以有两个方向
1. 代码的可读性
1. 架构的合理性（性能方向考虑，包括健壮性和可扩展性和性能

代码可读性上更多是单个文件层面的上，其实感觉可以有些结构可以把不同的操作放到不同的地方，代码其实主要就几个操作，dom操作，AJAX操作，数据处理。
联合架构的合理性，稍微复杂点的页面可以用一种伪MVC的架构，controller应该只做dom操作，把AJAX操作和数据处理的操作都放到model层，之前的不足在于，贪图方便，经常会吧数据的处理放到controller层上去，导致结构会有点乱，之后的应该执行得更加严格。
业务上的进步大概也就只能到这种程度了，剩下的都是慢慢熟练的过程了。想要有更大的进步就要站在更高的层面看问题，从架构上优化才是王道。同时如果可以从架构的优化上提取出一些处理问题的方法，那也是极好的。

####时间安排
通常在白天的时间都好零碎，通常被不同的项目的不同事情打扰了，几乎都不能挤出一段足够长的时间来进行高效开发，所以开始慢慢习惯吧零碎的东西放到白天进行（如页面的提测和发布啊，解决bug啊，处理文档，讨论需求等），到了晚上打断的人比较少了再进行新的需求的开发，不过这样会导致开发时间的紧张，毕竟我也不想每天到10点再下班。所以这就要求高效的开发，也是因为晚上的高效开发，才能在白天挤出更多的时间来做技术研究，写blog（这明明是不务正业好吧！）这样的事情。

