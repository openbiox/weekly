---
date: 2024-05-12
comments: true
---

# 生信爱好者周刊（第 122 期）：他山之石——开启个性化医疗的基因组探索

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://files.mdnice.com/user/4331/a0dac534-719b-4afc-a442-d4c177a05630.png)


[via](https://www.personalgenomes.org.uk/)

## 本周话题：他山之石——开启个性化医疗的基因组探索

![](https://files.mdnice.com/user/4331/c9550711-4f73-4d62-9046-2a7eba76620d.png)

Genomics England是一家领先的基因组研究组织，致力于在英国推动个性化医疗的发展，Genomics England的使命是通过对参与者的基因组进行广泛测序和分析，为研究人员、临床医生和患者提供有关基因与健康之间关系的宝贵信息。2012年时任英国首相卡梅伦在伦敦奥运会上宣布“100,000基因组计划”启动，2013年7月5日Genomics England正式成立，该组织通过实施“100,000基因组计划”，计划测序和研究英国境内10万名患者的基因组数据，2018年12月就已达到了这一目标。通过推动基因组研究和应用，Genomics England成为了个性化医疗的先驱者，为医学科学和患者健康带来了革命性的变革，他们的工作不仅在英国范围内产生了深远影响，还为全球医学界提供了宝贵的经验和启示。

- `@ShixiangWang`：这类项目是真正的他山之石。在落后十余年的情况下，目前国家层面还没有出现这种标志性的项目，我想原因有很多。我以前在想，国家的经济强盛，在这类国外项目中贡献和受益的华人学者不少，有很多相关的才俊都回国发展了，预期很快有相关的进展。但现在想来，顶层的设计、长期的布局、协作的意识、资源的分配、商业的运作、绩效的认可和科研项目的体制都面临着需要重重突破的困难。

## 生信研究


1、[Science｜首个果蝇全生命周期单细胞图谱，揭示衰老相关机制与特征](https://mp.weixin.qq.com/s/mu8STUgFHZLyN7m2kJTTgQ)


![](https://files.mdnice.com/user/4331/ec02e479-529f-49aa-be24-7c3f316a623e.png)


研究人员使用单细胞RNA测序技术，对果蝇整个生命周期内163种细胞类型的基因表达变化进行了全面分析，建立了迄今为止最完整的果蝇衰老单细胞图谱(Aging Fly Cell Atlas)。该图谱揭示了不同细胞类型在衰老过程中基因表达和组成的动态变化规律，确立了预测生物学年龄的"衰老时钟"模型，为深入理解衰老这一重要生物学过程提供了关键资源。考虑到果蝇与人类在衰老方面的相似性，这一成果有望为延缓衰老、防治老年相关疾病带来新的思路和策略。

- 论文链接：https://www.science.org/doi/10.1126/science.adg0934

2、[Nature Genetics | 更精准的预测异常剪接助力罕见病诊断](https://mp.weixin.qq.com/s/0pz5OTSIK1AY5rRumMZgDg)

![](https://files.mdnice.com/user/4331/86d24e8a-e883-4d5c-9de4-098d40c1d88b.png)

本研究报告了一种新的机器学习模型AbSplice，可以更精准地预测罕见DNA变异导致的RNA异常剪接。研究人员整合了DNA序列特征和RNA-seq数据，开发了两个版本的AbSplice模型：基于DNA的AbSplice-DNA将预测精确度提高了3倍，而整合RNA数据的AbSplice-RNA则将精确度提高了6倍。这些模型能够通过易获取组织如血液、皮肤的RNA剪接模式，来预测难以取样组织如心脏、大脑中的异常剪接。AbSplice模型有望加速罕见遗传病的分子诊断，为患者提供更精准的遗传学解释。该研究为开发新的基因组学分析工具、挖掘疾病新的遗传机制提供了新思路。

- 论文链接：https://doi.org/10.1038/s41588-023-01373-3

3、[Genome Biology | 跨模态最优传输方法CMOT，可准确预测单细胞的多模态特征](https://mp.weixin.qq.com/s/qYbFAWQg3GN9IdXYSCUBeQ)


![](https://files.mdnice.com/user/4331/67f8e070-35a1-44bb-a1c5-7e3df813cefe.png)

本研究提出了跨模态最优传输（CMOT）方法，这是一种基于最优传输（OT）来推断单细胞缺失模式的计算方法，它将可用的多模态数据（源数据）中的细胞比对到一个共同的潜在空间，并推断另一模态（目标数据）中细胞的缺失模态，此推断并不需要成对的源数据多模态数据来进行比对。研究发现，在脑发育、癌症及免疫学等各种应用中，CMOT比现有方法更优秀，并提供改进细胞分类或癌症分类的生物学解释。

- CMOT开源网站：https://github.com/daifengwanglab/CMOT
- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-02989-8

4、[Nat Methods | 新泛基因组研究工具包PGR-TK，可在多种尺度上分析重复/临床相关复杂基因变异](https://mp.weixin.qq.com/s/teCZZzc-bh01tQJ3mV6ALQ)


![](https://files.mdnice.com/user/4331/3eea2f38-018d-4919-8465-e21d9490b243.png)


研究团队开发了“PanGenome Research Tool Kit（PGR-TK）”软件包，可在多种尺度上分析复杂的泛基因组结构和单倍型变异。通过将PGR-TK中的图分解方法应用于二型主要组织相容性复合体（MHC-II）中，证明了人类泛基因组对分析复杂基因区域的重要性。综上，PGR-TK能够解析和可视化人类基因组中最复杂的区域。

- 论文链接：https://www.nature.com/articles/s41592-023-01914-y


## 博文资讯


5、[2024美国国家科学院院士名单揭晓，鲍哲南等9位华人学者当选](https://mp.weixin.qq.com/s/_z-PHDaV74t5rXd69w8jxg)

美国国家科学院（National Academy of Sciences, NAS）是美国科学界最高水平的四大学术机构(美国国家科学院、美国国家工程院、美国国家医学院、美国国家自然基金会)之一。自 1863 年成立以来，NAS 每年增选新院士，以表彰他们在科技和工程方面取得的杰出成就。该奖项被视为美国学术界最高荣誉之一，目前，NAS 共有约 2,400 名院士和 500 名外籍会员，其中约 190 名获得过诺贝尔奖。近期，NAS 公布了新一届院士名单，此次评选新增共计 120 名院士及 24 名外籍院士。其中，当选的华裔科学家有鲍哲南（斯坦福大学），金芳蓉（加州大学圣地亚哥分校）、冯国平（麻省理工学院），付强（华盛顿大学），侯一钊（加州理工学院），Liu Chen-yu（伊利诺伊大学厄巴纳-香槟分校），施扬（牛津大学），孙太平（杜克大学）。王贻芳（中国科学院高能物理研究所）当选为美国科学院外籍院士。

6、[Cancer Cell | 肿瘤突变负荷检测亦有不同：算法过滤种系差异的临床有效性探讨](https://mp.weixin.qq.com/s/oFes0NmBKSjnAL1wvgcz3A)


![](https://files.mdnice.com/user/4331/0c3cdf7e-71ce-41ea-97a1-b418da233871.png)


在Cancer Cell 2022年10月的一期中，Nassar等人从血统差异的视角研究了肿瘤突变负荷与接受免疫检查点抑制剂治疗的患者的预后之间的关系。他们使用名为Oncopanel的下一代测序（NGS）技术研究患者的遗传血统，发现肺癌患者基于TMB的临床结果存在差异，并将其归因于“TMB膨胀 (TMB inflation) ”和需要“重新审视纯粹肿瘤样本的TMB计算”。但是他们也承认他们分析的结果“可能受到小样本大小的限制”。2023年4月13日，来自剑桥大学的研究人员在Cancer Cell上发表了题目为Not all TMB assays are the same: Clinical validity of robust algorithmic germline filtering的文章，作者提出算法种系过滤可用于准确计算纯肿瘤样本中的TMB-H，而无需进行单独的种系测序。这种方法保持了不同血统的临床有效性，可用于选择肿瘤变异进行个性化ctDNA监测和分子残留疾病检测。作者还强调了在不同基因组分析的复杂生物标志物计算中保持一致性的重要性。

- 论文链接：https://www.cell.com/cancer-cell/fulltext/S1535-6108(23)00090-9

7、[UML活动图大白话入门教程](https://mp.weixin.qq.com/s/NJ391VbEPIrRZCJnOYrtFQ)

![](https://files.mdnice.com/user/4331/76791123-3b76-4c98-b0e9-914cc03e9dd7.png)

本文介绍了UML活动图的基本概念和不同应用场景下的示例，并推荐了PDDON这个在线画图工具。

8、[Segment Anything](https://zhuanlan.zhihu.com/p/619815666?utm_campaign=shareopn&utm_medium=social&utm_oi=555487086006820864&utm_psn=1627307040568672256&utm_source=wechat_session&wechatShare=1&s_r=0)

Meta 在论文中发布的新模型名叫 Segment Anything Model (SAM)，可能是 CV 领域的 GPT3 时刻 。他们在博客中介绍说，「SAM 已经学会了关于物体的一般概念，并且它可以为任何图像或视频中的任何物体生成 mask，甚至包括在训练过程中没有遇到过的物体和图像类型。SAM 足够通用，可以涵盖广泛的用例，并且可以在新的图像『领域』上即开即用，无需额外的训练。」在深度学习领域，这种能力通常被称为零样本迁移，这也是 GPT-4 震惊世人的一大原因。

- 论文地址：https://arxiv.org/abs/2304.02643
- 项目地址：https://github.com/facebookresearch/segment-anything
- Demo 地址：https://segment-anything.com/

9、[Creating a blog with Quarto in 10 steps](https://beamilz.com/posts/2022-06-05-creating-a-blog-with-quarto/en/)


![](https://files.mdnice.com/user/4331/dc048cef-c872-4346-9cef-505b04070216.png)


这篇英文博客详细地介绍了如何使用 quarto 来创建个人博客站点。

10、[英国版“中国行动计划”将1100名中国年轻学者和研究生“拒之门外”](https://mp.weixin.qq.com/s/B7X8jpeiqxfA9KC9TjfNpg)


![](https://files.mdnice.com/user/4331/288c7e79-3aac-4203-b1ba-1b544e50b5ca.png)

留学近年来广泛受到政治因素的影响。2018年，美国发起“中国行动计划”，不断对华人科学家、学者进行莫须有的指控。紧随其后，英国政府也在效仿美国，不断减少与中国学者的科研合作，2022年，逾千名中国科学家和研究生被英国外交部拒之门外。英国一顶尖学者表示，“该计划使英国学府难以从国外招聘到最优秀的人才”。

## 工具

11、[vg ｜ 处理基因组变异结构图](https://github.com/vgteam/vg)


![](https://files.mdnice.com/user/4331/0654e73f-8fd7-488b-98a1-7f15537cf504.png)


12、[speedtest-cli | 在终端测网速](https://www.speedtest.net/apps/cli)


![](https://files.mdnice.com/user/4331/9bd1b0cd-f599-48f0-bdf5-ee64dcaa6f99.png)


13、[rproject-template](https://github.com/EricSDavis/rproject-template)

这是一个使用 `docker` 和 `GNU Make` 创建可复现 R 项目的模板。文件夹结构是主观的，旨在保持你的项目组织和可复现性。

14、[gridea | 在几分钟内建造你的数字花园](https://gridea.dev/)


![](https://files.mdnice.com/user/4331/267d636b-52a0-400d-9c89-69fe4c2d7ea7.png)


## 资源

15、[awesome-quarto](https://github.com/mcanouil/awesome-quarto)


![](https://files.mdnice.com/user/4331/e9b559ce-f713-4578-acba-4a0b30fcf1ac.png)

一个精选的Quarto演讲、工具、示例和文章列表！欢迎贡献！

16、[Globe Explorer ｜ 革命性的信息发现之旅](https://mp.weixin.qq.com/s/XMYTnddjwAk9uiPumG0FOw)


![](https://files.mdnice.com/user/4331/0a3525e2-7564-453b-b721-0e0cc8561560.png)


Globe Explorer是一个创新的AI驱动的搜索引擎和知识探索平台，为用户提供了一种全新的搜索体验。通过简单输入感兴趣的主题，Globe Explorer就能利用尖端人工智能技术智能分析搜索请求，在网络上探索并呈现最相关的信息来源。与传统的搜索引擎不同，Globe Explorer将搜索结果以类似维基百科的结构化、可视化方式呈现，利用思维导图等方式帮助用户轻松探索知识的广度和深度。它整合了文章、研究报告、视频等多元形式的内容，全方位满足用户的知识需求。同时，Globe Explorer还鼓励用户参与协作式知识构建，用户可以为主题页面贡献自己的见解、添加注释和评论，并与社区分享自己的发现，促进集体智慧的生成。通过Globe Explorer，用户可以节省大量筛选信息的时间，快速高效地连接到可靠且相关的知识来源。总之，Globe Explorer开创性地融合了传统搜索引擎、维基百科和Perplexity AI等工具的优势，代表了知识搜索和探索领域的一大进步。

- Website: https://explorer.globe.engineer/

17、[百图生科推出生命科学AI评测榜“Life Science Leaderboard”](https://mp.weixin.qq.com/s/LZbnsn8wg8_r8idlNP01aA)


![](https://files.mdnice.com/user/4331/883d16b1-5469-4da2-98b3-ed003774a556.png)

百图生科发布"Life Science Leaderboard"（http://www.biomap.com/sota/）评测榜单，该榜单覆盖了6个方向26个最具代表性和前沿性的任务。

## 历史上的本周

- 生信周刊第 81 期：[好人情结](https://mp.weixin.qq.com/s/l0jX4wbJjeD4kAHkeREYOA)

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

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

