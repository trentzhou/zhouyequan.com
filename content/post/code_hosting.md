---
title: "代码放在哪里"
date: 2019-01-03T10:53:57+08:00
lastmod: 2019-01-03T10:53:57+08:00
draft: false
keywords: []
description: ""
tags: ["tech"]
categories: []
author: ""

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

我们自己业余时间写的代码往哪里放？

<!--more-->

## github.com ##

这个应该是最为广泛使用的代码托管平台了。我也在github上面放了一些代码，偶尔还会被路过的人看到，然后收藏或者fork。

有几个用着不舒服的地方：

* 如果不给钱，那么你的所有项目都是开放的。所有人都能看到。有时候这会让人有点不舒服。
* Github自己不带在线编辑器。你需要把代码clone下来才能修改。
* Github自己不带CI。不过它集成了第三方CI平台。

## gitlab.com ##

这个是我用着最顺手的一个。因为平常工作中我也用gitlab，所以它的功能我很熟悉。不费什么功夫我就把gitlab-ci给搭好了。
对于创业者来说，如果他们有自己的kubernetes集群，那么持续集成、持续发布都很轻松。

私有仓库、在线编辑、持续集成都有。任务管理、邮件通知也都很好。

## 腾讯云 ##

没想到吧？我有一些代码是放在 coding.net ，后来 coding.net 被腾讯云收编了。除了访问的网址变成了 https://dev.tencent.com/ ，基本功能没什么区别。

跟github相比，腾讯云是价格便宜量又足。私有仓库、在线编辑、Jenkins pipeline它都有。反正该有的功能都有。

## 阿里云 ## 

阿里云当然也什么都有。他们的代码托管平台是 https://code.aliyun.com 。 我感觉这就是抄了一个gitlab。但是功能弱多了。不推荐。

