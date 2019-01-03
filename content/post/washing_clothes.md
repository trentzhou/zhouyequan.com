---
title: "关于洗衣服的胡思乱想"
date: 2018-11-21T09:36:47+08:00
lastmod: 2018-11-21T09:36:47+08:00
draft: false
keywords: ["生活", "洗衣机"]
description: "关于洗衣机的一些幻想"
tags: ["生活"]
categories: []
author: ""

# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
comment: false
toc: false
autoCollapseToc: false
# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
contentCopyright: false
reward: false
mathjax: false
---

我一个人在南京街头散步，一边走一边胡思乱想。想到了一些关于洗衣机的东西。

<!--more-->
当最不爱做的事情就是洗衣服。手洗太麻烦。洗衣机也麻烦，还慢。我想象中理想的洗衣机是这样的：

1. 快速。脏衣服丢进去，20分钟拿出来的就是洗净烘干的，可以直接穿着走。
2. 安静。
3. 小。

淘宝上有很多洗衣机。快洗是有的。但是没有烘干。我总觉得洗衣机不带烘干似乎有点不合理，而单独添置一个烘干机有太占地方。

我想到[真空干燥](https://baike.baidu.com/item/%E7%9C%9F%E7%A9%BA%E5%B9%B2%E7%87%A5)。
如果能将洗衣机里面的气压降到足够低，那么水在40摄氏度就可以沸腾，理论上会大大加速衣服的干燥过程。

根据[水的饱和蒸汽压表](https://wenku.baidu.com/view/66d8a31755270722192ef7db.html)，想要在40摄氏度让水沸腾，
需要将气压从标准大气压的100 kpa降到7 kpa。

家用吸尘器一般可以产生27 kpa的气压。在这个压强之下，水的沸点是67摄氏度。看来还不够啊。
有一些强一点的吸尘器可以达到16 kpa的气压，能把水的沸点降低到56摄氏度。
不过我觉得，制造一个专门的容器来维持低气压应该不是很难的事情，而且完全可以不费什么电。
淘宝上就有很多真空桶和真空泵。

我搜索了一下，已经有[相关专利](https://patentimages.storage.googleapis.com/57/99/02/35bd270b4ac34d/CN102644188B.pdf)了。


那么，既然洗衣机现在要带一个真空桶，传统的波轮或者滚筒的样式就不行了。我能不能把洗衣机设计成活塞式的呢？
我们可以通过活塞的往复运动，带动衣服在水里来回动，这样来清洁衣服。网上我也搜索到了很多相关的专利，看来不是我一个人动过这个脑筋。

## 这个东西设计出来有什么用？

如果能解决成本和质量问题，还能做到小型化的话，这种洗衣机就太有用啦。想想每天有多少住酒店的人，他们都需要洗衣服啊。
我们可以开连锁的快速洗衣店，同时还能做其他经营项目，比如卖零食咖啡什么的。

为啥有那么多的专利，市场上却见不到呢？

Update: 我做过一些搜索，这并不是一个新想法。有人[做过实验](https://www.youtube.com/watch?v=hZLk6RJsDts)。效果并不好。有[类似的设计](http://www.yankodesign.com/2010/07/29/tumble-dry-in-vacuum/?utm_source=twitterfeed&utm_medium=twitter&utm_campaign=Feed%3A+yankodesign+%28Yanko+Design+-+Form+Beyond+Function%29)但是并没有做出令人信服的实验数据。
这个难点在于，水分的汽化需要吸收热量。在接近真空的环境里面，我们很难有效地保持衣服的温度。有专利说使用微波来加热衣服，但是假如衣服上有金属部件，会引起过热。我估计这个专利也没做过多少实验。因为桶里没有空气，而衣服纤维一般导热性能又很差，所以我能想到的有效加热的办法就是红外辐射，为了避免局部过热，还需要机械装置去翻搅衣服。这么一来成本就挺高了。

所以，真空不是好办法。那么，能不能使用冷凝的方式来去除衣服里面的水分呢？如果有一个装置可以产生干燥的空气，这个空气通过衣服的时候，含水量就会上升。然后使用另一个装置去除空气里的水分，不就可以了吗？蒸发吸收热量，另一个装置冷凝的时候又会释放热量，也许可以有比较节能的办法。百度百科里面的[空气干燥机](https://baike.baidu.com/item/%E7%A9%BA%E6%B0%94%E5%B9%B2%E7%87%A5%E6%9C%BA)或许可以。
