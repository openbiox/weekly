---
date: 2023-02-27
comments: true
---

# 生信爱好者周刊（第 19 期）：2022年值得关注的7大前沿技术

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/ShixiangWang/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/ShixiangWang/weekly/issues/480)

## 封面图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645929796354-image.png)

端粒到端粒（T2T）合作组正在对所有染色体进行测序。来源：Adrian T. Sumner/SPL


## 本周话题：[2022年值得关注的7大前沿技术](https://mp.weixin.qq.com/s/xdOZv6n2HI4YVWCy9Z_58Q)

从基因编辑到蛋白质结构解析，再到量子计算，以下七项技术或在科学界产生重大影响。

1. 完整版基因组
2. 蛋白质结构解析
3. 量子模拟
4. 精确基因组调控
5. 靶向基因疗法
6. 空间多组学
7. 基于CRISPR的诊断

可以看到几乎都与生命科学有关系。但未来国内如果想要深入和快速发展和应用相关技术，科技工作者需要被更好地管理和培养。

## 生信科技动态

1、[Briefings in Bioinformatics | SGANRDA - 预测circRNA与疾病关联的半监督生成对抗网络](https://mp.weixin.qq.com/s/M--XQgWxzj-WCACNz1-Atw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645930258335-image.png)


环状RNA（circRNA）在复杂人类疾病的诊断、发生和预后中起着至关重要的作用。与传统的生物实验相比，融合多源生物数据以识别circRNA与疾病之间的关联的计算方法可以有效地降低成本和节省时间。考虑到现有计算模型的局限性，作者提出了一种半监督生成对抗网络模型SGANRDA，用于预测循环RNA-疾病关联。

2、[NAR | RiboDetector - 高通量测序数据鉴别和去除rRNA序列利器](https://mp.weixin.qq.com/s/vHdYbXlEGV_DekRQorh9PA)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645930404045-image.png)

RiboDetector是一款用于从宏基因组、宏转录组、ncRNA和核糖体测序数据中准确而快速地检测和去除rRNA序列的软件（https://github.com/hzi-bifo/RiboDetector）。它是基于深度学习的BiLSTM（一款双向的循环神经网络架构）开发的软件。跟基于比对和隐马尔科夫模型的方法相比RiboDetector能抓取更长距离的序列特征，从而具有更好的准确性。文章中对比了目前常用的其他5款工具。在测试数据上，RiboDetector比其他软件的错误预测率低6到2000倍。另外它的CPU模式运行比目前最常用的软件有10倍左右的速度提升，而在GPU模式上实现了50倍左右的运行速度提升（见下图B-C）。文章中分析表明RiboDetector有很好的泛化能力，能预测发现新的rRNA（和数据库中已知rRNA相似性低于90%）序列。最后，在测试数据上它的假阳性预测序列没有显著的对某些功能的偏向性（没有GO term显著富集在假阳性预测的序列中）

3、[Neuron | 大脑的学习方式如何，机器学习与生物学习的联系将提供「答案」](https://mp.weixin.qq.com/s/idMNDCz5_AZ01Sp7aHwlHQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645930537983-image.png)


大脑的变化如何导致学习？要回答这个问题，请考虑人工神经网络 (ANN)，通过优化给定的目标或成本函数来进行学习。这种优化框架可能会提供有关大脑如何学习的新见解，因为神经活动的许多特殊特征可以通过经过训练，以执行相同任务的 ANN 来概括。

然而，在整个学习过程中神经群体活动如何变化的关键特征无法用优化来解释，也不是 ANN 的典型特征。在这里，详细介绍了其中的三个特征：

（1）整个学习过程中神经可变性的不灵活性；

（2）即使在简单任务中也使用多个学习过程；

（3）存在与任务无关的大型活动变化。

科学家认为，理解这些特征在大脑中的作用将是使用优化框架描述生物学习的关键。

## 文章

1、[eXtreme Gradient Boosting (XGBoost): Better than random forest or gradient boosting](https://liuyanguu.github.io/post/2018/07/09/extreme-gradient-boosting-xgboost-better-than-random-forest-or-gradient-boosting/)

本文通过实例介绍和对比了XGBoost, Gradient Boosting (GBM), Random Forest, Lasso, Best Subset几种算法。

2、[Sankey Diagram in R](https://plotly.com/r/sankey-diagram/)

本文介绍使用plotly绘制桑基图。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645930862743-image.png)

3、[Tabby：这个开源的终端工具更酷炫](https://mp.weixin.qq.com/s/8DykoYoLAtG9XIPF3dDXzQ)

本文介绍Tabby的安装和使用。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645930975380-image.png)

4、[一文读懂基因组浏览器绘制文件 bigwig](https://mp.weixin.qq.com/s/6e-un6dmTi1sMbhL0aPDeQ)

bigwig是一种常见的基因组文件格式，本文介绍它的特点、应用场景和相关工具。


## 工具

1、[pybedtools: Python wrapper -- and more -- for Aaron Quinlan's BEDTools (bioinformatics tools)](https://github.com/daler/pybedtools)

瑞士军刀[bedtools](http://bedtools.readthedocs.org/)是基因组区间数据处理的标杆，pybedtools提供了一个python接口。

```python
from pybedtools import BedTool

snps = BedTool('snps.bed.gz')  # [1]
genes = BedTool('hg19.gff')    # [1]

intergenic_snps = snps.subtract(genes)                       # [2]
nearby = genes.closest(intergenic_snps, d=True, stream=True) # [2, 3]

for gene in nearby:             # [4]
    if int(gene[-1]) < 5000:    # [4]
        print gene.name         # [4]
```

2、[rawgraphs - 表格数据分析和可视化平台](https://mp.weixin.qq.com/s/VSidDGcV8OChE8CHBiiT8g)

2013 年，来自米兰理工大学的一个研究室 DensityDesign，正式发布了 RAWGraphs。

项目诞生的初衷，主要是在于帮助设计师与开发者，打通电子表格应用与矢量图形编辑器之间的桥梁，让数据与图形的对接，变得更加流畅丝滑。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645931228005-image.png)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645931262823-image.png)

3、[multicolor - 丰富你的信息输出的R包](https://github.com/aedobbyn/multicolor)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645931419107-image.png)

4、[edgebundle - edge bundling算法实现R包](https://github.com/schochastics/edgebundle)

包含的算法实现：

- Force directed edge bundling
- Stub bundling
- Hammer bundling
- Edge-path bundling
- TNSS flow map
- Multicriteria Metro map layout



![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-27/1645931608469-image.png)


## 资源

1、[Machine-Learning-From-Scratch](https://github.com/Yimeng-Zhang/Machine-Learning-From-Scratch)

每天30分钟，系统梳理机器学习的各个知识点，概念+原理+代码。

2、[Bioinformatics-training-collection](https://github.com/BioinformaNicks/Bioinformatics-training-collection)

这是一个学习生物信息学相关工具和语言的资源集合。

2、[Gene set enrichment analysis for genome-wide DNA methylation data](http://oshlacklab.com/methyl-geneset-testing/)

包含一系列甲基化分析的文档。


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者往期的赞赏：

- 李浩

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

