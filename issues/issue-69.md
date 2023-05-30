---
date: 2023-04-17
comments: true
---

# 生信爱好者周刊（第 69 期）：如何引导年轻科研工作者？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图


![](https://files.mdnice.com/user/34023/be08aa52-02b3-4b25-add5-b2941c277169.png)

图片来源：Dave Cutler (artist)

## 本周话题：

[如何引导年轻科研工作者？](https://www.pnas.org/doi/epdf/10.1073/pnas.1704511114)

> CharlesDavid Allis作为一名资深科学家在培养和支持年轻科研工作者方面的经验和建议：
>
> -  鼓励年轻科学家追求他们的激情和好奇心，并帮助他们克服在出版和筹资方面的挑战和挫折。
> -  教导青年科学家如何撰写清晰严谨的论文和资助提案，以及如何通过口头报告有效地交流他们的发现。
> -  通过鼓励青年科学家参加研讨会、讲习班、座谈会、会议等，让他们接触不同的观点和想法，并对他们的工作给予反馈。
> -  支持青年科学家制定自己的研究议程和愿景，并在适当时候给予他们自主权和独立性。

`@NiEntropy` - 这篇文章还让我感受到了作者对年轻科研工作者的关心和尊重，他不仅给出了很多有用的建议，还鼓励我们追求自己感兴趣和有价值的领域。指导年轻科研工作者对我来说还有些遥远，举一反三，将这些建议应用在培养子女身上：1. 引导子女进行反思，让他们能够认识自己的优势和劣势，发现问题并寻求改进。同时，也要尊重子女的个性和选择，不要强加自己的意志或期望。2. 给予子女积极支持和鼓励，让他们感受到父母的关心和信任。在他们遇到困难或挫折时，给予他们安慰和帮助。在他们取得成就或进步时，给予他们赞扬和肯定。3. 除了教授基本的知识和技能外，还应该培养子女的上网、玩游戏等方面的能力，以便他们能够有效地表达自己的想法，与他人交流和合作。

## 生信研究

1、[Nature  |  p53缺失诱导癌症基因组发生可预见的变化](https://mp.weixin.qq.com/s/8LKa6JFMyPb4Bxd77lB3Nw)


![](https://files.mdnice.com/user/34023/3b56f1af-f3ca-479b-9fb5-466ae70f22dc.png)

近日，纪念斯隆·凯特琳癌症研究中心（MSKCC）Scott W. Lowe团队，在国际顶级期刊《自然》上发表有关TP53突变与癌症发展之间关系的研究。
研究人员发现，当细胞缺失p53后，在引起基因混乱的同时，会诱导一种可预测、有序且确定的癌症基因组进化。这一突破性发现无疑为癌症治疗提供了新的思路。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/35978189/

2、[US-align | 蛋白质、核酸及其复合物通用结构比对算法](https://mp.weixin.qq.com/s/YoJ63PhH-E32LgqKyJqC0g)


![](https://files.mdnice.com/user/34023/55ad9341-9e53-44c9-8e0b-9487121af4b2.png)

2022年8月29日，密西根大学张阳课题组在《自然-方法》上发表了题为“US-align: universal structure alignments of proteins, nucleic acids, and macromolecular complexes”的研究工作。在该项工作中，他们发布了第一款通用的结构比对软件US-align，基于统一的打分函数（TM-score）和比对算法，实现了蛋白质、RNA、DNA单体与复合物的两两比对和多重比对等重要功能。测试结果表明，其在准确性和速度上都超越旧版的MM-align。

- 论文链接：https://www.nature.com/articles/s41592-022-01585-1
- github：https://github.com/pylelab/USalign

3、[Cancer research | 基于51种人类癌症类型、6万个肿瘤绘制RAS基因突变图谱](https://mp.weixin.qq.com/s/gghfRNbXXD5vkiDMLVi39Q)

![](https://files.mdnice.com/user/34023/28532310-adf1-46cf-9b63-48e96f28d484.png)


为了更好地了解体细胞RAS突变的患病率和RAS突变肿瘤中共突变的基因概要，美国约翰霍普金斯大学医学院、范德比尔特大学医学中心以及纪念斯隆凯特琳癌症中心等机构的研究团队分析了美国癌症研究协会（AACR）项目GENIE中涉及51种癌症类型的66,372个肿瘤607,863个突变的靶向NGS序列数据，估计了RAS和非RAS体细胞突变癌症特异性患病率，揭示了肿瘤突变负荷和突变特征对共突变模式的影响。该研究结果突出了RAS基因组的多样性，为开发有效的组织特异性靶向治疗策略提供了信息。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/36074020/

4、[Nucleic Acids Research | 细胞分类库Cell Taxonomy](https://mp.weixin.qq.com/s/8Hb_s345Ov7Rj3W8IQHu7A)


![](https://files.mdnice.com/user/34023/67ede9b8-0c28-4408-94ae-4a2f9bfb29d4.png)


中国科学院北京基因组研究所（国家生物信息中心）国家基因组科学数据中心搭建的细胞分类库Cell Taxonomy基于4299篇文献审编、15个相关数据资源整合和单细胞测序数据分析（约350万个细胞），最终收录了3143种细胞类型和26613个细胞标志物（cell marker），涵盖34个物种、387种组织和257种生理/病理状态。同时Cell Taxonomy中的在线工具Cell Type Predictor和Cell Type Comparator可以协助用户进行细胞注释和细胞类型比较。

- 论文链接：https://academic.oup.com/nar/article/51/D1/D853/6717827
- 数据库链接：https://ngdc.cncb.ac.cn/celltaxonomy/


5、[上海交大瑞金医院携手华大等机构发布首个中国人群血液病毒组图谱](https://mp.weixin.qq.com/s/ibn5FzGqsmxob_OlAcog0A)

![](https://files.mdnice.com/user/34023/0f1822b3-2b95-499b-b114-af318cd1f61e.png)


上海交通大学医学院附属瑞金医院、上海交通大学转化医学研究院联合华大对来自中国代谢解析计划（ChinaMAP）的10585人全基因组测序数据中的非人源基因序列进行了深入分析，构建了首个中国人群血液病毒组学图谱，分析了14种病毒的人群携带率、病毒丰度和地理分布，为疾病预防与流行病学研究提供了参考。相关研究成果近日发表于Cell Discovery期刊。

- 文章链接：https://www.nature.com/articles/s41421-022-00476-1

## 博文资讯

6、[肿瘤代谢全景介绍](https://mp.weixin.qq.com/s/aQEPGQ3NABts-od6X8a4tw)

![](https://files.mdnice.com/user/34023/836a45d5-3427-4623-9ad2-a53ce59ed89e.png)


与肿瘤相关的代谢变化不仅维持肿瘤细胞本身的异常增殖，更迫使TME内的基质细胞、甚至整个机体的代谢平衡都发生重塑，共同促进了癌细胞的积聚和扩散，降低了免疫系统抵抗的抵抗能力，并直接升高癌症相关的致死率。通过解析肿瘤所依赖的代谢适应特征，有助于指导发现新的治疗甚至饮食干预方法，可能与现有的治疗措施（如化疗、靶向抑制剂和免疫检查点阻断）协同作用。

7、[trancriptVis 的左膀右臂: bedVis 和 trackVis](https://mp.weixin.qq.com/s/M7iMdi43vcgrINDoympUdA)


![](https://files.mdnice.com/user/34023/9fa24a9e-58a4-4d9d-bcd9-7332b372ca56.png)


本文通过具体实例介绍了如何使用transPlotR包中的trancriptVis对peak和bigwig文件进行可视化。

- R包链接：https://github.com/junjunlab/transPlotR

8.[因果判断的统计方法](https://mp.weixin.qq.com/s/RtCNOJAxCjn1tpLqZ4lFwQ)

![](https://files.mdnice.com/user/34023/6b76e9b3-2a67-4484-a364-618dd17f2277.png)

探求事物之间的因果关系是哲学、自然科学和社会科学等众多研究所追求的终极目标。本文介绍了（1）因果推断的潜在结果模型，因果作用的可识别性，和随机化试验；（2）观察性研究和混杂因素，以及混杂因素完全观测时的因果推断方法；（3）存在未观测的混杂因素时因果作用的估计方法；（4）替代指标悖论和确定替代指标的准则；（5）因果网络模型和结构学习的算法。最后，作者展望了因果推断在现代大数据研究中的前景。



9、[从爆火的chatGPT讲起: 自然语言生成式AI的前世今生](https://mp.weixin.qq.com/s/I3x-fddZmasKGPwgxilYyw)

![](https://files.mdnice.com/user/34023/8d83b784-afca-4a5f-a96e-2d9199b4ec8b.png)

这篇文章借由最近爆火的chatGPT，系统回顾了生成式人工智能的前世今生。对于想探究chatGPT背后发展历史的人来说值得一读。

## 工具

10、[archivist  |   一个用于数据集和绘图归档的工具集](https://github.com/pbiecek/archivist)

![](https://files.mdnice.com/user/34023/53945a53-4cc1-4441-a757-a50589e6f631.png)

archivist包可以用来存储R语言中对象的副本以及它们的元数据。它有助于管理和重新创建带有数据分析的结果。

- R包链接：https://github.com/pbiecek/archivist

11、[survex包 | 在生存分析中应用可解释的机器学习](https://github.com/ModelOriented/survex)


![](https://user-images.githubusercontent.com/45822462/225641247-06770a71-cf86-4681-84f6-cbc0281aed81.png#id=wJBOA&originHeight=1545&originWidth=2000&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)


survex包为解释生存模型提供了易于应用的方法，包括复杂的黑箱和较简单的统计模型。

- 工具链接：https://github.com/ModelOriented/survex

12、[unikn  |  调色盘+文本设计](https://github.com/hneth/unikn)

![](https://files.mdnice.com/user/34023/e2acacaf-2070-4c8a-8aca-d0d3ea9e9db2.png)

unikn包可以用来定义和使用企业设计元素，如颜色和样式文本。它有助于创建一致和识别的可视化效果。

- 工具链接：https://github.com/hneth/unikn

13、[AUCell | 基因集评分工具 ](https://www.bioconductor.org/packages/devel/bioc/vignettes/AUCell/inst/doc/AUCell.html#gene-sets)

![](https://files.mdnice.com/user/34023/8a691964-450e-4e10-83b6-008167792950.png)

本教程介绍了如何使用AUCell识别具有活跃 “基因集” 的细胞 (即基因签名) 在单细胞rna-seq数据中。AUCell使用 “曲线下面积” (AUC) 来计算输入基因集的关键子集是否富集在每个细胞的表达基因内。AUC评分在所有细胞中的分布允许探索标记的相对表达。由于评分方法是基于排序的，因此AUCell独立于基因表达单位和归一化程序。此外，由于单元是单独评估的，它可以很容易地应用于更大的数据集，如果需要，可以对表达式矩阵进行子集化。

- 教程链接：https://www.bioconductor.org/packages/devel/bioc/vignettes/AUCell/inst/doc/AUCell.html#gene-sets

## 资源

14、[CSAMA  |  基因组数据科学中的统计和计算](https://bioconductor.org/help/course-materials/2022/CSAMA/)

![](https://files.mdnice.com/user/34023/f3a6388a-a2fc-441d-8c31-80f13cc42044.png)

由bioconductor主办的基因组数据科学统计和数据分析课程，共5天。这个课程涵盖了 RNA-Seq、单细胞转录组学、质谱学、机器学习、可视化、人类细胞图谱等主题，并且课程的所有教材都可以在 GitHub 上免费获取和使用。

- 课程链接：https://bioconductor.org/help/course-materials/2022/CSAMA/
- github：https://github.com/Bioconductor/CSAMA

15、[RCrashCourse_Book | 生物学家的R速成](https://github.com/ColauttiLab/RCrashCourse_Book)

![](https://files.mdnice.com/user/34023/ba815b7e-04b1-40b0-a308-103e4f2f0787.png)

这本书是关于 R 语言的教程书籍，它讲了以下内容：
基本概念和操作：向量、数据框、函数、类、方法等。
基本和高级图形功能： qplot () 和 ggplot () 函数，以及如何自定义和优化图形效果。
正则表达式功能：如何使用通配符、特殊字符、方括号等进行文本匹配和提取。
数据科学功能：如何使用 tidyverse 包进行数据整理、转换、连接和重塑，以及如何处理缺失值和日期格式。
高级功能：如何使用 R Markdown 进行可重复性研究，以及如何编写自定义函数和软件包。

- 书籍获取：https://github.com/ColauttiLab/RCrashCourse_Book

## 历史上的本周

第 29 期：[Hiplot开发库开源](https://mp.weixin.qq.com/s/x-tZ6XnAgWz5HN6AeZScwg)

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
