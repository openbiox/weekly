---
date: 2023-06-18
comments: true
---

# 生信爱好者周刊（第 80 期）：生活就像一个鱼缸

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/33257/31025dbd-46d8-4199-b007-52310eb6fc00.png)
鱼缸-马岩松

## 本周话题：[生活就像一个鱼缸](https://www.ruanyifeng.com/blog/2022/12/weekly-issue-233.html "生活就像一个鱼缸")
> 当代人看上去很自由，但是实际上，（大多数人的）自由很有限，生活中到处都是看不见的高墙，财富、职业、家庭、阶层等等限制了你能去的地方，每个人其实都生活在自己的鱼缸里面。

@kktjmac 这里借用Chatgpt的回复：1.生活就像一个鱼缸，我们就像鱼缸里的鱼，被困在一个有限的空间里，有时候我们会感到无聊，甚至绝望，但是我们也可以在这个有限的空间里找到乐趣，找到生活的意义。2.生活就像一个鱼缸，我们需要自己创造自己的环境。鱼缸里的水质、温度、光照等都需要我们自己去调整，这就像我们在生活中需要自己去调整自己的心态，去创造自己的生活环境。3.生活就像一个鱼缸，我们需要不断地学习和成长。鱼缸里的鱼需要不断地游动，才能保持健康，这就像我们在生活中需要不断地学习和成长，才能保持心理的健康。

@科技爱好者周刊 可以去一些没有去过的地方，做一些没有做过的事情，读一些以前不读的书，接触一些"同温层"之外的朋友。这样就相当于在生活中搭建出各种奇怪的空间，活得可以更有意思一些，遇到更多的可能。

## 生信研究
1、[Nature | 最新人类细胞类型DNA甲基化图谱，发现不同个体相同细胞类型的甲基化模式极其相似 ](https://mp.weixin.qq.com/s/9A7lPjC93MTl1GbuPds-kQ)

![](https://files.mdnice.com/user/33257/af2ebaab-36c1-4822-b085-f7f9814995fc.png)

DNA甲基化是一种重要的表观遗传标记，但现有的人类DNA甲基化数据集存在很大的局限性。大多数DNA甲基化分析主要针对大块组织，因此掩盖了那些罕见细胞类型。作为部分解决方案，近期有研究利用来自全组织的单细胞转录组测序数据来识别在特定细胞类型中表达的标记基因，然后鉴定出甲基化与表达负相关的特定CpGs，但这对于鉴定液体活检中的罕见细胞可能仍不够准确。
近日，为了克服这些限制并准确表征人类细胞甲基化特征，来自以色列希伯来耶路撒冷大学等单位的研究团队在Nature发表了题为“A DNA methylation atlas of normal human cell types”的文章。研究团队构建了39种不同细胞类型的深度甲基化图谱，并将整个基因组的甲基化模式合并为甲基化的CpG位点模块，使用这些模块来研究不同细胞类型甲基化模式的变化。同时，研究团队还识别描述了组织或细胞类型特异性的甲基化基因组区域，分析了其可能的生物学功能。该甲基化图谱为研究基因调控、疾病相关遗传因素以及开发用于液体活检的组织特异性生物标志物提供了宝贵的数据资源。

- 论文链接：https://www.nature.com/articles/s41586-022-05580-6

2、[Genome Biology | 稳健、快速、低成本！INSERT-seq方法可对DNA整合特征进行高分辨率定位 ](https://mp.weixin.qq.com/s/K5isCf1mSJqdDGY-BPmaBg)

![](https://files.mdnice.com/user/33257/e9fcfa41-f27c-4cc0-be90-298d38d3626f.png)

近日，西班牙巴塞罗那庞培法布拉大学的科研人员在Genome Biology上发表了题为“INSERT-seq enables high-resolution mapping of genomically integrated DNA using Nanopore sequencing”的文章。研究团队开发了一种名为“INSERT-seq”的测序方法，其主要工作流程包括single-tail adapter/tag（STAT-PCR）文库制备和牛津纳米孔（Oxford Nanopore）长读长测序。INSERT-seq方法将整合DNA的靶向扩增、基于唯一分子标记（UMI）的PCR偏差校正以及Oxford Nanopore长读长测序相结合，可以稳健、快速和低成本的方式解析已编辑的基因组中未知的有效载体整合位点，定量分析不同体外、体内样本的DNA整合特征，检测极限为1%。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02778-9

3、[Nature | 迁移学习使得基因互作网络预测成为可能](https://mp.weixin.qq.com/s/pq3kQhnbP0136WKi_YB-5w)

![](https://files.mdnice.com/user/33257/1742719f-148c-49c7-b9e9-0458fe410af9.png)

Geneformer是一种基于深度学习的、对上下文敏感的模型，通过大规模转录组数据的预训练，可以在数据有限的场景中进行预测。本文中作者
利用3000万个单个细胞转录组构成的大规模语料库进行了预训练,以在有限数据情形下实现下游网络生物学任务的预测。同时在有限患者数据的疾病建模的应用中,Geneformer鉴定了心肌病的候选治疗靶点。
Geneformer代表了一个预训练的深度学习模型,可通过微调适应广泛的下游应用，进一步促进对关键网络调节因子和候选治疗靶点的发现。

- 论文链接：https://www.nature.com/articles/s41586-023-06139-9

## 博文资讯

4、[测序冷知识，为什么illumina测序叫做P7与P5接头？](https://mp.weixin.qq.com/s/a4p38Cw4DuPvfLfXsQtjGw)

![](https://files.mdnice.com/user/33257/48d76cd9-4be3-468e-adf8-da9d194293d0.png)

推特上关于为什么illumina测序连接的是3'端和5‘端的接头，但是接头命名是P7与P5而不是P3与P5的讨论，原因是illumina收购的solex测序技术里面，P7和P5是测序效果最好的接头，所以就保留了第5个和第7个接头原始的编号，而不是符合常识的命名为P3和P5。

5、[基因集分析的前世今生](https://mp.weixin.qq.com/s/iwG3Gor6f9s400LamBQ8Rw)

![](https://files.mdnice.com/user/33257/2cfaf368-9a41-4ca1-ae45-4aeac3ecfaaa.png)

本文作者通过两篇文献，展示了GSA的前世今生，包括当下富集分析的主流算法、方法，统计学原理及其在解释科学问题时的局限性和不足，最后作者还补充了在选择对应方法、工具进行GSA时需要注意的问题。

6、[前瞻性研究VS回顾性研究，分清了吗？](https://mp.weixin.qq.com/s/EQZJqW2KJ1VzOdFN3e_RNA)

![](https://files.mdnice.com/user/33257/cf5b4667-360b-4c87-ac7e-6e75f45eed05.png)

前瞻性研究和回顾性研究是流行病学中两种主要的观察性研究方法。本文介绍它们的含义和区别。

7.[一文掌握卡方检验](https://mp.weixin.qq.com/s/MGGcHM6t1S6DHQiecpIccA)

![](https://files.mdnice.com/user/33257/6b9acbbc-e082-4812-8627-a3d00120e1fa.png)

本文从假设检验入手，详细介绍了卡方检验的基本内容。

## 工具

8、[buildr ｜ 舒适地组织和运行构建脚本](https://github.com/netique/buildr "buildr ｜ 舒适地组织和运行构建脚本")

![](https://files.mdnice.com/user/33257/cb8a1bc6-2642-43b5-8714-c2e93535131b.png)

处理可重复的报告或任何其他类似的项目通常需要运行脚本，以指定的方式“构建”输出文件。buildr可以帮助你组织、修改和舒适地运行这些脚本。该软件包提供了一组功能，以交互方式指导你完成整个过程，这些功能可以作为RStudio插件使用，这意味着你可以设置键盘快捷键，使你可以随时随地一键选择并运行所需的构建脚本。

- 工具链接：https://github.com/netique/buildr

9、[ProjectTemplate | 项目管理的R包](http://projecttemplate.net/getting_started.html "ProjectTemplate | 项目管理的R包")

![](https://files.mdnice.com/user/33257/10ad7b29-0066-4652-8709-0e7955c7d16d.png)

ProjectTemplate是一个可以自动化管理R语言项目的R包，可以简化日常使用R语言的一些流程，推荐使用。

- 工具链接：https://github.com/KentonWhite/ProjectTemplate

10、[Zotero Better Notes | Zotero笔记管理工具](https://github.com/windingwind/zotero-better-notes "Zotero Better Notes | Zotero笔记管理工具")

![](https://files.mdnice.com/user/33257/725936e8-59c5-4784-bb6b-4e23b286ec00.png)

Zotero Better Notes作为Zotero一个插件，是Zotero中进行笔记管理的强大工具。

- 工具链接：https://github.com/windingwind/zotero-better-notes

11、[circrna| circRNA分析流程工具](https://nf-co.re/circrna/dev "circrna| circRNA分析流程工具")

![](https://files.mdnice.com/user/33257/83c551d2-1b46-43b1-a9b2-6cb7e99fe67f.png)

nf-core/circrna是基于Nextflow进行circRNA定量、差异表达分析和miRNA靶向预测的分析流程。

- 工具链接：https://nf-co.re/circrna/dev

## 资源

12、[CRAN平台多组学分析的R包集合](https://cran.r-project.org/web/views/Omics.html "CRAN平台多组学分析的R包集合")

![](https://files.mdnice.com/user/33257/c7a35737-2202-4ad6-88df-bc1d6021e595.png)

本文介绍了CRAN平台上组学分析时重要的R包工具，可用于基因组学、蛋白质组学、代谢组学、转录组学等。

- 资源链接：https://cran.r-project.org/web/views/Omics.html

13、[单细胞测序的里程碑文献集锦](https://mp.weixin.qq.com/s/uFnLrEz7aVqtDa9TftJlRw)


![](https://files.mdnice.com/user/33257/4c261f43-7c2b-44d2-a19e-009bc2e3c733.jpg)

本资源整理了2009年以来的单细胞领域的里程碑文献（见上图）。

## 历史上的本周

- 第 40 期：[bTMB指导肿瘤免疫治疗临床研究](https://mp.weixin.qq.com/s/bS1ap7dOY0yjoxDOMVoaLg)

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

![](https://files.mdnice.com/user/33257/8e1e9214-22bc-447c-a64a-df8b9f374cee.png)

（完）