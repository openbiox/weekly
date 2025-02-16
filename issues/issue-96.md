---
date: 2023-10-22
comments: true
---
# 生信爱好者周刊（第 96 期）：如何取得杰出成就

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图
![image](https://github.com/openbiox/weekly/assets/108639312/29765c2f-acd5-4336-ab9e-f175d2d85a32)
来源：https://demo-zh.photoprism.app/library/browse

## 本周话题：[如何取得杰出成就](https://mp.weixin.qq.com/s/31iL-Kbs4KrqpgrERVRNzQ)
> 取得伟大成就的因素在字面上，数学上是因素，它们是：能力、兴趣、努力和运气。运气是我们无法左右的，所以可以忽略它；并且，如果确实想要取得伟大成就，我们可以假设每个人都很努力；所以问题归结为能力和兴趣 —— 我们能否找到一种工作，将自己的能力和兴趣结合起来，让新想法迸发？
> 我们有乐观的理由。有很多不同的方式来取得伟大成就，与此同时，还有更多的方式还未被发现。在所有这些不同类型的工作中，我们最适合的那一种可能是非常接近的匹配，可能是一个滑稽的接近的匹配 —— 这其中只有一个问题，我们要找到它，以及我们的能力和兴趣能带自己走多远 —— 我们只能通过尝试来回答这个问题。

`@JnanZhang`："一直走或跑同样的路线可能有所帮助，因为这给思考留出更多注意力。"

## 生信研究
1、[Genome Medicine | 包含空间信息的肝癌多区域测序新策略，揭示空间异质性和分子异质性关联](https://mp.weixin.qq.com/s/bZo2-OcRECbgTLmwMHzHEg)

![](https://files.mdnice.com/user/38661/10c4c1f3-f5c4-4bd0-abbd-38e85cbb8357.png)

上海交通大学附属仁济医院团队联合华中科技大学附属同济医院团队提出了一种空间定位抽样（SLS）策略，该策略可以在二维（2D）空间中记录每个采样点的坐标。研究团队开发了标准化多样性评分，可以减少抽样偏差。同时，研究团队还开发了一种计算方法用于定量检测这种异质性，从而直接比较不同特征的ITH程度。结果显示，SLS方法可以揭示空间和分子异质性之间的显著关联 。
- 论文链接：https://genomemedicine.biomedcentral.com/articles/10.1186/s13073-022-01143-6

2、[Science | 综述：空间组学技术概览与展望](https://mp.weixin.qq.com/s/PgTeRLbtBVUiCd2GiKeHuQ)

![](https://files.mdnice.com/user/38661/bede1adf-8f48-4343-9261-68b8eb9e7ac8.png)

空间组学是继单细胞测序技术之后的又一个生物技术研究热点，其能够弥补单细胞测序技术无法获取细胞空间分布信息的缺陷，本技术主要研究细胞在组织样品中的相对位置关系，用于揭示细胞空间分布关系对疾病的影响，主要检测蛋白质及其修饰或mRNA。虽然该领域在过去的5年里发展迅猛，但仍然面临一些挑战：进入技术壁垒，稳健性、实验设计及最佳分析实践不明确，以及缺乏标准化。该综述中，研究团队系统介绍了不同的空间组学技术，全面阐述了其优势及局限性，并给出了合理的建议。

- 论文链接：https://www.science.org/doi/10.1126/science.abq4964

3、[Cell | 张泽民课题组合作通过大规模整合生物信息分析揭示泛癌种自然杀伤细胞异质性](https://mp.weixin.qq.com/s/ileE8PvKrN63UnGFid1s9Q)

![](https://files.mdnice.com/user/38661/d853caaa-f8bd-4081-9975-8bfa1e7e7bdb.png)

这篇文章总结了张泽民课题组等在国际期刊Cell上发表的一项研究。研究通过整合来自14个数据集的1223个样本中的NK细胞scRNAseq数据,首次在泛癌水平上系统画出了NK细胞的亚群表型及功能多样性。研究发现NK细胞在不同肿瘤中的亚群组成有明显偏好性,不同组织类型的NK细胞亚类也有差异。同时识别出RGS1基因可作为非血液NK细胞的新标志物。文章还报道研究者在肿瘤组织中发现的一类功能障碍的NK细胞,称为TaNK细胞,其丰度与多种癌症的不良预后和免疫治疗耐药相关。总之,这项研究通过大规模整合分析,系统阐明了NK细胞在不同肿瘤中的异质性,为NK细胞治疗提供重要依据。

- 论文链接：https://authors.elsevier.com/sd/article/S0092-8674(23)00849-8

4、[Nature Communications | scMerge2 实现跨样本、跨条件单细胞数据高效整合分析](https://mp.weixin.qq.com/s/w0GD0apKEw5c7yteTc3ndg)

![](https://files.mdnice.com/user/38661/faf755b9-e8c3-4c22-bbb2-3cda67753266.png)
随着多样本、多条件单细胞研究的快速出现和用于集成数据集数量的增加，scMerge2能够解决细胞和研究的可扩展性以及产生分析准备数据（即调整表达矩阵）相关的挑战。scMerge2存在三个关键的创新点：（1）通过分层整合捕获不同研究之间的局部和整体差异；（2）通过伪bulk构造确保计算可扩展性；（3）在每个条件内进行伪复制来捕获来自多个条件的信号。

- 论文链接：https://doi.org/10.1038/s41467-023-39923-2



## 博文资讯
5、[GPT让你的RStudio如虎添翼](https://mp.weixin.qq.com/s/HMML8TQr0k2y9f7aQfhXHw)

![](https://files.mdnice.com/user/38661/447632cf-4fe2-4fc8-b91d-fc0e1b97b967.png)
介绍如何使用在RStudio里面使用gptstudio插件，从而使用Chat-GPT功能的文章。感兴趣的可以翻翻。

6、[WGCNA,all in 还是DEGs？](https://mp.weixin.qq.com/s/4kqja4KnG6yii_oEwtGB9g)


![](https://files.mdnice.com/user/38661/db1a7c2a-7d89-4a0f-bab6-ba22d29c79da.png)


WGCNA 和 DEG 是两种并行又可以相互整合的转录组分析方法，本文介绍后总结：在所有情况下，WGCNA + DEGs的表现明显优于DEGs + WGCNA。另外，DEGs+WGCNA会影响网络的结构并导致错误的结论。此外，这种方法的有效性从未被证实，官方也并不建议在WGCNA之前应用DEGs。


7、[一步实现文库制备和靶向富集！安捷伦携手Element Biosciences发布人全外显子测序简易工作流程](https://mp.weixin.qq.com/s/IDoKTZGz0FMF1qUgrFnNQw)

![](https://files.mdnice.com/user/38661/ea7982f8-bff2-44ff-8eb9-6f257f8520cc.png)

自2009年安捷伦推出全球第一款人全外显子产品至今，已走过十四载春秋。十四年来，安捷伦人全外显子产品在医学转化研究和临床应用中受到了全球用户的广泛信赖，PubMed相关引文数量连年攀升。2021年4月，安捷伦宣布首款基于机器学习探针设计方案的全外产品——人全外显子组V8（SureSelect Human All Exon V8）正式在中国上市，继续书写人全外显子靶向捕获技术新篇章。目前，安捷伦SureSelect文库制备和靶向富集试剂盒与元素生物科学（Element Biosciences, San Diego, CA）的AVITI测序系统在肿瘤变异分析等关键NGS应用上，实现了对单核苷酸多态性、结构和拷贝数变异、基因融合、插入和缺失的高灵敏度检测。

8、[太神奇了，网页上简简单单的5步完成转录组差异分析！！！](https://mp.weixin.qq.com/s/SbbIK8y3uSUKsPT3RkGj1Q)

![](https://files.mdnice.com/user/38661/dbc67895-6246-4f41-aaf2-2f5dce83862e.png)

本推文介绍了基于iDEP0.96进行的转录组差异分析，重点查看iDEP差异分析结果与R差异分析的区别，并查看两者PCA结果的差异。




## 工具

9、[ChatGPT-Next-Web](https://github.com/Yidadaa/ChatGPT-Next-Web "ChatGPT-Next-Web")

![](https://files.mdnice.com/user/38661/0b70032b-ee4e-4ed8-8e6b-f716429ea618.png)

ChatGPT-Next-Web可帮助用户一键免费部署跨平台私人 ChatGPT 应用，具有体积小、速度快等优势。

10、[PESSA ：一款基于通路富集基因集激活水平作为肿瘤预后分子标志物的预后分析可视化网页工具](https://mp.weixin.qq.com/s/BuUsPkMfLExkx14s-ilY1g)

![](https://files.mdnice.com/user/38661/550d9250-f08b-4f92-8fdf-3b3bf2c6735e.png)
这篇文章介绍了一款新的肿瘤预后分析在线工具PESSA。PESSA运用ssGSEA算法,根据预设基因集的整体表达水平来判断其在不同癌种中的激活程度,作为肿瘤预后分子标志物进行研究。

- 工具链接：https://smuonco.shinyapps.io/PESSA/

11、[CellAnn | 网页版的单细胞注释工具](https://github.com/Pinlyu3/CellAnn "CellAnn | 网页版的单细胞注释工具")


![](https://files.mdnice.com/user/38661/4570caa7-68c0-445e-95f0-158fa60005d3.png)


CellAnn是一个包含204个人类和191个小鼠单细胞数据集的细胞注释数据库。作者开发了一种从参考数据集到查询数据集的聚类对聚类对齐方法，可以实现将细胞标签从参考数据集转移到查询数据集，相比现有方法具有更高的准确性和可扩展性。

- 工具链接：https://www.cellann.io/
- 论文链接：https://doi.org/10.1093/bioinformatics/btad521


## 资源
12、[Interactive Bayesian Updating](https://github.com/GeostatsGuy/PythonNumericalDemos/blob/master/Interactive_Bayesian%20Updating.ipynb "Interactive Bayesian Updating")


![](https://files.mdnice.com/user/38661/87a1e2cf-ed3f-4d48-bcb7-84df435d4595.png)

这是一个 Notebook，介绍了贝叶斯更新的公式和实际基于 Python 的实现与可视化。

13、[RNAstructure](https://rna.urmc.rochester.edu/research.html "RNAstructure")

![](https://files.mdnice.com/user/38661/bf36ac24-8e7f-4d9a-b7cd-7492a01a3f81.png)

RNA是一种重要的生物分子。它被细胞用来表达基因和调节基因表达，它可以催化反应。RNA也是重要的药物靶标。Mathews实验室使用计算方法研究RNA，开发软件工具来预测RNA的结构，模拟构象灵活性，自动化从基因组序列到3D结构的RNA结构和功能建模。

14、[实用R语言技巧和快捷方式资源](https://github.com/nanxstats/r-base-shortcuts#r-base-shortcuts "实用R语言技巧和快捷方式资源")


![](https://files.mdnice.com/user/38661/21cb6af3-2fe4-4597-b838-adcfd45e1110.png)

本资源收集了一些鲜为人知但非常有用的R语言技巧和快捷方式的合集，从而于编写简洁而高效的R代码。



## 历史上的本周
- 第56期：[2022诺贝尔奖的点击化学或可作为单细胞多组学开发的有力工具](https://mp.weixin.qq.com/s/uhXPJXdYeUCgurozxIJpCw)

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


![](https://files.mdnice.com/user/38661/3bed10c3-dbfd-4f94-8880-e44f819e4964.png)


（完）

