---
date: 2024-08-04
comments: true
---

# 生信爱好者周刊（第 134 期）：时隔四年撤稿：微生物组与癌症类型存在相关性是数据分析错误所致 

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图

![](https://files.mdnice.com/user/37191/28f79645-9108-49c2-9669-4787f7db5313.png)


## 本周话题：[时隔四年撤稿：微生物组与癌症类型存在相关性是数据分析错误所致](https://mp.weixin.qq.com/s/SdXZ5cGIki4MLsklkOYFxg)


![](https://files.mdnice.com/user/37191/25b0f0eb-ed39-4d3d-b343-d50aabb0419b.png)


>2020年3月11日，来自加州大学圣地亚哥分校的Rob Knight团队在Nature杂志上发表了一篇题为Microbiome analyses of blood and tissues suggest cancer diagnostic approach的文章，他们通过对包含33种癌症共18116个样本癌症基因组图谱（TCGA）的全基因组和全转录组测序结果的分析，提出微生物DNA特征与大多数癌症类型之间存在强相关性，并创建一种机器学习模型作为基于微生物组的肿瘤诊断工具。
>
>然而，时隔四年，来自约翰霍普金斯大学的Steven L. Salzberg等对该文章的数据分析及研究结论提出质疑，他们指出该文章报告与癌症相关的大多数微生物根本不存在于人类样本中，该研究数据及之后以此为基础的十余项后续研究结果可能是无意义的。

## 生信研究
1. [Cancer Cell | 张泽民课题组合作揭示结直肠癌免疫治疗响应相关的肿瘤微环境细胞类型时空动态变化规律](https://mp.weixin.qq.com/s/emSDzVMMW4i7aEA19nSNRg)


![](https://files.mdnice.com/user/37191/153276d4-5bcb-4823-aafa-00cad684d247.png)


2024年7月8日，北京大学生物医学前沿创新中心（BIOPIC）张泽民课题组联合北大肿瘤医院武爱文课题组，在国际期刊Cancer Cell上发表了题为“Spatiotemporal single-cell analysis decodes cellular dynamics underlying different responses to immunotherapy in Colorectal Cancer”的研究论文。该研究动态追踪了结直肠癌患者在免疫治疗下原位癌灶及外周系统的时空变化，通过系统性鉴定“细胞程序”揭示了肿瘤微环境中多种细胞类型在免疫治疗过程中的协同演化规律，进一步解析了外周免疫系统对免疫治疗疗效的关键作用，建立了基线水平外周CD8+ T细胞的激活状态与患者疗效的关联，为理解免疫治疗响应差异提供了新的视角。

- 论文链接：https://www.sciencedirect.com/science/article/pii/S1535610824002344


2. [Cell | 高分辨率空间转录组学技术绘制亚细胞精度的病变组织三维图谱，大大降低技术使用门槛](https://mp.weixin.qq.com/s/6RIxW2-txkiS-cFok6M3rA)


![](https://files.mdnice.com/user/37191/0900ef10-5777-4cb8-b75f-75cfe34d436b.png)


2024年6月24日，柏林医学系统生物学研究所（BIMSB）、马克斯-德尔布吕克中心（Max Delbrück）的尼古拉斯-拉杰夫斯基（Nikolaus Rajewsky）团队和尼科斯-卡拉斯科斯（Nikos Karaiskos）团队的研究人员以“Open-ST: High-resolution spatial transcriptomics in 3D”为题在 Cell 杂志发表了最新研究成果，报道了一种名为Open-ST的空间转录组学平台，使科学家能够以三维方式重建组织内细胞的基因表达。该平台生成的图谱分辨率极高，研究人员能够看到分子和（亚）细胞结构，而传统的二维图谱往往看不到这些结构，该技术将可能提高常规临床病理学水平。

- 论文链接：
https://doi.org/10.1016/j.cell.2024.05.055


3. [Nature Machine Intelligence | 基于Transformer的RNA语言模型](https://mp.weixin.qq.com/s/waafWP5zaxFO9auH8k_t_A)

![](https://github.com/user-attachments/assets/b5334472-f855-4db3-b83a-952102557f55)

预训练语言模型在分析核苷酸序列方面显示出了良好的前景，但使用单个预训练权重集在不同任务中表现出色的多功能模型仍然存在挑战。百度大数据实验室（Big Data Lab，BDL）和上海交通大学团队开发了 RNAErnie，一种基于 Transformer 架构，以 RNA 为中心的预训练模型。研究人员用七个数据集和五个任务评估了模型，证明了 RNAErnie 在监督和无监督学习方面的优越性。

- 论文链接：https://www.nature.com/articles/s42256-024-00836-4


## 博文资讯

4. [染色质三维结构 | compartment & TADs & loop](https://mp.weixin.qq.com/s/SbGoUgblN7Anqj_c-4BqHg)


![](https://files.mdnice.com/user/37191/bc9cdf43-0b5d-461d-9ef1-25c0b99bd5b6.png)


> 这几天听了有关三维基因组的几场报告，突然发现之前学的细胞生物学中染色体多级螺旋模型只是对染色质宏观的描述，染色质三维结构还能进行更精细的划分。这篇笔记主要整理一下染色质三维结构--compartment、TADs、loop。

5. [大模型及发展趋势](https://mp.weixin.qq.com/s/uJXmY-hU-OsRI_GFgf4hPw)

![](https://github.com/user-attachments/assets/58cafcbf-4223-4fe3-b2c7-ad5c799dd598)

大型语言模型（LLMs）无疑是此次人工智能革命的核心，其构建于Transformer架构的坚实基础之上，并依据缩放定律（Scaling Law）不断进化。

6. [CentOS/Redhat R包使用新的gcc编译](https://mp.weixin.qq.com/s/BoMEGabgWvjfETnIPPxJVA)


![](https://files.mdnice.com/user/37191/369fc1c9-4695-428d-bd8c-762700c76cba.png)


R包在Linux下编译不通过，原因是gcc版本太低怎么办？

一些有C++代码的R包可能会用到一些新的C++特性，需要C++11或者C++14。这个问题通常在CentOS/红帽系统上出现，因为系统稳定的要求，这个系列的系统它的C++版本很低。但请读者前往注意了别自己编译新版本的gcc，然后替换掉系统的。这种操作我试过几次，系统基本上就崩掉了。

正确的解决方式是安装独立的gcc，通过环境变量引用和使用它。


## 工具

7. [web-check](https://github.com/Lissy93/web-check "web-check")


![](https://files.mdnice.com/user/37191/0b4ed7c4-112b-4fc2-b55c-cec93cc73912.png)

web-check可以帮助用户深入了解给定网站的内部运作，包括发现潜在的攻击媒介、分析服务器架构、查看安全配置，并了解网站正在使用的技术。

目前，该软件会提供给用户网站的IP 信息、SSL 链、DNS 记录、Cookie、标头、域信息、搜索抓取规则、页面地图、服务器位置、重定向账本、开放端口、traceroute、DNS 安全扩展、站点性能、跟踪器、相关主机名、碳足迹。

8. [ggsankey](https://github.com/davidsjoberg/ggsankey "ggsankey")


![](https://files.mdnice.com/user/37191/cb1c133d-9109-430b-853e-42a245a56674.png)


ggsankey可以帮助用户制作美丽的桑基图、冲积图和桑基凹凸图。


## 资源

9. [Critical care education one page at a time！](https://onepagericu.com/index "Critical care education one page at a time！")

![](https://files.mdnice.com/user/37191/9ff65b12-29b2-44d3-8e16-afbc6143e4f8.png)

一个开源的重症监护教育网站。

10.[Cheatography | Over 6,000 Free Cheat Sheets](https://cheatography.com/ "Cheatography | Over 6,000 Free Cheat Sheets")


<img width="1218" alt="image" src="https://github.com/user-attachments/assets/ab28e6c6-bcf9-4007-9ea4-4bd2bba340dc">


对于爱好学习的不可错过。

- 正则：https://cheatography.com/davechild/cheat-sheets/regular-expressions/
- Python：https://cheatography.com/davechild/cheat-sheets/python/
- R：https://cheatography.com/non-human-entity/cheat-sheets/r-cheat-sheet/


## 历史上的本周
- 2023 [生信爱好者周刊（第 94 期）：非线性的世界，线性的你](https://mp.weixin.qq.com/s/DBNBTEqidRIVbOYxfFTjoQ)

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


![](https://files.mdnice.com/user/37191/484e56e7-6d4d-41a3-a70c-53e240bb2dcd.png)


（完）