---
title: README
date created: 2022-06-09
tags: readme说明
home: true
date modified: 2022-07-06
---
![](https://api.checklyhq.com/v1/badges/checks/3117d17b-44cf-47ee-a400-68bab9a0c76e?style=flat&theme=default&responseTime=true)

![](https://api.checklyhq.com/v1/badges/checks/0861a3c7-d17c-43e6-a59a-977bc4a87b64?style=flat&theme=default&responseTime=true)

![](https://api.checklyhq.com/v1/badges/checks/895cedb5-dcc4-4495-a53d-62bb5ef178be?style=flat&theme=default&responseTime=true)

## 这是什么

- 真实袒露的[[第二大脑]]。是个人每日阅读、笔记和写作的完整实时的过程与结果的全盘分享。大部分笔记是写给自己的，是希望能为自己将来所用的[[常青笔记]]。
- 未经美化的[[数字花园]]。避免为了正式发表而过度修葺美化文章，保留了最真实完备的细节。小部分笔记是写给观众的，希望能使得你有序漫步，避免陷入云深不知处。

## 为什么要开源笔记

- 新手也许能从本『实例库』中，获取如何基于[[双链笔记]]构建[[个人知识管理]]系统的[[内容、工具与方法论]]三位一体的实质性参考。而网上大部分『抛开内容谈方法论，抛开方法论谈工具』高屋建瓴式的文章或示例库，也许很难让你直观真切感受到双链笔记的魅力。
- 用[[双向链接]]做笔记很像编程，可以不断去引用和复用其他模块。软件源码可以开源，我的笔记有何不可？各种博客，只能看到局部的他，这个仓库[^1]，算是几近整体的我。除了个人隐私，我的全部思考和想法，或短暂或永恒，或黑暗或光明，都可以公之于众，也许没有人看，但这是我的态度和学习理念：[[输入驱动输出，输出倒逼输入]]。其实这个事儿，有一位编程界的大佬已经做了，吾仰望之： [Andyʼs working notes](https://notes.andymatuschak.org/About_these_notes)

## 快速开始

- 在线逛一逛。访问本库的实时在线版本，借助页面底部或右侧的[[反向链接]]面板随意漫游，感受[[双链笔记]]和[[卡片笔记]]的魅力：[oldwinter 的数字花园](https://notes.oldwinter.top)[^2]。这里是地图：[[☘️ 花园导览 🍀]]。
- 下来用一用。若简单漫游后，还算感兴趣，则 `git clone` 本库，并用 [[obsidian]]、[[logseq]]或[[VSCode]][^3]任意一款app打开本库后进行编辑和进一步探索。如果你也使用obsidian，想借鉴本库的一些配置、插件以及使用理念，这里是传送门：[[🧰 本库使用指南]]

## 进阶话题

> 这里篇幅太小写不下🤪，请点击以下链接跳转，可以随时通过目标页面底部的[[反向链接]]面板找到回来的路👣。

- [[2022年7月，obsidian 依然必装的 10 个插件]]
- [[本库的设计哲学]]
- [[如何通过obsidian打造自己的第二大脑]]

## 目录结构和本开箱即用库截图

- [[ACCESS 笔记组织法]]

![开箱即用库首页截图](https://my-public-pic.oss-cn-hangzhou.aliyuncs.com/202206251428706.png)

![开箱即用库暗色模式截图](https://my-public-pic.oss-cn-hangzhou.aliyuncs.com/202206251434534.png)

## 本库涉及 app 及作用

- [[obsidian]]主用
    - 基于[[markdown]]，进行阅读、笔记和写作。即[[闪念笔记]]、[[文献笔记]]、[[永久笔记]]。
    - 当前阶段聚焦项目的[[文件夹和标签]]式的管理。即[[项目笔记]]。
    - 多端同步。借用第三方[[remotely save]]插件由[[onedrive]]负责云存储和同步。
- [[logseq]]备用
    - push至[[github]]。使用[[github action]]自动定时发布。即 [oldwinter 的知识花园](https://garden.oldwinter.top/)[^4]。
- [[VSCode]]辅助
    - 文本和文件的批量[[正则表达式]]编辑和删除。
    - 管理dot隐藏文件等非md配置文件。
    - 借用[[Github Pilot]]插件进行AI写作。

## 周边 app 的联动与配合

- 本库聚焦于[[个人知识管理]]，而完整的[[工作和生活的效率体系建设]]，在我看来，共有4项：
    - [[个人信息管理系统]]。以[[cubox]]为中心。
    - [[个人任务管理系统]]。以[[滴答清单]]为中心。
    - [[个人知识笔记系统]]。以[[obsidian]]为中心。即本库。
    - [[个人输出发布系统]]。以[[notion]]为中心。
- 各个系统之间的联动与配合，参见[[效率系统4大子系统联动与配合]]。

## 找我从诗词歌赋，谈到人生哲学

- 微信：oldwinter2
- [[个人简介]]

[^1]: [👨‍💻‍ Github 源代码](https://github.com/oldwinter/knowledge-garden)。官方20美元1个月的发布服务地址：[🌲 oldwinterの数字花园](https://oldwinter.top)。太贵了我随时可能不续费😂。
[^2]: 这是[[obsidian publish 发布]]的免费替换方案1，基于开源项目[[jekyll]]
[^3]: vscode 需额外安装 foam 插件后，便支持 [[双链笔记]] 的 `[[` 语法
[^4]: 这是[[obsidian publish 发布]]的方案替换方案2，基于开源项目[[logseq]]
