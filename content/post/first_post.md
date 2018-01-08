---
title: "怎么建一个自己的网站"
date: 2018-01-08T19:36:57+08:00
lastmod: 2018-01-08T19:36:57+08:00
draft: false
keywords: []
description: ""
tags: [经验]
categories: []
author: "周叶铨"

# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
comment: true
toc: false
autoCollapseToc: false
# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
contentCopyright: false
reward: false
mathjax: false
---

## 我为什么要建这个网站？

我平常的博客是放在[简书](https://www.jianshu.com/nb/2052563?order_by=seq) 上面的。碰巧想试试看自己建一个网站，就建了这么一个个人主页。

网站的域名也没有用什么花哨的名称，就是我自己的姓名。其实如果只是想要有一个博客的话，用简书就挺好了。自己建站还是挺费事的。如果你不怕折腾，那就看下去吧。

## 建网站需要怎么做呢？

要拥有自己的网站，首先需要有一个域名。其次需要有地方上传你的内容。接下来我会一步一步地说怎么搞。

### 申请域名并备案

如果我们的网站是在中国国内的话，首先声明，你的域名必须是在国内的域名服务商那里注册的，而且需要备案。这一点可能会吓跑一部分朋友。我自己操作了一遍，其实流程并不复杂，但是需要一点耐心。

我是在阿里云上申请的域名。从 https://wanwang.aliyun.com/ 进去，可以很方便地申请域名。域名使用一年也就几十块钱。不贵。此处要做一个实名认证，否则域名没法被访问。如实填写个人信息就可以了。

然后就是需要做备案了。https://beian.aliyun.com/order/index 去一步一步填表格吧。其中会需要你下载一个文档，打印出来，签上名字，再扫描上传。我是用了gimp搞定，或者你也可以用任何一款图像处理工具把自己的签名填进去。然后阿里云会给你邮寄一个蓝色幕布。你需要以这个幕布为背景，拍照上传。

这里我要夸一下阿里云的服务。我一开始表格填错了，过了几分钟就有小姑娘打电话给我，指导我该怎么填表。另外阿里云给我寄的幕布也没有收费，隔天就收到了。

照片上传完毕之后，就是漫长的等待了。我其实也就等了不到两个星期，就显示备案通过了。

当然，如果你选择国外的域名服务商的话，比如说godaddy.com，就省去了很多事。交了钱，分分钟你的域名就能用了。一般说来，你的个人网站这么做也可以。不过GFW什么时候把你拦住就说不准了。

### 内容放在哪里？

我在阿里云申请了一年的虚拟机。这一台虚拟机不仅仅放这个个人主页，我如果开发了什么小网站，也可以部署在上面，比如说 https://trentzhou.com （这个域名没有备案）。我申请的是档次最低的虚拟机，一年的费用500多块。

用一台虚拟机存放内容的话，你就可以任意配置你的网站了。我开了nginx，上面可以有好几个虚拟主机。

如果你不想花这笔钱，我强烈建议你看一下 http://www.cnblogs.com/purediy/archive/2013/03/07/2948892.html 。把内容放在github上，然后把域名指向github pages。这些都是免费的。

### SSL证书

用自己的虚拟机来部署网站，如果有SSL证书，那么我们就可以用 https 来访问了。幸运的是，阿里云也提供了免费的证书。https://www.aliyun.com/product/cas ，参考 https://ninghao.net/blog/4449 的经验。

另外我发现，域名没有备案的时候，通过http是没法访问的。但是通过https却是可以的。这个算是一个小小的后门吧。

## 开始创作啦

我的静态页面是使用 [hugo](http://gohugo.io/) 生成的。你也可以使用任何你喜欢的方式来呈现网站内容，比如说wordpress。
