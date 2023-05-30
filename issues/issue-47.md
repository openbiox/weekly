---
date: 2023-03-25
comments: true
---

# 生信爱好者周刊（第 47 期）：RStudio 改名 Posit

> 祝各位读者国庆假期快乐，我们下期将延期一周准备和发布。

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)

## 封面图

![](https://files.mdnice.com/user/4331/dcbbee08-610a-45c0-b206-aa88bc0d685d.jpeg)

世界上最大的洞穴-道恩洞（[via](https://mossandfog.com/earths-biggest-cave-will-blow-your-mind/)）。



## 本周话题：RStudio 改名 Posit

![](https://files.mdnice.com/user/4331/67ad3cb6-2e5f-4e5a-96d5-1fe97fbd75e1.png)

2022年的RStudio大会上RStudio宣布改名为Posit（https://posit.co/），以拓宽其在数据科学领域的探索与应用，其核心产品RStudio编辑器将维持原名。

![](https://files.mdnice.com/user/4331/0bd6c3db-9ba6-449b-bf93-fbad9968665d.png)

推特用户`@Sharon Machlis`写道：RStudio changes its name to Posit as it expands focus to Python and VS Code - but officials say they're not forsaking R.

`@ShixiangWang` - 之前万万没想到改名，但RStudio公司的改名对我们使用RStudio软件的人来说没什么影响。从改名我们也不难推测出该公司在走上坡路，想要在数据科学领域进行拓展、占据更重要的位置。本期推荐的产品quarto其实就承载着这样的志向，把RMarkdown的成功推向多种编程语言。希望Posit公司未来的进步为R社区带来更多的进展，包括软件生态、编程范式、计算性能。

## 生信研究

1、[Science | 人类细胞图谱](https://mp.weixin.qq.com/s/S0uzcQyEwTlD8tbgIURGSQ)


![](https://files.mdnice.com/user/4331/641f5917-69d3-4f53-ad0e-85df3f59b200.png)

5月份Science杂志封面展示了人类细胞图谱合作组（Human Cell Atlas Consortium）的四篇人类多组织单细胞图谱的研究，同时邀请北京大学张泽民教授进行评述并发表了专门的观点文章：Mapping cell types across human tissues。发表的这四篇论文提供迄今为止最全面、最多组织的细胞图谱，横跨了人类33个器官共计超百万个单细胞数据。

- 论文链接：
  - https://www.science.org/doi/10.1126/science.abq2116
  - https://www.science.org/doi/10.1126/science.abl4896
  - https://www.science.org/doi/10.1126/science.abl4290
  - https://www.science.org/doi/10.1126/science.abl5197
  - https://www.science.org/doi/10.1126/science.abo0510

2、[iScience | 首个细胞级组装的人体集成细胞图谱hECA](https://mp.weixin.qq.com/s/eCY605JMrc1pLdc32heNAg)


![](https://files.mdnice.com/user/4331/054cda4a-6762-4609-95d7-ab42e095ea09.png)

张学工研究团队开发了一个统一的信息学框架，用于细胞中心数据无缝组装，并从分散的数据中构建了人类集成细胞图谱（hECA）。据悉，这是首个细胞级组装的人体集成细胞图谱，汇集了来自116个已发表数据集的1,093,299个已标记的人类细胞，涵盖38个器官和11个系统。

这里涉及一个新概念：细胞级组装/集成，解释为：

> 细胞级组装就是对不同来源的人体单细胞数据经过统一质控和预处理后，按统一信息框架集成到同一个数据集合体中，保存关于每个细胞的所有信息。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/35602947/

3、[Nature Genetics | 多维空间组学研究揭示：肿瘤微环境结构可作为乳腺癌临床预后的有效指征](https://mp.weixin.qq.com/s/iqEMK7nI0dDVCdhxakm2Eg)


![](https://files.mdnice.com/user/4331/b5ffa513-9886-457d-a257-0d906b00cf9d.png)

剑桥大学的研究团队使用成像质谱流式技术（Imaging Mass Cytometry, IMC）结合来自693名乳腺肿瘤患者样本的基因组、临床数据进行了多维空间分析，揭示了乳腺肿瘤中TME结构分布及其与基因组特征和临床结果的关系。该研究系统绘制了TME的原位结构，并确定了10个具有不同富集模式的复发性TME结构，其中一些结构与指示免疫逃逸的基因组谱相关。该研究揭示的多细胞结构将保守的空间组织与局部TME功能相结合，可以用于改善患者分层，也为未来理解癌症组织的空间组织原理奠定了基础。

- 论文链接：https://www.nature.com/articles/s41588-022-01041-y

4、[Cancer Research | 发文揭示不同癌症类型TMB与免疫治疗反应关联的免疫决定因素](https://mp.weixin.qq.com/s/B9bVKJZiBnspA3G3PWpPUw)


![](https://files.mdnice.com/user/4331/c031632a-3e5b-4543-bb4e-1d2432a489db.png)

美国国立卫生研究院（NIH）国家癌症研究所的研究团队检测了TCGA中31个具有不同癌症类型TME特征的免疫相关因子水平，并将其与2,277名接受ICI治疗（抗PD-1/抗PD-L1）患者的TMB和反应数据相结合，在14种不同癌症类型中确定了决定TMB效力的关键免疫因子。结果显示，TME中高水平的M1巨噬细胞和低静息的树突状细胞表征了具有高TMB效力的癌症类型。此外，基于这两种免疫因子的模型也准确预测了特定癌症类型中的TMB影响。

- 论文链接：https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9177633/


## 博文资讯

5、[获6亿美元融资，基因测序公司Ultima Genomics推出100美元全基因组测序](https://mp.weixin.qq.com/s/zWUcnM-K5Rr0K1MQASy2mg)


![](https://files.mdnice.com/user/4331/418f2219-13b5-4e9c-8e15-51f924032c03.png)

基因组测序公司 Ultima Genomics 走出隐身模式，宣布完成6亿美元融资，并推出新型高通量、低成本基因测序平台，可提供100美元的全基因组测序，这直接将当前1000美元的全基因组测序价格降了一个数量级。据悉，使用该测序平台的第一批科研成果——全基因组测序、单细胞测序和癌症表观遗传学测序，在预印本平台 bioRxiv 上发表，或在基因组生物学技术进展大会（AGBT）上发布。

6、[epistack 优雅的可视化你的基因区域](https://mp.weixin.qq.com/s/DuNDOFV8eapPHU0ulPeu-g)


![](https://files.mdnice.com/user/4331/8052c6c2-a0ed-4b2d-aada-693f3bc4b398.png)

epistack 包的主要目的是以感兴趣的基因组区域为中心的将基因组印记(支持但不限于 ChIP-seq、ATAC-seq、DNA 甲基化或基因组保守数据)整合可视化。

7、[节省夏令时？（英文）](https://www.garrickadenbuie.com/blog/saving-daylight-time/#around-the-world)


![](https://files.mdnice.com/user/4331/7fa6fa55-2311-4151-92ca-dbc2001598f7.png)

国外有一些国家地区使用夏令时，本文以数据可视化探索世界各地和美国城市的夏令时。对于可视化感兴趣的读者不妨读读、学习下可视化优化源代码。

8、[Python已可在浏览器端运行，或将成为前后端通吃语言？](https://mp.weixin.qq.com/s/67Z5n1c9n9x4b7iPItBPyg)


![](https://files.mdnice.com/user/4331/f9778834-1ce0-4c2c-b434-45edf31afd7a.png)

Anaconda发布了可在浏览器端运行的 Python—PyScript开发框架。它为开发者提供了在标准 HTML 中嵌入编写 Python 代码的能力、使用 Python 调用 JavaScript 函数库，以及创建 Python Web 应用。目前 PyScript 处于 alpha 测试阶段，下载和安装地址：https://pyscript.net/。


## 工具


9、[演讲展示工具 | Marp & DeckDeckGo](https://twitter.com/learn_byexample/status/1504444089416105987)


![](https://files.mdnice.com/user/4331/00f02c4b-2262-4c90-857b-078df2f44336.png)

该推文介绍了两个不同平台的演讲展示工具。Marp是基于Markdown的演讲展示制作工具，而DeckDeckGo是web端的编辑工具。

- 工具链接:
  - https://github.com/marp-team/marp
  - https://github.com/deckgo/deckdeckgo

10、[toastui - 交互式数据展示](https://github.com/dreamRs/toastui)


![](https://files.mdnice.com/user/4331/d0cbf838-95df-4054-a710-f7855adceb12.png)

toastui包可以创建交互式表格、日历和图表。


11、[susieR](https://github.com/stephenslab/susieR)


![](https://files.mdnice.com/user/4331/b72aaafe-8928-4192-8f99-d261f783c895.png)


susieR利用一种简单的新方法来执行多元回归中的变量选择（$y=Xb+e$）。这里实现的方法特别适用于某些X变量高度相关、真实效果高度稀疏的设置。其中的一个例子是基因精细制图应用程序，这是开发本方法的主要动机。同时，本方法也可以应用于更普遍的情况。

12、[pkgverse - 像tidyverse一样构建自己的R包集](https://github.com/mkearney/pkgverse)


![](https://files.mdnice.com/user/4331/7871ad6f-35e0-4e3b-a036-21ee299301e9.png)


13、[Warp](https://github.com/warpdotdev/Warp)


![](https://files.mdnice.com/user/4331/da95199b-adbe-403b-8aa4-93011f9e2dc3.png)

Warp 是一款速度极快的现代基于 Rust 的 GPU 加速终端，旨在提高个人和团队的工作效率。目前仅支持MacOS。


14、[quarto - 支持多种语言的可执行markdown工具](https://quarto.org/)


![](https://files.mdnice.com/user/4331/907b63f7-8672-4c56-904c-a6c070eb59f4.png)

Quarto 是一个基于 Pandoc 的开源科技出版系统，新一代的markdown，支持VS_Code ，RStuido(Posit)，Jupyterr，Text_Editor等多种软件。


## 资源

15、[Smart - 免费医学图像集合](https://smart.servier.com/)


![](https://files.mdnice.com/user/4331/15ac271d-796b-4823-8073-cd361916f215.png)


16、[哈佛大学的生物信息学培训](https://hbctraining.github.io/main/)


![](https://files.mdnice.com/user/4331/d10b3e88-41ab-4bae-9897-c7b160f9f4db.png)

Shell、R、Python的基础使用教程；RNAseq、sc-RNAseq、ChIPseq的高级分析教程。

## 历史上的本周

- 2021：[第 7 期：为何年轻便科研至死](https://mp.weixin.qq.com/s/LAwMeyFP3qn9uI38DUK-VA)

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

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

