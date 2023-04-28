---
date: 2023-02-24
comments: true
---

# 生信爱好者周刊（第 16 期）：癌症新特征

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/ShixiangWang/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/ShixiangWang/weekly/issues/428)

## 封面图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-16/1642323259179-image.png)

> Cancer Discov. 2022; 12: 31-46. 

## 本周话题：[癌症新特征](https://mp.weixin.qq.com/s/mpxVT3BdL8Xr3nJxxGA05w)

*Hallmarks of Cancer*发布第3版。在既往10个特征的基础上，再一次增加了4个特征，分别是：1、解锁表型可塑性（Unlocking phenotypic plasticity），而表型可塑性可以破坏细胞分化。2、衰老细胞（Senescent cells），细胞衰老被认为是维持组织稳态的一种保护机制，然而越来越多的证据提示，在某些情况下，衰老细胞可以各种方式促进肿瘤的发生、发展。3、非突变表观遗传重编程（non-mutational epigenetic reprogramming），表观遗传即DNA序列没有发生变化，但基因功能发生了可遗传的变化。4、多态微生物组（Polymorphic microbiomes），存在于结肠、其他黏膜及其连接器官，或肿瘤自身的微生物组。前两个特征为“新出现的特征”，后两者为“赋予的特征”。

Hallmarks的又一次更新是人类从新方向研究癌症近期结果的汇总，拓展了癌症研究的纲要和主要研究范围。

## 生信科技动态

1、[Nature Methods | 结合DNA远端互作的高精度基因表达预测模型——Enformer](https://mp.weixin.qq.com/s/6SAQ9zFJpDFDz7HvUqoAVw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-16/1642323805924-image.png)

结合DNA远端互作预测基因表达和染色质状态的计算模型可以帮助更好地理解转录调控以及变异对转录调控的影响，补充基于人群的关联研究。

本文通过Enformer整合了来自基因组的远端互作信息，能够更准确的预测变异效应。此外，Enformer结合了直接从DNA序列预测增强子-启动子相互作用的方法，使得精细映射人类疾病成为可能。

2、[Nature Machine Intelligence | 基因组学中高效设计深度卷积神经网络的自动化框架](https://www.nature.com/articles/s42256-021-00316-z)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-16/1642324243811-image.png)


卷积神经网络(cnn)已成为生物序列分析的标准。网络架构的调整对于CNN的性能至关重要，但它需要大量的机器学习知识和投入的时间和精力。因此，这一过程对现代深度学习在基因组学中的广泛和有效应用造成了重大障碍。在这里，我们提出了生物循证研究的自动化建模(AMBER)，一个完全自动化的框架，有效地设计和应用基因组序列的cnn。AMBER通过最先进的神经结构搜索(NAS)为用户指定的生物问题设计最优模型。我们将AMBER应用于基因组调控特征建模的任务中，并证明了AMBER设计的模型的预测明显比等效的基线非nas模型更准确，与已发表的专家设计的模型相匹配甚至超过。琥珀建筑搜索的解释揭示了它的设计原则，利用计算操作的全空间精确建模基因组序列。此外，我们还阐明了使用AMBER在等位基因特异性结合和疾病遗传力富集中准确发现功能性基因组变异。AMBER为基因组学中设计精确的深度学习模型提供了一种高效的自动化方法。

> <https://github.com/zj-zhang/AMBER>

3、[Nature communications | ClusterMap for multi-scale clustering analysis of spatial gene expression](https://mp.weixin.qq.com/s/__xhmsBsHtwWbP2xKuIM5g)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-16/1642324420220-image.png)


在空间环境中定量RNA对于理解复杂组织中的基因表达和调控至关重要。原位转录组方法在完整组织中生成空间分辨的RNA谱。然而，目前还缺乏一个统一的计算框架来整合原位转录组数据分析。本文由此引入了一个无监督和无注释的框架，称为ClusterMap，它包含了RNA的物理位置和基因身份，将任务作为点模式分析问题，并通过密度峰聚类(DPC)识别具有生物学意义的结构。具体来说，ClusterMap在二维和三维空间中精确地将RNA聚集到亚细胞结构、细胞体和组织区域，并在各种组织类型上一致地执行，包括小鼠大脑、胎盘、肠道和人类心脏器官。本文证明ClusterMap可广泛应用于各种原位转录组测量，从具有高维转录组特征的图像中揭示基因表达模式、细胞生态位和组织组织原则。



## 文章

1、[sjPlot - R语言中的流行病数据分析神器](https://mp.weixin.qq.com/s/Ob1mkxMfyfhIt1OlEFIUzA)

此包不仅可以实现三线表的绘制，同时可以进行模型结果的可视化展示、评估。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-16/1642324693006-image.png)

2、[ComplexHeatmap：一个完全定制的注释](https://jokergoo.github.io/2021/10/17/a-completely-customized-annotation/)

本文介绍使用ComplexHeatmap进行完全自定义的注视。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-16/1642324810974-image.png)

3、[用Python构建API的八大流行框架](https://mp.weixin.qq.com/s/_xxoii0eqOHYziXQ7Q6P2Q)

本文八种可用于构建API的优秀Python框架。


## 工具

1、[ggeffects - ggplot2回归模型的边际均值估计和边际效应](https://github.com/strengejacke/ggeffects)

一个支持多种模型的可视化和预测神器。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-16/1642324978787-image.png)


2、[ggiraph - 使“ggplot”图形具有交互性](https://github.com/davidgohel/ggiraph)


```r
library(ggplot2)
library(ggiraph)
data <- mtcars
data$carname <- row.names(data)

gg_point = ggplot(data = data) +
    geom_point_interactive(aes(x = wt, y = qsec, color = disp,
    tooltip = carname, data_id = carname)) + 
  theme_minimal()

girafe(ggobj = gg_point)
```

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-16/1642325086319-image.png)

3、[ggcorrplot - 使用ggplot2可视化相关矩阵](https://github.com/kassambara/ggcorrplot)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-1-16/1642325206460-image.png)



## 资源

1、[爪哥的awesome列表](https://github.com/shenwei356/awesome)

生物信息学、数据科学、机器学习、编程语言(Python、Golang、R、Perl)和其他方面的宝贵资源。

2、[陈巍学基因】视频、文章目录](https://mp.weixin.qq.com/s/-ZfP5utoY52iJwq6y44eFg)

## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

