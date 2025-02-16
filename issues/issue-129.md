---
date: 2024-06-30
comments: true
---
# 生信爱好者周刊（第 129 期）：怎么才算真正拥有科研思维？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/33257/b9b57ff3-ec10-42f1-927e-b5db88abae69.png)
来自[BioByte 080](https://decodingbio.substack.com/p/biobyte-80-bust-to-boom-in-biotech "BioByte 080")

## 本周话题：[怎么才算真正拥有科研思维？](https://mp.weixin.qq.com/s/TvcDsjFBMT7arXsvkvOV2Q)

@kkjtmac 科研思维是一种系统化的综合性思维，要求具备严谨的逻辑推理能力、创新的思考方式和批判性的评估态度。真正拥有科研思维的人能够通过提出问题、设计实验、收集数据、分析结果并得出结论的过程，不断优化和提升自己的研究能力。同时，还需具备开放的心态，善于吸收新知识，并在团队协作中发挥自己的专业特长。

## 生信研究
1、[Nature | All of Us项目发表超24万个临床级基因组数据，鉴定超2.75亿种新变异](https://mp.weixin.qq.com/s/6LZQAUL5jvABlGmxgpHbyA)

![](https://files.mdnice.com/user/33257/693f1d6b-acf0-4746-b722-c0480eb9d3a9.png)

本文详细介绍了由美国国立卫生研究院(NIH)领导的"All of Us"研究项目的最新进展。该项目旨在收集100万以上美国人的健康数据，促进精准医疗的发展。研究团队在Nature上发表了24.5万余名参与者的全基因组测序数据，鉴定出超过10亿个遗传变异，其中2.75亿个为新发现的突变。通过将基因组数据与电子健康记录相结合，研究人员评估了3724个与117种疾病相关的遗传变异。这些高质量的临床级基因组数据为深入理解人类遗传多样性和开发个性化治疗方案提供了宝贵资源。

- 论文链接：https://doi.org/10.1038/s41586-023-06957-x

2、[Cancer Cell | 第二代癌症依赖性图谱发表，优先筛选27种癌症类型的370个抗癌治疗靶点](https://mp.weixin.qq.com/s/INJ26uEYcpoIzVmJ2vekhQ)

![](https://files.mdnice.com/user/33257/3e270652-5a35-499f-9f84-d7825049ecaa.jpg)

这篇文章详细介绍了英国Sanger研究所Mathew J. Garnett团队构建的第二代癌症依赖性图谱(Cancer DepMap)的最新研究成果。研究整合了多组学数据，利用CRISPR-Cas9筛选分析了27种癌症类型的基因依赖性，并开发了一个靶点优先级排序框架，最终确定了370个潜在的抗癌治疗靶点。这项工作是迄今为止对癌症依赖性最全面的分析，为癌症个性化治疗提供了新思路。

- 论文链接：https://www.cell.com/cancer-cell/fulltext/S1535-6108(23)00444-0

3、[Nat Commun｜基于长读长测序进行癌症和免疫单细胞的综合基因分型](https://mp.weixin.qq.com/s/TIIjOw-mgMm-3h7uWP_VbQ)

![](https://files.mdnice.com/user/33257/b9685300-b15f-46fd-8a48-5e005bb3c250.png)

研究团队设计了一个灵活的长读长测序工作流程和分析管线，称为nanoranger，该方法从中间单细胞cDNA文库开始，检测细胞谱系定义特征，包括单核苷酸变体、融合基因、异构体、嵌合抗原和TCR序列。通过对这些天然“条形码”的系统分析，研究人员定义了nanoranger的最佳靶点，即靠近高表达基因5'端、转录长度短于4kB的基因位点。作为概念证明，研究人员将nanoranger应用于急性髓系白血病（AML）亚克隆的纵向追踪，并描述了数千个骨髓浸润免疫细胞的异质性亚型特征。总之，使用nanoranger可以增强细胞基因分型，改善对单细胞肿瘤和免疫细胞共同进化的追踪。

- 论文链接：https://doi.org/10.1038/s41467-023-44137-7

## 博文资讯
4、 [R语言的24个高效操作](https://mp.weixin.qq.com/s/QIaZ1FT-9XVgeSks1MfXVQ)

![](https://files.mdnice.com/user/33257/bdfd26b8-d4f1-4c0c-a602-bccae2c899e5.png)

这篇文章介绍了24个非常实用的R语言高效操作技巧，包括如何修改默认语言、查看内存消耗、查看源代码、设置CRAN镜像等基本操作，以及如何使用管道操作、拆分列数据、自动加载常用包、迁移已安装的R包等进阶技巧。文章语言简洁易懂，每个操作都配有示例代码。无论是R语言初学者还是有经验的老司机，相信都能从中学到些使用的技能。

5、[利用 bulletchartr 包绘制子弹图 ](https://mp.weixin.qq.com/s/ljvVb8kOz50XbDBskjHDBw)

![](https://files.mdnice.com/user/5208/68b1ce05-4e83-4441-a848-83540ccacfc4.png)
子弹图(Bullet chart) 给大多数据人的第一印象可能就只是简单的柱形图叠加，但其所使用的场景和表达的含义却远远超过柱形图，特别是在分析环比、同比的时候。

6、[6类肿瘤异质性研究模型](https://mp.weixin.qq.com/s/I5lMun97ZUWBVBuAMqPL2A)

![](https://files.mdnice.com/user/33257/680a389e-f062-4ec6-b388-407143a47221.png)

本文通过图文结合的方式介绍了研究肿瘤的6类模型：
- 小鼠模型
  - 基因工程小鼠（Genetically Engineered Mouse Models，GEMM）
  - 患者来源的异种移植（ patient derived xenograft，PDX）模型
- 类器官
- 微流控模型/器官芯片
- 酵母
- 斑马鱼
- 果蝇

7、[LC24: 只需要一个纳米孔测序就够了!!!...??](https://mp.weixin.qq.com/s/lsGSE1YkQJQ6ng-zsfRMew)

![](https://files.mdnice.com/user/5208/7e7d199d-b3c0-44c0-b674-b094f7d931ad.png)
ONT LC24上，CTIPO Clive Brown重点展示了几个方面的技术更新及进展：
- 引入基于Transformer的大语言模型训练了新的base caller - v5 sup，实现了单链读取Q26、细菌组装Q50、indel变异识别错误率15%的降低，引入了HERRO校正算法实现了simplex组装前Q40的准确率；
- 在只使用纳米孔测序技术（nanopore-only）的T2T完整基因组组装方面取得显著进步，使用4张flow cell实现了nanopore-only的Q50 T2T，相应的解决方案现在打包对客户提供

## 工具
8、[editbl | 动态修改表格的R包](https://github.com/openanalytics/editbl "editbl | 动态修改表格的R包")

![](https://files.mdnice.com/user/33257/51a93ca0-d510-4cf1-bd47-fa2723b0fc2e.png)

editbl是一个R语言包，提供类似电子表格的界面来修改表格数据，支持内存中的data.frame对象以及数据库中的数据。它具备多后端支持、可定制性、易于集成进Shiny应用、撤销/重做功能、无需将所有数据加载到内存、处理外键强制和隐藏替代键的挑战、事务性提交等特性。此外，它还支持为新行设置默认值，如UUID、当前日期、插入者等，使得数据编辑既灵活又尊重后端模式和约束。

9、[Go Get Data](https://gogetdata.github.io/ "Go Get Data")

![](https://files.mdnice.com/user/33257/ebb527c8-bcc4-471b-a4bf-6a81dea98570.png)

"Go Get Data"（ggd）是一个数据管理系统，它提供了访问包含自动整理的基因组数据的数据包。ggd数据包包含了数据提取、处理和处理所需的所有必要信息。随着科学数据集数量的增加，ggd提供了这些数据集的访问，无需您自己寻找、下载和处理它们。ggd利用conda包管理系统和Bioconda的基础设施，提供了一种快速且简便的方式来检索处理过的注释和数据集，支持数据来源追踪，并提供了可复制性的稳定来源。使用ggd数据管理系统，任何用户都可以快速访问所需的所有数据集，在环境中管理这些数据，并可以通过ggd数据包的名称和版本来引用数据访问和使用。

![](https://files.mdnice.com/user/33257/5a2b8a4a-f17d-4762-92ba-a7858b1654d5.png)


10、[利用shinyjqui包作为jQuery UI javascript库的R封装器](https://github.com/Yang-Tang/shinyjqui "利用shinyjqui包作为jQuery UI javascript库的R封装器")

![](https://files.mdnice.com/user/33257/d86a9587-0977-4379-98c6-3f077077c1b7.png)

![](https://files.mdnice.com/user/33257/8d331a04-726a-42a3-b6ac-0567ba1f6af3.png)

shinyjqui包是jQuery UI javascript库的R封装器。它可以用来很容易地添加交互和动画效果。

## 资源
11、[3Blue1Brown的微积分主题讲解](https://www.3blue1brown.com/topics/calculus "3Blue1Brown的微积分主题讲解")


![](https://files.mdnice.com/user/33257/a5791159-adf4-4be1-a98d-ba327b137880.png)

3Blue1Brown网站提供了一套微积分核心概念的视频教程，旨在通过直观的动画和易于理解的方式，让用户能够自行发现微积分的基本原理。教程以重新发现圆面积公式为例，阐释了这一发现与微积分基本定理之间的联系。视频系列涵盖了微积分的多个方面，包括导数、积分以及它们在数学和物理中的应用，致力于帮助用户深入理解微积分的精髓。

12、[1000个用户指南官方手册](https://1000userguide.com/#/ "1000个用户指南官方手册")

![](https://files.mdnice.com/user/33257/19d587c1-2753-4ae4-b36f-4e9ba59720b3.png)

1000个用户指南是一个综合性的在线资源，提供了详尽的使用说明和帮助信息。该网站涵盖了各种主题和领域的指南，旨在帮助用户快速找到所需信息，提高效率。用户可以通过网站首页获取更新记录，并通过链接直接访问GitHub上的源代码，以便进一步了解或参与项目的开发和改进。

## 历史上的本周

- 第 88 期：[Vim之父因病离世，一生写下Vim传奇](https://mp.weixin.qq.com/s/_7zBoE3UtryGqEX2azrdkA)


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

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）