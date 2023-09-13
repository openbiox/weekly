---
date: 2023-07-15
comments: true
---


# 生信爱好者周刊（第 84 期）：认识自己的缺点

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图


![](https://files.mdnice.com/user/5208/fbfa6072-1289-4290-98eb-9e44d2fbb15d.png)


## 本周话题：[认识自己的缺点？](https://mp.weixin.qq.com/s/0M6xvHM9Y0DYMWNvILs20Q)

> 人人都有优点和缺陷，但不一定都能认识到自己的优缺点。不能意识到自己的缺点更是常态。认识自己缺陷深刻到可以推动人类知识的提高，这需要一定的才能，比如英国科学家道尔顿具有这样的才能。

@He-Kai-fly - 与别人的比较中认识自己，以身边的人为参照物，知道自己在这些参照物中所处的位置，完善自己。  

@ShixiangWang - 每个人都有自己的缺点，缺点常常是一类人共有的精神/行为特征，而在自身/他人看来是一种不完美的体现。有时候，缺点难以或者完全没办法改正，但如果自身能认识到，那么就可以尽量减少对其他人的伤害。

## 生信研究
1、[Nature Communications| AI 赋能全身危及器官勾画，加速放射治疗](https://mp.weixin.qq.com/s/X-Ruz3jzAzOZzNDsi5LSpg)


![](https://files.mdnice.com/user/5208/be3eceb2-2b95-43ac-9388-db407b90c5c0.png)


>近日，由上海科技大学生物医学工程学院与联影智能、复旦大学附属肿瘤医院、联影科技合作完成的全身多器官「AI 放疗勾画」,其有效性和安全性首先依赖于危及器官(Organ At Risk, OAR) 和靶区的准确勾画。传统的放疗计划 (Radiotherapy Treatment Planning, RTP) 需医师手动勾画器官和靶区，耗时较长且不同医师勾画结果差异性较大。针对该痛点，本课题设计了一种通用型的分割网络框架以实现多种器官和病灶的自动、快速、精准分割，为后续 All-In-One 一站式放疗提供一致性高、重现性好的靶区勾画结果。

- 论文链接：https://www.nature.com/articles/s41467-022-34257-x



2、[Genome Biology | iDNA-ABF: 基于多尺度深度学习的生物序列与功能语义模型实现DNA甲基化可解释性预测](https://mp.weixin.qq.com/s/ZLWchph9tsaBnkpGd8P2WQ)


![](https://files.mdnice.com/user/5208/96914eb9-ff95-4d1d-aeb6-bfd0c713ee33.png)


>  魏乐义教授团队提出了一种基于多尺度深度学习的生物序列与功能语义模型iDNA-ABF实现对DNA甲基化的可解释性预测。在多物种数据集及人类细胞系数据集中，iDNA-ABF均展现出较好的性能。通过引入对抗训练策略，增强了模型的鲁棒性从而让模型在不同大小的训练集上都获得较优异的性能，也可以预防出现大模型的过拟合问题。另一方面，通过引入attention机制，iDNA-ABF获得了良好的可解释性，能够有效从序列层面建立起甲基化功能的关系，从而为生物学家的研究和发现提供启发。

- 论文链接：https://www.nature.com/articles/s41587-022-01652-0



3、[Nature Biotechnology丨 PRPS 有效消除文库大小、肿瘤纯度和批次效应对RNA-seq数据分析的影响](https://mp.weixin.qq.com/s/OxBpgc30mGXRzfjshYeOZA)

![](https://files.mdnice.com/user/5208/0171eb5b-44d8-460f-843e-c42587a2efa1.png)


> 为从RNA-seq数据中获得有意义的生物学结果，准确识别和有效去除不同因素产生的基因表达差异至关重要，特别是在大型、复杂的研究数据中。研究团队利用来自TCGA的RNA-seq数据，开发了一种名为RUV-III-PRPS的方法，能够有效去除文库大小、肿瘤纯度和批次效应对TCGA RNA-seq数据的影响。经验证，该方法可用于整合、规范来自多个实验室或平台的其他大型转录组数据集。

- 论文链接：https://www.nature.com/articles/s41587-022-01440-w



4、[nature systems biology and applications | 疾病建模和药物控制中的计算系统生物学](https://mp.weixin.qq.com/s/Hsnx7NJJpVtRKjH8tqFjGQ)


![](https://files.mdnice.com/user/5208/f127ec9e-002e-46cd-a6df-8b777c003c91.png)


> 基于Omics的方法在确定疾病机制和药物应答方面的影响越来越大。考虑到疾病和药物应答在相关的组学数据交互中是共同表达和调节的，传统的从单个孤立获取组学数据的方法不能总是获得有价值的推断。此外，药物有可能给患者带来副作用，而且针对疾病推出新药的成本很高。系统生物学通过整合基因组、蛋白质组、转录和代谢层的组学数据来预测潜在的分子相互作用。结合已知的药物应答，由此产生的模型通过药物重利用并结合药物分子提高药物的治疗性能，而不会产生非靶向效应。基于确定的计算模型，药物管理控制旨在平衡毒性和疗效。

- 论文链接：https://www.nature.com/articles/s41540-022-00247-4



## 博文资讯

5、[两院院士评选“2022年中国/世界十大科技进展新闻”揭晓](https://mp.weixin.qq.com/s/pcrLeOyq3MPcwylaVElIsQ)

![](https://files.mdnice.com/user/5208/34590860-62e6-4d18-a2fb-db209834cb4c.png)


> 由中国科学院、中国工程院主办，中国科学院学部工作局、中国工程院办公厅、中国科学报社承办，中国科学院院士和中国工程院院士投票评选的2022年中国十大科技进展新闻、世界十大科技进展新闻于2023年1月12日在京揭晓。



6、[Multipass | 免费轻量级的虚拟机命令管理工具](https://mp.weixin.qq.com/s/dOJyAFgpKdSM_iwM3Gc0HA)


![](https://files.mdnice.com/user/5208/9d6bd0e0-4d5a-4372-a7ae-66d377801156.png)


本文推荐了一款虚拟机工具：Multipass，它是非常轻量级的虚拟机命令管理工具，运行环境支持 Linux、Windows 和 macOS。此外，作者还简要介绍了本工具的基本操作。

- 工具链接：https://multipass.run/

7、[Python也能画漂亮的complex heatmap？ ](https://mp.weixin.qq.com/s/UQvyy3-n1UkD47RUDyE1ZA)


![](https://files.mdnice.com/user/5208/645d9e65-079f-4639-b6ba-b9216d1b2e84.png)  

介绍一款可以在python中画出类似于R中ComplexHeatmap效果的包：**PyComplexHeatmap**  

- Github: https://github.com/DingWB/PyComplexHeatmap





8、[使用dendextend包进行两个聚类树的成对比较](https://mp.weixin.qq.com/s/0oXYAjcebveCIumQJrRY7Q)

![](https://files.mdnice.com/user/5208/bf535035-3092-40cf-a519-53c689d71821.png)

>　为了比较同一数据使用不同聚类方法的差异（例如，平均聚合聚类和Ward最小方差聚类），或者评价两组存在某种关联的数据间的一致性（例如，来自同一采样点的物种和环境，同一个体的基因表达和蛋白表达等），这种涉及两个聚类树的比较的情况，在R中可借助dendextend包来实现。




## 工具

9、[gpttools | 将chatGPT整合至Rstudio的R包](https://github.com/JamesHWade/gpttools "gpttools | 将chatGPT整合至Rstudio的R包")


![](https://files.mdnice.com/user/5208/7cebb377-e607-4b50-aaf3-02565fda72a6.png)

gpttools的目标是为R包开发人员扩展gptstudio，使其更容易将大型语言模型(llm)的使用合并到他们的项目工作流中。



10、[超过 230 个的纯 Python 实用工具库](https://mp.weixin.qq.com/s/vYKyXJNH43IjtlsTdS-avQ)


![](https://files.mdnice.com/user/5208/50b04b53-d93b-4f72-8f79-c179b99cc3e3.png)


本文推荐第三方库 -- Boltons，和大多数第三方库不太一样，它并不是针对某一功能的工具库，而是将开发中那些重复性（经常使用）及复杂度较高（不容易编写）较高的代码剥离出来，并按照操作对象分门别类整合在一起的工具库。

Boltons 使用的是 BSD 许可证，到目前为止已经收录超过 230 个的纯 Python 实用工具库，这些工具库与 Python 标准库并没有重合，是补充的关系。



11、[Workflowy| 提供了一种工作流项目管理](https://workflowy.com/ "Workflowy| 提供了一种工作流项目管理") 

![](https://files.mdnice.com/user/5208/bf6e5e81-3173-40e0-9497-5b08cec37031.png)

Workflowy提供了许多工作流的模板供使用，感兴趣可以尝试


## 资源
12、[Orchestrating Single-Cell Analysis with Bioconductor](https://bioconductor.org/books/release/OSCA/ "Orchestrating Single-Cell Analysis with Bioconductor")


![](https://files.mdnice.com/user/5208/a8abdce5-abc9-4d45-b7cf-ca3c739ab530.png)

《Orchestrating Single-Cell Analysis with Bioconductor》这本书教给用户一些分析单细胞RNA-seq数据（scRNA-seq）的常见工作流程。 本书将展示如何利用生物处理工具来处理、分析、可视化和探索scRNA-seq数据。



13、[Arch-guide系统简明指南](https://github.com/nakanomikuorg/arch-guide "Arch-guide系统简明指南")

![](https://files.mdnice.com/user/5208/f5e0d77c-7d93-4305-8e53-224682fcfc0f.png)

- 中文Tutorial : https://github.com/ArchLinuxStudio/ArchLinuxTutorial



14、[深入了解Bioconductor项目的教程](https://carpentries-incubator.github.io/bioc-project/ "深入了解Bioconductor项目的教程")



![](https://files.mdnice.com/user/5208/83d797a4-0cc0-41ef-9aa8-013abac3af11.png)


本教程提供了在R和RStudio中如何有效地使用Bioconductor上的包进行多组学数据分析和可视化的相关基础知识和流程。




## 历史上的本周
- 第44期：[为何动物的寿命差异那么大？](https://mp.weixin.qq.com/s/15Pdgf9cfYCRH1l7nMZ5QQ)

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



