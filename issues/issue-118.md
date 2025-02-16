---
date: 2024-04-07
comments: true
---
# 生信爱好者周刊（第 118 期）：滴血验癌

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://files.mdnice.com/user/34023/8825a8b9-2108-4277-a734-5e0f9df699d5.jpg)
来源：Copilot



## 本周话题：[滴血验癌 ](https://mp.weixin.qq.com/s/ugZJHKJS2AhR4eqBp_X7Ww)


![](https://files.mdnice.com/user/34023/5eb8aa5f-b890-4d86-9e8e-621525b3a4f1.png)

>循环肿瘤DNA (ctDNA)检测是一种通过抽血诊断和监测癌症的无创方法，即使在肿瘤位置未知的情况下也可以识别肿瘤DNA。但是血液中 ctDNA 的稀缺意味着它需要非常灵敏的方法来捕获和分析存在的ctDNA。该研究引入了两种类型的引发剂，它们可暂时降低 游离DNA (cfDNA) 清除率，从而增加血液中的 ctDNA 水平并增强液体活检的灵敏度。

`@NiEntropy` - 随着技术的不断进步，未来滴血验癌有望成为一种简单、快速且成本效益高的癌症筛查方法。这将极大地促进肿瘤的早期发现和治疗，避免肿瘤的转移和扩散，从而提高患者的生存率和生活质量。

## 生信研究

1、[Nature Reviews immunology | 迟洪波团队发表CRISPR筛选在免疫系统中的最新应用的综述](https://mp.weixin.qq.com/s/0Es85v-ZKDBkgUfNM5-ADA)
![](https://files.mdnice.com/user/5208/c6d15111-d891-4c4c-88ad-de33a8f72064.png)

**基于CRISPR的技术代表了生物医学科学的重大突破，因为它们为包括免疫学在内的各个领域的无偏筛选和功能基因组学提供了一个强大的平台。** 2022年12月8日，美国圣裘德儿童研究医院迟洪波团队在Nature Reviews Immunology（IF=109）在线发表题为“CRISPR screens for functional interrogation of immunity”的研究论文，该研究综述了用于免疫功能的CRISPR筛选。CRISPR筛选发现了先天和适应性免疫细胞中先前未知的细胞内驱动因素，用于免疫调节，以及介导细胞-细胞相互作用的细胞间调节因子。最近的单细胞CRISPR筛选平台将读数扩展到转录组，并能够推断基因调控网络，以获得更好的机制见解。CRISPR筛选还允许绘制遗传相互作用的图谱，以确定协同或缓解复杂免疫表型的基因。在这里，作者回顾了CRISPR技术的进展和新兴适应性，以推进基础的免疫学知识，并确定新的疾病靶点，用于感染、炎症和癌症的免疫治疗。
- 论文链接：https://www.nature.com/articles/s41577-022-00802-4


2、[bioRxiv | 基于生物银行数据的罕见变异研究](https://mp.weixin.qq.com/s/_WKrasJH10PieUQXXtEYnQ)



![](https://files.mdnice.com/user/34023/f91ddcc6-4487-4e19-b7bd-d6ba56c33b31.png)

由Weedon和同在埃克塞特大学的人类遗传学家Gareth Hawkes领导的研究小组对英国生物库数据中的前20万个完整基因组进行了挖掘，发现了29个罕见的DNA变体，这些变体与高达7厘米的身高差异有关；这些变体在以前的遗传研究中从未发现过。Weedon说，这项研究是对所有 50 万个基因组进行分析的试点，他计划进一步对基因组数据进行初步研究。最终，研究人员将需要50万个以上的全基因组来全面绘制罕见基因变异与健康之间的关联图。"我认为这是获得我们可能需要的数百万个样本的良好的下一步"。
- 论文链接：https://www.biorxiv.org/content/10.1101/2023.11.19.566520v1


3、[ Cancer Cell | 肝癌转移的时空多组学演化图谱](https://mp.weixin.qq.com/s/rmWgPFonC2Eka_9SoSu4wA)


![Pasted image 20240407193045](https://github.com/openbiox/weekly/assets/97931116/50efeec0-6697-4e29-a66b-1e2aaf1fbdde)


肝细胞癌（简称“肝癌”）是世界上最常见的恶性肿瘤之一，在我国尤为高发，每年新发病例和死亡病例均占全球近一半。论文通过整合多组学分析（包括基因组学、转录组学、单细胞RNA测序、空间转录组学和免疫组化），研究了182名患者的原发性和转移性肝细胞癌（HCC）的时空演化。研究揭示了转移性HCC中的高度肿瘤异质性、复杂的进化轨迹、亚克隆选择以及肿瘤微环境（如癌相关成纤维细胞和B细胞）在转移过程中的关键作用。

- 论文链接：https://www.cell.com/cancer-cell/abstract/S1535-6108(23)00401-4

4、[scQTLbase | 首个集成的人类单细胞 eQTL 数据库](https://mp.weixin.qq.com/s/xoHOdGX6HDffm6pYt8Xu6A)
![image](https://github.com/openbiox/weekly/assets/108639312/3807fa9e-c723-4464-893a-0d0a9d9a78ad)
这是第一个集成的人类 sc-eQTLs 门户，具有涵盖 57 种细胞类型和 95 种细胞状态的 304 个数据集。它包含约 1600 万个与细胞类型/状态基因表达显著相关的 SNP，以及来自 3333 种性状/疾病的约 69 万个与疾病相关的 sc-eQTL。此外，scQTLbase 还提供 sc-eQTL 搜索、UMAP 图中的基因表达可视化、基因组浏览器以及基于感兴趣的 GWAS 数据集的共定位可视化。scQTLbase 为 sc-eQTL 提供了一站式门户，将显著推进疾病易感基因的发现。

- 链接：http://bioinfo.szbl.ac.cn/scQTLbase/
- 论文连接：https://pubmed.ncbi.nlm.nih.gov/37791879/



## 博文资讯

5、[基因表达热图+GO富集分析词云图](https://mp.weixin.qq.com/s/87E8DzQ93wKFXyCTuEFR9w)

![](https://files.mdnice.com/user/5208/45559971-8fb0-4a87-8721-5b09579246b8.png)

 利用ComplexHeatmap包将GO富集的结果和热图结合起来


6、[生存分析机器学习模型解释的一揽子解决方案-survex包（一）基本用法](https://mp.weixin.qq.com/s/HqqcBEn0w5TvTXaoZ6IBew)
![image](https://github.com/openbiox/weekly/assets/108639312/c8aa2eb7-0de4-406f-a2c5-dd2f7f01c8d6)
这篇示例总结了 survex 包的功能，通过比较两种生存模型。一种是 Cox 比例风险模型，另一种是随机生存森林，展示了解释功能，并找出两种模型之间的差异和相似之处。
- github:https://github.com/ModelOriented/survex

7、[科普中国 | 内含子是干啥的](https://mp.weixin.qq.com/s/Jdzwc2rr0uC6Rmu9-blUBg)

![](https://files.mdnice.com/user/34023/1443b894-7e0f-4b9d-acf2-ee33a4b588a3.png)


所谓的“垃圾DNA”——内含子——在人类基因组中的作用和重要性。它回顾了基因和DNA的发现历史，解释了内含子是如何被发现的，以及它们在细胞功能和生物演化中的关键作用。文章还讨论了内含子的不同类型、它们的产生机制，以及它们对生物演化的意义。通过对内含子的深入分析，文章揭示了这些DNA序列并非无用，而是对生物体的生存和发展至关重要。基因组通过组合外显子和内含子，通过可变剪接的机制制造新的变异，生成新的调控模式或功能模块（酶、蛋白质、通路等）。

## 工具


8、[ggstats | ggplot2 绘制统计图拓展包](https://github.com/larmarange/ggstats/)

![](https://github.com/openbiox/weekly/assets/25057508/0f68b898-7eb3-4741-afd9-303092275de4)


9、[LIANA+ | 细胞间通信](https://github.com/saezlab/liana-py?tab=readme-ov-file)

![Pasted image 20240407194820](https://github.com/openbiox/weekly/assets/97931116/2f27756d-1e9a-4b63-af96-0447b5b83038)

基于Python，用于研究单细胞、空间解析和多模态组学数据中的细胞间通信的包。


- 教程：https://liana-py.readthedocs.io/en/latest/


10、[ToppGene Suite](https://toppgene.cchmc.org/)

![image](https://github.com/openbiox/weekly/assets/25057508/8b823893-ebe3-4815-8813-a24703407168)

基于功能注释和蛋白质相互作用网络的基因列表富集分析和候选基因优先级排序的一站式门户网站。引用上千，维护十多年了！

- 论文：https://academic.oup.com/nar/article/37/suppl_2/W305/1149611

11、[利用anndata包跟踪与注释数据](https://github.com/dynverse/anndata)
![](https://files.mdnice.com/user/5208/5d6dd2ea-6ae3-4a9a-8b24-530e802445c7.png)

- Github：https://github.com/dynverse/anndata
- Getting strated：https://anndata.dynverse.org/articles/getting_started.html



## 资源

12、[llamafile |  本地开源大语言模型](https://github.com/Mozilla-Ocho/llamafile)
![Pasted image 20240407195358](https://github.com/openbiox/weekly/assets/97931116/c4179a8c-21f3-406a-a6cd-246a7c069250)





13、[分享8个单细胞数据库的使用教程](https://mp.weixin.qq.com/s/g5ApsFjkZ41oqhZSe3p5ng)
![image](https://github.com/openbiox/weekly/assets/108639312/527a35b5-a2d5-4dd6-b119-b86619fad588)


## 历史上的本周
- 第 77 期：[科研成果被截胡抢发](https://mp.weixin.qq.com/s/hxcmKVLdcJkwi4CfQXBc3Q)

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

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）
