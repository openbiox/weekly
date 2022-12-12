# 生信爱好者周刊（第 56 期）：

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions "「生信周刊讨论区」")

## 封面图
![](https://files.mdnice.com/user/38661/ee539268-e88c-42b6-9d28-7c0ed97a0db2.png)

2022年诺贝尔化学奖获奖者：美国化学家卡罗琳·贝尔托西（Carolyn R. Bertozzi）、丹麦化学家摩顿·梅尔达尔（Morten Meldal）和美国化学家卡尔·巴里·夏普利斯（K. Barry Sharpless）。

## 本周话题：[2022诺贝尔奖的点击化学或可作为单细胞多组学开发的有力工具](https://mp.weixin.qq.com/s/swYKnEJhCBefIBcmi-U3FA)

![](https://files.mdnice.com/user/38661/c7b66bef-de9b-412c-ad32-2772a21848e2.jpg)
图源：Introduction: Click Chemistry

>点击化学（Click chemistry），又译为“链接化学”、“速配接合组合式化学”，是由化学家巴里·夏普莱斯（K B Sharpless）在2001年引入的一个合成概念，主旨是通过小单元的拼接，来快速可靠地完成形形色色分子的化学合成。它尤其强调开辟以碳-杂原子键（C-X-C）合成为基础的组合化学新方法，并借助这些反应（点击反应）来简单高效地获得分子多样性。点击化学的代表反应为铜催化的叠氮-炔基Husigen环加成反应（Copper-Catalyzed Azide–Alkyne Cycloaddition）。点击化学的概念对化学合成领域有很大的贡献，在药物开发和生物医用材料等的诸多领域中，它已经成为最为有用和吸引人的合成理念之一。

`@JnanZhang`：新方法的发展和新技术的进步共同推动了生物学的蓬勃发展，单细胞测序技术与点击化学的结合可能会拓展对单细胞认识的边界。

## 生信研究
1、[Nature Biotechnology | 通过迁移学习将单细胞数据映射到参考集](https://mp.weixin.qq.com/s/QmCe8vbMdzoji43RudSQhQ)

![](https://files.mdnice.com/user/38661/8f4a69e4-89e6-4cce-9b97-ba930dfb84b7.png)

大型单细胞 Atlas 现在经常被生成，来作为较小规模研究对象进行分析的参考。然而，由于数据集之间的批处理效应、计算资源的有限性和对原始数据的分享限制，从参考数据中学习是复杂的。本文介绍了一种深度学习策略，用于将查询数据集映射到称为单细胞体系结构手术(scArches)的参考数据之上。

- 论文链接：https://www.nature.com/articles/s41587-021-01001-7

2、[Cancer Discovery | REFLECT-预测癌症最佳联合疗法的新型生物信息学平台](https://mp.weixin.qq.com/s/uA7DxaM84iXrZ5WgEuPt5w)

![](https://files.mdnice.com/user/38661/23bb576a-1e1f-45fd-bba8-86580a243821.png)

MD安德森癌症中心生物信息学与计算生物学系的Anil Korkut教授和李旭斌博士共同领导的研究团队开发的一种可以预测癌症的最佳联合疗法的新型生物信息学平台-REFLECT (REcurrent Features LEveraged for Combination Therapy)。这个平台整合了机器学习和癌症信息学的算法，通过分析癌症病人的分子数据，包括基因突变、 拷贝数变异、基因表达、蛋白表达，并从中发现复现的、可以被药物分子靶向的协同畸变，进而获得系统的、与病人分子特征匹配的最佳联合治疗方案。相关研究成果以题为Precision Combination Therapies Based on Recurrent Oncogenic Coalterations 的研究论文于近期在线发布。

- 论文链接：doi: 10.1158/2159-8290.CD-21-0832

3、[Nature|利用图泛基因组找回丢失的遗传力和促进番茄育种](https://www.nature.com/articles/s41586-022-04808-9 "Nature|利用图泛基因组找回丢失的遗传力和促进番茄育种")

![](https://files.mdnice.com/user/38661/d70701d5-c09d-4c80-ac71-4982e50d6932.png)

全基因组关联研究中遗传性缺失是复杂生物性状遗传分析中的一个主要问题。近日《Nature》上发表的一篇文章报道了一个来自838个基因组的1900多万个变体构建的番茄泛基因组图，该图谱用于20323个基因表达和代谢物性状的全基因组关联研究分析和遗传力估计。该研究促进了对复杂性状遗传力的认识，并证明了图泛基因组在作物育种中的作用。

- 论文链接：https://www.nature.com/articles/s41586-022-04808-9

4、[王鹏远/鲁志/徐振江团队合作发表泛癌早诊研究新成果：利用血浆中人源+微生物源cfRNA诊断早期癌症及其组织来源](https://mp.weixin.qq.com/s/sbM2M_uZhuUXttdumdBCJQ)

![](https://files.mdnice.com/user/38661/8181a25b-0ea3-44c4-93a6-eb9b09fe92b2.png)

北京大学第一医院王鹏远团队与清华大学鲁志团队、南昌大学徐振江团队合作，在生物医学权威期刊《eLife》上发文，阐述了细胞外RNA（cfRNA）在泛癌早期诊断中的应用和前景。肿瘤液体活检技术中的标志物包括循环肿瘤细胞（CTC）、细胞外DNA（cfDNA）及其甲基化、细胞外 RNA(cfRNA)、外泌体蛋白等。与CTC/cfDNA相比，cfRNA作为癌症标志物至少有以下3个优势：、敏感性和功能性、组织特异性和低成本。

- 论文链接: 10.7554/eLife.75181


## 博文资讯
5、[用R语言解读传染病模型](http://blog.fens.me/r-infectious-disease/ "用R语言解读传染病模型")


![](https://files.mdnice.com/user/38661/f3c2cc41-25cf-4339-bb8e-6dc84e890e8d.png)


本文结合传染病学的专业知识，通过R语言的技术手段，通过相应的代码解释了传染病传播的一些底层原理。

- 文章代码：https://github.com/bsspirit/infect/blob/main/code/model.r

6、[iMeta | 华南农大陈程杰/夏瑞等发布TBtools构造Circos图的简单方法](https://mp.weixin.qq.com/s/QJIsP9UWRcv_j1dIN5uHcA)

![](https://files.mdnice.com/user/38661/d10e1cc1-52f8-4b00-ae4f-7c7223b62bf3.png)

Circos图使科学家能够轻松地在全基因组尺度上探索生物大数据，但繁琐的输入数据准备和复杂的参数配置限制了其应用。TBtools中开发了“Advanced Circos”功能，提供构造Circos图的简单方法。作为一个开箱即用的软件，TBtools集成了系列便于输入数据准备的功能。“Advanced Circos”功能提供了一个用户友好界面，用于定制参数设置，并可用于可视化各种基因组水平数据，如基因组关联信息、比对数据、基因密度和QTL位置。本文介绍了“Advance Circos”的主要特点和上游数据准备方法，旨在让更多用户能够使用Circos图进行基因组大数据探索。

- 软件地址：https://github.com/CJ-Chen/TBtools
- 论文链接：Chen, Chengjie, Ya Wu, and Rui Xia. 2022. “A painless way to customize Circos plot: From data preparation to visualization using TBtools.” iMeta. e35. https://doi.org/10.1002/imt2.35


7、[图形化泛基因组构建工具-mingraph介绍](https://mp.weixin.qq.com/s/iWFrKe9XA-6zVvBKpzvcJQ)

![](https://files.mdnice.com/user/38661/c0cb963d-ff33-4dcd-8c8b-a262f4f76672.png)

随着测序技术的发展，同一物种中，越来越多的高质量基因组被测出。如何整合来自同一物种的多个基因组，是目前一个生物界中的难题。其中一种办法就是使用图形化泛基因组去表示多个基因组的变异。在这里，给大家介绍一个由李恒大神设计的图形化泛基因组工具：minigraph。该工具在保留线性参考基因组的坐标同时，使用基于图形的数据模型和相关格式来表示多个基因组，可以有效的构建图形化泛基因组，表示当前基因组中缺失的变异体。

8、[forestmodel | 可视化回归模型包](https://mp.weixin.qq.com/s/Id2fK0bhPISEakOhkGG9IQ)

![](https://files.mdnice.com/user/38661/59e8d1b4-3590-4c26-83bc-577c47778a7f.png)

通过forestmodel包，可以构建lm、glm、coxph三种回归模型，同时支持survival包的Cox回归模型结果可视化。

- github：https://github.com/NikNakk/forestmodel
- R包教程：https://shixiangwang.github.io/forestmodel/index.html
- Reference manual：https://cran.r-project.org/web/packages/forestmodel/forestmodel.pdf


## 工具
9、[fullPage | Shiny界面设置调整的工具](https://github.com/RinteRface/fullPage "fullPage | Shiny界面设置调整的工具")


![](https://files.mdnice.com/user/38661/7c4b92a3-50c0-4e62-b31d-c91c69dc6e6a.png)


fullPage是一个对Shiny界面进行全屏、分页等多种调整配置的工具。

10、[ParlAI | 对话AI](https://parl.ai/ "ParlAI | 对话AI")

![](https://files.mdnice.com/user/38661/58227885-4bf1-4428-b447-2caac11d8dde.png)

ParlAI是一个用于共享、训练和测试对话模型的 python 框架，从开放域聊天到面向任务的对话，再到视觉问答。

- github：https://github.com/facebookresearch/ParlAI
- 官网：https://parl.ai/

11、[https://github.com/fantasticit/think ](https://github.com/fantasticit/think "https://github.com/fantasticit/think ")

![](https://files.mdnice.com/user/38661/8d8f4397-6ecb-482f-8297-5c3e94aae592.png)

Think 是一款开源知识管理工具。通过独立的知识库空间，结构化地组织在线协作文档，实现知识的积累与沉淀，促进知识的复用与流通。同时支持多人协作文档。使用的技术如下：

- MySQL：数据存储
- next.js：前端页面框架
- nest.js：服务端框架
- tiptap：编辑器及文档协作

可访问[云策文档帮助中心]( "云策文档帮助中心")，查看更多功能文档。

12、[一个解决你的所有饼图绘制的 R 包](https://mp.weixin.qq.com/s/ijkbXTgxl5LhhYxjGPRzsA)

![](https://files.mdnice.com/user/38661/9a7fca36-756c-498b-94ad-dae459cdf5f4.png)

一个比较综合性绘制饼图的 R 包 ggpie。

## 资源推荐
13、[https://github.com/alteryx/featuretools
Featuretools](https://github.com/alteryx/featuretools)

![](https://files.mdnice.com/user/38661/ece1f740-c26f-4772-adf3-4d7533faea62.png)

是一个用于自动化特征工程的python库。

14、[面向程序员的 Top 10 精品开源字体](https://mp.weixin.qq.com/s/C6TwyxZqV-mY0RmLt1WCeA)


![](https://files.mdnice.com/user/38661/6df0de02-0643-4e0c-bab6-efd9d0e8f7c7.png)

![](https://files.mdnice.com/user/38661/0855a6eb-b8ab-4a77-92db-bf37ceab26b6.png)

本文提供 10 款开源字体的介绍、预览和下载方式，推荐码代码的各位使用。


## 历史上的本周

2022年1月：[第16期：癌症新特征](https://mp.weixin.qq.com/s/uU83rEnrkX9jFXjhHQdlqQ)

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

![](https://files.mdnice.com/user/38661/9ef4bd50-6875-405f-bbd4-3f2dae29c6d2.png)

