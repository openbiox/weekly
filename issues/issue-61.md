# 生信爱好者周刊（第 61 期）：基因对寿命的影响


这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions "「生信周刊讨论区」")

## 封面图


![](https://files.mdnice.com/user/34023/6d0c3209-db50-421c-8915-405b88a5add5.png)

人的一生剪影图（[图来源](https://www.nipic.com/show/9415444.html "图来源")）。

## 本周话题：[基因对寿命的影响]([https://mp.weixin.qq.com/s/eGnpMKX-RYi2pNAGjiuRgw](https://mp.weixin.qq.com/s/eGnpMKX-RYi2pNAGjiuRgw))



![](https://files.mdnice.com/user/34023/2f6d985c-7e44-456e-a8bf-c24bc6f13a3b.png)


>   瑞士洛桑大学和美国田纳西大学健康科学中心的研究团队在国际顶尖学术期刊 Science 上发表了题为：Sex- and age-dependent genetics of longevity in a heterogeneous mouse population 的研究论文。该研究通过观察了3200多只基因多样化的小鼠，发现了影响小鼠寿命的几个染色体区域。并且有些基因效应在雄性和雌性之间有所不同，而有些基因效应只影响到了一定年龄后的寿命。

`@NiEntropy` - 想到了生物课本中的一句话：生物的性状是由基因决定的，而基因的表达受环境因素影响；想到了秦始皇炼丹渡海寻仙求长生，Google投资Calico专注衰老研究。从古至今，人类一直在追寻着长寿，而在日复一日的生活中，我更感兴趣未来会是什么样？是像《赛博朋克：边缘行者》中“低端生活与高等科技结合”的悲剧，还是我们共同的理想：在高度发达的社会生产力和广大共识范围，人们科学文化水平和思想觉悟，道德水平极大提高的基础上，实行各尽所能、按需分配原则的劳动者有序自由联合的社会经济形态。未来源于当下，还是要脚踏实地把当下的工作干好。


## 生信研究

1、[Nat Biotechnol | 首个高灵敏度、高通量、单细胞全长转录组测序方法VASA-seq](https://mp.weixin.qq.com/s/7rs15z3jgG1c3cLyU1R_Uw)

![](https://files.mdnice.com/user/34023/9c2ffc93-ee8b-4d2c-b333-c441dd4d86ec.png)

Nature Biotechnology上的这篇题为“High-throughput total RNA sequencing in single cells using VASA-seq”的文章介绍了一种结合了高灵敏度、全长转录组覆盖和高通量的单细胞测序技术-‘vast transcriptome analysis of single cells by dA-tailing’ （VASA-seq）。VASA-seq结合了10x Chromium平台提供的高通量、Smart-seq3方法的高灵敏度和Smart-seq-total在单一实验工作流中提供的非编码RNA的广谱捕获。此外，VASA-seq方法涉及的试剂成本较低，不依赖其他商业试剂盒，为廉价、大规模、深入的进行单细胞转录组测序成为可能。

- 论文链接：https://www.nature.com/articles/s41587-022-01361-8

2、[Nat Commun | 性能优于传统生物标志物！基于网络生物学的机器学习方法可准确预测癌症患者免疫治疗反应](https://mp.weixin.qq.com/s/mBl8nmbuIuP0Th-GKLAlkw)


![](https://files.mdnice.com/user/34023/b421b71a-8983-479b-8c13-0fa5abdfff20.png)


 近日，韩国浦项科技大学、延世大学的研究团队提出了一种基于网络生物学的机器学习（ML）模型，可以对ICI数据集进行稳健的预测，并识别潜在的网络生物标志物（NetBio）。研究团队整理了700多例接受ICI治疗的患者样本，包括临床结果和转录组数据。在基于NetBio的预测中，该方法准确预测了三种不同癌症（黑色素瘤、胃癌和膀胱癌）对ICI治疗的反应。此外，基于NetBio的预测效果优于基于其他传统生物标志物（如ICI靶标或肿瘤微环境相关标志物）的预测。

- 论文链接：https://www.nature.com/articles/s41467-022-31535-6

3、[Nat Mach Intel｜用语言模型进行可控的蛋白质设计](https://mp.weixin.qq.com/s/WUXjNYWHH64fsuSgjyNTvA)

![](https://files.mdnice.com/user/34023/7931ddf8-e9bc-4952-987c-537ce6d2c977.png)


> 蛋白质序列在本质上类似于自然语言：氨基酸以多种组合方式排列，形成承载功能的结构，就像字母组成单词和句子承载意义一样。因此自然语言处理（NLP）的许多技术被应用于蛋白质研究问题。
> 有几个特征证明了人类语言和蛋白质序列之间的相似性，其中最明显的可能是它们的分层组织。与人类语言类似，蛋白质是由字符串的连接表示的：20个标准氨基酸。然后字母组合成单词，氨基酸组合成二级结构或保守的蛋白质片段。然后，就像单词组合成带有意义的句子一样，片段可以组合成带有功能的不同蛋白质结构。

过去几年里，NLP领域有了革命性的突破。来自西班牙赫罗纳大学信息学与应用研究所的Noelia Ferruz等人在Nat Mach Intel杂志发表文章，讨论了人工智能领域的最新进展--语言模型在蛋白质设计中的潜力和影响。Transformer预训练模型的实施使文本生成具有类似人类的能力，于Transformer的蛋白质语言模型将彻底改变蛋白质设计领域，并为许多当前和未来的社会挑战提供新的解决方案。

- 论文链接：https://www.nature.com/articles/s42256-022-00499-z


4、[Genome Research | scFEA：一站式解决单细胞代谢分析](https://mp.weixin.qq.com/s/yW8Z6OBExlND63jGFc_XmQ)

![](https://files.mdnice.com/user/34023/e1ca330c-0f99-42af-9bb4-6851054c61fe.png)

细胞代谢是影响细胞功能的基础条件之一，在很多特定条件下，细胞代谢的改变往往早于细胞功能的改变。因此，成功的揭示不同条件下细胞的代谢状态，能够给我们研究细胞功能提供很好的参考价值。但是，即使是组织水平的代谢流也是稍纵即逝的，传统的生物学技术无法较好的捕捉同一时间下不同功能状态下的细胞代谢，而单细胞测序技术可以给我们提供一个新的研究思路。
细胞间的代谢异质性，和代谢物之间的相互作用被认为是疾病治疗耐药性的重要影响因素。然而，由于缺乏成熟的高通量单细胞代谢组学技术，我们尚未对组织内代谢异质性和协同机制建立系统的认识。为了缓解这一技术短板，作者开发了一种新的计算方法，即单细胞通量估计分析(scFEA)，以从scRNA-seq数据推断细胞内代谢物的通量研究。

- 论文链接：https://genome.cshlp.org/content/early/2021/07/22/gr.271205.120

## 博文资讯

5、[揭秘生存曲线背后的生物统计学](https://mp.weixin.qq.com/s/QWqnEM3poxx4g71yr0eVUQ)

![](https://files.mdnice.com/user/34023/48b726e7-e20e-45fe-a095-17550181ed42.png)

比较系统的生存分析概念科普，推荐大家阅读。

> 近年来中文出版界出现了包含数学公式的专业科普未必曲高和寡的可喜现象。在这些成功范例的鼓舞下，本文将从最基本的概念开始，对“生存分析海洋”的两大水域大胆进行深度潜水式科普。


6、[jjAnno | 优雅的帮你添加注释](https://mp.weixin.qq.com/s/x92SNB-Cixa6G1FG0PwoWg)

![](https://files.mdnice.com/user/34023/8433c90f-aa3e-4143-9bba-b7d198552cd1.png)

本文介绍了如何通过jjAnno包给Figure周围添加各种各样的注释(文字、线段和矩形等等)。

- R包地址：https://github.com/junjunlab/jjAnno

7、[连线图应该如何画？](https://mp.weixin.qq.com/s/_T7k13RGn_3UaU7Jc54GzA)

![](https://files.mdnice.com/user/34023/d97f3f54-cb39-4ef2-a93f-a6aa7fffa30c.png)

细胞-细胞配体-受体 (LRs) 和细胞因子相关通路网络分析图的绘画教程。

8、[xTrimo Multimer | 加速蛋白质预测，比AlphaFold2快10倍](https://mp.weixin.qq.com/s/F5Xl8iS_UuXObiapGHpNkg)

![](https://files.mdnice.com/user/34023/c6ef8db2-3005-4676-bbcb-824e10c37a9d.png)

在2022年3月，Colossal-AI 团队曾推出蛋白质结构预测模型AlphaFold的训练推理加速方案FastFold，用更低的成本将总体训练时间从11天减少到67小时，在长序列推理应用中实现超11倍的提升。以此为起点，Colossal-AI 团队在进一步探索蛋白质结构预测领域的技术革新。针对蛋白质单体(Monomer)与复合物(Multimer)结构预测的难题，本次Colossal-AI 团队联合百图生科提出行业内最新解决方案 xTrimo Multimer开源版模型，能够更好地理解蛋白互作关系，从而提升药物研发平台中靶点分析、蛋白质结构预测和模拟以及高精准抗体设计等方面的能力。xTrimo Multimer可以支持长达4K的序列推理，此时OpenFold和AlphaFold 2受限于显存无法完成推理，而xTrimo Multimer可以在20分钟左右完成。

- Github:https://github.com/hpcaitech/ColossalAI/#xTrimoMultimer
- Github:https://github.com/hpcaitech/ColossalAI

## 工具

9、[Nezzle | 一个用Python编写的交互式和可编程的生物网络可视化软件](https://academic.oup.com/bioinformatics/article/38/12/3310/6585333 "Nezzle | 一个用Python编写的交互式和可编程的生物网络可视化软件")

![](https://files.mdnice.com/user/34023/1fe7590f-6ee6-4d06-a545-ec00bda6575c.png)

Nezzle是一款网络可视化软件（意思是Net + Puzzle，因为调整网络的节点和边进行可视化类似于拼图）。它提供交互式和可编程的界面，允许用户通过Python编程调整节点和边的位置，并自动实现图形组件的风格化。

- 工具链接：https://github.com/dwgoon/nezzle

10、[diagrams.net | 图表绘制](https://www.diagrams.net/index.html "diagrams.net | 图表绘制")

![](https://files.mdnice.com/user/34023/fd9eed8e-0e55-4f28-8e6e-b5724e6e78ce.png)

diagrams 是一个免费的图表绘制网站，提供的丰富的功能和多平台的应用。

11、[facets | 可视化机器学习数据集](https://github.com/PAIR-code/facets "facets | 可视化机器学习数据集")

![](https://files.mdnice.com/user/34023/aadfda8f-8584-4a29-9d47-cf5cb7b88f49.png)

facets项目包含了两个可视化功能理解和分析机器学习数据集：Facets Overview 和 Facets Dive。可视化由Polymer网页部件实施，由Typescript代码支撑可以轻松嵌入到Jupyter笔记本和网页中。

- Github: https://github.com/PAIR-code/facets


12、[ProteinContactNetworks | 蛋白接触网络分析](https://github.com/hguzzi/ProteinContactNetworks "ProteinContactNetworks | 蛋白接触网络分析")

![](https://files.mdnice.com/user/34023/e75cf38c-d910-445b-8ed5-7e2d5ad73dfe.png)

蛋白质接触网络分析图，节点代表氨基酸，当两个节点的距离在 4 到 8  Angstrom间时，认为两个节点间存在接触。

> 1 Angstrom = 0.1 nanometre

- Github：https://github.com/hguzzi/ProteinContactNetworks

13、[nf-core/sarek | 体细胞变异开源分析管道](https://github.com/nf-core/sarek "nf-core/sarek | 体细胞变异开源分析管道")

![](https://files.mdnice.com/user/34023/ec079568-0343-4133-a643-240c2aeabd57.png)


- Github：https://github.com/nf-core/sarek


## 资源

14、[pzweuj | 生物信息实践](https://pzweuj.github.io/worstpractice/site/ "pzweuj | 生物信息实践")

![](https://files.mdnice.com/user/34023/b7d7e477-8e8c-448a-9082-c6f84c7602f7.png)

目前博主更新了，DNA-seq、RNA-seq、mNGS的相关分析教程。

- 博客：https://pzweuj.github.io/archive.html
- 教程：https://pzweuj.github.io/worstpractice/site/

15、[WebStack-Hugo | 无需服务器静态响应式网址导航主题](https://nav.bioitee.com/ "WebStack-Hugo | 无需服务器静态响应式网址导航主题")


![](https://files.mdnice.com/user/34023/e1853b26-6bbd-456f-aa38-862ef64d83ab.png)


- 安装教程：https://www.yuque.com/shenweiyan/cookbook/webstack-hugo#eH1Sb

## 历史上的本周

- 2022年3月：[第21期：科研与爱好]([https://mp.weixin.qq.com/s/jSkT1qM0dGK_4AkBVBNfbQ](https://mp.weixin.qq.com/s/jSkT1qM0dGK_4AkBVBNfbQ))

## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`（王诗翔）
- `@kkjtmac`（阚科佳）
- `@NiEntropy`（赵启祥）
- `@He-Kai-fly`（何凯）
- `@JnanZhang`（张佳楠）
- `@Tomcxf`（陈啸枫）
- `@wangdepin`（王德品）

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://files.mdnice.com/user/34023/49236e50-4d98-4333-9d27-62c31f613057.png)

（完）
