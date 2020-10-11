# 每日一荐

![历史共访问次数](https://visitor-count-badge.herokuapp.com/total.svg?repo_id=azl397985856.daily-featured)
![今天被访问次数](https://visitor-count-badge.herokuapp.com/today.svg?repo_id=azl397985856.daily-featured)

> 统计数据的时间是从 2019-09-15 16:50 起至今

![](https://tva1.sinaimg.cn/large/006y8mN6ly1g8d0sktqrwj30hs07maae.jpg)

每天给你推荐一个新奇，好玩，高品质的开源库，好文，观点或言论等。

> 项目主页维护当前月份的内容，想看往期内容，可以翻到下方历史汇总部分，然后选择自己感兴趣的月份点进去即可。

## 新鲜出炉 (2020-10)

### 2020-10-12[资料]

vue3 出来了，大家都开始学了起来。这里有一份 vue3 学习资料的集合，或者可以帮助你。

![](https://tva1.sinaimg.cn/large/007S8ZIlly1gjlbt5q7ygj30u00w1wkz.jpg)

地址：https://github.com/gautemo/vue-3-playground

### 2020-10-10[书籍]

给大家安利一本书现代操作系统（第 4 版），豆瓣评分 9.1。很多人推荐的一本书， 读完绝对有巨大的收获。

如果实在觉得读起来吃力，可以关注一下小林和 cxuan，这两个人对操作系统的理解还是蛮深刻的，文章通俗易懂。

### 2020-10-09[工具]

figlet.js 是一个用于生产 FIGfont 规范的一个 JS 库。效果图：

![](https://tva1.sinaimg.cn/large/007S8ZIlly1gjlbpo5l30j31c00tgdix.jpg)

地址：https://github.com/patorjk/figlet.js

### 2020-10-08[工具]

我们平常使用 vue 或者 react 脚手架生产的项目的时候， 启动项目会自动打开浏览器， 你可以借助这款工具实现这个效果。

用法：

```js
const open = require("open");

(async () => {
  // Opens the image in the default image viewer and waits for the opened app to quit.
  await open("unicorn.png", { wait: true });
  console.log("The image viewer app quit");

  // Opens the URL in the default browser.
  await open("https://sindresorhus.com");

  // Opens the URL in a specified browser.
  await open("https://sindresorhus.com", { app: "firefox" });

  // Specify app arguments.
  await open("https://sindresorhus.com", {
    app: ["google chrome", "--incognito"],
  });
})();
```

地址：https://github.com/sindresorhus/open

## 历史汇总

- [2020-09](./backup/2020-09/)
- [2020-08](./backup/2020-08/)
- [2020-05](./backup/2020-05/)
- [2020-04](./backup/2020-04/)
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
