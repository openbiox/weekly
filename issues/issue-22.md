---
date: 2023-02-28
comments: true
---

# 生信爱好者周刊（第 22 期）：为什么生产率在提高而我们却越来越忙

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647746124188-image.png)

美国一家神经技术新创公司 Kernel 的研究人员，开发了一种名为「Kernel Flow」的可穿戴设备，这个形似头盔的设备，采用 TD-fNIRS（时域功能性近红外光谱）技术，可通过记录局部血氧变化来测量大脑活动。（[via](https://www.ifanr.com/1476931?utm_source=rss&utm_medium=rss&utm_campaign=)）


## 本周话题：[为什么生产率在提高而我们却越来越忙](https://yihui.org/cn/2020/07/productivity-busy/)

本周的话题来自阅读谢益辉（@yihui）的这篇文章，这篇文章里面透露出的思考是发人深省的，我们生活在一个科技驱动发展的时代，但这个科技发展大多数时间并没有解放我们自身，反而让我们深陷效率之渊。

> 大半年前看到一篇文章说人类社会生产率一直在显著提高，但它带来的结果似乎只是我们在购买越来越多的东西，并同时失去越来越多的自由时间。在前工业时代，人们每周的工作时间比现在更短。按理说，如果我们对当前（物质）生活水平感到满足的话，生产率提高应该是让我们在更短的时间内完成生产工作，然后可以享受更多闲暇时间。为什么结果是反过来的呢？
>
> 信息在人与人之间毫无阻碍地快速流通，表面上让我们可以更高效地获取信息、节省等待时间，然而这样让我们也暴露在太多低价值的信息中，从而要花掉更多的精力或心理能量。比如任何人都可以轻松在 Github 上报告软件问题；尽管公平地说，多数报告的质量都还令人满意，但总有那么些低质的报告让人感到需要控制情绪去回复。或比如社交媒体对人的训练，就算没有直接与自己有关的新消息，也难免去刷一遍，看看有没有其它吸引眼睛的新事情，而刷着刷着，就花了计划外的一小时在上面。
>
> 尽管生产率在提高，但生产目标越来越高（夹杂着琐碎的目标），我们并没有因为越来越有效率而变得能越来越快处理完我们的事情。分子分母都在涨，但分子可能涨得更快。何解？我也不知，感觉这是一项艰难的平衡艺术。

拓展这个话题，我们思考更多。例如，当代信息的聚集让我们有了更多选择（的机会），但我们最终做出来最满意的结果了吗？

不知道读者们针对该话题有哪些想法，欢迎在「语雀讨论区」交流。（输入邀请码「ZIXONZ」获得3个月会员）

## 生信科技动态

1、[Science | 张泽民/季加孚/步召德等团队发表泛癌T细胞单细胞图谱](https://mp.weixin.qq.com/s/Xt0VdmqjrJlPv_lMYxZquQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647747752548-image.png)

为更好地了解肿瘤浸润T细胞的全貌，揭示癌种间的共性和特殊性，研究团队对来自21种癌症类型316名患者的肿瘤、癌旁组织和血液样本进行了scRNA测序，获得了更多癌种的T细胞数据，包括骨髓瘤、淋巴瘤、肾癌、卵巢癌、子宫内膜癌、食道癌、甲状腺癌、乳腺癌、胃癌和胰腺癌等。同时，研究团队通过创新生物信息方法整合了已发表的scRNA-seq T细胞数据，构建了系统的单细胞水平泛癌T细胞图谱（图1），涵盖了397,810个高质量T细胞数据。

2、[Nat. Biotechnol | 基于多维数据的深度融合，大幅提升空间转录组分辨率](https://mp.weixin.qq.com/s/tnEyKcK9xwDYHipjBvpUMQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647747923206-image.png)


空间转录组可帮助科研工作者在不破坏组织原有空间形态的前提下，从分子水平了解生物组织之间复杂的交互网络关系，探索关键因素与环境之间的响应和变化。为科研工作者提供了研究复杂多细胞生物在组织系统和组织互作的工具，使得全面了解组织水平的基因表达图谱成为可能。

目前，空间转录组研究的常用方法都存在局限性：基于原位测序（ISS）或杂交（ISH）的方法具有较高的分辨率和灵敏度，但通量有限，单次只能检测少数的基因，限制了其在探索全转录物相互作用时的通用性；基于原位捕获（ISC）的方法可以同时靶向所有带有poly（A）尾的转录本，但由于在组织水平的分辨率和灵敏度较低，对其应用和发展造成了限制。来自瑞典皇家理工学院（KTH）的Joakim Lundeberg教授研究团队提出了一种空间表达数据的深度生成模型，能够将ISC数据与高分辨率组织学图像结合，提升空间转录组的分辨率。

3、[Briefings in Bioinformatics | SMNN: batch effect correction for single-cell RNA-seq data via supervised mutual nearest neighbor detection](https://mp.weixin.qq.com/s/tZ38J8PRCcg9QCJ9WKWsHA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647748034163-image.png)


当整合来自多个批次的单细胞RNA测序(scRNA-seq)数据时，批效应校正被认为是必不可少的。最先进的方法忽略了单细胞聚类标签信息，但这些信息可以提高批次效应校正的有效性，特别是在生物差异与批次效应不正交的现实情况下。为了解决这个问题，我们提出了SMNN，通过监督互最近邻检测对单细胞RNA测序数据进行批量效应校正。我们在仿真和真实数据集的广泛评估表明，SMNN提供了跨批次相应细胞类型的改进合并，使MNN、Seurat v3和LIGER在跨批次分化减少。此外，SMNN保留了更多的细胞类型特异性特征，部分表现为经过SMNN校正后发现的细胞类型之间的差异表达基因在生物学上更相关，精度提高了高达841.0%。


## 文章

1、[R中的聚类分析：确定最优的聚类个数](https://stackoverflow.com/questions/15376075/cluster-analysis-in-r-determine-the-optimal-number-of-clusters)

这是StackOverflow的一个帖子，讨论如何确定最优聚类个数的方法。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647748348489-image.png)


2、[利用R介绍功效分析](https://newpblog.netlify.app/2021-11-19-bit-by-bit-power-analysis/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647747605938-image.png)

3、[《细胞》2021深度解读免疫治疗](https://mp.weixin.qq.com/s/wVmxoVez7ujBb-i4pbsZ-g)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647747668934-image.png)


## 工具

1、[dittoSeq - 单细胞和大量RNA测序数据的色盲友好可视化 R包](https://github.com/dtm2451/dittoSeq)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647746896900-image.png)

2、[datapasta - 助力你粘贴数据的R包](https://github.com/MilesMcBain/datapasta)

> datapasta的作用是减少向R复制和粘贴数据的阻力。这是对我经常使用像Sublime这样的中间程序将文本转换成合适格式这一认识的一种回应。

例如，表格复制粘贴为Tibble：

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647747063559-image.png)


3、[ISO - helloSystem Live and installation ISO](https://github.com/helloSystem/ISO)

4、[Playwright - Web测试和自动化的框架。它允许用一个API测试Chromium、Firefox和WebKit](https://github.com/microsoft/playwright)

```sh
# Run from your project's root directory
npm init playwright@latest
# Or create a new project
npm init playwright@latest new-project
```

5、[JuliaConnectoR - 从R调用Julia的面向函数的接口](https://github.com/stefan-m-lenz/JuliaConnectoR)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647747313038-image.png)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647747347532-image.png)

6、[tidygate - 在用户绘制的窗口标记元素](https://github.com/stemangiola/tidygate)

通过Tidygate，你能够使用鼠标框选元素并返回对应数据。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-3-20/1647747442819-image.png)



## 资源

1、[图书 - Scientific Visualization: Python + Matplotlib](https://github.com/rougier/scientific-visualization-book#read-the-book)

2、[VannoPortal | SNP综合性查询数据库](https://mp.weixin.qq.com/s/PZdmkzkoD5bJzA2GcnVQAg)

3、[Python resources for everybody](https://github.com/learnbyexample/py_resources)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

