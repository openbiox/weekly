---
date: 2023-09-17
comments: true
---
# 生信爱好者周刊（第 93 期）：来自妈妈的Y染色体

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/43254/f918c7b0-8a0a-460a-80c7-7771b0c3fc78.png)

## 本周话题：来自妈妈的Y染色体

> 在人类繁殖方面，传统认知以为只有拥有来自父亲的Y染色体才能发育成男性，性染色体为XY的为男性，Swyer综合征患者无生育能力。但是，医学上却有这样的现实案例：一名发育为正常女性，性染色体为XY 的母亲经历了自发性青春期、月经初潮，拥有卵巢且月经规律，经历了两次妊娠，并最终生下一名性染色体同样为XY但性腺完全发育不全的女儿。

@kongjianyang：性别不仅只是XX或者XY，应该认识到人群中每个人的性别有差异，不应强加定型。应该尊重每个人的性取向和性别自我认同选择。

## 生信研究

1、[《科学》重磅：首次实现监测多种神经元间实时毫秒级互动](https://mp.weixin.qq.com/s/yf9PsXdrOXPn1OrJ2ZHQSg)

![](https://github.com/openbiox/weekly/assets/108639312/36aae834-1dfd-4ae1-aabc-7990ab37be0b)

来自耶鲁大学The John B. Pierce实验室的Madhuvanthi Kannan、Ganesh Vasan、Vincent A. Pieribone和斯坦福大学的Mark J. Schnitzer，在先前开发的绿色和红色荧光GEVI（Ace-mNeon和VARNAM，在细胞膜电位去极化时荧光减弱）的基础上[2,，进一步开发了灵敏度更高的下一代GEVI（Ace-mNeon2和VARNAM2），以及对应的具有相反响应极性的荧光GEVI——pAce和pAceR（在细胞膜电位去极化时荧光增强），相关结果发表于《科学》杂志。
该研究中的新一代GEVI可在同一视野下对超过50个细胞（放电频率达0.4-1kHz）进行电活动监测，且在果蝇中的连续监测时间长达30分钟。
利用这一电压成像系统，理论上可同时记录多达四个不同的神经元类型，为首个可对不同类型神经元进行实时、亚毫秒级监测的技术。

- 论文链接：https://doi.org/10.1126/science.abm8797

2、[Nature | 张宁/张泽民/朱继业合作揭示肝癌免疫微环境亚型和中性粒细胞异质性](https://mp.weixin.qq.com/s/dOzJrYa6lj7iJjMq4xw_AA)

![](https://github.com/openbiox/weekly/assets/13445428/12bf3721-9db1-4cfc-bc95-943d3df0c666)

由张宁、张泽民和朱继业等研究人员团队在Nature杂志上发表的一项关于肝癌免疫微环境异质性研究。研究人员采用单细胞转录组技术,对189例肝癌标本和8只小鼠标本进行了全面检测,首次定义出肝癌免疫微环境的五种亚型。他们还发现了肿瘤相关中性粒细胞中11个新的亚群,并鉴定了其中两个亚群CCL4+ TAN和PD-L1+ TAN可能通过不同机制促进肿瘤生长。利用小鼠肝癌模型,他们进一步证实了中性粒细胞在肿瘤发展中的作用,中性粒细胞清除能延缓肿瘤生长。这项研究通过单细胞测序技术系统揭示了肝癌免疫微环境异质性,证实了中性粒细胞在肝癌中的促肿瘤作用,为将来开发针对肿瘤相关中性粒细胞的新型免疫治疗提供了理论依据。

- 论文链接：https://www.nature.com/articles/s41586-022-05400-x


3、[Nature Genetics | 新型表观组测序法助力临床诊断](https://mp.weixin.qq.com/s/fUVxIm9yCB3merHnRBIZEA)

![](https://github.com/openbiox/weekly/assets/25057508/dab4d28e-72e0-44d3-9f9e-e4623240abb9)

基因调控元件的系统鉴定和功能研究对于了解人类疾病机制十分重要。在这项研究中，研究人员基于靶向纳米孔测序法，富集测序长达115 kb的DNA分子片段，克服了二代测序覆盖和读取长度的限制。同时，研究团队结合NOMe-seq法，在广泛的发育、免疫等位点上对遗传变异、DNA甲基化和染色质可及性进行分期，评估基因组中元素的相互依赖性，捕获单分子动力学，加深对基因调控元件的认识，并对H19/IGF2上游的印记控制区的修饰状态与其转录水平进行分析。

- 论文链接：https://www.nature.com/articles/s41588-022-01188-8


## 博文资讯


4、[靶向肿瘤的上市小分子药物—受体酪氨酸激酶抑制剂](https://mp.weixin.qq.com/s/RPViz5FRGslNH_kMtgU8xQ)

![](https://github.com/openbiox/weekly/assets/108639312/344a39cc-dca8-4d21-8654-39195e740a2e)

自2001年美国食品药品监督管理局(FDA)批准首个酪氨酸激酶抑制剂伊马替尼(imatinib)进入市场以来，越来越多的小分子靶向药物被开发用于治疗恶性肿瘤。截至2020年12月，已有89种小分子靶向抗肿瘤药物获得美国FDA和中国国家药品监督管理局(NMPA)的批准。尽管小分子靶向抗癌药物取得了很大的进展，但仍面临着反应率低、耐药等诸多挑战。

5、[可以用ChatGPT搜索论文了](https://mp.weixin.qq.com/s/1ZxzisPkPx1vOenInil3rg)

![](https://github.com/openbiox/weekly/assets/13445428/b4a90204-0793-4f9b-97db-22f6041ade6e)

文章介绍了利用OpenAI技术进行语义搜索的论文搜索网站arXiv Xplorer。它利用OpenAI的embedding技术，将arXiv上的论文标题和摘要进行向量嵌入,实现论文的语义搜索。用户只需要输入关键词或论文URL,就可以找到与之最相关的论文。亲测好用！

- arXiv Xplorer地址：https://arxivxplorer.com/

6、[MSKCC 尚待解决的肿瘤基因组检测临床应用问题](https://mp.weixin.qq.com/s/RS7RMRszEfRJd9dxR1ixyA)

![](https://github.com/openbiox/weekly/assets/25057508/384241c6-d3b6-420d-8c15-8aa2892c6733)

熊的这篇文章总结了MSK前瞻性临床队列 MSK-IMPACT和MSK-ACCESS样本量突破10万之后，MSKCC的分子肿瘤中心 (Center for Molecular Oncology, CMO) 主任 David Solit 对当前临检问题的相关看法，或许对读者有启发意义。

1. cfDNA能否取代肿瘤组织进行检测，如果可以的话是针对哪些病人，什么时候cfDNA和肿瘤组织检测又是互补的呢？
2. 更全面的全外显子组/全基因组测序在临床中的应用是什么？
3. 与其配套其它技术平台，比如全转录组测序和蛋白质组学的的应用又是什么？
4. 哪些人应该进行胚系检测？胚系突变不仅可以为遗传性癌症风险提供信息，而且还可以成为药物反应的生物标志物。
5. 怎样才能提高肿瘤/胚系检测的可及性？如果需要进行基因组分析来确定最有效的治疗方法，无法获得这种技术的患者很可能就不能得到最好的治疗。
6. 如何才能扩大精准肿瘤治疗的影响？最重要的是需要更好的药物，仍然有太多「无法治疗」的靶点，比如RB1、TP53、STK11、NF1和多数RAS突变。我们也需要更多具有选择性/低毒性的药物以便进行更精准的联合治疗。
7. 我们还需要更低的检测价格（这是采用全基因组测序的主要障碍）以及更好的报告注释。
8. 还能从目前的panel测序中得出哪些更丰富的信息：大片段拷贝数；杂合性缺失评估；靶向突变克隆性评估；更好的signatures分析来为突变解读提供信息。

## 工具

7、[Cancer Genomics Cloud：癌症基因组的云平台](https://www.cancergenomicscloud.org/ "Cancer Genomics Cloud：癌症基因组的云平台")

![](https://github.com/openbiox/weekly/assets/13445428/d4b2602a-1eff-453d-86a9-6c8a4867ffd4)

由美国国立癌症研究所（NCI）和美国国家基因组研究所（NHGRI）共同创建的网站Cancer Genomics Cloud，旨在为癌症研究人员提供一个平台，共享和分析癌症基因组数据。

- 网站链接：https://www.cancergenomicscloud.org/

8、[Chat Thing AI](https://chatthing.ai/ "Chat Thing AI")

![](https://github.com/openbiox/weekly/assets/13445428/715fcb67-9775-4750-99a6-ef7a8f0e79e6)

chatthing.ai 是一个聊天机器人平台，允许用户创建、管理和使用聊天机器人。它提供拖放式界面、多语言支持、机器学习和集成等功能，可用于各种目的，包括客户服务、教育和娱乐。

- 网站：https://chatthing.ai/


9、[ggquiver](https://github.com/mitchelloharawild/ggquiver "ggquiver")

![](https://github.com/openbiox/weekly/assets/108639312/8a91c00f-195f-4449-855d-62ce0b4160a4)
`ggquiver`是`ggplot2`的扩展，提供矢量、可视化的箭头图。

## 资源

10、[港大单细胞培训公开课](https://mp.weixin.qq.com/s/5avLw8HmO5cVP3RVZjMGjQ)

<img width="798" alt="image" src="https://github.com/openbiox/weekly/assets/25057508/b3e720e2-4eb1-4bd9-94fc-13682aedc8f6">

资料地址：

- https://statbiomed.github.io/HKU-single-cell-workshop/
- https://statbiomed.github.io/SingleCell-Workshop-2021/

> 整体上是完备和有益的资料，但部分内容可能过时了，需要读者自行甄别。

11、[Sandbox.bio：Interactive bioinformatics tutorials](https://sandbox.bio/ "Sandbox.bio：Interactive bioinformatics tutorials")

![](https://github.com/openbiox/weekly/assets/13445428/e288ca7c-c8c5-4276-90cf-94fa277a717d)

Sandbox.bio 是一个生物信息学沙盒平台，允许用户在安全隔离的环境中运行生物信息学实验。它提供各种工具和资源，包括数据库、算法和工具包，可用于各种生物信息学任务，例如数据分析、模型构建和机器学习。

- 网站：https://sandbox.bio/

12、[OpenAI Cookbook](https://github.com/openai/openai-cookbook "OpenAI Cookbook")

![](https://github.com/openbiox/weekly/assets/13445428/da1797fe-cd90-40e0-b889-2bf86bc29e13)

openai-cookbook是一个存储库,内容包括使用OpenAI API的代码示例和使用指南。

- 工具地址：https://github.com/openai/openai-cookbook

## 历史上的本周

[生信爱好者周刊（第 53 期）：为什么现在的中国大学生普遍焦虑内卷？](https://mp.weixin.qq.com/s/psS2TWhPxllwDAz4BIP0OA)

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

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://files.mdnice.com/user/38661/17812364-5134-43ba-92cf-0be6aff405e8.png)

（完）

