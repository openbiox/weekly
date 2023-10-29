---
date: 2023-10-29
comments: true
---
# 生信爱好者周刊（第 97 期）：失败的读博经历：如何从跌倒中爬起来？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/33257/7ae5c7de-2a2c-4679-9c2b-70293498535e.png)
这幅来自SCIENCE杂志封面（VOLUME 381|ISSUE 6660|25 AUG 2023）的图像展示了完整的染色体，其中一些可能存在于癌症中的结构异常。

## 本周话题：[失败的读博经历：如何从跌倒中爬起来？](https://mp.weixin.qq.com/s/8Ya5WE-CvlyqhJ4Kw-xvVw)

@Geszvain 我想给大家做个榜样，让大家知道即使读研的一开始失败了，最后还是能取得成功。希望这能让大家的压力小一点，放松一些。

@Akazue 在脑中有一个清晰的目标，就更容易把目标转化成行动；很多事情将超出你的掌控范围，把精力集中在能掌控的事情上。

@Thakurela 失败不是结局：通往成功的道路上，挫败无处不在。中考分数不理想没有什么好大学可以选。本科毕业后，没通过医学院的入学考试，后来拿到了计算生物学的硕士学位，但找不到读博的机会。

@kkjtmac 用几个短语总结吧：放开心（接受失败）、换个角度（换个心情再继续or换个方向继续）

## 生信研究

1、[Nature Reviews Cancer | 癌症起源理论综述](https://mp.weixin.qq.com/s/EyJZwMZLQhAXID5bENu2IQ)

![](https://files.mdnice.com/user/33257/510ecca0-68bd-47e7-96f2-5b14dcdcd12a.png)

在本综述中，作者讨论了癌症起源的主要理论及其基础因素的相对重要性。

- 论文链接：https://www.nature.com/articles/s41568-023-00602-5

2、[Nucleic Acids Research | 端粒序列多样性综合数据库TeloBase，覆盖超9000个物种](https://mp.weixin.qq.com/s/BuzNUa0pg5hkR79fyd_f6A)

![](https://files.mdnice.com/user/33257/6627acbd-df9f-42af-8967-f3980bcc4ff2.png)

端粒是一种复杂的核蛋白结构，可以区分染色体的自然末端和DNA断裂，并保护基因组的编码区不因染色体末端的不完全复制而丢失。在哺乳动物和植物中，端粒酶的活性在发育过程中受到严格调控，并且仅限于具有高增殖能力的组织。TeloBase数据库包含9000多个物种的端粒序列，不仅提供交互式操作和数据可视化的图形，还允许基于用户的管理，避免了今后数据更新对管理员的过度依赖，以确保数据库更新的及时性。

- 论文链接：https://doi.org/10.1093/nar/gkad672

3、[Journal of Investigative Dermatology | 首个人类头皮发旋GWAS研究揭示多基因遗传效应](https://mp.weixin.qq.com/s/86KmbLkz4RVkXvYqqetG9g)

![](https://files.mdnice.com/user/33257/ead7642a-9ce3-424a-ac11-30c5eac6f40c.png)

中国科学院计算生物学重点实验室、中国科学院上海营养与健康研究所汪思佳团队通过对来自中国身体特征调查队列的2149名个体进行了发旋的全基因组关联研究（GWAS），并使用泰州纵向研究队列的1950名个体对GWAS结果进行验证，最终确定了四种相关的遗传变异（7p21.3、5q33.2、7q33和14q32.13），表明发旋方向受多个基因累积效应的影响，即存在多基因遗传。该研究发现，这些基因变异很可能通过调节毛囊的细胞极性来影响头发的生长方向，并可能对颅神经管的闭合和生长起作用。

- 论文链接：https://www.jidonline.org/article/S0022-202X(23)01995-4/fulltext

## 博文资讯
4、[使用snakemake管理转录组流程](https://mp.weixin.qq.com/s/lDDK_h-KgnybvZ1iCP5IGg)

![](https://files.mdnice.com/user/33257/ce786e96-22f4-45b4-a2bc-981c3998db24.png)

本文介绍利用 snakemake 进行转录组流程实现的实战演练，并介绍很多遇到的问题及应对技巧。

5、[ChIP-Seq带有spike-in的处理流程](https://mp.weixin.qq.com/s/taeE2kznwM4ldDQczNLvSA)

![](https://files.mdnice.com/user/33257/945f7fee-471b-4ca8-9417-2faa41f85409.png)

spike-in就是在提取的 DNA 或 RNA 样品中加入等量的非目标生物的基因组，但其 GC 含量与目标生物的 GC 含量类似。掺入spike-in的 DNA 片段的长度一般与文库构建前的 DNA 片段大致相同。spike-in应用很广泛，尤其是可能引起整个基因组大部分区域发生改变的实验，例如组蛋白修饰或者转录因子的敲减、激活等（人的H3K27me3建库样本中加入果蝇的基因组）。

6、[开发纳米孔测序很难吗？](https://mp.weixin.qq.com/s/Fo6nrr6WQvmfEPNJb1Ihpg)

![](https://files.mdnice.com/user/33257/b016f70c-890a-4f3f-913b-c4f801913e6c.png)

现如今，测序已经变成了一个老生常谈的话题，似乎也已经变成了一个成熟的不能成熟的技术。同样，ONT纳米孔测序在过去18年间的持续投资也在落地开花，我们也将逐渐享受到这一投资的便利，它至少启发了国内多家纳米孔测序公司的创立和创新发展。
很多事物，一旦多起来了，就会有人觉得“好像这个事情不难嘛”。经常会有人问，ONT的技术路线很难实现吗？
我们似乎容易犯的一个错误就是，以为脑子里想清楚了就都能做到，以为原理很简单那么实施就不会太难。
那么，开发ONT这种技术路线的纳米孔测序真的很难吗？本文可能会对你有所启发


7、 [Linux文件上下传小技巧-BaiduPCS-Go](https://mp.weixin.qq.com/s/HSJspAsODZfgtv3Ws2xjXw)

![](https://files.mdnice.com/user/33257/6308fa04-6e62-4ca9-8b44-a9516b117253.png)

BaiduPCS-Go是一款仿 Linux shell 文件处理命令的百度网盘命令行客户端，可进行Linux文件传输，本文从软件部署、登录以及使用方面对其进行了介绍。

## 工具
8、[DXMarkers| 多数据库批量检索，一键驾驭单细胞注释！](https://mp.weixin.qq.com/s/SDIqY6bSMOsPOakF1qhB4A)

![](https://files.mdnice.com/user/33257/0223ba39-a8de-4b2c-9156-3a5b88c8038f.png)

DXMarkers 是一款精心设计的 R 包，其目标是在单细胞测序(scRNA-seq)分析中手动注释细胞类型时 中提供更高效的工具来区分细胞类型。它利用在特定细胞类型中高表达的基因-也称为 Marker，可以在 CellMarker、CellMarker2.0 和 PanglaoDB这三个主流的 Cell Marker 数据库中进行高效的检索。除此之外，DXMarkers 提供了按物种和组织类型筛选搜索结果的功能，从而可以为用户提供更为精准的信息。

- 工具链接：https://gitee.com/DaXuanGarden/dxmarkers

9、[TOmicsVis | 一个all in on进行e转录组分析和可视化R包](https://github.com/benben-miao/TOmicsVis/ "TOmicsVis | 一个all in on进行e转录组分析和可视化R包")

![](https://files.mdnice.com/user/33257/c67be983-5649-433d-aeda-1d3feb04fec8.png)

TOmicsVis (Transcriptomics Visualization)专注于整合并提供给生物学科研者转录组学从样品性状统计到转录组学基因挖掘的完整可视化方案，递进地包含6大分类：①Samples Statistics -> ②Traits Analysis -> ③Differential Expression Analyais -> ④Advanced Analysis -> ⑤GO and KEGG Enrichment -> ⑥Tables Operations

- 工具链接：https://benben-miao.github.io/TOmicsVis/
- 中文介绍：https://mp.weixin.qq.com/s/g8sRcK_ExlsOFniMWEJnVQ

10、[1Panel | 开源Linux服务器运维管理面板](https://github.com/1Panel-dev/1Panel "1Panel | 开源Linux服务器运维管理面板")

![](https://files.mdnice.com/user/33257/3c4254f5-e48f-4f53-8641-111a3de1ae56.png)

1Panel 是一个现代化、开源的 Linux 服务器运维管理面板。1Panel 的功能和优势包括：
- 快速建站：深度集成 Wordpress 和 Halo，域名绑定、SSL 证书配置等一键搞定；
- 高效管理：通过 Web 端轻松管理 Linux 服务器，包括主机监控、文件管理、数据库管理、容器管理等；
- 安全可靠：基于容器来管理和部署应用，最小漏洞暴露面，提供防火墙和日志审计等功能；
- 一键备份：支持一键备份和恢复，备份数据到各类云端存储，永不丢失；
- 应用商店：精选各类高质量开源工具和应用软件，助力您轻松安装和升级。

- 工具链接：https://github.com/1Panel-dev/1Panel

11、[BPCells | 高性能单细胞转录组和ATAC-seq分析R包](https://bnprks.github.io/BPCells/index.html "BPCells | 高性能单细胞转录组和ATAC-seq分析R包")

![](https://files.mdnice.com/user/33257/6bf70741-d249-4399-818b-ae5ce6d9af29.png)

BPCells可以在大约10分钟内使用2GB的内存分析130万细胞的数据集，这使得在笔记本电脑上分析百万级别的数据集成为可能。另外BPCells支持与其他单细分析包（如Seurat）转换衔接。

- 工具链接：https://bnprks.github.io/BPCells/index.html

## 资源
12、[深度学习之强化学习100题](https://p100.koki-saitoh.com/zh-CN "深度学习之强化学习100题")

![](https://files.mdnice.com/user/33257/c2f1c130-82a7-4cab-b9fb-f5a65c12d63e.png)

13、[Docker-OSX | 在Docker中运行原生苹果系统](https://github.com/sickcodes/Docker-OSX "Docker-OSX | 在Docker中运行原生苹果系统")

![](https://files.mdnice.com/user/33257/5cd49d1f-bb00-47b1-8697-6a557f1c4231.png)

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

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）