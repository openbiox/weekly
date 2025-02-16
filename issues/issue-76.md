---
date: 2023-05-21
comments: true
---

# 生信爱好者周刊（第 76 期）：人生是一个长板问题

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/33257/5c108876-90c1-4d76-95fd-0007fcf20c8b.png)
被海浪扔回陆地的加菲猫（图源：BBC Future-Richard Fisher）

## 本周话题：[人生是一个长板问题](https://www.ruanyifeng.com/blog/2023/05/weekly-issue-254.html "人生是一个长板问题")
> 来自科技爱好者周刊的话题：除了著名的“水桶原理”-水桶的容量由最短的那块木板决定。“长板问题”也应该得到关注，它是指问题的关键不在于最弱点，而在于最强点。只要有一个点特别出色，这件事情就成功了，其他点的好坏无所谓。

@kkjtmac 这个问题可以用一个俗语概括：“一招鲜，吃遍天”，但是另外一个词可能更合适一点：“取长补短”。就像科技爱好者周刊的评论-“我们必须学会区分"短板问题"和"长板问题"，它们的解决方法完全不同。短板问题的解决，需要盯着薄弱环节，补齐最短的那块板；长板问题的解决，只需要推进最强的环节，不要在乎别的。”

## 生信研究
1、[Nature | 首个人类泛基因组草图公布](https://mp.weixin.qq.com/s/S8fHZt_0tcntFSPA3bpt1Q)

![](https://files.mdnice.com/user/33257/040ec083-186e-49e0-9ada-12c7264a9a16.png)

人类泛基因组参考联盟（Human Pangenome Reference Consortium）提出了首个人类泛基因组参考草图以及两个使用这一参考为基础进行新遗传学研究的发现。此次公布的泛基因组草图，源自47名祖先不同个体的阵列，为当下的参考人类基因组（GRCh38）添加了1.19亿碱基对和1115个基因重复（一个DNA区域里含有一个基因重复的变异）。

- 论文链接：https://www.nature.com/articles/s41586-023-05896-x

2、[PNAS | 同时检测同一DNA分子的遗传和表观遗传特征的新方法——MethylSaferSeqS](https://mp.weixin.qq.com/s/bPMddTAdam1MPiDlO-T-JQ)

![](https://files.mdnice.com/user/33257/71d2f580-78c1-4181-a2ce-0ec36998914c.png)

美国约翰霍普金斯大学医学院的研究团队报道了一种名为“MethylSaferSeqS”的方法。在样本量有限的情况下，该方法能够检测同一DNA模板分子中的遗传和表观遗传变化，且适用于不同大规模平行测序的标准文库制备。经验证，MethylSaferSeqS具有检测癌症患者和健康个体cfDNA中预期突变、甲基化和拷贝数变化的能力。

- 论文链接：https://doi.org/10.1073/pnas.2220704120

3、[Nature | 通用医学人工智能基础模型](https://mp.weixin.qq.com/s/hY94YeSbJKyK6fLmNXuoyA)

![](https://files.mdnice.com/user/33257/04ac870c-0391-4215-b42d-f55f4a9b06f7.png)

这是一篇由Eric J. Topol和 Pranav Rajpurkar研究团队发表的一篇关于医学人工智能的综述论文。文章介绍了GMAI (Generalist Medical Artificial Intelligence) 模型的概念和其在医疗保健中的应用。GMAI模型能够处理多种数据模态，并具有在执行任务时学习新内容的能力和利用领域知识的能力，这为医疗保健任务提供了无限的机会。GMAI的灵活性使得模型能够适应新的环境和应对新兴疾病和技术的变化，而无需经常重新训练。此外，GMAI应用程序将部署在传统的临床环境和远程设备上。但是，GMAI模型也存在独特的挑战，包括验证模型的准确性、收集和保护大规模的训练数据以及应对计算成本。面对快速发展的AI技术，这篇文章值得有志于投身医疗人工智能研究的科研人员深度阅读。

- 论文链接：https://www.nature.com/articles/s41586-023-05881-4

## 博文资讯

4、[你为什么找不到「完美」的键盘？macOS 的按键到底特殊在哪](https://mp.weixin.qq.com/s/21ebpdYQ-AO3DASmGjPPCA)

![](https://files.mdnice.com/user/33257/742397cd-ad50-4343-9e7a-f77165b2ee2a.png)

本文介绍了macOS 下的键盘发展历史，进而解释了苹果系统的按键的特殊性。


5、[Linux 系统性能监控工具](https://mp.weixin.qq.com/s/lyMtYPmevR6u7r31UoMWOA)

![](https://files.mdnice.com/user/33257/f7bf1688-6d75-4d76-80a2-0bf63976d7bc.png)

top命令是Linux系统自带的系统资源监视工具，除此还有简洁功能强大的类似工具htop、atop、vtop、btop++、Glances、nmon。该推文精简地介绍这些工具的特点和安装方法。

6、[重新认识中性粒细胞](https://mp.weixin.qq.com/s/mHWYZ8QHxwr8_2IAR7qXfw)

![](https://files.mdnice.com/user/33257/d2b224ba-aabf-47ad-b091-f2ac2e8b6643.png)

最近发现的许多“新”中性粒细胞( Neutrophils)功能令人兴奋不已。人们逐渐认识到中性粒细胞具有比抗菌反应更多的功能，并且在不同的组织和病理条件下具有不同表型，这表明中性粒细胞确实有未被刻画的异质性。然而，在大多数已发表的文章中，证据往往是间接的，我们需要可靠的实验证明所描述的细胞实际上是新的中性粒细胞亚群。

7、[单细胞测序在药物研发中有什么用？](https://mp.weixin.qq.com/s/msMJQf3CoFEdJPPdIwrmOA)

![](https://files.mdnice.com/user/33257/a9b1fb4d-1bda-43a2-ba86-8d8f6e748e06.png)

这篇文章探讨了单细胞RNA测序 (scRNA-seq) 技术在药物研发中的主要作用。为了理解单细胞技术是如何应用于药物研发流程，文章系统回顾了单细胞测序的基础，并基于此讨论了其他的一些单细胞技术，例如单细胞CRISPR 筛选技术，单细胞T细胞受体和B细胞受体测序技术。

- 论文链接：https://www.nature.com/articles/s41573-023-00688-4

## 工具

8、[RTutor.ai | 让AI帮你处理数据](https://github.com/gexijin/RTutor "RTutor.ai | 让AI帮你处理数据")

![](https://files.mdnice.com/user/33257/c555a9be-ba03-4f9b-be35-be4be67976bf.png)

RTutor 是一款基于 chatGPT的API的开发的工具，可以快速生成和测试 R 代码。RTutor 将自然语言翻译成 R 脚本，然后在 Shiny 平台内执行。你可以上传一个数据集，然后用英语提出问题或者请求分析，RTutor.ai会自动生成和测试R代码。需要chatGPT的API。

- 工具链接：https://github.com/gexijin/RTutor

9、[Word GPT Plus |  集成chatGPT 模型的 Word 插件](https://github.com/Kuingsmile/word-GPT-Plus/blob/master/README_cn.md "Word GPT Plus |  集成chatGPT 模型的 Word 插件")

![](https://files.mdnice.com/user/33257/8ec0ada7-dc96-45d2-97a8-8152cda26f26.png)

Word GPT Plus 是一个集成了 chatGPT 模型的 Word 插件。它允许你基于你在文档中写的内容生成文本。你可以使用它来翻译、总结、润色或者从零开始写一篇文章。

- 工具链接：https://github.com/Kuingsmile/word-GPT-Plus

10、[XClone |  单细胞克隆拷贝数变异推断](https://github.com/single-cell-genetics/XClone "XClone |  单细胞克隆拷贝数变异推断")

![](https://files.mdnice.com/user/33257/3a00dc2c-85e5-4e68-9172-0c919a2817f8.png)

XClone是基于Python开发的一种算法，可以从低覆盖度和稀疏的单细胞RNA测序数据（例如，由10x Genomics，Smart-seq等生成的数据）中推断细胞中的等位基因和单倍型特异性拷贝数。

- 工具链接：https://github.com/single-cell-genetics/XClone

## 资源

11、[MetaSRA ｜ SRA的标准化元数据](https://mp.weixin.qq.com/s/EOx6bojULKMBw1vBttlNCw)

![](https://files.mdnice.com/user/33257/5a764342-0636-44d4-b6e8-3f1741802d13.png)

MetaSRA 是一个规范化管理SRA人类特定样本元数据的数据库，受启发并遵循于ENCODE项目元数据管理的模式。该模式包括将样本映射到生物医学本体中的术语，用样本类型类别标记每个样本，并提取实值属性。我们通过一套新的pipeline实现了这些任务的计算自动化。

- 资源链接：https://metasra.biostat.wisc.edu/

12、[在R中搭建可重复的分析流程](https://raps-with-r.dev/ "在R中搭建可重复的分析流程")

![](https://files.mdnice.com/user/33257/27061fde-c944-41ce-9285-9bbc3c259986.png)

本书的目的是教你如何使用软件工程和DevOps中的一些最佳实践来使你的项目稳健、可靠和可重现。无论您是独自工作，在小团队还是大团队中工作都无关紧要。无论你的工作是否经过（同行）评审或审计并不重要：本书中介绍的技术将使您的项目更加可靠，并为您节省很多挫败感！

13、[使用R语言做临床统计分析在线书籍 ](https://mp.weixin.qq.com/s/bbM5hJpGnvwwOO5smkU08g)

![](https://files.mdnice.com/user/33257/ce885b2e-1649-4fc3-8a82-cdcc817b6931.png)

一本介绍如何使用R语言做临床统计分析的英文小册子，并有配套的视频教程。可以用来翻翻读读。

- 资源链接：https://bookdown.org/MathiasHarrer/Doing_Meta_Analysis_in_R/

## 历史上的本周

- 第35期：[生物信息行业的经济生态](https://mp.weixin.qq.com/s/WdRtpAKrQ15sAx_b-o_Wnw)

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

![](https://files.mdnice.com/user/33257/8e1e9214-22bc-447c-a64a-df8b9f374cee.png)

（完）
