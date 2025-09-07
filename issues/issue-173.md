---
date: 2025-09-07
comments: true
---

# 生信爱好者周刊（第 173 期）：为研究需要经费，还是为烧钱而做研究？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图
![](https://files.mdnice.com/user/33257/c54b1238-67a4-4329-87a2-a771bc234d16.jpg)
The Colors of Heredity-遗传的色彩 
## 本周话题：为研究需要经费，还是为烧钱而做研究？

@kkjtmac 理想的研究是为探索未知，经费是必要的支撑。但现实中，当经费申请、预算执行和量化考核成为指挥棒时，科研便有异化为“为烧钱而研究”的风险。回归初心，让经费真正服务于好奇心和重大问题，而非沦为追逐指标的游戏，至关重要。

## 生信研究
1、[Nature | 陈鹏/伊成器建立RNA"暗码"，升级生命语言](https://mp.weixin.qq.com/s/i1DOA4e-lEkdU1qYzdr92Q)

![](https://files.mdnice.com/user/33257/2f89ed5c-52cc-4e14-8498-bd18d14ce611.png)

北京大学陈鹏团队和伊成器团队通过RNA假尿嘧啶Ψ修饰的定点编程，创造了三个全新的“ΨCodon”密码子，并筛选出能特异性解码这些密码子的tRNA变体，实现了在蛋白质特定位点精准插入非天然氨基酸，从而操控蛋白质功能。与传统DNA密码子拓展技术相比，该RNA密码子拓展技术（RCE）具有更高的全局特异性和正交性，显著降低了脱靶效应，为精准蛋白质工程、合成生物学和生物医学研究提供了新的工具平台，也为设计人工合成生物体提供了新的编解码元件。

- 论文链接：https://www.nature.com/articles/s41586-025-09165-x

2、[Nature｜癌症免疫疗法新突破：1种肠道细菌让PD-1治疗效果飙升](https://mp.weixin.qq.com/s/UXUw8HRgE3ovI_OCd1q39w)

![](https://files.mdnice.com/user/33257/8955d4aa-7598-4fd9-b3b6-4084ecb2c77c.jpg)

Nature上这篇研究成功从对PD-1阻断疗法有响应的患者粪便中分离出一种此前未被详细描述的新型细菌菌株YB328，并首次详细揭示了其通过特异性激活树突状细胞（DCs）来增强抗肿瘤免疫的分子和细胞机制。

- 论文链接：https://www.nature.com/articles/s41586-025-09249-8


3、[Nature｜Y染色体缺失致男性癌症高风险，发现抗衰老与抗癌新靶点](https://mp.weixin.qq.com/s/B7nB4snsKItcbzQd4-moXw)


![](https://files.mdnice.com/user/33257/809c521e-9bd7-453e-ae16-db3b7830441a.jpg)

该研究整合了4000余例男性癌症样本、逾100万个肿瘤微环境中细胞的单细胞转录组数据，并借助CRISPR小鼠模型和多平台组学，全面探索了Y染色体缺失的起源、传播路径及其临床意义。

- 论文链接：https://www.nature.com/articles/s41586-025-09071-2

## 博文资讯
4、[PE150，插入片段的大小要刚好300bp？](https://mp.weixin.qq.com/s/8BYxDR5LuTF_gOHDJvJRPQ?scene=1&click_id=52)

![](https://files.mdnice.com/user/33257/5bd62e3a-bd44-46cc-ab5d-cd7904240964.png)

这篇文章主要讨论了PE150测序模式下插入片段大小的选择问题：插入片段大小会影响测序结果的覆盖范围和质量。当插入片段大于300bp时，两端生成的150bp的reads无法覆盖中间区域；当插入片段在150bp到300bp之间时，两端的reads会有重叠区域，覆盖完整；而当插入片段小于150bp时，测序仪会记录无效碱基。文章建议常规文库构建的插入片段主峰在300bp到500bp之间，特殊文库如cfDNA和扩增子建库等有不同要求。插入片段的误差在几十bp范围内是可接受的，但严重偏离则意味着建库失败。插入片段过短会导致测序读到接头，造成数据浪费；过长则会降低成簇效率和测序质量。

5、[科研工作者如何实现财富自由？](https://mp.weixin.qq.com/s/pAGMJYC28ebmRxKDc6GYag)

![](https://files.mdnice.com/user/33257/3fd2cd0d-9bde-418c-ae6f-b1d399fe2314.png)

这篇文章探讨了科研工作者实现财富自由的途径。在经济转型期，科研人员面临机遇与挑战。文章提出了三种成果转化方式：一是自己创办公司，将技术产业化，但面临融资、管理等难题；二是与人合伙，通过技术入股成立初创公司，需找到靠谱合伙人；三是通过专利许可或技术转让，但可能面临被压价风险。作者鼓励科研人员走出舒适圈，利用国家政策支持，将科技成果转化为生产力，实现自身价值。

6、[P value、adjust.P、qvalue、FDR有何异同](https://mp.weixin.qq.com/s/snETYDmUfL5x7wRia8ZFKQ)

![](https://files.mdnice.com/user/33257/95f21b00-1e35-4bea-af32-7d86b40f2562.png)

文章介绍了P值、adjust.P、qvalue、FDR的概念及区别。P值是在原假设成立时观察到当前结果或更极端结果的概率。校正P值是为了解决多重比较问题，降低犯I类错误的概率。校正方法包括Bonferroni校正、FDR校正等，其中FDR是常用方法，通过控制假阳性比例来校正P值。qvalue是校正后的P值，用于控制整体FDR。这些都是生信分析中最基础常见的概念，推荐学习或者回顾。

7、[GPU组网基础知识](https://www.chipstrat.com/p/gpu-networking-basics-part-1 "GPU组网基础知识")

![](https://files.mdnice.com/user/33257/5b0f7462-8720-468e-ac61-68eb71d9b974.png)

这篇文章介绍了GPU网络的基础知识，特别是针对大规模训练语言模型（LLMs）的场景。文章指出，单个GPU训练大型模型耗时过长，因此需要大量GPU协同工作。这些GPU需要通过网络连接来共享进度和结果。文章讨论了全网状网络（full mesh）的不切实际性，因为需要过多的端口和电缆。接着介绍了使用网络交换机来简化连接，但指出单一的巨大交换机也不可行，因此需要分层交换架构。文章还讨论了水平扩展（scaling out）和垂直扩展（scaling up）的概念，以及它们在GPU集群中的应用。此外，文章还提到了GPU之间的通信方式，包括内部节点（intra-node）和节点间（inter-node）通信，并解释了为什么内部节点通信更快。最后，文章简要介绍了神经网络训练中的通信挑战，特别是all-reduce通信的重要性。

## 工具
8、[IOBR 2.0 | 免疫浸润综合分析工具 ](https://mp.weixin.qq.com/s/TAc8VSPbV3k6x7RX0JcXTw)

![](https://files.mdnice.com/user/33257/7a166d73-945b-4eae-a82e-fbbf1322f1ff.png)
IOBR 2.0是一个用于肿瘤微环境和免疫特征分析的工具。IOBR 2.0 提供了六个模块，包括数据预处理、微环境解析、交互作用分析等。它整合了8种免疫浸润分析算法，如CIBERSORT、TIMER等，并提供了323个特征基因集。IOBR 2.0 支持多种数据打分和可视化方法，适用于多组学数据。

- 工具链接：https://github.com/IOBR/IOBR

9、[scitable包 | 一键生成彩色（危险分层 Risk Stratification）的列线图](https://mp.weixin.qq.com/s/XIt6Va0WZkGx1yuUCe6RZQ)

![](https://files.mdnice.com/user/33257/c448cf7f-c42a-4ed8-ab2f-0dcf36eb5866.png)

scitable包是一个强大的R包，用于生成彩色列线图（Nomogram），可用于预测疾病风险。它基于回归模型，将多个变量的值转换为直观的视图。该包支持多种自定义功能，如更改颜色、字体、添加风险分层等。通过简单的函数调用，可以快速生成高质量的列线图，适用于临床研究和生物统计分析。

10、[PPI-ID | 让蛋白互作预测更精准高效的一款轻量化工具](https://mp.weixin.qq.com/s/WrkWvzHneYBgRvEMoSZhNA)

![](https://files.mdnice.com/user/33257/f7073572-70dc-4e4b-87c1-e76c5ea1656d.png)

PPI-ID 专为简化和优化 PPI 预测流程而设计，通过整合蛋白结构域（Domain）与短线性基序（SLiM）映射，极大提高了预测的效率与可信度。

- 工具链接：http://ppi-id.biosci.utexas.edu:7215/ 

## 资源
11、[「陈巍学基因」视频、文章目录](https://mp.weixin.qq.com/s/ncaPMEU3agF89dq5kKmC2w?scene=1)

![](https://files.mdnice.com/user/33257/14d2d552-89d6-4361-ad66-33bfc8643056.png)

「陈巍学基因」累计大量的生物技术/生物信息学知识视频图文分享，非常专业细致，推荐大家学习。PS：可能会过期，建议关注「陈巍学基因」公众号。

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
- `@Wangcy-rachel` - 王春阳
- `@zoe3251` - 舒晨阳

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）