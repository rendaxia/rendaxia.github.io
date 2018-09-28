---
layout: post
title:      "小结Http与Https"
subtitle:   "--计算机网络小结知识01"
date:       2018-08-10 10:20:01
author:     "任庭玉"
img:   https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1537268670185&di=d2993e1286f2a08b579081290908086f&imgtype=0&src=http://n1.itc.cn/img8/wb/recom/2016/09/09/147339592392689600.JPEG 
catalog: true
tags:
    - web
comments: true
excerpt: 今天学习了计算机网络方面的http和https相关知识，想和大家分享一下。
---

# 小结Http与Https

标签（空格分隔）： 计算机网络 web

---
![http https][1]

**Http**：全称 HyperText Transfer Protocol，超文本传输协议。它是用于从WWW服务器传输超文本到本地浏览器的传输协议。它可以使浏览器更加高效，使网络传输减少。它不仅保证计算机正确快速地传输超文本文档，还确定传输文档中的哪一部分，以及哪部分内容首先显示(如文本先于图形)等。
**Https**：是经过数据加密的http协议。


 在了解http与https区别之前，需要先明确几个概念。

> <1> 明文传输：从广义的讲明文就是一段未经过任何加密的数据。
 <2> SSL：全称secure sockets      layer，它是一种安全协议，目的是为网络通信提供安全和数据完整性保证。SSL在传输层中对网络通信进行加密，它在应用层协议通信之前就已经完成加密算法、通信密钥的协商以及服务器认证工作。在此之后应用层协议所传送的数据都会被加密，从而保证通信的私密性。
 <3> TLS：SSL标准化后的协议。

 

**Http与Https的区别**

 1. Http协议运行在TCP之上，明文传输<1>，客户端与服务器端都无法验证对方的身份。Https加入了SSL协议，运行于SSL上，SSL运行于TCP之上，是添加了加密和认证机制的HTTP。
 2. 端口：Http与Http使用不同的连接方式，用的端口也不一样，前者是80，后者是443端口。
 3. 资源消耗：和HTTP通信相比，Https通信会由于加减密处理消耗更多的CPU和内存资源；
 4. 开销：Https通信需要证书，而证书一般需要向认证机构购买； 



[1]: https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1537268670185&amp;di=d2993e1286f2a08b579081290908086f&amp;imgtype=0&amp;src=http://n1.itc.cn/img8/wb/recom/2016/09/09/147339592392689600.JPEG
