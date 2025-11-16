---
date: 2025-11-16
comments: true
---
# 生信爱好者周刊（第 177 期）：单细胞基因表达数据是否会泄露个体基因型信息，从而带来隐私风险？

这里记录值得分享的生信相关内容，每半月发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

# 封面图

![](https://files.mdnice.com/user/146141/77d1a7ae-cc29-429c-aa45-9178d3a27a87.jpg)

# 本周话题：[单细胞基因表达数据是否会泄露个体基因型信息，从而带来隐私风险？](https://pubmed.ncbi.nlm.nih.gov/39362221/)

> 单细胞基因表达数据（如scRNA-seq数据）虽然噪声较高，但仍包含足够的基因型信息，使得通过eQTL关联预测基因型并跨数据集链接到个体成为可能，从而带来此前被低估的隐私泄露风险。
# 生信研究
1、[Science | 单细胞染色质开放性“提纯”肿瘤“调控程序”](https://mp.weixin.qq.com/s/k5b8gGhsevWFqnSsMwpPdw)

![](https://files.mdnice.com/user/146141/d82a21b6-279f-4f85-9115-91c38d5eab2e.png)

该研究利用TCGA样本构建了跨8种癌症、22.7万细胞核的单细胞染色质可及性图谱，区分出癌细胞与微环境细胞，并训练可解释深度学习模型，揭示癌症特异性调控语法、亚克隆差异及非编码突变对染色质可及性的功能性影响，为解析人类原发癌恶性表型的分子程序提供新资源。
- 论文链接：https://www.science.org/doi/10.1126/science.adk9217

2、[Bioinformatics | Pangene：李恒开发泛基因图谱构建工具——探索群体基因组时代研究新方向](https://mp.weixin.qq.com/s/x5YH5Ows8wlWgnybPXtFjQ)

![](https://files.mdnice.com/user/146141/bdb46f8b-b6e2-47cb-92f5-e62bb780e662.png)

该研究开发了全新工具 Pangene，它能够基于单倍型群体基因组学数据，一站式解析并可视化基因结构变异，把所有变异整合成一张“全景图”，精准呈现整个类群的遗传多样性。
- 论文链接：https://academic.oup.com/bioinformatics/article/40/7/btae456/7718494#476450906

3、[上科大团队带来“双子座”模型，AI筛选药物如何实现“集百家之长”? | 上海国际计算生物学创新大赛](https://mp.weixin.qq.com/s/LxRYqGvT3TpGKtgtcrFtKg)

![](https://files.mdnice.com/user/146141/18f480f7-a76c-4d94-a648-746e479d835a.png)

上科大GeminiMol团队凭“双子座”AI模型在上海国际计算生物学创新大赛夺冠，该模型首次大规模整合小分子动态构象空间与对比学习，1小时筛完1800万化合物，可集多活性分子之长生成新结构，在难啃的NMDA受体赛道验证普适性，为AI药物设计提供新思路。
- 论文链接：https://advanced.onlinelibrary.wiley.com/doi/full/10.1002/advs.202403998

# 博文咨询
4、[50年的前沿研究：Nucleic Acids Research(NAR)](https://academic.oup.com/nar/pages/50th-anniversary-of-nar)

![](https://files.mdnice.com/user/146141/aee5ed8e-0430-47dc-ad7c-1a43bd21d666.png)


1974年，伯明翰大学的 Richard T. Walker、A. Stanley Jones 与耶鲁大学的 Dieter Söll 三位远见编辑创办 *Nucleic Acids Research*，旨在打破学科壁垒、汇聚核酸及相关领域的研究成果；半个世纪后，NAR 已成长为生命科学顶级期刊，持续引领并见证学科创新。

5、[Cell Genomics | 基因组学数据处理云平台](https://mp.weixin.qq.com/s/WZYtWhLCWDSvvY1lWOpyCA)

![](https://files.mdnice.com/user/146141/cd58ba90-6af5-48a5-8b02-02f6c50bedb9.png)

AnVIL是NHGRI打造的联合云平台，通过 Terra、Galaxy 等组件把 PB 级基因组数据、分析工具与弹性算力集中在同一安全空间，让研究者无需搬运数据即可在线协作完成人口规模分析，从而颠覆传统共享模式，加速科学发现。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/35199087/

6、[骰子图（DicePlot）](https://mp.weixin.qq.com/s/864TsclDXPfDU1Aa23d9QA)

![](https://files.mdnice.com/user/146141/9ebd9a77-bdec-41b2-9553-588589f833c3.png)

diceplot包允许为包含两个以上分类变量和额外连续变量的数据集创建可视化图表（骰子图）。该工具对于探索复杂的分类数据及其与连续变量之间的关系特别有用。

- https://cran.r-project.org/package=diceplot
- https://github.com/maflot/Diceplot

# 工具
7、[PanDepth | 用于快速有效的基因组覆盖率计算工具](https://mp.weixin.qq.com/s/bfqQWCjcW7yIsAGWk_fpKw)

![](https://files.mdnice.com/user/146141/4f86b2d2-ef33-47cb-a505-375fab03a371.png)

支持排序或未排序的 BAM 和 CRAM 格式对齐文件，并接受 GTF、GFF 和 BED 格式或特定窗口大小的配置文件。

- https://github.com/HuiyangYu/PanDepth

8、[citadel](https://github.com/every-day-things/citadel "citadel")

![](https://files.mdnice.com/user/146141/de8efa3c-6cc7-444d-82ff-a7189b8cb01b.png)

一个可以轻松实现管理电子书库的工具。

9、[AI Image Editor](https://aiimageeditor.me/ "AI Image Editor")

![](https://files.mdnice.com/user/146141/a37e0f77-6110-424d-ba96-9f5ddcbf20ef.png)

一款利用AI技术提高图片质量的软件。

# 资源
10、[Humanity's Last Exam](https://agi.safe.ai/ "Humanity's Last Exam")

![](https://files.mdnice.com/user/146141/94fb8d82-920b-45e7-9e49-4b2d40c8f2dc.png)

Humanity’s Last Exam 由全球 50 国、500 余家机构的近千名专家联合打造，汇集 2500 道横跨百门学科的高阶难题，对主流大语言模型进行闭卷测试，为评估通用智能进展提供全新硬核基准。

11、[build-your-own-x](https://github.com/codecrafters-io/build-your-own-x "ild-your-own-x")

![](https://files.mdnice.com/user/146141/ca65165d-7f0a-4b24-968a-c321183eb529.png)

# 贡献者（GitHub ID）
「Openbiox 生信周刊」运维小队：
- @ShixiangWang（王诗翔）
- @kkjtmac（阚科佳）
- @NiEntropy（赵启祥）
- @He-Kai-fly（何凯）
- @JnanZhang（张佳楠）
- @Tomcxf（陈啸枫）
- @wangdepin（王德品）
- @kongjianyang（空间阳）
- @donghongyu2020（董弘禹）
- @DrRobinLuo（罗鹏）
- @Wangcy-rachel（王春阳）
- @zoe3251（舒晨阳）
- @yanbin85 （严彬）
- @MadDERt（王章宇）

# 订阅
这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://files.mdnice.com/user/146141/3e7099c5-ec08-41c5-8f41-34d0d58bbd71.png)
（完）

