---
date: 2023-08-20
comments: true
---

# 生信爱好者周刊（第 89 期）：

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/33257/7d0615a4-7015-4db2-a7e5-da30245b45bd.png)

[生物信息学的 11 大机器学习用例](https://www.mdpi.com/1422-0067/22/6/2903 "生物信息学的 11 大机器学习用例")

## 本周话题：[视频学习胜过读书吗？](https://www.ruanyifeng.com/blog/2021/07/weekly-issue-166.html "视频学习胜过读书吗？")


![](https://files.mdnice.com/user/33257/827e643f-738c-4c93-b75b-f8f89157eb66.png)


@kktjmac 在短视频盛行的年代，通过视频学习新知识、入门新领域越来越普遍。视频学习从一定程度上可以缩短学习周期，更直观地理解复杂的概念和过程，但是读书提供更深入的理论和概念解释，以及更广泛的视角和观点，同时在读书的过程中可以锻炼自己的独立思考能力和阅读理解能力。因此将两种学习方式结合使用，以达到更全面的效果。

## 生信研究
1、[Nature | 1000多种肿瘤的转录异质性特征](https://mp.weixin.qq.com/s/JPu8e4x7KYTGBS5tjdibxQ)

![](https://files.mdnice.com/user/33257/f6551578-927a-4787-a2bc-22ae40e427b3.png)

近期发表在Nature上面的一篇文章，通过scRNA-seq分析的1000多个肿瘤，对肿瘤内转录异质性（intratumour heterogeneity）进行了系统的泛癌症特征分析。研究人员在恶性细胞中确定了41个共识转录异质性元程序（meta-programs）。每个元程序由数十个基因组成，这些基因在许多肿瘤中的细胞亚群中协调上调。文章还将这些元程序分析扩展到六种常见非恶性细胞类型上,以描绘肿瘤微环境中的细胞互动。这项泛癌症研究系统地定义和注释了肿瘤内转录异质性特征，为未来探索新的治疗策略提供了框架。

- 论文链接：https://www.nature.com/articles/s41586-023-06130-4

2、[Protein & Cell | 基于R语言的微生物组数据挖掘的最佳流程](https://mp.weixin.qq.com/s/EAJpBOUjNrlHAjbpPW394w)


![](https://files.mdnice.com/user/33257/28be4764-d049-4e62-8997-d0d124a03914.png)

随着测序技术的逐步成熟，许多生物信息相关微生物组软件相继发表。然而，数以万计的R包和无数类似的分析工具给许多研究人员挖掘微生物组数据带来了重大挑战。如何从众多的R包中选择合适、高效、方便、易学的工具已经成为许多微生物组研究人员面临的问题。作者整理了324个用于微生物组分析的常用R包，并根据应用类别对其进行分类，以帮助研究人员快速找到用于微生物组分析的相关R包。此外，又对微生物组分析的集成R包进行了系统的分类，并总结了它们的优点和局限性，以帮助研究人员选择合适的工具。最后，对用于微生物组分析的R包进行了全面的回顾，总结了微生物组中大多数常见的分析内容，以构建最适合微生物组分析的流程。

- 论文链接：https://doi.org/10.1093/procel/pwad024

3、[Nature Biotechnology | BioCypher 推动生物医学知识表征大一统](https://mp.weixin.qq.com/s/bHRDtrLV2URNBFaoBdTgLA)

![](https://files.mdnice.com/user/33257/8375764b-b538-47e5-9951-a008bfc66a60.png)

标准化的生物医学知识表征是一项难以克服的任务，它阻碍了许多计算方法的有效性。为了促进知识表征的协调和互操作性，该工作将知识图谱创建的框架标准化。本文提出的BioCypher实现了这一标准化，这是一个FAIR（可查找、可访问、可互操作、可重用）框架，可以透明地构建生物医学知识图谱，同时保留源数据的来源。将知识映射到生物医学本体有助于平衡协调、人类和机器可读性以及对非专业研究人员的易用性和可访问性的需求。本文展示了该框架在各种用例中的有用性，从维护特定于任务的知识存储，到生物医学领域之间的互操作性，再到为联邦学习按需构建特定于任务的知识图。

- 论文链接：https://doi.org/10.1038/s41587-023-01848-y

## 博文资讯

4、 [Nature带来基因研究新风向：人工智能系统预测基因修改的后果](https://mp.weixin.qq.com/s/Goir7Dk9DsiGGAEVuim89w)

![](https://files.mdnice.com/user/33257/ede71151-586d-4a7a-9e0e-79239ab6ee85.png)

大型语言模型（Large language models），也被称为基础模型，是一种人工智能系统，它从大量的通用数据中学习基础知识，然后应用这些知识来完成新的任务——这个过程被称为迁移学习 (Transfer Learning)。随着ChatGPT的发布，这些系统最近获得了主流的关注，ChatGPT是一个基于OpenAI模型构建的聊天机器人。
在发表在《Nature》杂志上的这项新研究中，Christina Theodoris博士开发了一个理解基因相互作用的基础模型。这个新模型被称为Geneformer，它从大量人体组织的基因相互作用数据中学习，并将这些知识用于预测疾病中可能出现的问题。
Theodoris团队使用Geneformer来阐明心脏细胞在心脏病中是如何出错的。此外，这种方法也可以治疗许多其他细胞类型和疾病。

5、[区分肿瘤细胞的单细胞CNV分析原理](https://mp.weixin.qq.com/s/Gpt_haoyOB9G3LRPrCtxCQ)

![](https://files.mdnice.com/user/33257/206429f4-a04d-474e-a3e7-1511f7cd882f.png)

本文介绍 3 种单细胞拷贝数变异分析软件，cna、inferCNV、copyKAT，它们的分析原理各有不同，其中cna方法是基迪奥参照最初的单细胞CNV分析相关的文献方法自写的脚本，inferCNV是继最初的cna算法发展而来的，copyKAT是一个全新开发的适用于细胞通量高和基因表达稀疏的软件算法。

6、[DNA甲基化的时间和地点](https://mp.weixin.qq.com/s/CpCOlKjvq79pJ9KQU6nlVQ)

![](https://files.mdnice.com/user/33257/883ce2f7-7ef1-410c-8d08-716dfe35aa3e.png)

这篇文章阐述了DNA甲基化主要发生位点和机制,并指出组蛋白修饰在指导DNA甲基化模式形成中的重要作用。一些要点：

- DNA甲基化主要发生在基因组CpG位点,如启动子、增强子和基因体上。
- DNA甲基化由DNA甲基转移酶DNMTs负责,其中DNMT1负责维持甲基化,DNMT3A和DNMT3B负责新一轮甲基化。
- 组蛋白修饰如H3K4me3可以阻止启动子区域的甲基化,H3K36me3可以招募DNMT3B实现基因体区域的甲基化。
- 最新研究发现NSD1通过H3K36me2修饰实现基因间区和非CpG位点的甲基化。
- 组蛋白修饰可以指导DNA特定区域的甲基化模式,但是否始终如此及DNA甲基化是否也可以反过来影响组蛋白修饰尚不明确。

7、[肿瘤药临床试验IIa期与IIb期区别](https://mp.weixin.qq.com/s/P8Qt_1sPod2xG7ui8lxvmA#)

![](https://files.mdnice.com/user/33257/063f43eb-2e1b-4ae1-bb8b-44f6c87db2fc.png)

这篇文章悉数了肿瘤药临床试验II期中的IIa期和IIb期，其二者的目的和设计有明确区别。IIa期的目的是初步证明药物的临床疗效和生物活性,也称概念证明研究。采样受试者较少,给药剂量接近MTD,疗效终点重在生物学指标。IIb期的目的是寻找临床效果最大并且安全性最佳的剂量,也称剂量发现研究。采样受试者数量更大,给药剂量设多个剂量组,疗效终点重在临床指标。

## 工具
8、[rPanglaoDB | 获取PanglaoDB单细胞转录组数据的R包](https://mp.weixin.qq.com/s/yeMxhToGlNhjNL4JXraf3A)

![](https://files.mdnice.com/user/33257/4d4570db-3313-4f6c-b5b5-3f55843fe5d1.png)

PanglaoDB数据库，这是2019年发布的一个单细胞转录组数据库，收集了人和小鼠的单细胞数据，目前共计包含来自1300+例样本、250+种组织的550万+细胞数据，另外还有6000多个marker基因可以用来做细胞注释。现在作者团队开发了对于的R包可以在R中完成单细胞的注释工作。

- 论文链接：https://academic.oup.com/bioinformatics/article/38/2/580/6329823
- 工具链接：https://github.com/dosorio/rPanglaoDB/

9、[Pandora | 顺畅访问ChatGPT的工具](https://github.com/pengzhile/pandora "Pandora | 顺畅访问ChatGPT的工具")

![](https://files.mdnice.com/user/33257/3a19f101-1a6b-456b-b18a-2895207efff8.png)

- 工具链接：https://github.com/pengzhile/pandora

10、[pinyin |将汉字转换为拼音的R包](https://github.com/pzhaonet/pinyin "pinyin |将汉字转换为拼音的R包")

![](https://files.mdnice.com/user/33257/e746359b-2205-4851-b868-dba87e8616b0.png)

- 工具链接：https://github.com/pzhaonet/pinyin

11、[logomakerr | AI辅助设计个性化logo的在线工具](https://logomakerr.ai/ "logomakerr | AI辅助设计个性化logo的在线工具")

![](https://files.mdnice.com/user/33257/79ce7c87-0ede-4a51-897b-f4576d51e647.png)
logomakerr是一个AI辅助的logo设计工具，通过输入logo的名称、应用领域、风格就可以快速多个定制化的logo。

- 工具链接：https://logomakerr.ai/

## 资源

12、[2023年Single Cell Genomics Day From Satija Lab](https://mp.weixin.qq.com/s/kTwqqEYs0nsJ3YaCywaxvg)

![](https://files.mdnice.com/user/33257/ca9fce0f-5906-4bba-b686-dac9f17de313.png)

做过单细胞分析的人没有谁不知道Seurat，其开发者Satija是单细胞分析领域的领航者之一。Satija实验室每年都会举办Single Cell Genomics Day活动，本资源提供了2023年度活动的相关内容。

- 资源链接：https://satijalab.org/

13、[生物信息入门Linux命令行的教程](https://github.com/telatin/learn_bash "生物信息入门Linux命令行的教程")

![](https://files.mdnice.com/user/33257/c7c7b9be-4716-4744-a36a-6c0fc0501f5c.png)

- 资源链接：https://github.com/telatin/learn_bash/wiki

## 历史上的本周

- 第27期：[真与假的界限在哪里](https://mp.weixin.qq.com/s/izptp-_1CQ7_8nEwMMFMqQ)

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
