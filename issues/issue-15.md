---
date: 2023-02-23
comments: true
---

# 生信爱好者周刊（第 15 期）：科学家的层次

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/openbiox/weekly/issues/392)

## 封面图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-8/1641657309511-image.png)

（[via](https://mp.weixin.qq.com/s/Y1BXowa7PAwxlu5Lzu2GPQ)）


## 本周话题：[科学家的层次](https://mp.weixin.qq.com/s/rFCUpNj2GgI6TMjsR9o5rg)

这周话题分享饶毅教授的评述。

> 三流及以上对99.99999%国人学者来基本是梦想，请看上面链接的原文。希望大家都脱离九流，做着六七流，勇争四流。

四流：研究的科学或应用意义被同学科科学家交口称赞，二十年内都知道其代表性重要工作，为本学科中坚；

五流：研究意义一般科学工作者误认为很有噱头，虽然少数优秀科学家早就看穿其局限性，挡不住这类科学研究在短时间得到很多瞩目，研究者个人得到利益，但其研究结果不到十年就被同一学科所忘记。

六流：很能总结研究结果，特别能够发文章，无论研究本身有没有意义，虽然优秀科学家很快嗤之以鼻，但研究者有办法把文章发表在读者多的场景，例如发表在Nature。读者还不少，但两周内大家都不记得做了什么，一个月后自己也说不清楚发现了什么，灰飞烟灭；

七流：做完研究自己都不记得为什么科学原因而开始研究，但能够发文章，还有少量读者，对其他人的研究永远没有影响；

八流：能够自己设计课题，勉强能够发表，在国际上主要是只能职业爬坡，在某些局部环境被认为是科学家，文章无人阅读，同一课题组也不再继续做；

九流：不知道该研究什么，为了职业不断模仿其他人的研究。


## 生信科技动态

1、[Cell | 加州大学任兵团队发表迄今最大规模人类单细胞染色质可及性图谱](https://mp.weixin.qq.com/s/Y1BXowa7PAwxlu5Lzu2GPQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-8/1641657596251-image.png)


全基因组关联研究（GWAS）已经确定了数十万种与人类特征和疾病广泛相关的遗传变异，这些变异大多数是非编码的。此外，研究发现疾病相关组织和细胞类型中的候选顺式调节元件（CCRE）富含非编码疾病风险变异，因此科学家们推测非编码变异影响疾病风险的主要机制是通过影响特定细胞类型中的转录调节元件。但由于缺乏人类基因组中调控元件的细胞类型解析图，这些非编码变异的注释仍具有挑战性。

美国加州大学圣地亚哥分校任兵教授课题组在Cell上发了题为“*A single-cell atlas of chromatin accessibility in the human genome*”的研究文章。研究人员使用改良的单细胞测序技术sci-ATAC-seq对来自多个个体30种成人组织类型的615998个细胞进行了染色质可及性分析，并将这些数据与15种胎儿组织类型的细胞染色质可及性图谱相结合，绘制了迄今最大规模的人类单细胞染色质可及性图谱。该图谱在222个细胞亚型中注释了近120万个CCRE，为揭示细胞类型与疾病的相关性，发现人类细胞类型的相关治疗靶点，以及人类复杂疾病的致病机理提供了宝贵的参考资源。（资源获取：http://catlas.org/humanenhancer）

2、[Nature Methods | 李明瑶团队发表空间转录组数据分析的新算法SpaGCN，可检测出具有空间表达模式的SVG](https://mp.weixin.qq.com/s/4SlSQt4VkSAOJkNS5JUmMA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-9/1641657660637-image.png)

近年来，空间转录组（Spatially Resolved Transcriptoms, SRT）技术的进步使得利用组织中的空间信息进行基因表达谱分析成为可能。目前，关于SRT的实验策略大致可分为两类：第一类是具有单细胞分辨率的原位杂交或测序技术（包括seqFISH、MERFISH等），能够检测单个细胞中数百到数千个基因的表达水平；第二类是基于原位捕获的技术（包括SLIDE-seq和10x Visium等），即先进行空间条形码编码再进行测序，可以检测捕获特定位置中数千个基因的表达水平。这些不同的SRT技术使得揭示异质组织的复杂转录结构成为可能，并增强了人们对疾病细胞机制的理解。 

本文提出了空间转录组数据分析的新算法SpaGCN。SpaGCN首先构建表示数据空间依赖性的无向加权图，再将基因表达、空间位置和组织学进行整合来识别空间域。此外，SpaGCN还可以检测每个空间域丰富的SVG，通过将搜索空间限制在空间域上，以保证检测到的SVG都具有空间表达模式。SpaGCN适用于分析多种类型的SRT数据，包括ST、10x Visium、SLIDE-seqV2等。  



## 文章

1、[Creating a custom color palette class with vctrs](https://www.wjakethompson.com/blog/taylor/2021-10-24-taylor-palettes/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-9/1641657862929-image.png)

本文介绍如何使用vctrs创建一个自定义的调色板🎨。

2、[A Zotero Workflow for R](https://www.anthonyschmidt.co/post/2021-10-25-a-zotero-workflow-for-r/)

这篇简短的博客文章的目的是概述作者写论文时正在使用的软件包和工作流。

3、[PD-1与PD-L1的6大区别](https://mp.weixin.qq.com/s/B--1OB8miM17Gfr21RwDfg)


## 工具

1、[“文献单词”微信小程序](https://mp.weixin.qq.com/s/j7o2sav6tmmLIPsblr0-Dw)

“文献单词”指的是文献中的高频词汇，它们有特殊的用法，不同学科也有对应的专业英语，因此其范畴和四六级单词不同。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-9/1641658233174-image.png)

2、[Python 图形界面框架 PyQt5](https://mp.weixin.qq.com/s/Cod1O4C7YlM_IsxcF_d_8Q)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-9/1641658311359-image.png)

3、[mlverse生态：扩展数据科学的开源库](https://github.com/mlverse)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-9/1641658386173-image.png)


4、[iCOBRA：对排名和分配方法进行交互式基准测试](https://github.com/csoneson/iCOBRA)

iCOBRA是一个软件包，用于计算和可视化排序和二进制赋值方法的性能指标。一个典型的用例可以是，例如，在基因表达实验中比较调用差异表达的方法，这可以被看作是一个排序问题(估计正确的效应大小并根据显著性对基因排序)或一个二元分配问题(将基因分为差异表达和非差异表达)。

## 资源

1、[The Innovation | 视频: Y叔谈clusterProfiler 4.0 前沿应用](https://mp.weixin.qq.com/s/xUJ4Z7_IFrgcBUgg1W4_HA)

2、[视频：国自然申请书撰写经验分享](https://mp.weixin.qq.com/s/MZEfPlXk8-4jI8n7iSRKJg)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

