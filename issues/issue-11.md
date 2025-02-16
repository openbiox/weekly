---
date: 2023-02-19
comments: true
---

# 生信爱好者周刊（第 11 期）：中科院近20年院士增选之数据分析

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/openbiox/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/openbiox/weekly/issues/306)

## 封面图


![中科院院士学部分析](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638673015304-image.png)

用热力图看中科院各个学部近20年的入选人数。（[via](https://mp.weixin.qq.com/s/kWMpiGvx09qJ_nsgQGUtsg)）

## 本周话题：中科院近20年院士增选之数据分析

本周的话题是统计之都发布的文章[《数说风云：中科院近20年院士增选之数据分析》](https://mp.weixin.qq.com/s/kWMpiGvx09qJ_nsgQGUtsg)。在此之前，还无人系统整理相关的数据。该文整理了2000-2021年共11次中科院院士增选信息以及相关单位地址和类型， 从人数、学部、单位、双一流大学、区域、单位类型、年龄等多个角度进行统计、可视化和比较分析。详细的信息可以通过网址<https://costudy.gitee.io/cas-fellow/>进行查看。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638673372738-image.png)

不知道各位生信看官对此次增选有何感触评价？是否参与了院士评选工作而所有经验感想？


## 生信科技动态

1、[Nature & Science | 新疆出土四千年前遗骸完成DNA测序，证实并非移民而是土著](https://mp.weixin.qq.com/s/ZMPd6k8L5behAbVBn9_zMw)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638673543387-image.png)

近期一个关于中国塔里木盆出土的数百具自然保存的遗骸考古研究，同时登上了著名学术期刊《自然》和《科学》的官网首页。
这一研究解决了困扰考古学界很长时间的问题，这些埋藏在塔里木盆地上千年的遗骸，究竟来自哪里？

根据基因测序，这些保存完好的遗骸可以追溯到大约9000年前生活在亚洲的石器时代狩猎采集者，并非来自其他地域的移民，而是长期居住在此的土著。这些遗骸在基因上是独立的，神奇的是，他们却学会了其他群体相同的饲养牲畜和种植谷物的方式。

圣路易斯华盛顿大学考古学家Michael Frachetti表示，这一发现表明，文化交流并不总是与遗传关系相伴而行。这些人仅仅是互通往来，但这并不一定意味着要结婚生子。

2、[Nature | 基于45万样本WES数据揭示564个健康性状关联基因，有望开辟基因功能研究新航道](https://mp.weixin.qq.com/s/70BgKeRl4rEePnLBwY5iJQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638673881872-image.png)

近期，来自美国“再生元”遗传研究中心的研究团队与UK Biobank团队合作，对45万名参与者进行了外显子组测序，利用生物信息分析研究了蛋白质改变带来的表型变化。

（什么时候中国有此规模、系统的计划和公开数据？）

3、[NC | 网络分析揭示了生物组织的多个层次的罕见疾病特征](https://mp.weixin.qq.com/s/ENGbS2LJpLqHl7gOYLj8hw)

![https://github.com/menchelab/MultiOme  ](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638674003983-image.png)

罕见的遗传疾病通常是由单个基因缺陷引起的。尽管基因型和表型之间有明确的因果关系，但在生物组织的不同层次上确定病理生物学机制仍然是一个实践和概念上的挑战。本文介绍了一种网络方法，用于评估罕见基因缺陷在生物尺度上的影响。本文构建了一个由超过2000万个基因关系组成的多重网络，这些基因关系被组织成46个网络层，跨越了基因型和表型之间的6个主要生物尺度。对3771种罕见疾病的综合分析揭示了不同的表型模块在各个层次。这些模块可用于机械分析基因缺陷的影响，并准确预测罕见疾病候选基因。结果表明，疾病模块形式可以应用于罕见疾病，并推广到物理交互网络之外。这些发现为应用基于网络的工具进行跨规模的数据集成开辟了新的途径。

4、[Communications Biology | 基于深度学习算法的DIA数据处理方法，有效提升DIA蛋白质组学分析性能](https://mp.weixin.qq.com/s/GbuU6Stjj3uP-hh7X3XnbQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638674122527-image.png)

数据独立采集（Data-independent acquisition，DIA）是当前蛋白质组学中应用范围较广的采集方式。与数据依赖采集（Data-dependent acquisition, DDA）的策略相比，DIA避免了仅对高丰度蛋白质信号采集的偏好性，转而采取“兼容并包”的策略，将一级质谱的荷质比范围分为数个窗口，在二级质谱中采集各个窗口内所包含的所有母离子碎裂所产生的子离子信号。正是如此，DIA具有相比DDA更好的重现性与定量准确性，在样本数量较大时能够获得更加准确而稳定的蛋白表达矩阵，因而更加适用于大规模的定量蛋白质组学研究。

本文，研究团队开发了基于深度学习算法的DIA数据处理方法DreamDIAXMBD，通过对DIA谱图库以及数据的分析，设计了包含上百种色谱峰类型的新型谱图数据结构代表性谱图矩阵（representative spectral matrix，RSM），使用深度学习算法提取DIA肽段谱图中的洗脱特征，有效提升了DIA数据处理算法的准确度，并在定性、定量等多个方面超越了目前广泛使用的开源DIA数据处理软件OpenSWATH、Skyline和DIA-NN。


## 文章

1、[在Linux的黑白命令行无法看R语言配色的解决方案](https://mp.weixin.qq.com/s/1N2hFFI6YDKz6J5xKJFpMA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638674297282-image.png)


Linux的黑白命令行无法看R语言配色，本文推荐了一个工具并介绍如何使用。

2、[远程运行jupyter notebook：密码登录和token登录](https://blog.csdn.net/ACBattle/article/details/89401165)

本文介绍如何使用密码和token登录Jupyter Notebook。

3、[Jetbrains 发布下一代编辑器「Fleet」](https://mp.weixin.qq.com/s/TbHsKpqAoFi1h_4pEnEl7Q)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638674497644-image.png)


这是一个对标VS Code的软件，目前处于邀请测试中。

因为 Fleet，我们不再需要打开不同的 IDE 来获得特定技术所需的功能。使用 Fleet，一切都在一个应用程序中。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638674512269-image.png)


## 工具

1、[easystats](https://github.com/easystats)

easystats是一个组织，提供了一系列方便在R中处理统计分析与建模的工具包。

2、[hardhat](https://github.com/tidymodels/hardhat)

hardhat是一个以**开发人员**为中心的包，旨在简化新的建模包的创建，同时促进良好的R建模包标准，这些标准是由R建模包的一组传统的约定所制定的。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638674692514-image.png)

3、[BruceR - 一个统计检验的R包，可以很方便地进行简单效应检验和多重效应检验](https://github.com/psychbruce/bruceR)

(感谢知乎`@谷雨`投稿)


## 资源

1、[用R访问人类细胞图谱数据](https://twitter.com/AedinCulhane/status/1446181653664178180)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638674856549-image.png)

课件链接：<https://www.aliyundrive.com/s/DjUaNNPxegL>

2、[Pre-submission inquiry模板](https://mp.weixin.qq.com/s/XSIaNrm1wPwtbTUGUwNnQw)

3、[Recount3：75万个转录组数据重分析项目](https://mp.weixin.qq.com/s/KHoX0poOrAszSmE2NT2D7g)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2021-12-5/1638675091989-image.png)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

感谢以下读者往期赞赏：

- 李浩

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）
