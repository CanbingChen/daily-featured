# 每日一荐

![历史共访问次数](https://visitor-count-badge.herokuapp.com/total.svg?repo_id=azl397985856.daily-featured)
![今天被访问次数](https://visitor-count-badge.herokuapp.com/today.svg?repo_id=azl397985856.daily-featured)

> 统计数据的时间是从 2019-09-15 16:50 起至今

![](https://tva1.sinaimg.cn/large/006y8mN6ly1g8d0sktqrwj30hs07maae.jpg)

每天给你推荐一个新奇，好玩，高品质的开源库，好文，观点或言论等。

> 项目主页维护当前月份的内容，想看往期内容，可以翻到下方历史汇总部分，然后选择自己感兴趣的月份点进去即可。

## 新鲜出炉 (2020-04)

### 2020-04-28[仓库]

这个是一个基于 Chrome Develop Protocl（简称 CDP）的工具， 可以帮你管理多种服务，包括 NetWork，Page（功能类似 Chrome 开发者工具）。

业界很多工具，比如 Puppeteer 也是基于 CDP 完成的。 值得注意的是，其有多种实现，可以作用在不同的浏览器，只要浏览器实现了 CDP 规定的接口即可。如果没有实现，那么你需要做一个代理进行格式转换。

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ge9ism7vtcj30l30783zd.jpg)
（不同实现）

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ge9iutukhnj30al08zmyd.jpg)
（API 种类）

https://github.com/cyrus-and/chrome-remote-interface

### 2020-04-23[研究]

原文标题《Audio samples from "Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis"》。

研究人员搭建了一个系统，该系统只需要你提供几秒的语音信息，就能通过神经网络的训练，从而在在许多不同的说话者的声音中生成语音音频。

这是一个划时代的技术。试想，你可以拥有任何人的声音，那么你就可以将某些人作为虚拟人物永远存在这个世界上，比如已故的人，明星等。当然用的不好，也可能会被用到不好的地方。

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ge4thpquajj31ex0mmn24.jpg)

https://google.github.io/tacotron/publications/speaker_adaptation/

### 2020-04-21[仓库]

来了一个挑战 TS 的货？JSMonk/hegel 号称是没有`运行时的类型错误`，上次看到 No Runtime Error 还是在看 Elm，不过 ELM 更牛逼的地方在于， 其是真正的 No Runtime Error。

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ge01re791aj310t06qjt0.jpg)

https://github.com/JSMonk/hegel

### 2020-04-20[好文]

如果你被考察过一些 JS 诡异行为知识，比如让你猜测输出，会不会报错等，那么你很可能有很多疑问“为什么？为什么这么诡异？为什么不同浏览器执行结果还不一样？为什么相同浏览器不同版本执行结果也不一样？”。

要回答这些问题，恐怕仅靠查阅 MDN，是很难查到的。比如 `String.prototype.substring.call(undefined, 2, 4)`会输出什么？ `String.prototype.substring.call(window, 2, 4)`又会输出什么？ 要回答这个问题，最根本的就是查 ECMA 文档，比如上面这个问题， 我就会查到[ecma262/#sec-string.prototype.substring](https://tc39.es/ecma262/#sec-string.prototype.substring)，可以看出 ECMA 给出了我们答案：

![](https://tva1.sinaimg.cn/large/007S8ZIlly1gdz71b627aj31w80j6wkb.jpg)

但是这些符号 - `?`，`!`代表什么？ `RequireObjectCoercible` 和 `ToString()` 是什么？ 很多人是懵逼的，即使你是很熟悉 JS 的各种特性，但是阅读标准或许不是一件容易的事情。 为了方便描述，它掺杂了很多其他内容，比如一些记法（Notation）。如何阅读 ECMA 文档呢？

我这里推荐三个资料：

- [dmitrysoshnikov](http://dmitrysoshnikov.com/)
- [How to Read the ECMAScript Specification(内容较少，还在更新中，不过似乎断更一年了)](https://timothygu.me/es-howto/)
- [V8 团队出品的系列文章]

1. [understanding-ecmascript-part-1](https://v8.dev/blog/understanding-ecmascript-part-1)
2. [understanding-ecmascript-part-2](https://v8.dev/blog/understanding-ecmascript-part-2)
3. [understanding-ecmascript-part-3](https://v8.dev/blog/understanding-ecmascript-part-3)

### 2020-04-17[工具]

前端基本都是对前端应用进行打包，生成静态资源。那么如何将你的 NodeJS 应用打包，从而可以在没有 Node 环境的地方直接使用呢？这里介绍一个由鼎鼎大名的 ziet 开发的工具`pkg`，这里有一篇介绍的中文文章 [《把你的 NodeJS 程序给没有 NodeJS 的人运行》](https://github.com/75team/w3c/blob/master/articles/20191113_liuguanyu_%E6%8A%8A%E4%BD%A0%E7%9A%84NodeJS%E7%A8%8B%E5%BA%8F%E7%BB%99%E6%B2%A1%E6%9C%89NodeJS%E7%9A%84%E4%BA%BA%E8%BF%90%E8%A1%8C.md)，也可以看下。

https://github.com/zeit/pkg

### 2020-04-16[仓库]

现在公司会做一些大屏数据展示的功能。目前我们使用的是 echarts，会基于他们做二次封装。但是有一些东西做起来还是比较繁琐的。这个仓库提供了更加丰富的封装功能，更加容易上手使用。这是 一个 Vue 数据可视化组件库（类似阿里 DataV，大屏数据展示），提供 SVG 的边框及装饰、图表、水位图、飞线图等组件，简单易用，长期更新(React 版已发布)。

https://github.com/DataV-Team/DataV

### 2020-04-15[好文]

AntV 是如何处理 Canvas 的局部刷新的？看完这个你就明白了，绝对干货满满～

https://www.yuque.com/antv/blog/ydsuqn

### 2020-04-14[仓库]

一个可视化图标网站，可以在线拖拽生成图表，支持多种图表类型。

![](https://tva1.sinaimg.cn/large/007S8ZIlly1gdt9pamyhqj30rm0ekgmg.jpg)
![](https://camo.githubusercontent.com/ff9a469b4660550135a442fcae2f1c400ca6654b/68747470733a2f2f7770696d672e77616c6c7374636e2e636f6d2f66656332366636372d663762642d343463352d393839392d3337313238333566323161642e676966)

https://github.com/dongsuo/vue-data-board

### 2020-04-10[好文]

来自 Chrome 官方人员最最权威的宏任务，微任务指南。 这篇文章是目前我看过最好的讲解《浏览器事件循环，宏任务，微任务》的文章。

![](https://tva1.sinaimg.cn/large/00831rSTly1gdoh95vy36j30by0940t3.jpg)

他的教程的特点是可以可视化交互式学习，真的很赞：

![](https://tva1.sinaimg.cn/large/00831rSTly1gdoh9td11hj30ke0fit9p.jpg)

https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/

### 2020-04-09[好文]

Nginx 作为一个优秀的反向代理，常常活跃于各大公司，甚至有的大公司会对 nginx 做二次开发。Nginx 里面的配置很多，每次学习一点点，日积月累，你也能变成 nginx “配置专家”。

今天我们来看一篇来自网易游戏运营平台发布的 nginx 中的“失败重试机制”。

https://mp.weixin.qq.com/s/yDOXb9diMFcmbKhc58oH4w

### 2020-04-08[网站]

大家经常会在分享大会上看到过一些高大上的 PPT，这些看起来高大上 PPT 除了内容本身优质之外，还有一个共同点，就是善于运用图和表。之前我分享过一篇文章 - [累死累活干不过一个写 PPT 的](https://lucifer.ren/blog/2019/12/11/ppt-data/)。里面讲到了如何讲数据说话，将自己的成果通过可视化的方式展示出来，其中也推荐了几个工具。今天再向大家推荐一个相对来说“更加面向新手，入门更容易”的产品，虽然操作简单，但实际上其自定义设置也非常丰富。

![](https://tva1.sinaimg.cn/large/00831rSTly1gdmc53wwrdj318j0jwwm3.jpg)

对于常见的图表可以直接使用，并且支持导入数据，多种自定义设置等。

![](https://tva1.sinaimg.cn/large/00831rSTly1gdmc68fz5yj31h60nywi2.jpg)

![](https://tva1.sinaimg.cn/large/00831rSTly1gdmc6lom1lj31gk0gagnq.jpg)

地址： https://app.flourish.studio/projects

### 2020-04-07[好文]

> 清明节后的第一天。

我想大家应该都听过 PWA。但是真正将 PWA 用到实际项目中的很少，更多的是网上看的一些资料。这里有一份教程，这个教程特点是一步步带你构建 PWA 应用，相信你跟着作者一起做一遍，一定会学到更多。

地址： https://blog.logrocket.com/how-to-build-a-progressive-web-app-pwa-with-node-js/

### 2020-04-03[工具]

新一代的前端打包工具，采用 Go 编写，由于采用 Go 编写，而不是 JavaScript，因此性能相对较好，下面是一个 benchmark 对比图：

![](https://tva1.sinaimg.cn/large/00831rSTly1gdge8ksiphj30mq07h40j.jpg)

只不过这个仓库目前只有一人维护，因此更新可能会是个问题，大家不妨先关注一下。

![](https://tva1.sinaimg.cn/large/00831rSTly1gdgea4hjm7j30uj069751.jpg)

地址： https://github.com/evanw/esbuild

### 2020-04-02[好文]

如果你想知道 ES 最新标准的细节知识，比如我想知道 ES10 中某一个方法究竟是做什么的。那么最好的方法莫过于直接查看 ECMA 规范。但即便你是一个 JS 老手，在没有准备知识的情况下，直接啃规范还是很吃力的。因为规范中会有大量的术语和记法。本系列教程由 V8 团队执笔，帮你看懂 ECMA 规范。

地址： https://v8.dev/blog/understanding-ecmascript-part-3

### 2020-04-01[好文]

WebAssembly 是一种一种新的“语言”。允许开发者使用 C/C++等转化为 JS 可以直接调用的形式，由于是二进制形式，因此相比直接使用 JS 实现，性能更好。

![](https://tva1.sinaimg.cn/large/00831rSTly1gdd3aut07ij30lb07awfn.jpg)

本文（英文）详细解释了如何使用 WebAssembly 来进行图片处理。实际上基于 WebAssembly 来实现 webp，视频编解码等都在业界有所实现。这篇文章相对其他而言有两个特点： 简单，实用。

文章地址： https://blog.logrocket.com/image-styling-and-filters-using-webassembly/

## 历史汇总

- [2020-03](./backup/2020-03/)
- [2020-02](./backup/2020-02/)
- [2020-01](./backup/2020-01/)
- [2019-12](./backup/2019-12/)
- [2019-11](./backup/2019-11/)
- [2019-10](./backup/2019-10/)
- [2019-09](./backup/2019-09/)

## 关注我

我重新整理了下自己的公众号，并且我还给它换了一个名字`脑洞前端`，它是一个帮助你打开大前端新世界大门的钥匙 🔑，在这里你可以听到新奇的观点，看到一些技术尝新，还会收到系统性总结和思考。

在这里我会尽量通过图的形式来阐述一些概念和逻辑，帮助大家快速理解，图解是我的目标。

之后我的文章会同步到微信公众号 `脑洞前端` ，你可以关注获取最新的文章，并和我进行交流。

另外你可以回复大前端进大前端微信交流群， 回复 leetcode 拉你进 leetcode 微信群，如果想加入 qq 群，请回复 qq。

<img width="300" src="https://tva1.sinaimg.cn/large/006y8mN6ly1g7he9xdtmyj30by0byaac.jpg">

## 贡献

- 如果有想法和创意，请提 [issue](https://github.com/azl397985856/daily-featured/issues) 或者进群提
- 如果想贡献代码，请提 [PR](https://github.com/azl397985856/daily-featured/pulls)
- 如果需要修改项目中图片，[这里](./assets/) 存放了项目中绘制图的源代码， 大家可以用 [draw.io](https://www.draw.io/) 打开进行编辑。

## License

[Apache-2.0](./LICENSE)
