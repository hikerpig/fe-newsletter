---
date: 2020-10-23
---

# FE 无事通讯 - 第 4 期，Story Telling

## 文章

### [Fauna | Building a minimum viable full-stack with RedwoodJS and FaunaDB](https://fauna.com/blog/building-a-minimum-viable-stack-with-redwoodjs-and-faunadb)

- RedwoodJS 是一个 Serverless 的 web 全栈应用框架，用于构建和部署 JAMstack 应用程序。技术栈有 React + GraphQL + 快速部署(Netlify)等支持。
- FaunaDB 是一个支持 Serverless 应用的数据库服务。

此文教程教读者使用这两者搭建一个简单的全栈 Serverless 服务。

## 网站

### [The Pudding](https://pudding.cool/)

![](https://i.loli.net/2020/10/09/a2IWNCfRqUTED57.png)

一个做视觉和交互文章的数字互动杂志，载体为网页，选题采编和呈现方式都很有趣。是新媒体的一个尝试方向，但是这个媒介对作者和读者的要求都比较高，国内感觉直接跳过了这个阶段，直接进入短视频时代。

核心团队有 8 个人，人员构成主要有主编、设计、 journalist-engineer （新闻工程师？一个挺有趣的交叉领域）。视觉设计和创意都十分优秀，数据收集和分析也是其中一个重要的环节。

他们的[团队介绍](https://pudding.cool/about/)提到了项目运作方式：项目制，有偿接受外部贡献者的点子，也向其提供帮助（编辑、视觉设计、前端代码等），每个项目从立项到上线从几周到几个月不等。

The Pudding 本身完全免费，也没有扰人的广告，那团队是怎么活下来的呢？同一拨人有另一个商业化产品 The Polygraph ，接受定制化项目合作，The Pudding 便是一个团队能力展示板和探索空间。

其中一名编辑分享了[工作流程和教学]([Making Internet Things, Part 1: Working with Data](https://pudding.cool/process/how-to-make-dope-shit-part-1/))，对有志于做新媒体媒介探索的人是一个不错的系列。

## 资源

### [My 5 favourite APIs](https://medium.com/swlh/my-top-5-apis-for-new-developers-5191031da102#60a4)

5 个有趣的免费公开 RESTful API，前端工程师尝试新的玩具项目（或是学习新框架等）的时候可以直接使用，第一个就是有趣的神奇宝贝图鉴 [PokéAPI](https://pokeapi.co/)。

类似的还有 [The Lord of the Rings API - The one API](https://the-one-api.dev/) 。

## 小技巧

### [linux - Clear a terminal screen for real - Stack Overflow](https://stackoverflow.com/questions/5367068/clear-a-terminal-screen-for-real/5367075#5367075)

介绍了几种清除 terminal text buffer 的方式，有使用 `Ctrl+L` 或是 `reset` 命令的， 但使用 `printf "\033c"` 是最有效的，原理补充阅读:

- [printf（“\ 033c”）是什么意思？](https://stackoverrun.com/cn/q/13010766)