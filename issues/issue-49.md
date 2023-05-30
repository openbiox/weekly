---
date: 2023-03-27
comments: true
---

# 生信爱好者周刊（第 49 期）：面对知识孤岛，你会怎么处理？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)

## 封面图

![](https://files.mdnice.com/user/33257/0e5bd273-9f64-4d75-9f50-bdb58ed1b1aa.jpg)

法国圣米歇尔山（Mont-Saint-Michel），是联合国教科文组织列为世界文化遗产，在山顶上则建有著名的圣米歇尔山隐修院。
（图源：pixabay.com）

## 本周话题：[面对知识孤岛，你会怎么处理？](https://www.ruanyifeng.com/blog/2022/07/weekly-issue-213.html)

![](https://files.mdnice.com/user/33257/86668e48-57e3-4ebb-b3d2-286b01424518.png)

> "知识孤岛"（knowledge silos）就是在遇到问题，要么没人可问，要么没有文档，工作就卡在那里，进行不下去时所面临的处境。这就是知识时代的痛苦：太多的知识没有流动性，难以了解，难以获取，难以传播。

`@kkjtmac` - 这种“知识孤岛”也存在于日常的生信分析过程中，比如分析过程遇到各种大大小小奇怪的报错，这时候我的解决办法就是：1.首先是通过百度或者谷歌搜索进行解决，运气好的可以顺利解决。2.不能则求助于热心网友得到解决。3.再就是搁着N天，在某次偶然的情况下查到了相关知识，最终解决。4.搁置绕道，用别的方法。

`@ShixiangWang` - 世界上的知识在泛化、深化，个人越来越难以掌握系统的知识图谱，构建对知识、科学的整体印象，建议在学习技能的同时多看一些书籍，记录和输出笔记、感想等等。

## 生信研究

1、[Nat Rev Genet | 使用单细胞转录组学进行时间建模](https://mp.weixin.qq.com/s/l2IHP7yFyIOUeGLEWlux8Q)

![](https://files.mdnice.com/user/33257/9e8d40fd-c2ce-4039-befa-2ad4b8ab7cf7.png)

在这篇综述中，作者讨论了时间序列scRNA-seq分析和建模的几种方法，重点介绍了它们的步骤、关键假设以及数据类型和它们最适合的生物学问题。

- 论文链接：https://www.nature.com/articles/s41576-021-00444-7

2、[Cell Research | 汤富酬课题组开发基于单分子测序平台的单细胞染色质可及性测序技术](https://mp.weixin.qq.com/s/CuBecxqFcxSXqAnNBu0aCg)

![](https://files.mdnice.com/user/33257/e0422ef5-66af-493f-ba4b-96da80250723.png)

北京大学生物医学前沿创新中心（BIOPIC）汤富酬课题组首次报道了名为scNanoATAC-seq的基于三代测序平台（单分子测序平台）的单细胞染色质可及性测序技术。该技术整合了长读段单分子测序平台和单细胞染色质可及性测序技术（scATAC-seq：Single cell Assay for Transposase Accessible Chromatin with high-throughput sequencing）的优势，实现了在一个单细胞中同时检测染色质开放状态以及基因组结构变异。

- 论文链接：https://www.nature.com/articles/s41422-022-00730-x

3、[Nature Reviews Cancer | 大数据在癌症基础研究和临床应用中的应用和挑战](https://mp.weixin.qq.com/s/bGMjk4HRpVweWljowNxsAw)

![](https://files.mdnice.com/user/33257/4dd58dd0-f08a-42ad-97fb-394ac955d33b.png)

美国国家癌症中心的姜鹏和 Eytan Ruppin 博士系统总结了大数据在癌症基础研究和临床应用中的应用和挑战，讨论了大数据驱动研究中的几种常见策略以及癌症数据科学中系统性局限。

- 论文链接：https://www.nature.com/articles/s41568-022-00502-0

## 博文资讯

4、[用大白话解说 2022 年诺贝尔化学奖的技术](https://mp.weixin.qq.com/s/wNHGRGs0SFxTpRmhbYXqBA)

![](https://files.mdnice.com/user/33257/80ddbc7a-208d-491a-9cb5-882babdee02a.png)

2022年的诺贝化学奖，颁给了三位科学家：Carolyn R. Bertozzi，Morten Meldal，K. Barry Sharpless，奖励他们在“for the development of click chemistry and bioorthogonal chemistry”中的贡献，翻译成中文就是“奖励在点击化学和正交生物化学开发中的贡献”。陈巍老师在他的公众号用大白话详细解释这项技术。

5、[具有更好临床相关性的肿瘤小鼠模型： PDX模型](https://mp.weixin.qq.com/s/iuKkKUcRupEPzFEa7LYqoQ)

![](https://files.mdnice.com/user/33257/5ee89e4e-9703-4438-8b60-673136ff59e5.png)

近年来，动物模型在某些方面进行了改造，以提高临床价值。其中一种方法是创建人源化的小鼠模型。该模型主要代表之一是创建患者衍生的异种移植(PDX)模型。在最近的几年里，研究评估了化疗在这些模型的准确性，并发现在大多数情况下，PDX模型的化疗反应与患者之间存在显著相关性。此外，PDX模型具出显著的异质性，很好的反应了其亲代肿瘤在遗传和功能水平上的特征。因此，由于其具有良好的临床上的相关性，近些年被广泛应用。

6、[如何创新？](https://mp.weixin.qq.com/s/Uftlhv9V_2nFfXxwewPIIQ)

![](https://files.mdnice.com/user/33257/2df3b102-91a1-4aba-9fbf-13892db3a362.png)

本文分享的是诺奖得主Karl Barry Sharpless教授2008年11月在中国天津大学 Honeywell Nobel Lecture 上给过的一个异常而且极为精彩的演讲。报告的题目是：“How to find something new”（如何发现新事物），Barry一生做过很多重要的演讲，但这个演讲可以说是其中最特殊的一次！

> “科学家中有收藏家，分类者和强迫症患者。从性格上讲，他们之间许多是侦探，许多是探险家；有些是艺术家，有些则是工匠。”

7、[IGV说明书](https://mp.weixin.qq.com/s/HmBvF0Sq_6vvTKYlzVgwnQ)

![](https://files.mdnice.com/user/33257/e91216d4-0aee-4133-82f1-4aacd0e6a75a.png)

IGV，Integrative Genomics Viewer 交互式基因组浏览器，它是一种高性能的可视化工具，主要用来交互式地探索大型综合基因组数据。例如，可视化基因组突变信息，为基因组突变结果提供更加直观可靠的信息，它支持各种数据类型，包括array-based的和下一代测序的数据和基因注释。IGV的作用并不是找突变，而是可视化突变结果。在科学文献中经常会出现使用IGV来展示突变的结果。

- 工具链接：https://igv.org/

## 工具

8、[plot1cell | 单细胞可视化R包](https://github.com/TheHumphreysLab/plot1cell)

![](https://files.mdnice.com/user/33257/faec8e02-67dc-442a-a60a-43d2b061106a.png)

plot1cell包提供了Circlize plot、Dotplot、Violin plot、Umap geneplot、ComplexHeatmap、Upset plot、Cell proportion plot等多种类型的单细胞可视化功能，并且功能在不断地更新中。

9、[rcssci包 | 限制性立方样条全自动切点靓图](https://mp.weixin.qq.com/s/UBd36b9LqB4IqiZsRoyPmQ)

![](https://files.mdnice.com/user/33257/9cc4a49a-a601-4992-b5f1-e203da16f033.png)

RCS(Restricted Cubic Spline或Natural cubic splines )实质上是通过选择节点的位置和数量，拟合样条函数RCS（X），使得连续变量X在整个取值范围内呈现光滑的曲线；开发的rcssci包V1.0版核心函数有3个，rcssci_cox、rcssci_logistic、rcssci_linear，分别适合于模型为等比例风险cox模型，经典二分类logistic和一般线性模型。

10、[ggcoverage | 基因组可视化R包](https://github.com/showteeth/ggcoverage)

![](https://files.mdnice.com/user/33257/13c7f9c8-ef1a-44af-8df7-b13b99394877.png)

ggcoverage 基于ggplot2编写的基因组可视化R包，支持多种NGS数据，如WGS, RNA-seq, ChIP-seq, ATAC-seq等。

11、[Startme | 自定义你的浏览器主页](https://zhuanlan.zhihu.com/p/493675070)

![](https://files.mdnice.com/user/33257/5685b887-3746-479c-86ea-a2830127ff32.png)

一个功能全面、超级实用的浏览器主页Startme（<https://about.start.me/>），可以帮助你提高工作效率，构建你的个人办公学习空间。

## 资源

12、[看见统计：统计学入门教程](https://seeing-theory.brown.edu/cn.html#firstPage)

![](https://files.mdnice.com/user/33257/cf46b32c-57ab-48ed-9839-56733d3c653a.png)

统计学正迅速成为数学中最重要和多学科的领域，看见统计致力于用数据可视化让统计概念更容易理解，目前内容包括：基础概率论、进阶概率论、概率分布、统计推断：频率学派、统计推断：贝叶斯学派和回归分析。

13、[oddgenes注释知识库](https://github.com/cmdcolin/oddgenes)

![](https://files.mdnice.com/user/33257/c26ccd2c-0eb5-4e69-8ff8-293dc2a7776d.png)

该github仓库收藏了一系列少见、新奇的基因注释(比如1bp length exon)。

14、[正则表达式快速入门](https://www.regular-expressions.info/quickstart.html)

![](https://files.mdnice.com/user/33257/5fb9bb6b-b5f4-465c-97a8-0aec2239c507.png)

Quick Start可以让您快速掌握正则表达式。显然，这个简短的介绍不能解释关于正则表达式的一切。有关详细信息，请参阅[正则表达式教程](https://www.regular-expressions.info/tutorial.html)。快速入门中的每个主题都对应教程中的一个主题，因此您可以轻松地在这两个主题之间来回切换。

15、[网站资源集合](https://mp.weixin.qq.com/s/_dpyNeywKsj0DnxUlrnI-g)

![](https://files.mdnice.com/user/33257/c4f7babe-fe97-43a2-acbe-6a1630f49612.png)

该推文整理了一些日常生活中可以直接访问的常用网站资源。

## 历史上的本周

- 2021：[第 9期：统计建模之道和术](https://mp.weixin.qq.com/s/wBUAQCPHXlUWSUYBP9Rh9Q)

## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`（王诗翔）
- `@kkjtmac`（阚科佳）
- `@NiEntropy`（赵启祥）
- `@He-Kai-fly`（何凯）
- `@JnanZhang`（张佳楠）
- `@Tomcxf`（陈啸枫）
- `@wangdepin`（王德品）

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

