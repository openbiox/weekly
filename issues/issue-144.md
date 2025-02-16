---
date: 2024-10-20
comments: true
---
# 生信爱好者周刊（第 144期）:物理诺贝尔奖为何颁给了 HNN 之父和深度学习之父？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图


![](https://files.mdnice.com/user/77986/e520f6b6-ad19-4e09-9879-33c790593ce5.png)


## 本周话题：[物理诺贝尔奖为何颁给了 HNN 之父和深度学习之父？](https://mp.weixin.qq.com/s/AuCeGzKNZpidGCL4ETi8aA)

就在几天前，瑞典皇家科学院决定将 2024 年诺贝尔物理学奖授予约翰·J·霍普菲尔德 (John J. Hopfield) 和杰弗里·E·辛顿 (Geoffrey E. Hinton)，以“表彰他们通过人工神经网络实现机器学习的基础性发现和发明”。这一消息马上就引起网友热议，就连得奖者Hinton表示，这也太突然了。诺奖官方随后解释道：“今年物理学奖得主的突破建立在物理科学的基础上”。

@Wangcy-rachel AI的最初开创，包含了许多物理学的核心思想。如今AI已经应用到我们科研和生活的方方面面，影响深远。物理诺贝尔奖颁给了HNN 之父和深度学习之父，不仅是因为AI的最初开发与物理学关系紧密，而且是因为AI带来的广泛、多领域的深远影响。



## 生信研究

1、[Cell｜樊荣团队开发全球首个临床级FFPE样本空间全转录组测序技术](https://mp.weixin.qq.com/s/SWI4JqjkG9q6vlQs4Iz-cw)

![图1. Patho-DBiT技术流程及全场景空间分析能力](https://camo.githubusercontent.com/dc7cc268fb1bae76776020fb2034b1fd440805887d8d5cbe8098961ab2ba9f9a/68747470733a2f2f66696c65732e6d646e6963652e636f6d2f757365722f353230382f32326264386336662d616538382d346636302d626538612d6335323935353831326536392e6a7067)

2024年9月30日，耶鲁大学樊荣团队的白志亮博士等在Cell杂志上报道了全球首个临床级FFPE样本空间全转录组测序技术——Patho-DBiT。该平台巧妙地利用FFPE样本中自然发生的RNA片段化，向广泛多样的RNA分子原位添加poly(A)尾，结合微流控条形码标记和算法创新，成功实现了对临床存档FFPE组织的全覆盖、逐碱基的空间全转录组测序。Patho-DBiT通过对完整mRNA、缺失poly(A)尾的片段化mRNA、各类大/小非编码RNA、剪接异构体以及携带单核苷酸变异（SNV）的前体RNA进行空间条形码标记，精确解码了FFPE复杂组织中丰富的RNA生物学信息，包括单细胞级mRNA图谱、非编码RNA表达、可变剪接、遗传变异、microRNA调控及RNA动态变化等。

- 论文链接：https://www.cell.com/cell/fulltext/S0092-8674(24)01019-5

2、[8 x nature | 首个成年果蝇全脑连接组](https://mp.weixin.qq.com/s/H5YlDSwvOfkxcoRb4LPOjA)

![Fig. 1](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41586-024-07558-y/MediaObjects/41586_2024_7558_Fig1_HTML.png)

近日，FlyWire联盟等在*Nature*连发8篇论文，详细描述首个成年果蝇全脑连接组，并通过模拟与实验展示了它如何帮助人们形成新猜想，进而解析关键功能背后的神经环路机制。

- 论文链接：https://www.nature.com/collections/hgcfafejia

3、[The Innovation Life|医学数据计算建模：从数据采集到知识挖掘](https://mp.weixin.qq.com/s/-sKXjWmS-o6gGeJPb2raDA)

![img](https://camo.githubusercontent.com/182738da54da93715ceb0983032e5355b4dbae3eb51a2384eadb70b1c42c2450/68747470733a2f2f66696c65732e6d646e6963652e636f6d2f757365722f353230382f34623236396132382d663430372d346466322d383437652d3064633439313737373238302e706e67)

文章从数据的采集、存在的挑战、计算建模、高性能计算到未来展望等几个方面展开进行全面的综述。比如在高性能计算方面，对并行计算、云计算、AI计算、边缘计算等几个方面都进行讨论。

- 论文链接：https://www.the-innovation.org/article/doi/10.59717/j.xinn-life.2024.100079

## 博文资讯

4、[从AI的角度谈早期药物研发数据科学](https://mp.weixin.qq.com/s/DN_5aqAqIzB3ZklqgNMFHQ)

![Fig. 2](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41467-024-49777-x/MediaObjects/41467_2024_49777_Fig2_HTML.png)

最近，多所大药企和知名大学在nature子刊联合发表了关于早期药物研发数据科学的文献综述，报告了数据科学的经验指南。文章中，作者提出了数据管理和数据科学建议，以帮助实现人工智能在该领域的潜力。

- 论文链接：https://www.nature.com/articles/s41467-024-49777-x

5、[基因组数据处理小技巧](https://divingintogeneticsandgenomics.com/post/genomic-interval/?ck_subscriber_id=2105433013&utm_source=convertkit&utm_medium=email&utm_campaign=Resending%20with%20real-world%20examples:%20You%20need%20to%20master%20this%20if%20you%20deal%20with%20genomics%20data%20-%2015087044)

![img](https://camo.githubusercontent.com/f8b4af0b8dea809b001e933735bea52851ad4fd01a9c93a55b9b77725752a0d4/68747470733a2f2f66696c65732e6d646e6963652e636f6d2f757365722f353230382f62366635626232382d353737382d346430632d623531322d3130633732623861636536632e706e67)

该博文提出了一些关于解决基因组区间（Genomic Intervals）相关问题的方法。

6、[人基因组测序，平均覆盖度为啥要30×吗？](https://mp.weixin.qq.com/s/d_YUPG35cYDMNDJazxVSYQ)


![](https://files.mdnice.com/user/77986/0fb0d0e2-3c9a-4c6c-99cd-3f3d35e4a6a2.png)


在对人类全基因组进行测序时，需要 30 ×的平均基因组覆盖率才能使局部碱基覆盖率大于 15 ×，这样才能准确检测出同源变异和异源变异。

## 工具

7、[wget包｜让R使用断点续传](https://mp.weixin.qq.com/s/6ShcLvGtBsuiJwFVPUHj4g)


![](https://files.mdnice.com/user/77986/68f09e80-d900-40ca-b43d-8a81d1a4b893.png)


安装包有时候是个费劲的时，特别是一遍又一遍的下载安装，推荐新手朋友们使用。

8、[SignalingProfiler2.0 | 网络连接多组学数据与表型特征](https://mp.weixin.qq.com/s/2GIbMEXPAHqk7pWmF6DqMg) 


![](https://files.mdnice.com/user/77986/514ad755-fdda-44ae-b76a-1312a91b2b99.jpg)


揭示细胞信号转导在受到干扰后如何重塑，对于理解疾病机制和识别潜在药物靶点至关重要。
SignalingProfiler 2.0结合蛋白基因组数据与先验知识因果网络，推导出特定情境下的信号传导网络。该工具自由访问且灵活，结合了统计学、足迹分析和图算法，加速了多组学数据的整合与解读。

- GitHub：https://github.com/SaccoPerfettoLab/SignalingProfiler

9、[GenomeSyn 插件 | 快速轻松展示两个基因组组装的差异情况](https://mp.weixin.qq.com/s/5axLWPBA1FPSoWatfQ04CA)


![](https://files.mdnice.com/user/77986/abb50c1c-583e-40f9-a1bf-efe0dfc1430a.png)


GenomeSyn是一种用于基因组同一性和结构变异分析的生物信息学可视化工具，填上Mummer 插件上输入和输出的结果，调整sort参数选项，就可以得到可视化结果。

- GitHub：https://github.com/JM-SONG/GenomeSyn/

## 资源

10、[生物信息学期刊2024更新版](https://mp.weixin.qq.com/s/s1t3NUY1e4ZHHloTrEpl0w)


![](https://files.mdnice.com/user/77986/af990509-a95e-4ea9-a779-d77a7feaf9ce.png)


文中列举了2024年的可投稿的生物信息学期刊及其分区，推荐给需要生信选刊的朋友们。

11、[2024 年 12 个最佳 JavaScript 动画库，为您的 Web 项目提供动力](https://mp.weixin.qq.com/s/IsD0a7B-fAVWeSpwzz0kgg)


![](https://files.mdnice.com/user/77986/8a0c213b-0d27-4b5c-8ce1-9fcc01caf494.png)


文中推荐了12 个方便有用的JavaScript 动画库，可以将绘制动态的、引人注目的动画，使Web项目更加丰富多彩。

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
- `@donghongyu2020`（董弘禹）
- `@DrRobinLuo`（罗鹏）
- `@Wangcy-rachel` - 王春阳
- `@zoe3251` - 舒晨阳

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![img](https://camo.githubusercontent.com/2316fe421f5071d524e9de7a1c05bcdb5bd75e39494439562fc02d16f0f7f501/68747470733a2f2f63646e2e6e6c61726b2e636f6d2f79757175652f302f323032322f706e672f3437313933312f313634383330363339383730382d38393765376164342d363030382d343066382d393230302d6464656538333462303961372e706e67)

（完）
