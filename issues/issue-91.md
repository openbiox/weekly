---
date: 2023-09-02
comments: true
---

# 生信爱好者周刊（第 91 期）：探索的动机

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图


![](https://files.mdnice.com/user/5208/f7beb12f-4bce-4d0e-a8a2-363b0d0eb3a2.png)



## 本周话题：[探索的动机](https://mp.weixin.qq.com/s/GWmgS-oQY0wcsWMFux5nWQ)

> 人类自古以来就对世界有恐惧感，而科学可以帮助人们了解宇宙的规律、增长智慧，有了智慧之后，人类就不再困惑，也不再因为自身在宇宙中的存在而感到恐惧不安。当心安定了，人们做任何事情，成功也好，不成功也罢，都不那么容易患得患失。人心的焦虑往往源于此：没有时怕得不到，得到后又唯恐失去。用爱因斯坦的话来说，人类探索的一个主要目的就是追求思想上的解放。尽管科学探索的路并非坦途，但归根到底依然是为了仁、智、勇，为了真正做好一个“人”，这也是科学探索的最终奥义了。

@ShixiangWang: 探索的动机既是对未知的恐惧，也是对掌握的渴望。它塑造信息的不对称，又推进着文明的进程。

## 生信研究
1、[Briefings in Bioinformatics | 一站式肿瘤精准诊疗文献挖掘平台OncoPubMiner](https://mp.weixin.qq.com/s/jL-SNHM1qgUDUcmLNxclVQ)


![](https://files.mdnice.com/user/5208/1c5ea833-f4ad-4c29-9551-0b169df70814.png)


> 研究论文是科研发现的第一展示阵地，也是肿瘤精准诊疗知识数据的重要来源。该项目以文献数据挖掘为目标，从NCBI下载可公开使用（open-access）的PubMed摘要（Abstract）和PMC全文（Full-text），经过脚本处理、解析和格式转化后，利用基于人工智能的NLP技术对肿瘤精准诊疗相关的实体（如癌种、基因、变异、药物、临床意义、证据方向）进行挖掘。同时，利用业界常用的术语集（terminology）和本体（ontology），分别对自动化标注的实体进行标准化和层级化处理。最后，基于数据挖掘结果，构建一套包括文献检索、文库管理、团队搭建、表单定制、项目管理、数据摘录及审核等功能在内的全流程一站式平台。

- 论文链接：https://academic.oup.com/bib/article-abstract/23/5/bbac383/6691792?redirectedFrom=fulltext
- 网址：https://oncopubminer.chosenmedinfo.com/




2、[Nature Cancer | MSK团队开发新技术MACHETE，揭示染色体9p21.3缺失是肿瘤细胞免疫逃避和转移的介质](https://mp.weixin.qq.com/s/Jl6BeRtKdIAnU_OWpTKcWQ)


![](https://files.mdnice.com/user/5208/cc578b31-fe91-49be-ade6-4878f26a997a.png)



>  癌症中经常发生的一种大规模基因变化是拷贝数变异改变（CNA），有研究显示，一个典型的肿瘤平均有24个不同的CNA，影响其高达30%的基因组。美国纪念斯隆凯特琳癌症中心（MSK）此前的研究发现，具有较高水平CNA的肿瘤与乳腺癌、前列腺癌、子宫内膜癌、肾透明细胞癌、甲状腺癌和结直肠癌的复发和恶化有关。CNA的大小和种类影响了数千甚至数百万对DNA碱基对，而不仅仅是DNA序列中一个碱基的改变，因此不能通过操纵单个基因来重现，很难在实验室模型中重新生成以进行深入研究。
近日，MSK研究团队开发了一种基于CRISPR新技术MACHETE，可以切割基因序列的重要靶标部分，反映癌症和其他人类疾病中出现的变化，可用于实验室模型中高效地研究大规模基因缺失，例如CNA。研究团队利用MACHETE揭示了一种导致约15%癌症的基因变化，这可能有助于识别对免疫疗法有反应的患者。

- 论文链接：https://doi.org/10.1038/s43018-022-00443-5
        
        
        
        



3、[Nature丨 鉴定促进肠道炎症的环境因素 ](https://mp.weixin.qq.com/s/aKeLDzLJMGXv5dBJTYrOyg)

![斑马鱼中建立环境化学物质筛选平台](https://files.mdnice.com/user/5208/aa6d478f-3314-4055-b961-ceff7d8c97b2.png)
> 近日，美国哈佛大学Francisco J. Quintana研究组在Nature上发表了文章Identification of environmental factors that promote intestinal inflammation，通过结合公开的数据库、斑马鱼化学筛选、机器学习以及小鼠临床前模型等识别控制炎症性肠病的环境因素以及具体的发病机制。

- 论文链接：https://doi.org/10.1038/s41586-022-05308-6




4、[Nature Machine Intelligence | 基于对比学习的方法可快速映射到数百万规模的多模态单细胞图谱](https://mp.weixin.qq.com/s/XCWG4TGEg3aFrMWwnDPo_Q)

![](https://files.mdnice.com/user/5208/c7e86f76-018c-4371-9a3a-13bfaae22bc3.png)



> Nature Machine Intelligence上介绍了一个基于深度学习的、通过推导非线性细胞嵌入处理百万规模多模态单细胞数据的对比方法-Concerto。通过对真实数据集和模拟数据集进行基准测试，学习的嵌入可以针对各种下游需求进行微调，包括自动细胞类型分类、聚类、批次效应校正的数据集成以及query-to-reference映射。Concerto 可以灵活地处理多组学数据集，并在每个任务中优于其他方法。此外，作者利用Concerto 根据包含健康和感染样本的综合参考图谱查询 COVID-19 免疫细胞数据集，概括了具有不同疾病状态的患者的几种不同免疫特征。实验结果表明，Concerto 是一个强大、准确、可扩展的表示学习框架，可用于 1000 万个细胞规模的单细胞多模态分析。

- 论文链接：https://doi.org/10.1038/s42256-022-00518-z


## 博文资讯

5、[PyTorch 2.0](https://mp.weixin.qq.com/s/NzmUphWdQDemu-sWwh4vTg)

![](https://files.mdnice.com/user/5208/143d3813-eb2b-4dc7-a8ee-1a653cdc08f9.png)


> 一条稍微有些过时的资讯。

PyTorch 2.0 引入了 torch.compile，这是一种编译模式，可以在不更改模型代码的情况下加速模型。在 163 个涵盖视觉、NLP 和其他领域的开源模型中，该团队发现使用 2.0 可以将训练速度提高 38-76%。


6、[国内外开源免费的建站CMS有哪些？](https://www.zhihu.com/question/36861553/answer/2769588288 "国内外开源免费的建站CMS有哪些？")


![](https://files.mdnice.com/user/5208/0bdb4f46-e0a0-4fe5-8eae-cd8738ab99c5.png)


> 知乎讨论话题，总结了一些国内外著名的开源免费的建站CMS(Content Management System，内容管理系统)，例如WordPress、Django CMS等。对每款CMS进行了简要描述,并给出了相关GitHub地址和简单的安装步骤。



7、[回顾 | 系统进化树构建的常见方法](https://mp.weixin.qq.com/s/0p6JzDqjNrcPW_COFBd-zw)


![](https://files.mdnice.com/user/5208/c36b9d92-2db9-49a0-8f70-d4e9f92b4b83.png)

构建进化树的方法主要分为:

- 距离矩阵法（含 UPGMA、ME、NJ等）
- 最大简约法（MP）
- 极大似然法（ML）
- 贝叶斯法（Bayesian）



8、[MetaTiME:解析肿瘤免疫微环境中的元成分](https://github.com/yi-zhang/MetaTiME)

![](https://files.mdnice.com/user/5208/aa7af991-26bb-41e6-be31-40cbad454db0.png)

> MetaTiME通过整合数百个肿瘤scRNA-seq数据中的数百万个单细胞来学习数据驱动、可解释和可复制的基因程序。其想法是从大规模数据中学习具有生物学意义方向的单细胞空间地图，这有助于理解功能细胞状态并将知识转移到新的数据分析中。MetaTiME提供预训练的元组件(mec)，以自动注释细粒度细胞状态，并绘制肿瘤微环境新单细胞的特征连续谱。

- Tutorial: https://colab.research.google.com/github/yi-zhang/MetaTiME/blob/main/docs/notebooks/metatime_annotator.ipynb


## 工具

9、[ChatBot TheB.AI](https://beta.theb.ai/ "ChatBot TheB.AI")


![](https://files.mdnice.com/user/5208/d67a5a7f-ff6c-4e03-8cb8-120f6460000a.png)

多种对话模型选择（包括 ChatGPT）以及国内付费方案。可以一试。



10、[跟着Environ. Pollut.学群落组装机制（iCAMP）可视化](https://mp.weixin.qq.com/s/IhuiUPSw-ynp2U7xiNJxYg)


![](https://files.mdnice.com/user/5208/64112cf9-e227-4cc4-ade6-8bdb4dcf1dca.png)


> 为了系统展示itol.toolkit（辅助iTOL进行可视化的R包）的多个功能协同使用，本文选择了一些用iTOL制作并已发表的图来复现，本期的主题是群落组装机制，这是近些年微生物生态领域的大热门。



11、[WebR | 在浏览器中搭建R](https://github.com/r-wasm/webr "WebR | 在浏览器中搭建R")


![](https://files.mdnice.com/user/5208/dbfe3da4-50fa-49d0-af0e-f384960ccfbb.png)


- 工具链接：https://github.com/r-wasm/webr

## 资源
12、[Shiny.gosling:  R shiny中的基因组可视化](https://appsilon.com/shiny-gosling-examples-genomics-in-r/ "Shiny.gosling:  R shiny中的基因组可视化")

![](https://files.mdnice.com/user/5208/a8abdce5-abc9-4d45-b7cf-ca3c739ab530.png)

文章介绍了shiny.gosling包，可以将Gosling.js的语法引入R/Shiny中，实现基因组可视化。


13、[单细胞多组学数据分析最佳实践(2023典藏版)](https://mp.weixin.qq.com/s/jAkmtUW1BS44CWXEAHLzmA)

![](https://files.mdnice.com/user/5208/5917153e-1473-4410-8e2e-857934fb9d9a.png)

> 本文将引导读者了解单模态和多模态单细胞数据分析的各个步骤，并讨论隐藏在其中的分析陷阱和建议(图1)。在某些地方，由于工具的新颖性或缺乏独立的基准而无法确定最佳实践，作者将列出广泛采纳的工具和建议。作者将文章组织成特定于模式的部分和分析步骤组，而不是单一的工作流，在现代单细胞分析中，由于任务的多样性，这已经很少存在了。为了进一步阅读，作者提供了更广泛和定期更新(但没有同行评审)的单细胞最佳实践在线书籍(https://sc-best-practices.org/)，全书超过50章，包括详细的代码示例，分析模板以及计算需求的评估。


14、[程序员需知的 58 个网站，一次性整理全了！](https://mp.weixin.qq.com/s/lLFeONkjMmDb2ehpqxZ3AA)


![](https://files.mdnice.com/user/5208/f979e1d1-abef-44e0-866d-19ba7cc1d0fd.png)

> 文章总结了程序员学习和工作常用的58个网站,涵盖的范围包括语言和框架教程、电子书资源、官方文档、技术社区、博客、开源项目、面试练习等常用资源类型。对程序员学习和进阶具有很好的参考价值。



## 历史上的本周
- 第51期：[职业对性格的改变](https://mp.weixin.qq.com/s/j0nOPlFmn5ruEoX6kbyKpw)


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

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）



