---
date: 2023-04-18
comments: true
---
# 生信爱好者周刊（第 70 期）：多彩多姿的科学家

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/38451/3a4a002f-86aa-4c39-9460-3f0670ede19a.png)

[图片来源：成都露天音乐公园 —— 成都大运会闭幕式举办场地](https://github.com/openbiox/weekly/issues/1445 "图片来源：成都露天音乐公园 —— 成都大运会闭幕式举办场地")

## 本周话题：[多彩多姿的科学家](https://mp.weixin.qq.com/s/dW8HuU_swmUdA7CG0mZCAA)  

> 在华人普遍不懂科学的时期，把科学家描述成为只会研究的书呆子，而事实远非如此。世界上，兴趣广的科学家和学者很多，有些不仅是有学术以外的兴趣，而且很有特长，特长到具有在其他行业的超过一般水平的专长。

@ShixiangWang - 国内大众对于科学家存在一些 “非人” 的定义和理解，饶毅先生的文章提升了大众对于科学和从事科学工作的 “人” 的认知。称为 “科学家” 的这些人有血有肉，有爱好、有情愁。在评判科学作品和为人处事时，我们都应当存有批判存疑的观点。回顾我们自身，也应当同时善待自己的工作理想和生活理想。

## 生信研究


1、[Nat. Commun. | 基于深度度量学习对单细胞转录组学数据进行批次对齐](https://mp.weixin.qq.com/s/puhLdjg1zOslJRW7rPqIlA)


![](https://files.mdnice.com/user/38451/6d1c78c3-4eec-4667-abd7-43ad3f0633de.png)


本文介绍由中国人民大学统计学院应用统计学中心的张景肖和昌平实验室的李向杰共同通讯发表在 Nature Communications 的研究成果。大多数scRNA-seq算法都是经过专门设计的，首先去除批次效应，然后进行聚类，但这可能会遗漏一些罕见的细胞类型。为此，作者提出了一种深度度量学习模型scDML，scDML以初始聚类、批次内和批次间的最近邻信息为指导，消除scRNA-seq数据中的批次效应。对不同物种和组织的综合评估表明，scDML可以消除批次效应，提高聚类性能，准确恢复真实细胞类型，并且始终优于Seurat 3、scVI、Scanorama、BBKNN、Harmony等流行方法。最重要的是，scDML保留了原始数据中的少数细胞类型，并通过单独分析每个批次来发现难以提取的新细胞亚型。

- 文章链接：https://doi.org/10.1038/s41467-023-36635-5



2、[Cell 综述｜ 从模式到患者：临床机器学习在癌症诊断、预后和治疗方面的进展](https://mp.weixin.qq.com/s/2N5zDAo81y1LrV0SJ-h4KA)


![](https://files.mdnice.com/user/38451/f8f36ae9-ce84-41e6-8d87-3b7f9d978a94.png)


机器学习在临床肿瘤学中越来越常用，可以用于癌症的诊断、预测患者的治疗效果以及辅助制定治疗计划。本文综述了机器学习在临床肿瘤学工作流程中的最新应用，回顾了这些技术在医学成像和液态/实体肿瘤活检分子数据方面的应用，用于癌症的诊断、预后和治疗设计。本文讨论了开发针对成像和分子数据所带来的不同挑战的机器学习的关键考虑因素。最后，我们审查了被监管机构批准用于癌症相关患者使用的机器学习模型，并讨论了提高机器学习的临床实用性的方法。

- 论文链接：https://doi.org/10.1016/j.cell.2023.01.035


3、[Nat Commun | 基于全基因组基因型 - 血清蛋白质组分析，首次揭示中国汉族人群血液蛋白质组的遗传机制](https://mp.weixin.qq.com/s/3aDaNyJ4cpQwCGt5oLC33A)


![](https://files.mdnice.com/user/38451/f40da5f7-2f76-457f-9903-db64e1241de4.png)


国内多个研究团队合作，通过使用数据独立采集（DIA）质谱技术，首次在中国汉族人群中揭示了血液蛋白质组的遗传机制。此外，通过对顺式 pQTLs 和复杂性状 / 疾病进行共定位分析以及孟德尔随机化分析，发现了蛋白质对临床相关表型的假定影响，并提出了几种蛋白质在某些疾病中的因果作用和潜在治疗靶点。最后，研究团队证明了该数据集可能有助于解释东亚人和欧洲人之间疾病易感性的差异，并揭示了具有不同祖先的两个人群之间显著不同的肥胖诱导蛋白质组学特征，为东亚人和欧洲人在肥胖诱发糖尿病和冠状动脉疾病风险方面的不同易感性提供了见解。

- 论文链接：https://www.nature.com/articles/s41467-023-36491-3
- 论文代码：https://github.com/nutrition-westlake/Chinese_pQTL/blob/main/Data_analysis


4、[Genome Med | 亚欧人群结直肠癌GWAS研究](https://mp.weixin.qq.com/s/6vadpkFnOvuH7J7mB60tPg)


![](https://files.mdnice.com/user/38451/dfb03dbc-9008-4b89-b089-da14a238a53e.png)

南京医科大学研究团队及合作者对东亚和欧洲人群进行大规模基因组荟萃分析，构建一个多基因风险评分，用于评估结直肠癌的风险，并验证不同人群的健康生活方式对降低风险的影响。遗憾的是文章没有提供整合好的亚欧人群基因组和临床信息数据。
另外作者开发了一个网页工具数据，输入你的单核苷酸多态性（SNP）的信息，即可用上CRC-RPS模型预测你患结直肠癌的风险。

- 论文链接：https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9875451/
- CRC-RPS网页工具：http://njmu-edu.cn:3838/CRC-RPS/


## 博文资讯

5、[利用ChatPDF进行文献阅读](https://mp.weixin.qq.com/s/iqqURvyZYfl_ZFDBnNGxKw)


![](https://files.mdnice.com/user/38451/07f1b0c7-0aca-4198-9719-bf535e764ca6.png)

ChatPDF 是 openAI 最新开发的一款产品，负责阅读 PDF 文档，并且可以向它提问关于文档内容的问题。这篇文章简单试验了下利用ChatPDF进行SCI文献阅读，效果不错。

- 工具链接：https://www.chatpdf.com/


6、[带你了解全外显子测序](https://mp.weixin.qq.com/s/0OjfvRPG8GUsnEYAOLF5hQ)


![](https://files.mdnice.com/user/38451/f4515a35-b35a-4075-bb62-fd2136ab61ca.png)


文章简单描述了全外显子测序的的工作原理，主要步骤以及分析中值得注意的细节。对于不熟悉全外显子测序的朋友值得一读。


7、[专访沃尔夫奖得主何川：38岁那年开始了一个新领域](https://mp.weixin.qq.com/s/68yvsV3cX4lP5MooC-sDnQ)


![](https://files.mdnice.com/user/38451/90b5d3a4-c5b4-4a3b-88d0-b2f1d0182bf7.png)


近日，2023年度沃尔夫奖揭晓。美国芝加哥大学教授、华裔化学生物学家何川教授因其在“RNA表观遗传学领域”的开创性贡献，与来自日本东京大学的Hiroaki Suga以及来自美国斯克利普斯研究所的Jeffery W. Kelly分享了本届沃尔夫化学奖。始创于1976年的沃尔夫奖是国际最高学术大奖之一，每个奖项奖金为10万美元。据统计，约1/3的沃尔夫奖得主最后都获得了诺贝尔奖，因此沃尔夫奖又被称为“诺奖风向标”。何川是第9位获奖华人。



8、[2022年度“中国生物信息学十大进展”公布](https://mp.weixin.qq.com/s/eXsPxHpONLaRVY9iVszaDQ)


![](https://files.mdnice.com/user/38451/736381e4-1945-4f33-9ee7-c6045f95722e.png)


为推动我国生物信息学的学科发展和创新研究，充分展示和宣传我国生物信息学领域的重大研究成果，《基因组蛋白质组与生物信息学报》（*Genomics, Proteomics & Bioinformatics*, 简称GPB）组织评选了[**2018年度**](http://mp.weixin.qq.com/s?__biz=MzU1OTExMTAxNA==&mid=2247484136&idx=1&sn=894fe60c1994beb1d0fb45bb7068d5be&chksm=fc1d0ce1cb6a85f71a5e9d86f2db9e46159264105045baf6be0ecb12983186c250a312b825bd&scene=21#wechat_redirect)、[**2019年度**](http://mp.weixin.qq.com/s?__biz=MzU1OTExMTAxNA==&mid=2247484553&idx=1&sn=9a2e0021611d6397d8d70170d2a0ebd6&chksm=fc1d0a80cb6a839650de3d9539f76c570665780567a7e4bbadecf4c62847dcd63a83d3f3036a&scene=21#wechat_redirect)、[**2020年度**](http://mp.weixin.qq.com/s?__biz=MzU1OTExMTAxNA==&mid=2247485208&idx=1&sn=7830dcaf9ea5480ce58dd7e1caf1e19d&chksm=fc1d0911cb6a800702aff2f12a23bb27dfa0357bdf16cf103056fb6541dc778de6d902870650&scene=21#wechat_redirect)和[**2021年度**](http://mp.weixin.qq.com/s?__biz=MzU1OTExMTAxNA==&mid=2247487028&idx=1&sn=fa9f018edc7513e3601259977e6c1445&chksm=fc1d003dcb6a892b6f02b05ddf83b1d239cb9535cfb2fed9f45bf973fd6b7ac076a8596c5f77&scene=21#wechat_redirect)“中国生物信息学十大进展”。在此基础上，GPB继续组织2022年度评选活动，经过推荐、初选和复选程序，现公布2022年度“中国生物信息学十大进展”评选结果。

## 工具

9、[stevedore](https://github.com/richfitz/stevedore "stevedore")

stevedore是基于R 的 docker 客户端，当需要从 R 脚本或包控制外部进程时，使用 docker 从容器中与此进程交互可能会很有用。

- 链接：https://github.com/richfitz/stevedore



10、[GitHub520 | 让你“爱”上 GitHub](https://github.com/521xueweihan/GitHub520 "GitHub520 | 让你“爱”上 GitHub")


![](https://files.mdnice.com/user/38451/5ef8c8c7-0b4f-424b-99d5-c0a3c3e1ee2f.png)

让你“爱”上 GitHub的 GitHub 项目，解决访问时图裂、加载慢的问题。它的原理是通过修改本地 hosts 文件，将 GitHub 的域名映射到最快的 IP 地址上。它提供了多种使用方法，包括手动方式、自动方式和第三方软件方式。它还提供了一个文件和一个 JSON 格式的链接，可以获取到最新的 hosts 内容。

- github：https://github.com/521xueweihan/GitHub520



11、[PRIMUS ｜ 一个专门针对肿瘤单细胞转录组数据整合的算法](https://mp.weixin.qq.com/s/LUdwAoxmteQfs3g_8qmkfQ)


![](https://files.mdnice.com/user/38451/5c83c174-c22f-4dc5-87e1-3b7cbb5bfe2e.png)

PRIMUS是一种整体聚类方法，能够从 scRNA-seq 数据中识别表型细胞群，同时考虑日期来源(例如患者，样本，数据集)特定的组分以及技术噪声。PRIMUS 采用双线性泊松回归模型，将表达数据同时分解为明确的干扰因素（defined nuisance factors）、未定义的细胞表型及其相应的转录组学特征。

12、[enrichR | 在线富集分析](https://maayanlab.cloud/Enrichr/# "enrichR | 在线富集分析")


![](https://files.mdnice.com/user/38451/0f8facac-af4b-43b5-a320-56b59c2d0ec2.png)


EnrichR 是一个在线富集分析的工具，功能非常多样丰富，并有 API 提供编程语言接口。

- R 包文档：https://cran.r-project.org/web/packages/enrichR/vignettes/enrichR.html

## 资源
13、[生信算法书籍｜Genome-Scale Algorithm Design](http://www.genome-scale.info/index.html "生信算法书籍｜Genome-Scale Algorithm Design")


![](https://files.mdnice.com/user/38451/fec6107f-b08e-41f4-a201-c966d0952c2e.png)


芬兰赫尔辛基大学计算机系的[Veli Mäkinen](http://www.cs.helsinki.fi/u/vmakinen/ "Veli Mäkinen")教授以及他的两位博后Djamal Belazzougui和Fabio Cunial创作了这本书，许多知名高校采纳这部书作为教材。涵盖的主题从生物序列分析的基础（序列比对、隐马尔可夫模型）到经典索引结构（k-mer 索引、后缀数组和后缀树）、Burrows-Wheeler 索引、图形算法以及许多组学技术中用到的算法介绍，而且包括许多例子、算法可视化、问题和章末练习题。

14、[自带全套图表复现代码的单细胞文章](https://mp.weixin.qq.com/s/ixacC1zEBQ7jZnaHKMak1g)


![](https://files.mdnice.com/user/38451/434b699e-af95-4688-b20c-bd9767c18352.png)


专注收集和分享的 GitHub 项目，它提供了一些单细胞相关的论文和代码，让大家可以重现论文的结果和提升单细胞数据分析的能力。

- 资源链接：https://github.com/genecell/single-cell-papers-with-code


15、[awesome-bioie](https://github.com/caufieldjh/awesome-bioie "awesome-bioie")


![](https://files.mdnice.com/user/38451/26053513-56e1-4363-86e4-b032e8fa787a.png)


与生物医学信息提取（包括 BioNLP）相关的github精选资源列表，收集了很多生物医学文本数据处理相关的资源。

## 历史上的本周

- 第 30 期：[生信的核心修炼道路在哪里？](https://mp.weixin.qq.com/s/eW7lWb1zc54NhsUjsY1C7A)

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


![](https://files.mdnice.com/user/38451/be3fadf5-2122-4bfe-94f5-fabf800ca684.png)


（完）

