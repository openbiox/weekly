---
date: 2023-04-11
comments: true
---

# 生信爱好者周刊（第 63 期）：停止寻找的最佳时间

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions)

## 封面图

![](https://files.mdnice.com/user/33257/7633d193-406e-419e-8aed-d3a62d794fba.png)
来源：Katie-Marie Case

这些人类鼻腔细胞覆盖着纤毛——抓住并清理鼻腔异物的细小毛发。在研究COVID-19为何对某些年龄阶段的影响较大时，博士生Katie-Marie Case注意到这些星系般的鼻细胞螺旋只出现在老年患者身上。

## 本周话题：[停止寻找的最佳时间](https://www.ruanyifeng.com/blog/2023/01/weekly-issue-238.html)

> 日常生活有很多"寻找-决策过程"，如果考察所有选项，要花费很长时间，可能还会错失机会，后面遇到的未必有前面的好。能否确定一个时间点，到了某个阶段就停下来，不再寻找了，这时找到合适候选人的概率最大？

`@《最佳停止时间》` "37%法则"的意思就是，寻找阶段进行到37%就要停止。日常生活中，只要符合"寻找-决策过程"的场景，都可以适用37%法则。

`@kkjtmac` 之前也遇到过类似的决策犹豫不决的时候，没有一个标准进行最终的决定，准备后续遇到相似的情况实行"37%法则"！

`@ShixiangWang` 这个策略在成本有限时可以获取比较优秀的结果，但在道德上可能涉及到对参与者不公平的待遇。

## 生信研究

1、[Nature Medicine观点文章 | 人类细胞图谱对医学的影响](https://mp.weixin.qq.com/s/kCnQmlXZVo0X8lkqJ_Am6Q)

![](https://files.mdnice.com/user/33257/c4cfcaf6-42b9-412c-a4aa-e9edfb6c150e.png)

剑桥大学团队联合Genentech公司团队在Nature Medicine上发表观点文章“Impact of the Human Cell Atlas on medicine”，展望了细胞图谱影响医学未来的潜力，并描述了过去十年中，该领域研究进展如何在常见复杂疾病、传染病（包括COVID-19）、罕见疾病和癌症中实现这一潜力。

- 论文链接：https://www.nature.com/articles/s41591-022-02104-7

2、[Cancer Research ｜ 解码癌症遗传祖先的新算法，可从癌症衍生分子数据进行遗传血统推断](https://mp.weixin.qq.com/s/wxNhs6XO6SnMSJUCa_3X-w)

![](https://files.mdnice.com/user/33257/0fb0f97d-b4b5-4efd-b7ca-5a99d8c3b43e.png)

该研究团队开发了一种从癌症衍生的分子数据中进行准确、稳健地祖先推断的计算方法。该方法将一种基于PCA的祖先推断技术与使用合成数据进行推断参数优化的方法相结合，有助于遗传血统导向的癌症研究。研究团队还从已知背景的癌症和不相关无癌基因组中创建样本图谱，并利用已知血统的胰腺癌、卵巢癌、乳腺癌和血癌样本验证了该算法的性能，结果显示该算法准确率超95%。

- 论文链接：https://aacrjournals.org/cancerres/article/83/1/49/711844/Genetic-Ancestry-Inference-from-Cancer-Derived

3、[Genome Biology | 多模态和单细胞/亚细胞水平空间组学技术的现状及发展前景](https://mp.weixin.qq.com/s/QedVyW8fZYQNdIutyA2QEg)

![](https://files.mdnice.com/user/33257/b30b30a5-7461-412c-b166-daa9b050e2a9.png)

空间组学技术能够帮助人们更深入地了解细胞组织和目标组织内的相互作用。这些技术方法可以识别组织中具有差异转录物或蛋白质丰度的特定区段或区域，描述其相互作用，并补充定义细胞表型的其他方法。与传统的单细胞测序方法相比，高分辨率空间组学数据包含原生组织构象的成对空间信息，允许发现新的细胞类型、细胞相互作用和组织结构。美国威尔康奈尔医学院的研究团队回顾了从单细胞到亚细胞分辨率的空间组学技术和分析工具的现状及前景，为科研研究和临床应用提供了一个全面、详尽的综合分析。

- 论文链接：https://doi.org/10.1186/s13059-022-02824-6

## 博文资讯

4、 [把OpenAI接入微信](https://mp.weixin.qq.com/s/IKKgQ5pxYvUyYp4plMHAZQ)

![](https://files.mdnice.com/user/33257/bfb7866f-327b-4d8c-8370-a8b952795763.png)

作者详细介绍了将OpenAI接入微信的流程，感兴趣的可以尝试一下。

5、[帕博利珠单抗、纳武利尤单抗……一文讲清肿瘤科常用单抗](https://mp.weixin.qq.com/s/QjRooEH2NCsMpuEzzv6pGw)

![](https://files.mdnice.com/user/33257/d2617432-de86-4c04-a88f-47f371a2e0ce.png)

随着抗肿瘤靶向治疗药物和免疫治疗药物的发展，单克隆抗体成为肿瘤临床治疗十分常见的药物之一。本文就单克隆抗体的概念、分类、命名和输液反应等方面进行阐述说明。

6、[2023年最值得关注的AI制药公司TOP10](https://mp.weixin.qq.com/s/vAtarUZoOyQUNvJWEsvuKA)

![](https://files.mdnice.com/user/33257/09ebf9ea-5537-42ef-b830-7a01458ff564.png)

随着人工智能（AI）和机器学习（ML）的不断发展，药物开发过程中的一些问题得到了有效解决。2022年，全球多家AI制药公司经历了融资、合作、交易等重要事件，本文结合医药魔方PharmaInvest数据库专有的评分系统，筛选了10家在2022年取得较大进展的AI制药公司，也是2023年该领域值得关注的10家公司，就其融资、交易和合作等情况进行简要介绍。

## 工具

7、[scCATCH - 单细胞自动注释工具](https://github.com/ZJUFanLab/scCATCH)

![](https://files.mdnice.com/user/33257/b35fef4c-a876-4c9c-b070-d40a2dfa4502.png)

- 工具教程：https://cran.r-project.org/web/packages/scCATCH/vignettes/tutorial.html

8、[paperneed - 文献搜索工具](https://www.paperneed.cn/articles/search)

![](https://files.mdnice.com/user/33257/9c593d82-bc15-478f-9bc8-c2e427dea8ae.png)

paperneed是一款在线文献搜索引擎，可以根据文献名或期刊名进行查找。

- 工具链接：https://www.paperneed.cn/articles/search

9、[scGSVA - 单细胞GSVA基因集变异分析工具](https://github.com/guokai8/scGSVA)

![](https://files.mdnice.com/user/33257/3283699c-f4b9-411c-b1c2-5dad8b8be267.png)

scGSVA包提供了对单细胞数据进行GSVA分析的wrap函数。scGSVA包含为几乎所有物种构建注释的函数。scGSVA还提供了基于GSVA结果生成图形的功能。scGSVA提供了生成注释数据的函数，这些注释数据可用于分析。

- 工具链接:https://github.com/guokai8/scGSVA

10、[AutoClass - 单细胞数据清洗、降噪工具](https://github.com/datapplab/AutoClass)

![](https://files.mdnice.com/user/33257/b03829b9-b9df-4476-abf4-34ecd8efd5b5.png)

AutoClass是一款用于scRNA-Seq数据清理和去噪的深度学习工具。AutoClass 集成了两个深度神经网络组件：一个自动编码器和一个分类器，以最大限度地提高噪声消除效率和信号保留程度。

- 工具链接：https://github.com/datapplab/AutoClass

## 资源

11、[Coding Club R Course配套资料纯链接版](https://mp.weixin.qq.com/s/hMvCNs_s6VcSMAQivGsK4g)

![](https://files.mdnice.com/user/33257/8fa56ce1-2ce6-48cb-a868-93e3dc03e686.png)

英国R课9次课程学习结束，本文历时长达10周整理了相关的配套资料。即使没有参加过课程，从头到尾过一遍这些资料，也可以增加对R语言的应用理解。

- 资源链接：https://ourcodingclub.github.io/tutorials/intro-to-r/

12、[23个机器学习最佳入门项目（附源代码）](https://mp.weixin.qq.com/s/uu_iDjv9MNFfLSMCPPBGyQ)

![](https://files.mdnice.com/user/33257/33741057-d540-46c7-8fa7-27072b892bbc.png)

在本文中，涵盖面向初学者，中级专家和专家的23种机器学习项目创意，可获取有关该增长技术的真实经验。

## 历史上的本周

- 第23期：[从美国博德研究所成功之道看生命科学前沿创新](https://mp.weixin.qq.com/s/ZqiHoDRXHg47M_zu7Whwzw)

## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`（王诗翔）
- `@kkjtmac`（阚科佳）
- `@NiEntropy`（赵启祥）
- `@He-Kai-fly`（何凯）
- `@JnanZhang`（张佳楠）
- `@Tomcxf`（陈啸枫）
- `@wangdepin`（王德品）

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://files.mdnice.com/user/33257/3e1baf88-6e69-40ed-bcb1-a4ba71628f1d.png)

（完）
