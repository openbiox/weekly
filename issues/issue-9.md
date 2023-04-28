---
date: "2023-2-17"
comments: true
---

# 生信爱好者周刊（第 9 期）：统计建模之道和术 

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/ShixiangWang/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/ShixiangWang/weekly/issues/258)

## 封面图


![太极](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-20/1637420054535-image.png)

（[via](https://www.guoyi360.com/tj/tjt/12_5.html)）

## 本周话题：[统计建模之道和术](https://mp.weixin.qq.com/s/7yxkb9-SjvqZcHvk3r04vA)


我认为一个更基本的对统计建模的二分是其原理与技术。中国人会把前者称为道 （“路线”、“原理”或“整体思想”），而把后者称为术（“技术”、“技巧”或“方法”）。想要准确地描述统计建模的这两个方面并不容易。以下是我的大致想法：

术：在这种观念下，统计分析始于一些由其他人准备好的数据集。我们的目标是尽可能好地分析数据集，但具体的任务通常取决于分析方法的复杂程度。这个方法可以是一个简单的线性回归或者一个有十亿个参数的神经网络。

道：在这种观念下，统计分析始于科学、工程或商业问题。我们的目标是了解问题背后的机理，并利用统计结论来更好地进行决策。这个问题可能是估计某种干预的因果效应，或是理解已有数据集的局限性。

（来源：公众号「统计之都」）


## 生信科技动态

1、[Nature｜可解释深度学习用基因组图谱预测前列腺癌转移状态](https://mp.weixin.qq.com/s/o64e5RmZ__iI-yHoJf4h8g)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-20/1637420630924-image.png)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-20/1637420646875-image.png)


麻省理工学院、哈佛大学等高校联合在*Nature*发表了*Biologically informed deep neural network for prostate cancer discovery*。该研究提出可解释深度学习P-NET模型，该模型能够在前列腺癌症患者基因属性的基础上结合生信中的层次信息预测癌症的状态。

P-NET的生物学可解释性揭示了已建立的基因与新基因变异的相关候选基因，如MDM4和FGFR1，这些基因与预测晚期疾病有关，并在体外进行验证。

广泛的来说，生物学上知情的完全可解释的神经网络使前列腺癌的临床前发现和临床预测成为可能，并可能在各种癌症类型中具有普遍的适用性。

2、[Transformer新玩法登Nature子刊：DeepMind用新变体读取DNA长序列，瞄准遗传病高发区域](https://mp.weixin.qq.com/s/LCI4vDopwb6wl8YS34eXVQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-20/1637420848892-image.png)


DeepMind与谷歌旗下生物科技公司 Calico 的一项研究登上了国际顶级方法学期刊*Nature Methods*。在这篇论文中，他们引入了一种叫做 Enformer 的神经网络架构，大大提高了根据 DNA 序列预测基因表达的准确性。为了进一步研究疾病中的基因调控和致病因素，研究者还公开了他们的模型及其对常见遗传变异的初步预测。

3、[国家生物信息中心在核酸研究发表单细胞DNA甲基化数据库—scMethBank](https://mp.weixin.qq.com/s/YelQgkfp5CLA_Jfe1qgEKQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-20/1637421009308-image.png)


DNA甲基化是表观遗传研究的一个重要层面，且与发育、衰老和疾病的发生发展密切相关。为了更好地利用已公开的海量甲基化数据，此前，中国科学院北京基因组研究所国家基因组科学数据中心（以下简称基因组数据中心）已经发布了一个DNA甲基化的综合性数据库MethBank（https://ngdc.cncb.ac.cn/methbank/），涵盖了多物种高质量的全基因组单碱基精度甲基化图谱、健康人参比甲基化组以及人工审编的甲基化分析工具集。这里，我们介绍基因组数据中心最新发布的单细胞甲基化数据库——scMethbank（https://ngdc.cncb.ac.cn/methbank/scm/）。

该项研究成果以*scMethBank: a database for single-cell whole genome DNA methylation maps*为题于2021年9月在国际学术期刊《核酸研究》（Nucleic Acids Research）在线发表。


## 文章

1、[R使用正则表达式匹配任何模式的初学者指南](https://regenerativetoday.com/a-beginners-guide-to-match-any-pattern-using-regular-expressions-in-r/)

正则表达式只不过是匹配文本或文本文件中的模式的字符序列。在许多编程语言中，它被用于文本挖掘。在所有语言中，正则表达式的字符都非常相似。但在不同的语言中，提取、定位、检测和替换的功能是不同的。本文介绍在R中如何使用和操作正则表达式。

2、[使用Python的XGBoost参数调优完整指南](https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/)

XGBoost算法已经成为许多数据科学家的终极武器。这是一种高度复杂的算法，强大到足以处理各种不规则数据。使用XGBoost构建模型很容易。但是，使用XGBoost改进模型是困难的。该算法使用多个参数。为了改进模型，必须进行参数优化。很难回答一些实际问题，比如：应该调优哪一组参数？为了获得最佳输出，这些参数的理想值是多少？

3、[R-操作数据库](https://shixiangwang.github.io/home/cn/post/2019-11-20-r-operate-database/)


本文介绍如何通过RSQLite操作关系型数据库。


4、[usethis包新增`pr_*`系列函数](https://www.garrickadenbuie.com/blog/pull-request-flow-usethis/)



![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-20/1637421355838-image.png)





## 工具

1、[r-script](https://github.com/joshkatz/r-script)

一个简单的小模块，用于将数据从NodeJS传递给R（并返回）。

2、[RestRserve](https://github.com/rexyai/RestRserve)

RestRserve是一个R web API框架，用于构建高性能和健壮的微服务和应用后端。在类unix系统上使用Rserve后端，它被设计成并行的。

3、[ggh4x](https://github.com/teunbrand/ggh4x)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-20/1637421628707-image.png)


ggh4x包是ggplot2扩展包。它提供了一些实用功能，这些功能并不完全符合“图形语法”的概念——它们可能有点笨拙——但在调整你的ggplot时仍然有用。示例包括调整facet的大小，将多种美学映射到颜色，以及为facet指定单独的比例。除此之外，它也是geoms, facets, positions, guides和stats的集合。


4、[r-codespaces](https://github.com/jakubnowicki/r-codespaces)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-20/1637421689517-image.png)


GitHub代码空间配置的R和Shiny。

## 资源

1、[一本从零开始全面了解贝叶斯优化过程的书籍](https://mp.weixin.qq.com/s/q-F139FODvvhnIfvOcycHw)

2、[临床基因组分析相关数据库汇总](https://mp.weixin.qq.com/s/MCYfgbtWWg3m7gxESo8iCw)

## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者往期的赞赏：

- \*林

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）
