---
date: 2024-02-03
comments: true
---

# 生信爱好者周刊（第 111 期）：三十多岁博士后对于生活的挣扎

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图


![](https://files.mdnice.com/user/5208/3e1794e4-f8af-4e01-bbac-852c59d9b1b6.png)

## 本周话题：[三十多岁博士后对于生活的挣扎](https://mp.weixin.qq.com/s/23unkXe5Ba2-oLa-USd_JQ "三十多岁博士后对于生活的挣扎")

> 中国的高等教育体系和学术就业市场同样经历着变革，这对博士后的未来规划产生了影响。在这个过程中，如何有效地利用现有资源、把握职业机会，并在此基础上构建一个充实的个人生活，成为每个博士后需要思考的问题。最终，成功的关键在于找到个人与职业之间的平衡，实现学术追求与生活质量的双赢。
- `@He-Kai-fly` ： 恰逢过年，凑巧看到另一篇帖子，深有感触 [博士返乡过年：没毕业没对象没发财的我，成了他们眼里的怪胎](https://mp.weixin.qq.com/s/DxshpWCqaLYSIzDvX5rLPQ)
- `@ShixiangWang`：正在经历博士后的阶段，普遍感知到年龄、阶层和认可等限制了青年科研主力军的个人独立发展。博士后在激增，未来学生、博后、老师未来可能存在更多的情感博弈。


## 生信研究
1、[Nat Commun | 结合HiFi、Hi-C技术优势的新算法pstools，可高效、准确重建癌症染色体单倍型基因组](https://mp.weixin.qq.com/s/xbHh5ml0tKYRFuJGqCxeuA)

![Pstools算法的工作流程](https://files.mdnice.com/user/5208/14ab04a1-d3a0-4278-a9d7-e463b650016a.png)


> 近日，丹麦技术大学Shilpa Garg团队在Nature Communications发表题为“Towards routine chromosome-scale haplotype-resolved reconstruction in cancer genomics”的文章。研究团队将高准确度的HiFi长读长测序和Hi-C长读长测序应用于黑色素瘤COLO829癌症细胞系中，并开发了一种高效的、基于图（Graph-Based）的pstools方法，可处理高分辨率的HiFi和Hi-C数据，用于染色体水平单倍型基因组重建，以精确表征癌症的SV情况。在没有亲本信息的情况下，pstools方法能在12h内生成染色体水平的高质量phased scaffold，优于现有方法。此外，该方法还在碱基分辨率下发现了准确的染色体水平SV。 


- 论文链接：https://www.nature.com/articles/s41467-023-36689-5


2、[Nat Commun | 新贝叶斯统计方法PhylEx，可利用单细胞转录组学重建肿瘤克隆树](https://mp.weixin.qq.com/s/UShjwMIR4YLdAiBlgnOyJg)


![](https://files.mdnice.com/user/5208/5236b004-1af9-4fac-b7e2-3f0694342f75.png)

> 研究团队介绍了一种名为PhylEx（Phylo Expression）的贝叶斯统计方法，其集成了DNA-seq和scRNA-seq数据，可利用在单细胞内观察到的单核苷酸变异（SNV）信息来识别克隆、改善克隆树重建，并将RNA表达谱信息高精度映射到克隆上。PhylEx解锁了系统表型分析的潜力，能够在与克隆基因型相关的单个克隆基因和通路水平上发现、描述肿瘤的进展及复发机制。

- 论文链接：https://www.nature.com/articles/s41467-023-36202-y
- 代码：https://github.com/junseonghwan/PhylExAnalysis


3、[Commun Biol | 跨越20种癌症类型！基于基因表达谱精确预测泛癌肿瘤纯度的新方法——PUREE](https://mp.weixin.qq.com/s/haMIDHSEqJm6S5izjinqPw)



![](https://files.mdnice.com/user/5208/7aa034ea-b1b7-4314-90ac-61a0e84afc33.png)


> 近期，来自新加坡国立大学的研究人员及合作者在Communications Biology发表了题为“PUREE: accurate pan-cancer tumor purity estimation from gene expression data”的研究论文。研究团队开发出一种使用弱监督学习方法从基因表达数据中精确预估泛癌肿瘤纯度的新计算方法PUREE。PUREE可对不同实体瘤类型纯度进行高精度预测，并可推广到来自未知肿瘤类型和队列的肿瘤样本。

- 论文链接：https://www.nature.com/articles/s42003-023-04764-8





4、[Nat Commun|空间分析工具包SPIAT & 组织空间数据模拟器spaSim联合表征、模拟组织微环境](https://mp.weixin.qq.com/s/CdvCagvbzpU7_WAM2q70hA)


![SPIAT工作原理流程图](https://files.mdnice.com/user/5208/92b64bc6-140f-4be4-9bfa-88af8c31f630.png)


> 近日，澳大利亚彼得麦卡勒姆癌症中心的研究团队在Nature Communications发表了题为“Spatial analysis with SPIAT and spaSim to characterize and simulate tissue microenvironments”的文章，报道了其开发的空间分析工具SPIAT和spaSim。SPIAT是一个与平台无关、用户友好型分析工具包，用于表征多重组织图像的空间模式；spaSim是一个新型的组织细胞空间模式模拟器，用于空间指标的基准测试。通过对多种不同癌症病例的分析，研究团队展示了SPIAT识别临床相关已知和新型免疫细胞亚型的能力。SPIAT和spaSim是量化空间模式、识别和验证临床结果相关性以及支持方法开发的有效工具，可帮助推动空间指标在基础、转化和临床研究中的应用。


- 论文链接：https://www.nature.com/articles/s41467-023-37822-0

## 博文资讯


5、[所谓“学术妲己”上热搜背后，真正的学术顽疾反而隐身了](https://mp.weixin.qq.com/s/dvoTDvkM-38-5pbMKYmQvw)



![](https://files.mdnice.com/user/5208/50c7d8b2-b1ec-409e-9f88-67f8011bfcaf.png)

互联网引发的舆论中，人们更热衷讨论所谓“学术妲己”，应该被郑重以待的学术不端和师生关系异化问题遮蔽在桃色新闻下。


6、[谷歌DeepMind打破十年算法封印，AlphaDev惊世登场，颠覆人类算法格局！](https://mp.weixin.qq.com/s/vSpjA-VnRTLMfBNXzqBaWQ)


![](https://files.mdnice.com/user/5208/3f178a79-7af9-4956-a054-fcae7a3431c7.png)

> 「Alpha」家族再添新成员AlphaDev！谷歌大脑DeepMind合体后首发力作，全新AI系统将排序算法提速70％，C++排序库十年来首次更改。


7、[华大等机构共同研制的宏基因组数据处理国际标准发布](https://github.com/openbiox/weekly/issues/1609 "华大等机构共同研制的宏基因组数据处理国际标准发布")



![](https://files.mdnice.com/user/5208/3561db72-0e3a-489a-a37a-136209a8da45.png)


> 5月19日，由深圳华大生命科学研究院联合中国科学院微生物研究所共同提出，中国食品发酵工业研究院有限公司、深圳华大智造科技股份有限公司等共同参与研制的国际标准《ISO/TS 24420:2023 Biotechnology — Massively parallel DNA sequencing—General requirements for data processing of shotgun metagenomic sequences（暂译名：生物技术-大规模并行DNA测序-鸟枪法宏基因组数据处理通用要求）》发布。


8、[OPPO造芯的最后18分钟：CEO数次低头哽咽，3000人团队原地解散](https://mp.weixin.qq.com/s/uDAXAAklXObDb_nihRZwtA)


![](https://files.mdnice.com/user/5208/7fb55d90-6e8a-469c-9b30-a79a808117f0.png)


> 3天前（5月12日），OPPO芯片设计公司哲库CEO刘君宣布宣布造芯业务终止，立即叫停所有业务，3000人团队就地解散。


## 工具

9、[Flow：在注释集上进行本地配置和执行分析的R包](https://github.com/mskilab/Flow "Flow：在注释集上进行本地配置和执行分析的R包")


![](https://files.mdnice.com/user/5208/2ea73f02-b852-4c6a-aa53-891f6be36c87.png)


> Flow 是一个 R 包，可在带注释的实体集（例如对、个体、样本）上进行本地配置和执行分析模块。工作可以部署在本地或集群中，然后进行监控和管理。工作完成后，它们的输出可以作为注释附加回各自的实体，以便轻松导入回数据库或与平面文件表合并。


10、[liger | 整合分析单细胞多队列数据](https://github.com/welch-lab/liger "liger | 整合分析单细胞多队列数据")

![](https://files.mdnice.com/user/5208/07b71333-d149-4c8a-9f0e-c570de071e79.png)
> LIGER是一个用于整合和分析多个单细胞数据集的软件包，由Macosko实验室开发并由Welch实验室进行维护和扩展。它依赖于整合性非负矩阵分解来识别共享因子和数据集特异性因子。

11、[pyCirclize:基于Python进行的环状图可视化](https://github.com/nrennie/ggflowchart "ggflowchart | ggplot 绘制流程图")


![](https://files.mdnice.com/user/5208/d1ce370a-6166-4b06-a42e-9324daed58b0.png)


pyCirclize是一个基于matplotlib实现的循环可视化python包。该软件包是为了在Python中轻松、精美地绘制圆形图形（例如Circos Plot和Chord Diagment）而开发的。此外，还实现了生物信息学领域有用的基因组和系统发育树可视化方法。 pyCirclize 的灵感来自 circlize 和 pyCircos。
- 文档：https://moshi4.github.io/pyCirclize/

## 资源
12、[842个单细胞数据集，超5000万个单细胞的数量](https://mp.weixin.qq.com/s/4CBQf1oVWcCjIRYt8alqGg)


![](https://files.mdnice.com/user/5208/0cec121e-5a80-49e4-a8e9-e59a670541f1.png)


- Single Cell Portal: https://singlecell.broadinstitute.org/single_cell
- 单细胞门户网站：https://singlecell.broadinstitute.org/single_cell

13、[ref-gen:人类基因组下载](https://github.com/lh3/ref-gen "ref-gen:人类基因组下载")

![](https://files.mdnice.com/user/5208/5bc1bb9f-0302-418f-8ddf-24aac61a0f2e.png)


> 人类参考基因组有多个版本。据 UCSC 称，迄今为止使用最广泛的是 GRCh38 或 hg38。 NCBI、GRC、UCSC 和 Ensembl 都提供了各自的 GRCh38 版本，这些版本彼此之间略有不同，并且通常不是最佳的。在分析中选择正确的参考基因组是非常重要的。



14、[R宇宙:一个关于R语言的最强搜索引擎](https://r-universe.dev/search/ "R宇宙:一个关于R语言的最强搜索引擎")

![](https://files.mdnice.com/user/5208/f134567e-0909-4664-a324-5b39d8836677.png)


## 历史上的本周
- 第70期：[多彩多姿的科学家](https://mp.weixin.qq.com/s/uxnBPpyv5HI8xQh36gHsvw)


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

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

