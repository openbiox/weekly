---
date: 2023-11-26
comments: true
---

# 生信爱好者周刊（第 101 期）：一生不被允许gap的中国人

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图


![](https://files.mdnice.com/user/37191/259b737e-8368-4f58-95b5-0f8cd42695bc.png)

## 本周话题：[一生不被允许gap的中国人](https://mp.weixin.qq.com/s/aydE2Smid_fcSqMhzPOD4w)


![](https://files.mdnice.com/user/37191/25a2185c-3db3-4fb3-8c74-00c6bcaec925.png)


>说到按部就班，国人就像是一具具被上紧发条、设置好程序的机器人。
>
>一生都在努力的上岸，不被允许有别的思想。
>
>那上岸之后呢？
>
>还会有下一个“岸”。
>
>于是有了网友的自嘲：“中国人是泡在水里了吗？”

`@Tomcxf`：我们从小就被教导好好学习，考上大学然后就可以如何如何，仿佛考入大学后美好的未来就已经收入囊中，可现实是世间没有所谓的标准答案，也没有那么多所谓的理所当然。所以，当对未来感到迷茫时，学生时代的惯性总是驱使我们向身边的人看，于是继续陷入相同的怪圈中不能自拔。

## 生信研究

1.[Science |  利用scCRISPR高通量研究GWAS位点的靶基因和途径](https://mp.weixin.qq.com/s/1PAQZal7zu6AP3W_MaF0oQ)

![](https://github.com/openbiox/weekly/assets/97931116/83164e19-416e-454e-bdba-418ea4ae51a7)

全基因组关联研究（GWAS）已经确定了数千种与疾病结果和疾病相关表型相关的遗传变异，但这些关联几乎总映射到非编码区域，因此难以捉摸它们的靶基因和功能，这也被称为variant-to-function（V2F）问题。本文作者利用英国生物银行（UKBB）中29种血液性状GWAS和来自血细胞联盟（BCX）的15种性状，筛选出候选顺式调控组件（candidate cis-regulatory elements，cCREs），然后利用CRISPR抑制（CRISPRi）技术批量干扰这些位点，并结合单细胞转录组和蛋白质组测序，分析这些位点对基因和蛋白质表达的影响。作者还使用碱基编辑技术（base editing）精确插入特定的GWAS变异，进一步验证这些变异的因果作用。

- 原文链接：https://www.science.org/doi/10.1126/science.adh7699

2. [NAR | STOmicsDB：用于时空组数据共享、分析和可视化的综合数据库](https://mp.weixin.qq.com/s/64XLj-h5paIPHOOTok6jVw)

![](https://files.mdnice.com/user/37191/67d547b6-aa95-4b8a-802a-d02cb882fcc3.png)


时空组学的最新技术发展使研究人员能够在单细胞水平上检测细胞的基因表达及其空间位置，从而对生物过程产生详细的生物学见解。综合数据库可以促进时空组数据的共享并简化研究人员的数据获取过程。

2023年11月11日，由深圳国家基因库和华大生命科学研究院共同研发的时空组学数据库（STOmicsDB）在国际学术期刊《Nucleic Acid Research》在线发表，STOmicsDB是一个用户友好的时空组学综合数据库，为时空组学研究提供“一站式”服务。

- 数据库链接：https://db.cngb.cn/stomics/

3.[Cancer Commun | 基于辅助化疗后残留ctDNA可有效预测II-III期胃癌复发](https://mp.weixin.qq.com/s/pSacPYaKgrxFBHLFj7ZOzQ)

![](https://github.com/openbiox/weekly/assets/25057508/e43bdfaf-7ed8-4b9c-9a22-77797f66eeb4)

中山大学肿瘤防治中心王峰、周志伟、徐瑞华团队合作对100例II/III期可切除GC患者的ctDNA进行了分析，使用425基因NGS panel准确捕获了ctDNA的肿瘤特异性体细胞突变，探究了ctDNA检测能否预测围手术期或ACT后的疾病复发，并分析了ctDNA作为术后反应评估生物标志物的附加价值。研究表明，ACT术后残余ctDNA可有效预测II/III期胃癌的高复发风险，结合组织基础和循环肿瘤特征可更好地实现风险预测。

- 论文链接：https://onlinelibrary.wiley.com/doi/10.1002/cac2.12494

## 博文资讯

4. [R session中软件包依赖关系网络](https://mp.weixin.qq.com/s/mKm97haa_L2WIeJPz8SKzA)

![](https://files.mdnice.com/user/37191/becd10d3-6d4f-443b-995c-1134fe0dfce0.png)

在R markdown文档中将sessionInfo()放在末尾几乎已经成为一种标准。sessionInfo()能够打印出加载到R session中的的包的列表。但这些包之间的依赖关系又如何呢？在这篇博文中，让我们来看看。

5.[和降维图保持一致的细胞类群统计图](https://mp.weixin.qq.com/s/PRStNRokP3oCgGStbiNRLw)

![](https://github.com/openbiox/weekly/assets/25057508/c3d618f2-6f92-4b8f-b073-f5faca7f3552)

Y 叔团队正在开发名为 `ggsc` 的包用于更优雅地可视化单细胞数据分析结果。在本文中，它展示了在组合图形时如何保持调色板的一致性。



6. [Seurat 版本4和5共存](https://mp.weixin.qq.com/s/Lyxaoz8A7TK8TnqqfJyziQ)



![](https://files.mdnice.com/user/37191/2c37f674-6fff-4370-88d4-9a2c8f2104a3.png)


Seurat升级了，更快了，能够应对更大的数据集了，当然还有新功能。升级是肯定的，但现在的问题是Seurat善于折腾用户，每次大版本更新，数据结构都有所改动，会有兼容问题。比较好的解决办法是同时安装两个版本的Seurat，于是Y叔将把版本4改名成Seurat4，让两个包可以共存。

## 工具

7. [ggkegg](https://github.com/noriakis/ggkegg "ggkegg")


![](https://files.mdnice.com/user/37191/bb27511c-fbb3-439e-976a-f07f8bfc14fa.png)


ggkegg是一组可以与tidygraph、ggraph、ggplot2配合的，用于分析和绘制 KEGG 信息的函数。


8. [torchdrug](https://github.com/DeepGraphLearning/torchdrug "torchdrug")



![](https://files.mdnice.com/user/37191/48793dc4-6d44-4d49-988a-31c4b358e97f.png)



TorchDrug 是一个基于 PyTorch 的机器学习工具箱，被设计用于多种用途：

- 在 GPU 支持下以 PyTorchic 风格轻松实现图形操作
- 对药物发现知之甚少的从业者友好
- 支持用于机器学习研究的快速原型设计

9. [这一款 Mac 系统终端工具，已经用的爱不释手了！](https://mp.weixin.qq.com/s/05z7Bog8Jkqxko5sbkjyPg)


![](https://files.mdnice.com/user/37191/028f41e9-3a54-4d46-bc9d-85885aa63720.png)


作为程序员或者运维管理人员，我们经常需要使用终端工具来进行服务器管理及各种操作，比如部署项目、调试代码、查看/优化服务、管理服务器等。

相信大家用的最多的终端工具就是 Xshell、iTerm2和Mobaxterm，尽管这些成熟的终端工具也很好，但是如果有更好用更灵活且强大的工具，我们可以一一体验选择适合自己的那一款。

在Windows系统上的终端工具百花齐放，但是Mac系统上的好用的终端工具却寥寥无几！今天推荐的这款Mac平台终端工具 Warp 就深得我心！小编从去年刚开始用，已经爱不释手了！

## 资源

10.[大语言模型教程](https://mp.weixin.qq.com/s/MQGTbpPvxDAQ8moo7aTKMQ)

![image](https://github.com/openbiox/weekly/assets/97931116/e462f2ca-5673-4150-b6f2-5091ab2ba420)

大型语言模型（LLMs）是一种基于Transformer的神经网络架构，可以在大量未标记的文本数据上进行预训练，然后根据不同的任务进行微调或零样本转换。本文是LLMs的教程，作者介绍了LLMs的基本原理、不同的训练和微调方法、以及一些应用和挑战。

11. [CRISPR screening 分析软件 MAGeCK](https://sourceforge.net/p/mageck/wiki/Home/ "CRISPR screening 分析软件 MAGeCK")

MAGeCK是一种计算工具，用于从最近的基因组规模 CRISPR-Cas9 敲除筛选（或 GeCKO）技术中识别重要基因。MAGeCK由Dana-Farber癌症研究所Xiaole Shirley Liu博士实验室的Wei Li和Han Xu开发，并由美国国家儿童医学中心的Wei Li实验室积极更新。

12. [分享18个单细胞数据分析数据库](https://mp.weixin.qq.com/s/apdbAdpbHmHyqCQHkKXYyQ)


![](https://files.mdnice.com/user/37191/3ce7eaa0-15ba-4eac-979c-a6b596b83993.png)


## 历史上的本周
- 2023 [生信爱好者周刊（第 61 期）：基因对寿命的影响](https://mp.weixin.qq.com/s/AodRQ2z1XBXiweQTUoED9Q)

## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`（王诗翔）
- `@kkjtmac`（阚科佳）
- `@NiEntropy`（赵启祥）
- `@He-Kai-fly`（何凯）
- `@JnanZhang`（张佳楠）
- `@Tomcxf`（陈啸枫）
- `@wangdepin`（王德品）
- `@kongjianyang`（空间阳）
## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。


![](https://files.mdnice.com/user/37191/484e56e7-6d4d-41a3-a70c-53e240bb2dcd.png)


（完）