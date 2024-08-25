---
date: 2024-08-25
comments: true
---
这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/5208/c383cb3d-1baa-4489-9a1d-bf23ca810611.png)

## 本周话题：[我为什么离开学术界？](https://mp.weixin.qq.com/s/aAXBcI5XhE8XJilowcdU5A)

> 关于“离开学术界”的报道似乎越来越多，诚然部分人群一开始就准备进入业界，但也有许多人始于对科研的热爱，但最终还是选择了离开。他们或是因为日趋饱和的就业市场，或是被环环相扣的体制所困，或是出于对科研和自我更深刻和清醒的认知。本文主人公属于后者，从十岁到三十岁，从对成为生物学家的笃信到对自己不适合做科研的冷静分析，她在这期间经历的自我怀疑和痛苦挣扎想必能引起很多朋友的共鸣。而她对自我价值和科学审美的独到思考，希望也能为仍在科研道路上前进的朋友们带来一些启发。



## 生信研究

1、 [BioRxiv|首个跨物种生命基础大模型+新型细胞命运预测AI模型发布](https://www.jiqizhixin.com/articles/2023-9-29 "BioRxiv|首个跨物种生命基础大模型+新型细胞命运预测AI模型发布")

![](https://files.mdnice.com/user/5208/db7b4149-9454-4add-bf34-402fcf216c8c.png)
>近日，由中国科学院多学科交叉研究团队组成的“指南针联盟”（Xcompass Consortium）在人工智能赋能生命科学研究方面取得了重要突破，成功构建了世界首个跨物种生命基础大模型——GeneCompass。 该模型集成了人和小鼠超过1.26亿个单细胞的转录组数据、融合了包括启动子序列和基因共表达关系等四种先验知识、基础模型参数量达到1.3亿，实现了对基因表达调控规律的全景式学习理解，同时支持细胞状态变化预测及多种生命过程的精准分析，展示了人工智能赋能生命科学研究的巨大潜力。
- 文章链接：https://www.biorxiv.org/content/10.1101/2023.09.26.559542v1



2、[Genomics Proteomics & Bioinformatics|北京基因组所（国家生物信息中心）合作发布开放生物医学影像存档库OBIA](https://mp.weixin.qq.com/s/eXtwLVD3kdBSfIp3thmotQ)

![](https://files.mdnice.com/user/5208/a6e3b630-a0d1-4364-ac92-c752740f596a.png)
> OBIA是一个集中存储、去识别的生物医学影像归档库。OBIA使用五个数据对象（Collection、Individual、Study、Series和Image）组织图像数据，与BioProject和GSA-Human无缝集成，有助于整合图像和基因组数据，以支持多组学分析。为保障影像数据中隐私信息的安全，OBIA制定了统一的去识别和质量控制流程，并设置了开放访问和受控访问两种不同类型的数据访问策略。此外，OBIA提供了友好直观的网络界面，用户可以很方便的实现对数据的提交，浏览，检索，申请和下载。
- 文章链接：https://pubmed.ncbi.nlm.nih.gov/37806555/




3、[Nature Biotechnology | 新空间组学方法同步实现转录组和代谢组的空间多模态精确分析](https://mp.weixin.qq.com/s/Mv8VT3Ucux0kn07KbItArQ)


![](https://files.mdnice.com/user/5208/5f292180-5235-4a10-beea-2f442c498022.png)

> 近日，来自瑞典乌普萨拉大学与瑞典皇家理工学院的联合研究团队通过引入空间多模态分析（SMA）方案，提出了一种结合组织学、质谱成像和空间转录组学的空间组学方法，以促进跨组织区域mRNA转录物和低分子量代谢物的精确检测，且该工作流程与Visium玻片兼容。研究团队证明了在单个组织切片中结合SRT和MALDI-MSI并保留两种模式的特异性和敏感性的可能性，并在多巴胺和帕金森病条件下的小鼠和人类大脑样本中证明了该方法的潜力。
Nature Biotechnology上这篇由瑞典乌普萨拉大学和瑞典皇家理工学院的研究团队开发的空间组学方法，通过空间多模态分析（SMA）结合组织学、质谱成像和空间转录组学，实现了在单个组织切片中同步进行转录组和代谢组的精确检测。该技术在多巴胺和帕金森病研究中显示出潜力，为空间生物学提供了新的研究工具，有助于深入理解疾病机理和发现新的生物标志物。

- 文章链接：https//doi.org/10.1038/s41587-023-01937-y


4、[Cell.Syst.|一种端到端的自动化机器学习工具，用于解释和设计生物序列 ](https://mp.weixin.qq.com/s/M54lFQRty1VrzcJTo4JBLQ)


![](https://files.mdnice.com/user/5208/c07f9b1a-b427-43d2-933d-98f0ec65483a.png)

> 自动化机器学习（AutoML）算法可以解决将ML应用于生命科学时面临的许多挑战。然而，由于这些算法通常不明确处理生物序列（如核苷酸、氨基酸或糖肽序列），且不容易与其他AutoML算法进行比较，它们在系统和合成生物学研究中很少被使用。在这里，作者介绍了BioAutoMATED，这是一个用于生物序列分析的AutoML平台，将多个AutoML方法集成到一个统一的框架中。用户可以自动获得分析、解释和设计生物序列的相关技术。BioAutoMATED可以预测基因调控、肽-药物相互作用和糖肽注释，并设计优化的合成生物学组件，揭示突出的序列特征。通过自动化序列建模，BioAutoMATED使生命科学家更容易将ML应用到他们的工作中。
- 文章链接：https://pubmed.ncbi.nlm.nih.gov/37348466/



## 博文资讯

5、[执行系统指令：小如麻雀的函数](https://mp.weixin.qq.com/s/8h7hPXsrwDjzVoC4Qfv58A)

![](https://files.mdnice.com/user/5208/56f81c21-057c-44d2-9fff-b99eed46f31d.png)
> 本文 Y 叔介绍了 yulab.utils 包中的一个系统命令调用函数 exec()，它可能比 R 默认提供的更为方便。



6、[不同年龄阶段科研人员的归属感](https://mp.weixin.qq.com/s/9dV3ki4u7q48LQ18q7MQcw)

![](https://files.mdnice.com/user/5208/d1d064a0-f032-4601-9d51-ea327c931ab1.png)

> 本文探讨了不同年龄阶段科研人员的归属感问题，指出博士毕业生在面临职业选择时的困境，如直接获得正式教职的难度、科研任务的压力，以及在高校环境中竞争与和谐的挑战。同时还讨论了新教工如何融入基层组织、参与公共事务、处理人际关系，以及如何在科研和教学中找到平衡。此外本文也提到了年轻人和资深教授之间因利益竞争可能出现的矛盾，以及如何通过有效沟通和相互尊重来解决这些问题，强调了归属感、认同感和勇于担当的重要性。


7、[博文资讯|全球首台生物计算机开放服务](https://mp.weixin.qq.com/s/9dV3ki4u7q48LQ18q7MQcw)

![](https://files.mdnice.com/user/5208/184d3d88-2331-481f-b4f3-fc15cc874fad.png)

>  近日，一家瑞士初创公司 FinalSpark 发布了全球首款生物处理器。据介绍，它们都是由人脑类器官的生物神经元驱动的，而且已开放了远程访问。




## 工具
8、[edibble包将实验的基本组件映射到面向对象的系统](https://github.com/emitanaka/edibble "edibble包将实验的基本组件映射到面向对象的系统")

![](https://files.mdnice.com/user/5208/8e28aeec-4536-4f49-ae60-3f8a71989c04.png)

> edibble R 软件包与构建实验设计的其他软件包有很大不同，它侧重于整个过程，较少关注随机化过程,感兴趣可以参照[Cookbook章节](https://emitanaka.org/edibble-book/cookbook.html "Cookbook章节")。




9、[segment-model-spy | 用于GATK CNV分析的交互式可视化工具](https://github.com/genome-spy/segment-model-spy?tab=readme-ov-file "segment-model-spy | 用于GATK CNV分析的交互式可视化工具")


![](https://files.mdnice.com/user/5208/af39247d-fefb-46a9-8002-dfe6dfb172b2.png)
> SegmentModel Spy 是GATK拷贝数分割结果的交互式可视化工具。




10、[Hmsic包进行数据描述性统计分析](https://github.com/harrelfe/Hmisc?tab=readme-ov-file "Hmsic包进行数据描述性统计分析")

![](https://files.mdnice.com/user/5208/c1a12a06-67c4-430f-9962-684259e73e40.png)


使用说明可看[参考手册](https://hbiostat.org/R/Hmisc/summaryFuns.pdf "参考手册")



11、[Minimap2 | 序列比对工具](https://github.com/lh3/minimap2 "Minimap2 | 序列比对工具")


![](https://files.mdnice.com/user/5208/6dfa12fe-6aba-4433-96cd-efab5c6a3496.png)

> Minimap2是一个由Heng Li开发的通用序列比对程序，用于映射DNA或长mRNA序列与大型参考数据库。它适用于处理不同长度和错误率的序列，包括短至100bp的准确序列、长达1kb的基因组序列、完整长度的噪声Direct RNA或cDNA序列，以及数百兆碱基长度的组装片段或密切相关的完整染色体。Minimap2采用分步比对过程，包括最小化种子的索引、基于动态规划的链式比对、优化的链式评分算法和过滤策略，以提高比对的准确性和效率。它在速度上是主流短读比对器的3-4倍，并且比长读基因组或cDNA比对器快约30倍。Minimap2在不同类型的输入序列上表现出高准确性，并且具有高灵活性和适用性。

- 工具链接：https://github.com/lh3/minimap2

## 资源
12、[2023生信10大突破](https://cbirt.net/top-10-bioinformatics-breakthroughs-of-2023/ "2023生信10大突破")

![](https://files.mdnice.com/user/5208/0b3356af-0f17-447e-8f20-1184683fa4b7.png)
- CRACKING THE CODE OF MYSTERIOUS “Y” CHROMOSOME
- UK BIOBANK’S GENETIC TREASURES
- SOLVING THE 50-YEAR BLOOD GROUP ENIGMA
- AI TOOLS DECODE GENES AND PROTEINS
- ILLUMINATING THE BRAIN’S INNER WORKINGS
- AI ASSISTS DESIGN OF NEW ANTIBIOTICS
- LARGE LANGUAGE MODELS INTERPRET BIOLOGY’S COMPLEX CODE
- AI-POWERED TESTS REVOLUTIONIZING DIAGNOSTICS
- BIOINFORMATICS REVOLUTIONIZES CANCER RESEARCH
- TRACING THE PATTERNS OF LIFE’S EVOLUTION

13、[国家生物信息中心Education板块提供免费资料学习库](https://ngdc.cncb.ac.cn/education/ "国家生物信息中心Education板块提供免费资料学习库")

![](https://files.mdnice.com/user/5208/2ab0bc2d-f31d-4905-aea6-0e14a9449623.png)

> Education 提供一系列教育材料，包括课程、教程和培训文档，这些材料是公开且免费的，仅供学术使用。



14、[Lenxinyminutes旋风式学习新的编程语言](https://learnxinyminutes.com/ "Lenxinyminutes旋风式学习新的编程语言")

![](https://files.mdnice.com/user/5208/e12bca78-1a59-477d-9ccb-22aef6b19f80.png)




## 历史上的本周
- 第97期：[失败的读博经历-如何从跌倒中爬起来？](https://mp.weixin.qq.com/s/ZT9dj8ior5CMQlm_PJWIlQ)


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

