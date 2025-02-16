---
date: 2023-02-21
comments: true
---

# 生信爱好者周刊（第 13 期）：他开发了基因界的百科全书，贡献却少有人知

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/openbiox/weekly/issues/349)

## 封面图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-19/1639905029485-image.png)

KEGG概览。（[via](https://www.genome.jp/kegg/kegg1a.html)）

## 本周话题：[他开发了基因界的百科全书，贡献却少有人知](https://mp.weixin.qq.com/s/jQCKj7eVFUhCiSWahaLoLQ)

之前在一期的话题是什么时候有生信诺奖。这篇来自知识分子的文章提供了一个实例可以让大家进一步思考和讨论。

2018年，日本京都大学金久实教授被美国咨询公司科睿维安列为可能获诺贝尔生理医学奖的人选之一，提名理由是 “对生物信息学的杰出贡献，特别是开发了京都基因和基因组大百科全书”。京都基因和基因组大百科全书英文全称是 “Kyoto Encyclopedia of Genes and Genomes”，简称KEGG。即使从事专业生物信息工作的人也未必知道金久实教授，但略微接触过生物信息的人都会知道KEGG。

> 生物信息要解决的问题是生物数据的产生、管理和挖掘。这种旷日持久的系统性推动与支撑，与通常意义上星光灿烂的概念和技术进展相比，似乎更容易被人们忽略低估。
>
> 生物信息确实在各个方向上有力地推动了生物学研究和应用的发展。其尴尬之处在于，作为实用工具缺乏深度，而概念和技术突破又非常依赖实验设计和数据质量。就诺奖而言，生物信息最大的痛点是自身很难闭环，很难达到普遍接受的高度。

生信作为交叉学科，涉及内容广泛。我们应该从事什么方向的研究？是否要为人熟知？未来是否能为诺奖添砖加瓦？

## 生信科技动态

1、[Bioinformatics | MoNET：一个多组学网络分析R包](https://academic.oup.com/bioinformatics/advance-article-abstract/doi/10.1093/bioinformatics/btab722/6409845?redirectedFrom=fulltext)

越来越多的多组数据可用性使得在不同规模上发现疾病生物标志物成为可能。了解多组生物标志物之间的功能相互作用正变得越来越重要，因为它具有提供潜在分子机制的巨大潜力。

R包地址：<https://github.com/JW-Yan/MONET>

2、[Cancer Discovery | 31个胃癌组织的单细胞图谱](https://mp.weixin.qq.com/s/4mUsuTyIsyRZZTSK0zD9WQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-19/1639904925378-image.png)


本文利用多个病人标本的单细胞测序数据，为我们呈现一个较为全面的细胞族系、肿瘤微环境和不同分型的特异性转录组表达情况的图谱。

3、[日本研发出新型口罩 遇新冠病毒能在紫外线下发光](https://language.chinadaily.com.cn/a/202112/13/WS61b6ea6aa310cdd39bc7b020.html)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-19/1639904481665-image.png)

日本的科学家近日研发出了一种新型口罩，如果佩戴者感染了新冠病毒，这种口罩就能在紫外灯下发出亮光。有了这款口罩，人们在家中就可以自测是否感染了新冠病毒。

## 文章

1、[四个 Python 项目管理与构建工具](https://mp.weixin.qq.com/s/cZocjukUht2iHxLaIuuWgA)

文章浏览一下四个工具的使用：

- CookieCutter
- PyScaffold
- PyBuilder
- Poetry

我自己之前使用过PyScaffold写过loon这个Pypi包，用的就是PyScaffold。

2、[因果表征学习最新综述：连接因果科学和机器学习的桥梁](https://mp.weixin.qq.com/s/PUztcJA8zlTF5hWpJNdZTA)

一篇名为*Towards Causal Representation Learning*的综述文章由因果领域领军人物马普智能系统所所长Bernhard Schölkopf及深度学习三巨头之一的Yoshua Bengio等人撰写。顾名思义，何为因果表征causal representation呢？其又拥有怎样优良的性质使我们想要学习因果表征呢？

## 工具

1、[Tidy Data Tutor](https://tidydatatutor.com/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-19/1639904012060-image.png)

Tidy Data Tutor让你在浏览器中编写R和Tidyverse代码，并查看Data Frame在数据分析管道的每个步骤中如何变化。

> R包：<https://github.com/seankross/tidydatatutor>

2、[JBrowse Jupyter](https://github.com/GMOD/jbrowse-jupyter)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-19/1639904136392-image.png)

JBrowse Jupyter是一个python包，它为JBrowse视图提供了一个python接口。


3、[fastp](https://github.com/OpenGene/fastp )

一个为FastQ文件提供快速一体化预处理的工具。这个工具是用c++开发的，支持多线程以提供高性能。

## 资源

1、[Big Book of R](https://www.bigbookofr.com/index.html)

R图书书签集合，大部分是免费的。

2、[biostat2课程](https://biostat2.uni.lu/lectures.html)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-19/1639904402702-image.png)

介绍R编程以及用于生物数据处理。

## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

