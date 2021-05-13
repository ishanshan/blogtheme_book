

# 输出平台需求

## 背景

最近我有越来越多输出的主题内容，想找一个方便分享和维护主题文档的平台。

主题内容是指比如 [策略产品经理修炼手记](https://github.com/ishanshan/Road2StrategyPM) ，[Collaboration Guide for Shaper](https://github.com/ishanshan/CollaborationGuide4Shaper) ，以及最近[输出实验室](https://ishanshan.im/community/selfedu/info_facilitate_output)的指南等系列文档。

期待输出平台能满足下列需求：


## 输出平台需求清单

> 注： `#1` 标注为已找到的两个 hugo 主题均已满足的需求。

### must have:

- [ ] 文档内容可托管于 GitHub ，并自动（双向）同步 #1
- [ ] 浏览体验相关
    - [ ] PC 和移动端都可以
      - [ ] 看到单篇文档的目录
      - [ ] 有入口方便地全站检索
      - [ ] 方便查看整个主题内容的目录
    - [ ] 移动端页面顶部有 floating bar ，方便地进行检索、切换到其它主题站点
- [ ] 侧边栏可以链接站外页面
- [ ] 单篇文档里的目录，可以生成锚点以便定向跳转
- [ ] 图床图片加了在线处理代码后，依然可以正常显示 #1
- [ ] 免费、开源、界面简洁 #1



### nice to have:

- [ ] 搜索时，可以搜到特定几个 GitHub 仓库对应站点的内容
- [ ] 可以给单篇文档添加标签，以便按标签筛选内容 #1
- [ ] 可以给单个页面设定不同于全局的自定义链接格式 #1
- [ ] 支持本地预览 #1
- [ ] 可以添加留言
- [ ] 可以显示字数统计/阅读时长建议
- [ ] 可以添加赞赏按钮
- [ ] 可以自动显示最后更新时间，并可按更新时间排序
- [ ] 有编辑当前页面的入口，可直接跳转 GitHub 对应文件进行在线编辑




## 目前已做尝试和进展

检索 `GitBook alternative` 并对比一些工具后，目前推测整合 [HUGO](https://gohugo.io/) 这两个主题，估计最易符合我的需求：
1. zdoc: https://themes.gohugo.io//theme/hugo-theme-zdoc/docs/contentmanagement/sections/
2. hugo-book: https://themes.gohugo.io//theme/hugo-book/docs/example/table-of-contents/


### 附：
#### 1. 其他可能的工具/主题：

1. Hexo 的这个主题 [Hexo Doc Theme | Get Started](https://zalando-incubator.github.io/hexo-theme-doc/get-started.html)

    没最优先考虑这个，主要是单篇文档的目录和主题文档目录混在一起，浏览起来容易迷失或分心。


2. Read the Docs：
    - demo 见 [Read the Docs features — Read the Docs 5.14.3 documentation](https://docs.readthedocs.io/en/stable/features.html)
    - 没最先考虑这个，主要是
        1. 单篇文档的目录和主题文档目录混在一起，浏览起来容易迷失或分心
        2. 搜索框和单篇文档的目录不是固定的，而是随正文滚动，使用起来不够方便。
        3. 上述两项调整起来比较麻烦吧




#### 2. 其他平台被排除的主要原因：

- [GitBook](http://gitbook.com/)：图床图片加了在线处理代码后，就无法显示了…… 而我[过往文章中大部分图片都是用七牛托管且直接加在线处理代码的](https://ishanshan.im/tool/community/HbMarkdownImage)，且不打算改变这个习惯，所以排除该平台。
- [Jekyll](https://jekyllrb.com/) ：主要是因为还没找到比较符合「must have」所列需求的主题。
- [Bookstack](https://www.bookstackapp.com/)： 界面不够简洁，不必要的元素较多


## 需要的支持

1. 有没有更易满足上述需求的其它工具或主题推荐？

2. 如果没有，目前整合那两个 hugo 主题来实现「must have 」里浏览体验相关的需求，对我来说有点头大>_< 有没有伙伴可以帮忙？

    如果能在这周日内实现出来，那真是太好了：D

3. 「nice to have」里的需求，对我来说实现起来更是头大 >_<  如果有伙伴能帮忙也一块儿实现，就真是太好了，感激不尽：D   

    「nice to have」的需求不是那么着急，这个月能实现就好。

如果你愿意帮忙，欢迎微信联系我（wechat ID: ishanshan42） ，或直接移步本仓库的 issue#1 回应。



## CHANGELOG 

- 210521 整理发布