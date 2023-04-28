---
date: 2023-04-21
comments: true
---
# 生信爱好者周刊（第 73 期）：迄今为止最开放、成果最多的大队列是如何建成的

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/38661/82f3d126-0e0d-4959-96ac-9bbbab8e9846.png)
来源：栗平/TNC Photo Contest 2022

## 本周话题：
[迄今为止最开放、成果最多的大队列是如何建成的](https://mp.weixin.qq.com/s/CEVJl9X4hKysL69VYgJn5A)
>从获得首个人类基因组已经过去了二十年，在当时，人们曾畅想在获得基因组之后就可以了解到每一个基因甚至是碱基的具体功能。但是二十年过去了，虽然对于人类基因组的研究在治疗癌症、寻找药物靶点以及诊断疾病获得了一定程度的进展，但是我们仍旧缺乏基因对于衰老、复杂性状以及疾病甚至是一些单基因致病疾病的具体影响。对于目前的这种困境，其中一个重要的原因就是高质量表型数据的缺乏，因此无法通过统计学的方法寻求性状与基因之间的具体关联。针对这一问题，一些包含有遗传数据的超大型前瞻性队列应运而生，其中最具有代表性的就是英国生物银行（UK Biobank）。

`@JnanZhang`："生物样本库作为生命科学基础研究与转化医学研究的宝贵资源，其重要性日益凸显，英国生物银行已成为了大数据时代下全世界队列研究的标杆。"

## 生信研究
1、[Genome Biology | 纳米孔测序可用于检测cfDNA的细胞起源和癌症特异性甲基化特征](https://mp.weixin.qq.com/s/t0V92wB_zkO8bKSQA-ETLw)
![](https://files.mdnice.com/user/38661/fb682f56-c9e3-4376-96b1-23177c093d48.png)
细胞游离DNA（cfDNA）携带起源组织的信息特征，包括基因组改变、DNA修饰和细胞类型特异性片段化模式等。其中，DNA甲基化是泛癌筛查研究中很有应用前景的cfDNA生物标志物。近日，来自以色列希伯来大学等单位的研究人员在Genome Biology杂志发表了题为“Detecting cell‑of‑origin and cancer‑specific methylation features of cell‑free DNA from Nanopore sequencing”的研究文章。研究团队进行了循环肿瘤DNA（ctDNA）ONT （Oxford Nanopore Technologies）测序的可行性研究，基于ONT全基因组测序检测癌症患者ctDNA的拷贝数变异（CNA），并通过比较ONT测序与短读长测序平台获得的甲基化和片段特征信息，证实了ONT测序可成为液体活检的有力工具。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02710-1

2、[Cell Genomics｜空间多组学技术解析肿瘤内空间异质性](https://mp.weixin.qq.com/s/_e1Bf0Y8uJ221V5Di9tdkQ)
![](https://files.mdnice.com/user/38661/20fb20c1-0635-4477-a569-3a6022dd82d7.png)
本研究利用多区域质谱分析（>5000个区域），多区域单细胞拷贝数测序（~2000个单细胞），以及循环免疫荧光（>1000万个细胞）三种空间组学技术，对147名肺腺癌患者的肿瘤进行了空间多组学分析。在肿瘤中发现了两种不同的空间异质性模式，定义为聚集模式（Clustered）和随机模式（Random）空间多样性（geographic diversification， GD）。并利用蛋白质组和基因组数据在相同的样本中观察到了一致的空间模式。随机模式的肿瘤，其特点是细胞粘附力不足和肿瘤互作内皮细胞水平较低，在两个独立的患者队列中与复发或死亡风险的增加显著相关。
- 论文链接：https://www.cell.com/cell-genomics/fulltext/S2666-979X(22)00107-0

3、[Nat. Commun|13.5小时即可获得WGS诊断结果！遗传病快速诊断管理系统GTRx与时间赛跑](https://mp.weixin.qq.com/s/bXW790fsA2BxYtPetrZZWA)

![](https://files.mdnice.com/user/38661/63c3f1d4-8659-4703-9b2f-60b520893b4a.png)
研究团队开发了一个13.5小时的诊断系统GTRx，用于自动化遗传病诊断和急性管理指导，以在扩大rWGS的使用范围，帮助一线医生在ICU中护理危重婴儿和儿童。据介绍，GTRx系统为原型系统，仅包含约500种进展迅速且有有效治疗方法的遗传疾病。在验证临床实用性后，该系统将扩展到所有遗传疾病，使一线医生能够在评估潜在遗传病因及其对患者的后续治疗方面发挥更积极的作用。

- 论文链接：https://www.nature.com/articles/s41467-022-31446-6

4、[Nat. Commun|侯英勇/丁琛/贺福初团队合作发布中国人群鳞状细胞癌蛋白质组学图谱，揭示鳞状细胞癌和腺癌的分子差异](https://mp.weixin.qq.com/s/BsGHFsCk5IoahvlVYwEagQ)

![](https://files.mdnice.com/user/38661/ed27d6a6-4c9b-437b-ada1-bbd356d01223.png)

复旦大学附属中山医院侯英勇团队、复旦大学人类表型组研究院丁琛团队以及北京生命科学研究所贺福初团队合作，通过系统地蛋白质组学分析揭示了中国人群SCCs和ACs之间的差异，并初步阐明了肿瘤发生机制和治疗策略。通过对蛋白质组数据进行深入分析，构建了包含19个蛋白的诊断分类器，并验证了PRKCE、SLC27A1和CPXM2的诊断价值。该研究证实深度蛋白质组学研究能够带来功能上的新见解，将有助于推动未来的机制探索和精准治疗。
- 论文链接：https://www.nature.com/articles/s41467-022-31719-0


## 博文资讯
5、[如何在分面中添加数学表达式标签?](https://mp.weixin.qq.com/s/Dbx9J_flkTtyi7LtRAdRPQ)

![](https://files.mdnice.com/user/38661/f1e4e2d0-e42b-461a-bce1-c3803c48438b.png)

设置数学表达式是科研绘图的一个需求，本文介绍了使用 expression() 函数定义表达式标签，并通过 ggplot2 进行绘制展示。

6、[ DESeq2 的 vst、rlog 和 normalized value 傻傻分不清?](https://mp.weixin.qq.com/s/2ZtTZx8E8K0rYu_wvP0JqQ)
![](https://files.mdnice.com/user/38661/d6bc0bf4-1c33-4d41-9a8f-02f57b960e62.png)
平常我们绘制热图什么的数据基本上用的可能是 TPM/FPKM/RPKM, 或者使用 DESeq2 的归一化值 normalized_counts <- counts(dds, normalized=TRUE) 。那么和 vst 和 rlog 又有什么区别呢?本文解决下面两个问题:
1.手动由 counts 数据计算 vst、rlog、normalized value。
2.探索它们之间的区别。

7、[严谨的生存分析](https://mp.weixin.qq.com/s/ODLHe0qK5-5-6Xup2TwQcQ)

![](https://files.mdnice.com/user/38661/c491e655-71ce-43a2-a25c-09a776a0e828.png)
在生物医学研究中，生存分析是非常重要和常见的分析方法。其中Cox模型是生存分析中常见的模型，可用来描述一个寿命类变量和若干因素之间的关系。本文通过一项卵巢癌的预后分析工作探讨了在应用Cox模型分析时候对于实际数据的一些处理，使得处理的数据既要合理也不至于损失太大信息。值得一读。

8、[EGA 数据申请与下载](https://mp.weixin.qq.com/s/FhzUjGF-Xcj-GcObXlO51A)

![](https://files.mdnice.com/user/38661/a51ee6cb-bbcb-4399-92e9-eb3436145a76.png)
本文用一个具体实例介绍了如何在European Genome-phenome Archive（EGA：收集了多种测序以及分型数据，如基因组关联分析、分子诊断以及各种目的的测序数据）申请数据以及后续下载操作。

- 数据库地址：https://ega-archive.org/


## 工具

9、[Huxtable ｜ 创建LaTeX和HTML表的友好现代接口](https://github.com/hughjonesd/huxtable )

![](https://files.mdnice.com/user/38661/d74dad1e-16ca-4451-8b46-09f675e89c6a.png)

Huxtable 是一个强大的表格展示工具，具有多样的使用方式，完善的文档，丰富的样式和导出等特性，非常值得尝试。

- 文档：https://hughjonesd.github.io/huxtable/

10、 [可视化代码库的7种工具](https://lmy.medium.com/7-tools-for-visualizing-a-codebase-41b7cddb1a14)

![](https://files.mdnice.com/user/38661/295ae744-cccd-4141-8f5e-cc263f5940ab.png)

当需要撰写README文件时，可能会因为不知该说什么而感到纠结，这时就可以考虑用图表来更好的表现你的想法。毕竟，一图胜千言。本文就介绍了7种可视化代码库的工具。


11、[Glasbey分类色板工具](https://github.com/lmcinnes/glasbey)

![](https://files.mdnice.com/user/38661/2b038d87-5d84-4b14-9bc7-e39f52568755.png)
Glasbey工具是通过算法创建用于分类数据的颜色调色板，与预定义的调色板相比，它更灵活，易于使用，并且可以扩展现有调色板。此外还可以生成适用于分层类别的块状调色板。
- github: https://github.com/lmcinnes/glasbey

12、[https://github.com/enblacar/SCpubr](https://github.com/enblacar/SCpubr "https://github.com/enblacar/SCpubr")

![](https://files.mdnice.com/user/38661/82eb0869-ba38-4e35-ab99-eb971ff3b153.png)
该R包旨在提供一种简化的方法，以“pub lication ready”格式（SCpubr）为已知的Single-Cell自动生成高质量的绘图。

## 资源
13、[通俗易懂的机器学习](https://mp.weixin.qq.com/s/Bj0QcBMHlUfqwwSkFEj42Q)

![](https://files.mdnice.com/user/38661/fe8c3f9b-b29c-43e8-90eb-2d99cc09f346.png)

对于了解机器学习，如果阅读网上关于机器学习的文章，你很可能会遇到两种情况：充斥各种定理的厚重学术三部曲，或是关于人工智能、数据科学魔法以及未来工作的天花乱坠的故事。这会对学习进程造成困难。本文作者希望通过本文对那些想了解机器学习的人做一个简单的介绍。不涉及高级原理，只用简单的语言来谈现实世界的问题和实际的解决方案。
- 链接(英文)：https://vas3k.com/blog/machine_learning/

14、[得意黑字体](https://github.com/atelier-anchor/smiley-sans)

![](https://files.mdnice.com/user/38661/bc39fae1-4f9e-4cd8-8950-20199dfbccf9.png)

得意黑是一款在人文观感和几何特征中寻找平衡的中文黑体。整体字身窄而斜，细节融入了取法手绘美术字的特殊造型。字体支持简体中文常用字（覆盖 GB/T 2312-1980 编码字符集）、拉丁字母、西里尔字母、希腊字母、日文假名、阿拉伯数字和各类标点符号。


## 历史上的本周

- 第32期：[有害的同义突变](https://mp.weixin.qq.com/s/C7ZX7wRPWIbeIXl_aV9xow)

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

![](https://files.mdnice.com/user/38661/17812364-5134-43ba-92cf-0be6aff405e8.png)


（完）

