---
date: 2020-09-11
---

# FE 无事通讯 - 第 2 期，秋高气爽

## 文章

### 1. [小议超链接的规范使用](https://sspai.com/post/62419)

> 超链接是互联网最突出的功能之一，添加超链接也是所有网络用户需要掌握的基本功。

谈论了超链接的正确语义以及一些优秀的视觉设计。

其中提到 [beepb00p.xyz](https://beepb00p.xyz/) 博客中的外链网站 icon 标注样式，很适合技术博客使用，不过域名和 svg icon 匹配主要是体力活，该博主也只做了一些。

<figure>
  <img src="https://cdn.sspai.com//2020/08/31/7097c7a82e8341eef02ab6c570c94dd6.png?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1">
  <figcaption>beepb00p 的链接设计</figcaption>
</figure>

[私货] 想要这个效果的，可以试试在自己博客网站内引一下这个精简可自定义图片配置的库, [marka-js](https://marka-js.vercel.app/)。

### 2. [What is the Value of Browser Diversity?](https://daverupert.com/2020/09/the-value-of-browser-diversity/)

Mozilla 裁员之后，大家都开始担心 Firefox 是否还会花费巨大人力和精力去维护独有的渲染引擎。如果 Firefox 的 Gecko 这座堡垒最终也转向 Chromium，那么走向大一统的 Web 浏览器生态，是否会丧失以前由于分裂局面反而带来的好处（浏览器厂商不得不深思熟虑，坐下来讨论合作以达成共识和标准），变成一个被 Google 产品经理的 OKR 推进的临时功能大集合？

### 3. [Beyond Media Queries: Using Newer HTML & CSS Features for Responsive Designs](https://css-tricks.com/beyond-media-queries-using-newer-html-css-features-for-responsive-designs/)

能更好支持响应式设计的 HTML & CSS 特性。

`<picture>` 标签对 `media` 属性有支持。

更主要的是介绍了好多实用的 CSS 特性， 包括 `min-resolution: 192dpi` 这样的媒体查询语句，以及 `min()`/`max()`/`clamp()` 这样的函数。

同样也推荐一篇类似的，介绍 JS `matchMedia` 函数的 [Working with JavaScript Media Queries](https://css-tricks.com/working-with-javascript-media-queries/) 。

### 4. [10 Tips to Improve Productivity using Chrome Dev Tool](https://blog.bitsrc.io/10-tips-to-improve-productivity-using-chrome-dev-tools-7918fc8203f3)

使用 Dev Tool 的一些小技巧，前端都可以看看，说不定学到了平时调试能省点功夫。

## 工具

### 1. [AnchorJS](https://www.bryanbraun.com/anchorjs)

为网页添加 deep anchors（暂译为“深链接”），可为段落(p)和标题(h*)等元素（可使用 css 选择符定制选择目标）添加可跳转的页面内链接，并为锚点元素添加合适的样式。

非常适用于增强文档页面，在许多 github pages 使用的 [jekyll-theme-primer](https://github.com/pages-themes/primer) 中有集成。

![anchorjs](https://github.com/bryanbraun/anchorjs/raw/master/docs/img/anchoring-links.png)

### 2. [Site-Shot - Capture a Website screenshot](https://www.site-shot.com/)

输入网页 URL，可以选择各种浏览器分辨率以及图片大小，手动操作是免费的，就是有点慢。同时还提供付费的 API 调用方式，是一个不错的服务。

不过如果是个人使用而且量不大，其实可以考虑自己跑一个 phantomjs 服务，图片保存在本地，github 上应该有很多例子。
