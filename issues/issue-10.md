---
date: 2023-02-18
comments: true
---

# 生信爱好者周刊（第 10 期）：开放科学

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/openbiox/weekly/issues/281)

## 封面图


![开放科学建议书](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-27/1638023181705-open-science.png)

愈加开放的科学是未来的潮流。（[via](https://mp.weixin.qq.com/s/MOHQwjnihAdEkB8LPdZvsQ##)）


## 本周话题：开放科学

联合国教科文组织（UNESCO）大会第41届会议于2021年11月9-24日召开。在经过一个包容、透明和多利益相关方的协商过程之后，会议审议通过《开放科学建议书》，标志着开放科学迈入全球共识的新阶段。

《开放科学建议书》旨在为开放科学政策和实践提供一个国际框架，即承认关于开放科学的观点存在学科和地区差异，考虑到学术自由、促进性别平等变革的方法以及不同国家特别是发展中国家的科学家和其他开放科学行为者所面临的具体挑战，并有助于缩小国家之间和国家内部存在的数字、技术和知识鸿沟。

>「开放科学建议书.pdf」，点击链接保存，或者复制本段内容，打开「阿里云盘」APP ，无需下载极速在线查看，视频原画倍速播放。
链接：https://www.aliyundrive.com/s/zbYedF3XwRF

## 生信科技动态

1、[预印｜在临床相关低Map区域纠正甲基化检测](https://www.biorxiv.org/content/10.1101/2021.10.04.463127v1)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-27/1638023688497-image.png)

DNA甲基化是胚胎发育、致癌和遗传调控等重要生物学功能的重要组成部分。准确评估基因组甲基化状态的方法对于其在许多情况下的有效使用至关重要，尤其是在疾病的检测和诊断中。甲基化对比器，如Bismark和bwa-meth，经常分配比所映射的区域的唯一性所支持的MapQ值高得多。这些不正确的高MapQ导致重复区域中不适当的甲基化定量检测。本研究为甲基化检测工具MethylDackel创建了一个新特性，以执行基于读段的过滤。这种新的甲基化调用方法将一些表面上的混合甲基化修正为0%或100%甲基化，并消除了许多可信的甲基化检测结果。

2、[BIB｜深度学习能在多大程度上提高癌症细胞系对药物反应的预测?](https://mp.weixin.qq.com/s/bbPnEkIjpB7Ytbsfx5vUMw)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-27/1638026751750-image.png)

深度神经网络已被应用于1000多个癌症细胞和组织的多组学数据，以更好地预测药物反应。作者总结并研究了最近发表的最先进的深度学习方法。尽管深度学习方法在药物反应预测方面取得了重大进展，但深度学习方法在预测未出现在训练数据集中的药物反应方面显示出其弱点。特别是在药物盲测中，所有被评估的深度学习方法都比相似性-正则化矩阵分解（SRMF）方法表现差。作者概述了将深度学习方法应用于药物反应预测的挑战，并提出了将深度学习与已有的生物信息学分析相结合的方法。

3、[Nature | 表型关联分析揭示罕见变异与上万种常见疾病的关系](https://mp.weixin.qq.com/s/0-_67qsshh6K7Pltki-9mg)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-27/1638026759776-image.png)

全基因组关联研究发现了与人类疾病相关的数以万计的常见变异。然而，这些变异只能解释很少一部分疾病的发病原因。罕见变异（MAF<1%）在疾病的发生过程中发挥着重要的作用。但是，罕见变异对常见疾病的贡献仍然未知。英国生物银行（UK Biobank，UKB）纳入了约50万人的基因组数据及详细的电子病例信息，这为遗传学家提供了前所未有的机遇来评估罕见变异对常见疾病发生的影响。在本研究中，作者纳入了UKB中269171个具有欧洲血统的人群，分析了17361种二元表型（如是否为精神分裂症）和1419种定量表型（如血糖等指标）与罕见突变的关系。以基因为单位（Gene-based collapsing）的关联分析显示，存在1703个具有统计学意义的基因-二元表型关联，中位数比值比（odds ratio）为12.4。另外，83%的关联通过单一变异关联分析无法检测到，这强调了基于基因的collapsing分析在高等位基因异质性下的检出效力。重要的是，与表型相关的基因显著富集于FDA已批准的药物靶点上。最后，作者进一步从UKB中纳入了具有非洲、东亚和南亚血统的11933名人员的外显子组测序数据，进行了谱系特异性和泛谱系collapsing分析。总之，本研究阐述了罕见变异在常见疾病发生过程中的重要作用。

## 文章

1、[高通量数据整合分析中批次效应的鉴定和处理](https://mp.weixin.qq.com/s/KK8cSvdfxM2GX7aT-TIikA)

批次效应表示样品在不同的批次处理和测量时引入的与生物状态不相关的系统性的技术偏差。很多因素都可能导致批次效应的产生，如不同实验条件、不同操作者、不同公司的试剂、不同批的试剂、实验开展的时间、检测设备、不同的测序批次等。

2、[使用R包Boruta进行特征选择评估变量的重要性](https://mp.weixin.qq.com/s/CSHSjVILHPotr2vt7AhVEw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-27/1638024961750-image.png)


高维数据在机器学习问题中非常普遍，要从大量数据中提取有用信息（例如，哪些变量对于预测或解释结果更重要），必须使用统计技术来减少噪声或冗余。挑选重要变量的方法有很多，本篇简介一个R包，Boruta，它是围绕随机森林分类算法构建的包装器，用于捕获数据集中所有与结果变量相关的重要、有趣的变量。

3、[Cancer Cell 长文综述：微生物与癌症](https://mp.weixin.qq.com/s/oryI6opGKN2Cg0qkT1_SBQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-27/1638024987062-image.png)

人体微生物组成了一个复杂的多界群落，在多个身体部位与宿主共生互作。宿主-微生物的互作影响多种生理过程、是多种多因素疾病的条件。在过去10年，微生物群落被认为影响多种癌症的发生、发展、转移和对治疗的反应。然而微生物对癌症生物学存在影响的因果证据才刚刚被揭示，因此解析微生物对癌症的调节以及对癌症治疗产生影响在分子层面上的机制，具有重大的科学价值和临床意义。

在这篇综述中，研究者描述了不同促进癌症发生发展的微生物生态位共同具有的分子致病机制；强调了对相关问题理解的进步性、局限性、挑战和前瞻，这些问题包括微生物如何影响癌症和癌症对治疗的反应、微生物或其分泌的具有生物活性的代谢物如何具有潜在的利用价值、如何成为癌症治疗的精准靶标等等。


## 工具

1、[gggenomes - 比较基因组学的一种图形语法](https://github.com/thackl/gggenomes)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-27/1638025086521-image.png)

2、[pins - 发现和共享资源](https://github.com/rstudio/pins)

pins包发布数据、模型和其他R对象，使得跨项目和与同事共享它们变得容易。你可以把对象钉到各种不同的钉板上，包括文件夹(在网络驱动器上共享或与DropBox等服务共享)、RStudio Connect、Amazon S3、Azure存储和微软365 (OneDrive和SharePoint)。可以自动对引脚进行版本控制，从而可以直接跟踪更改、对历史数据重新运行分析和撤消错误。

3、[whatchanged - 一个优雅的变更日志生成器](https://github.com/release-lab/whatchanged)

方便生成规范优雅的代码变更日志信息。

4、[System Monitor - 微软❤️开源](https://mp.weixin.qq.com/s/7XpWvUFgOaqBn3XFgVqUiw)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-27/1638025542786-image.png)

System Monitor（Sysmon）是一个系统服务和设备驱动程序，一旦安装在系统上，就会在系统重启时保持驻留，以监控并记录系统活动到事件日志。它提供有关进程创建、网络连接和文件创建时间变化的详细信息。通过使用事件收集或 SIEM 代理收集它产生的事件，并随后对其进行分析，用户可以识别恶意或异常活动。


## 资源

1、[mathlets - 数学概念探索](https://mathlets.org/mathlets/)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-11-27/1638025772209-image.png)


2、[TICA - 精确肿瘤学的单细胞肿瘤免疫图谱](https://singlecellgenomics-cnag-crg.shinyapps.io/TICA/)

数据下载地址：https://zenodo.org/record/5186413

3、[网易云课堂引进亚马逊AWS近百门IT类课程，向社会免费开放](https://www.tmtpost.com/nictation/5805810.html)

钛媒体10月26日消息，专注于成人职业技能提升的网易云课堂，正式宣布上线亚马逊云科技（以下简称“亚马逊AWS”）中文在线培训课程，并承诺向全社会免费开放。


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者往期赞赏：

- \*啥
- 李浩

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）
