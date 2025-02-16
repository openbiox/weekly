---
date: 2024-06-10
comments: true
---

# 生信爱好者周刊（第 126 期）：为什么细菌不能变得更大？或者更小？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图


![](https://files.mdnice.com/user/4331/6dc7e362-5c61-4f4b-86f8-0c96d63be2eb.png)

来源：https://centuryofbio.com/p/scaling-crispr-cures?utm_source=profile&utm_medium=reader2

## 本周话题：为什么细菌不能变得更大？或者更小？


![](https://files.mdnice.com/user/4331/ab4b992f-0a70-47d8-bed9-a097ea5513fd.png)

空间约束控制着最大和最小细菌的尺寸。

细菌不能再缩小，因为剩余的空间不足以容纳DNA和必需的蛋白质。它们也不能变得更大，因为较大物种相较于其体积增加，能量需求更大。因此，较大的细菌需要更多核糖体。而试图比当前的最大记录保持者更大的细菌将无法容纳所需的额外核糖体。研究人员表示，了解微生物的最小尺寸有助于寻找地球以外的生命迹象，以排除过小的生命迹象。而知道细菌有最大尺寸也激发了生物学家更仔细地研究其他微生物（如单细胞真核生物）如何克服这种限制。

`@ShixiangWang` - 没有什么意外，仅仅是因为规律。

## 生信研究

1、[Nature | “生命之树”猴面包树的演化历史](https://mp.weixin.qq.com/s/QyrIKnkbOxWVWwfwuHR50g)

![](https://files.mdnice.com/user/4331/fa9b96a2-dd61-449c-837b-aea4e92f7daf.png)

猴面包树，是锦葵科猴面包树属的大型落叶乔木，它的果实、叶、树皮、根均可食用或入药，被称为“生命之树”。目前，全球现存猴面包树总计8个物种，分布在澳大利亚（1种）、非洲大陆（1种）、马达加斯加（6种），其中3个马达加斯加分布的物种为濒危保护植物。北京时间2024年5月15日23时，中国科学院武汉植物园/中国科学院中-非联合研究中心、英国伦敦玛丽女王大学、英国皇家植物园、华大科技等国内外研究团队，在国际顶级学术期刊《自然》（Nature）杂志上发布了猴面包树的演化历史及保护研究论文，该研究基于现存的八种猴面包树物种的基因组数据，重建其演化历史，并提出马达加斯加是现存谱系的起源中心。基因组学和生态学的综合分析揭示了马达加斯加猴面包树物种多样性产生的原因。马达加斯加猴面包树的历史种群动态可能受到种间竞争和该岛地质历史的影响，特别是当地海平面的变化。基于上述结果，本研究对马达加斯加特定猴面包树物种分别提出了新的保护建议和策略。

- 论文链接：https://www.nature.com/articles/s41586-024-07447-4


2、[Cell Reports | 大规模并行报告基因分析揭示疾病相关3' UTR突变可影响mRNA稳定性、翻译和癌症进展](https://mp.weixin.qq.com/s/pNtX8qtSbXDRtRrJM-RhGA)


![](https://files.mdnice.com/user/4331/6ef19a62-fbc4-42a0-afe1-c490660dd354.png)


研究团队在185个mCRPC（转移性去势抵抗性前列腺癌）患者中鉴定了3' UTR体细胞突变，发现了14,497个富含致癌通路和3' UTR调控元件的单核苷酸突变。通过两种互补的大规模并行报告基因分析（MPRA）方法，检测了数千个基于患者（patient-based）的突变，并发现影响mRNA翻译或稳定性的致癌3' UTR突变与更快进展为晚期疾病相关。

- 论文链接：https://www.cell.com/cell-reports/fulltext/S2211-1247(23)00851-3

3、[Bioinformatics | Ragged Experiment 可无损表示不规则基因组数据](https://mp.weixin.qq.com/s/dVH0sbtGFo8_WooWtmxy5g)

![](https://files.mdnice.com/user/4331/13d3e5c8-125a-4d6a-9aa7-b0801d6b9d50.png)

在基因组研究中，科研人员通过对样本的DNA拷贝数、体细胞突变、单核苷酸多态性（SNP）和其他基因组属性进行分析，以了解基因如何发挥作用并导致癌症等疾病。这些分析可产生“ragged（不规则）”的基因组范围（Genomic Ranges）数据，即每个样本在不同的基因组坐标都有对应结果，不能整齐地组装在一起。不规则数据可以VCF格式存储在磁盘上，但由于其不是矩形或矩阵状的，为下游统计分析带来了信息学方面的挑战。研究团队提出了Ragged Experiment R/Bioconductor数据结构，可无损表示来自多个样本的不规则genomic ranges数据，并为每个样本中相同Ranges的矩阵格式汇总提供了灵活、高效的工具，以支持广泛的下游统计分析。经验证，Ragged exexperiment有效地表征了TCGA（癌症基因组图谱）和cBioPortal数据库中的拷贝数和体细胞突变数据，适用性较强。

- 论文链接：https://dx.doi.org/doi:10.18129/B9.bioc.RaggedExperiment
- 包链接：https://github.com/Bioconductor/RaggedExperiment

4、[iMeta | 探索HPV相关肿瘤的肿瘤免疫微环境的shiny网页工具](https://mp.weixin.qq.com/s/1ti7VbVHjZkU2dE2PcDrJw)


![](https://files.mdnice.com/user/4331/587e426a-a88f-45cb-a9cd-2cc3ce7a00ed.png)

南方医科大学罗鹏、张健，香港大学袁硕峰和中南大学程全等团队在 iMeta 在联合开发了一个名为HPV相关肿瘤免疫微环境分析平台（HPVTIMER）的网络工具，它作为一个综合分析平台，整合了基因表达综合数据库（Gene Expression Omnibus，GEO）内现有的8种HPV相关肿瘤、共65个转录组数据集、2,290个样本、超过10,000个基因的表达数据。

- 论文链接： https://doi.org/10.1002/imt2.130
- 网站链接：http://www.hpvtimer.com/


## 博文资讯

5、[Python转录组学分析框架：Omicverse的安装以及差异分析](https://mp.weixin.qq.com/s/fIRVMNHFcffCuCzh_Qozhw)


![](https://files.mdnice.com/user/4331/3f2c35b4-2752-4d92-924b-c0d86404aaf5.png)

OmicVerse是用Python进行多组学（包括Bulk和单细胞分析）的基础框架。本文介绍了该软件的安装方法以及如何利用该软件进行差异分析。

6、[两位“食肉糜”的女生（外加一位男生）](https://mp.weixin.qq.com/s/dMAmQN8ASwPC_32mfYk4xw)

作者介绍了几位励志者的故事。

如作者所说：在无爹可拼，无矿可挖，人脉有限的情况下，把书读好是获得更好生活的最靠谱道路。一个人的发展中，人脉的重要性不能低估，每个年轻人都应该努力拓展并经营好自己的人脉。而读书与拓展经营人脉并不矛盾。一个有进取心，读书好，不整天怼天怼地中间怼空气的年轻人更容易让人愿意交往。

7、[低通量市场正在成为 NGS 公司竞争的一个主战场](https://mp.weixin.qq.com/s/Td4wNJZX50EkDlwUI4uqqQ)


![](https://files.mdnice.com/user/4331/398da064-4520-4bd8-b22c-bf5dd38c06ae.png)

一则译文，讨论了当前市场环境下低通量测序领域的激烈竞争。尽管近年来大型测序公司主要专注于高通量和中通量仪器，但低通量市场仍在持续发展。文章认为,在低通量测序市场中,价格将是关键竞争因素。


## 工具

8、[Rhino｜快速构建企业级 Shiny 应用程序](https://github.com/Appsilon/rhino)


![](https://files.mdnice.com/user/4331/9d2dc40b-83ee-4d8c-8881-bd75e31733a3.png)

Rhino是一款R语言插件，能够帮助你像全栈软件工程师一样，按照「Appsilon之道」创建 Shiny 应用。基于Rhino的开发应用了最佳软件工程实践，模块化代码，并可以编写完善的测试，打造美观的 UI。对于需要开发Shiny应用的小伙伴，值得尝试。

9、[Tidier.jl ｜ Julia 中用于数据分析的元包](https://github.com/TidierOrg/Tidier.jl)


![](https://files.mdnice.com/user/4331/7ee7b414-3ac8-4180-99ab-aa353ee96fce.png)


Tidier.jl 是一个专为 Julia 语言设计的数据分析包，灵感源自 R 语言的 tidyverse。喜欢tidyverse编码风格的小伙伴可以尝试。

10、[BigSeqKit | 一个并行大数据工具包，用于大规模处理FASTA和FASTQ文件](https://github.com/citiususc/BigSeqKit)


![](https://files.mdnice.com/user/4331/3df416a7-96c3-4bc5-8ca2-21318802614b.png)


11、[YouPlot | 命令行绘图工具](https://github.com/red-data-tools/YouPlot)


![](https://files.mdnice.com/user/4331/ed95ab08-7298-4b3f-8dea-311d6ad543a4.png)

一个例子：


![](https://files.mdnice.com/user/4331/24f47752-6b23-4d5d-9762-d5907d7fa56c.png)


## 资源
 
12、[15 个Web 开发者需要知道的杀手级网站](https://mp.weixin.qq.com/s/vZFTHYeyoPbhhTWh8nSiqw)


![](https://files.mdnice.com/user/4331/4ac48d6b-ba66-44e2-96c6-d306d5cb6674.png)


13、[diff.blog | 一个开发者新闻网站](https://diff.blog/)


## 历史上的本周

- 生信周刊第85期：[大学是否选生物：适合普通家庭、智力一般的学生](https://mp.weixin.qq.com/s/2zFb_8u_tzPkaAftJrCU0Q)

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

