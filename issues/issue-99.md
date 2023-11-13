---
date: 2023-11-12
comments:true
---

# 生信爱好者周刊（第 99 期）：发论文还是生孩子，女性在学术界会遭遇什么？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly )），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions )

## 封面图

![](https://files.mdnice.com/user/38661/70de0682-e20c-484e-bb67-41ae4869020a.png)

图片来源：https://demo-zh.photoprism.app/library/browse#&gid=1&pid=12

## 本周话题：[发论文还是生孩子，女性在学术界会遭遇什么？](https://mp.weixin.qq.com/s/ulk_d3blVxCMq4OFRSKXDQ)

> 我们经常看到，一些优秀的女性学者突出重围，成功实现事业发展，这些女性固然值得敬佩，但并不能让我们得到一个结论：这些成功经历意味着女性学者没有面临障碍（包括性别歧视障碍）。《妈妈教授》介绍了在美国学术背景下，女性学者在实现“工作和家庭平衡”面临的困境，同时，作为“前辈”，突出重围的女性学者们也提供了诸多指南给后辈女性，减少她们的弯路。

`@ShixiangWang`：关于人的事情，很多不存在明显的概念边界。女性权益不应该只有政策资源的倾斜，也应有文化的关怀和尊重。

## 生信研究
1、[Nature子刊：EarlyDx联合多家高校开发经济高效癌筛方法，解决cfDNA甲基化检测痛点](https://mp.weixin.qq.com/s/0oFRXOW-CT7TUxIlXvzJPg)


![](https://files.mdnice.com/user/38661/15437b93-a46d-4e49-9bd0-6ccf540dbb99.png)


发表在《nature communication》上的一篇文章，主要介绍了由EarlyDiagnostics、加州大学洛杉矶分校和南加州大学等团队联合开发的一种集成了实验和计算的系统，解决了cfDNA在低样本量情况下癌症早筛中的一些痛点问题。

- 论文链接：https://www.nature.com/articles/s41467-022-32995-6


2、[Nature｜大规模基因组分析绘制全面的癌症rRE图谱](https://mp.weixin.qq.com/s/zDkEMgErl9_EYm3c9tlRGw)

![](https://files.mdnice.com/user/38661/36780442-1a57-45a2-b9fa-2a41c96953ce.png)

研究团队在横跨29种癌症类型的2622个癌症基因组中确定了TR扩增，并在7种癌症类型中发现了160个反复出现的rREs，包括许多位于已知调控元件中或附近的rREs，其中大部分（155/160）是癌症亚型特异性的。研究结果表明，rRE可能是人类癌症遗传变异的一个重要的未开发资源，该研究则提供了一个全面的rRE图谱，以供研究人员进行更加深入的探索。

- 论文链接：https://www.nature.com/articles/s41586-022-05515-1

3、[Genome Biol | 多种测序技术分析癌症参考细胞系中的结构变异，构建高置信度共识调用集](https://mp.weixin.qq.com/s/LkXcVSOD43tKBk0BKHw4Ug)


![](https://files.mdnice.com/user/38661/647d04da-dd7a-43e9-a5e7-5c3be992cb48.png)

近日，美国弗雷德里克国家癌症研究实验室、洛马琳达大学基因组学研究中心等机构的研究人员合作，通过多种NGS平台系统地研究了参考癌症细胞系中的体细胞SV，并将其与相匹配的正常细胞系进行比较，建立了一个包含1,788个SV的共识调用集，为提高癌症基因组SV检测的敏感性和准确性提供了参考。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02816-6


## 博文资讯
4、[Method of the Year 2022](https://mp.weixin.qq.com/s/NqKX2kx_tf0I-6un44FAAA)


![](https://files.mdnice.com/user/38661/64e21abc-87c6-4200-ba09-bbc1d795f399.png)


迟到的一篇文章，将PacBio和Oxford Nanopore公司的长读测序技术确定为2022年Method of the Year，以及介绍了长读测序技术在完整基因组测序和组装等方面的重要进展与应用。


5、[R tips：R包安装之二三事](https://mp.weixin.qq.com/s/JeeYXeW920377A5_3we17g)

R使用过程中，必然需要安装各种R包来辅助分析，但是R包安装失败是一个比较麻烦的事情，本文介绍了个人安装R包遇到的报错及如何解决。

6、[遗传学与基因组学原理 | 遗传方式及多因素遗传](https://mp.weixin.qq.com/s/pRbV9ZnP2WvVOWFoA_tDTQ)


![](https://files.mdnice.com/user/38661/ca3d97d8-ca14-4e05-8280-a2f389665b7c.png)

该文详细介绍了遗传方式及相关术语，遗传因素、环境因素、外显性 三者之间的关系和多因素疾病/性状的 易患性 (Liability) 分布。


## 工具
7、 [https://github.com/astral-sh/ruff](https://github.com/astral-sh/ruff)


![](https://files.mdnice.com/user/38661/458baac0-be54-4c45-a283-d261545f87f6.png)

ruff是一个用 Rust 编写的，非常快的 Python linter 和代码格式化程序。


8、[rmt.rs ｜ 安全的rm](https://github.com/AmineZouitine/rmt.rs)

![](https://files.mdnice.com/user/38661/2f83d4e3-fda7-4970-a856-43c6bf35f335.png)

Rmt类似于rm命令，但它允许我们将删除的元素保存在垃圾桶中。如果你愿意，你可以使用交互式命令行恢复你之前选择的删除的元素（或永久删除它们）。

9、[Replit: Build software collaboratively with the power of AI](https://replit.com/ )


![](https://files.mdnice.com/user/38661/4222bc53-e230-4849-be52-fb4d07279149.png)


Replit是一个可以直接在线编码、部署和协作开发的软件开发平台，旨在帮助开发者快速实现项目想法。

## 资源
10、 [https://github.com/kevinblighe/E-MTAB-6141](https://github.com/kevinblighe/E-MTAB-6141)


![](https://files.mdnice.com/user/38661/6e9e9a9e-3d00-44b3-b87a-0de3f02b0e2c.png)
本文为关于ComplexHeatmap的一个简易教程。


11、 [infercnv ](https://github.com/broadinstitute/infercnv )


![](https://files.mdnice.com/user/38661/3600b131-6b59-4140-8685-65ee81facbc8.png)


InferCNV 是 TrinityCTAT 工具包的一个组成部分，专注于利用 RNA-Seq 的使用来更好地了解癌症转录组。其用于探索肿瘤单细胞 RNA-Seq 数据，以确定体细胞大规模染色体拷贝数改变的证据。



12、[14种癌症模型优缺点](https://mp.weixin.qq.com/s/KsAdIufbeyqVHMICN3AVSg)

![](https://files.mdnice.com/user/38661/f218996a-c6ef-4076-93bf-0177e5f30785.png)


医药研究，尤其是药物临床前研究需要选择合适模型。但是，所有模型都不完美，又有其特定优势。根据优缺点和研究目的，选择合适的模型至关重要。

## 历史上的本周
- 第59期：[AlphaCode 编程大赛卷趴一半程序员](https://mp.weixin.qq.com/s/N4dpmhE_hwlITUhhgAl7fw)

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

