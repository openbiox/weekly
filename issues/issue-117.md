---
date: 2024-03-31
comments: true
---
# 生信爱好者周刊（第 117 期）：半个世纪的争论: 分子演化论中的中性论/选择论之争

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图


![](https://files.mdnice.com/user/37191/c4cca2b9-ba20-45ef-bcc3-317ae45489d2.png)




## 本周话题：[半个世纪的争论: 分子演化论中的中性论/选择论之争](https://mp.weixin.qq.com/s/qYxWJmUJl1Til9tC0m_6WQ)

>基因组演化是主要由自然选择驱动，还是主要反映随机的非适应性过程，可以说是分子演化领域的核心问题。>自从Kimura和Ohta首次提出中性和近中性理论以来，这两个理论就一直是分子演化领域的焦点。这场争论在>20世纪末达到了高潮，在21世纪初仍然十分明显。50 多年前提出的中性和近中性理论，直到现在科学家们
>仍在讨论分子演化的作用力及其相对重要性。这场争论最初集中在种内多态性的数量和替代率的恒定性上，后>来逐渐扩大和成熟，现在已成为一系列主题和问题的基础。中性论者/选择论者之争构建了这一领域，并影响
>着分子演化科学家的研究构想


## 生信研究

1、 [Cancer Discov | 基于AI模型预测肿瘤何时会对化疗产生耐药性](https://mp.weixin.qq.com/s/Mmot45umeFNK8IMmKIeg1w)
![image](https://github.com/openbiox/weekly/assets/108639312/dd756566-61d9-44a2-b629-108e8a471ad5)

研究团队报道了如何利用机器学习算法来解决癌症研究面临的最大挑战之一：预测肿瘤何时会对化疗产生耐药性。研究人员采用深度学习算法开发了一套预测模型，阐明了癌症突变如何影响癌症对常见RSi药物的反应，促进了多种药物的预测和机制解释。通过对肿瘤细胞的初步研究确定了41个分子组件（molecular assemblies），这些分子组件整合了数百个基因的改变，可以用于准确的药物反应预测。这些分子组件涵盖了在转录、修复、细胞周期检查点和生长信号传导中的作用，其中有30个通过功能丧失基因筛查来调节药物敏感性或复制重启。验证研究显示，该模型可用于预测宫颈癌患者的顺铂治疗反应。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-03081-x

2、 [Cancer Discovery丨大规模泛癌细胞系筛选确定可行有效的药物组合](https://mp.weixin.qq.com/s/WF4gDh0iS1bNq7j0lwTvAQ)

![](https://github.com/openbiox/weekly/assets/25057508/efb5ec06-0577-4328-8011-a47054972c39)

研究团队展示了迄今为止发布的最大的癌症药物组合筛选，其中包含750多个细胞系中109种药物（来自阿斯利康公司抗肿瘤小分子组合）组合的7×7浓度响应矩阵，并辅以多组学预测因子的响应和“新兴”组合生物标志物的识别。研究团队优先考虑新的发现，以优化临床转化能力，并通过实验验证新的组合假设。

- 论文链接：https://doi.org/10.1158/2159-8290.CD-23-0388


3、 [Cell丨中性粒细胞的抗肿瘤潜能：抗原提呈](https://mp.weixin.qq.com/s/nwMJTRYkBAiyX1ldjuT3Gw)

<img width="533" alt="Pasted image 20240330210519" src="https://github.com/openbiox/weekly/assets/97931116/51962312-81e9-4d43-a5d7-67ad1e09f0f3">

中性粒细胞是最先对病原体做出反应的免疫细胞，这篇论文通过分析225个样本中的单细胞中性粒细胞转录组，揭示了中性粒细胞在17种癌症中呈现出的10种不同状态，包括炎症、血管生成和抗原呈递等。特别地，**抗原呈递**与大多数癌症的良好生存率相关，可通过**亮氨酸代谢**和随后的组蛋白H3K27乙酰化修饰来诱导MHC-II 基因表达。这些中性粒细胞还能进一步激发特异性和非特异性T细胞反应。研究不仅展示了中性粒细胞在癌症中的多样性，还提出了如抗原呈递中性粒细胞输送等治疗机会。

-  论文链接：https://pubmed.ncbi.nlm.nih.gov/38447573/


4、 [Nature | 利用单细胞和空间转录组揭示肺腺癌最早的细胞起源](https://mp.weixin.qq.com/s/iQ6Wc-Vk03zFgvaBIjOWSg)


![](https://files.mdnice.com/user/37191/d25b0a5a-2223-4d29-a3d0-ea601b55c302.png)


2024年2月28日，美国德克萨斯大学MD安德森癌症中心的王凌华教授和Humam Kadara教授的合作团队在Nature在线发表了题为 An atlas of epithelial cell states and plasticity in lung adenocarcinoma的文章。这项研究的主要成果是在早期肺腺癌组织和癌旁区域发现了一群携带KRAS致癌基因突变的，KRT8表达阳性的肺泡中间态细胞。通过和Jichao Chen教授合作，该团队在基因工程小鼠模型中对肺泡上皮细胞进行了谱系标记和追踪，并证实了KACs最终可转化为肺腺癌细胞。这项研究不仅为开发针对早期肺腺癌的检测和预防策略提供了新的启示，也为推动在最早阶段检测甚至阻断肺腺癌的发展开辟了新的研究方向。

- 论文链接：https://www.nature.com/articles/s41586-024-07113-9#change-history

## 博文资讯

5、[孟德尔随机化理论知识一站式学习](https://mp.weixin.qq.com/s/qzZNXn2OoaYS7jotCSMAnQ)
![1711680514103](https://github.com/openbiox/weekly/assets/108639312/d8100749-dd71-487b-9ab0-d1d75d853a1e)

本文是根据首都医科大学的王友信教授的课程所做的笔记，介绍了应用孟德尔随机化方法推断暴露因素与健康结局的因果关系。

6、[seurat v5直播，一键完成五种数据整合：harmony，CCA，RPCA,FastMNN,scVI](https://mp.weixin.qq.com/s/ZSOnvQ49F6mGz5856gfO1Q)

<img width="935" alt="image" src="https://github.com/openbiox/weekly/assets/45822462/8324cef4-2e91-4655-8a33-21684a9071f6">

这篇推文介绍了seurat v5版本的新功能，它能够一键完成五种不同的单细胞数据整合方法：Harmony、CCA、RPCA、FastMNN和scVI。作者提到了如何将seurat v4对象转换为v5对象，以便在同一个环境中同时使用v4和v5的对象，同时展示了CCA、RPCA和Harmony三种整合方法的结果。


7、 [Science news | 人类免疫组计划](https://mp.weixin.qq.com/s/x34koTBH5msKiEKtq5MVqQ)
![Pasted image 20240330210810](https://github.com/openbiox/weekly/assets/97931116/f496a777-7975-4333-91ff-ed8e20b9b446)


人类免疫组计划（Human Immunome Project，HIP）是一个正在进行中的宏伟计划，旨在构建迄今最大、最全面的免疫学数据库。
- 免疫组计划官网：https://www.humanimmunomeproject.org/

8、 [保姆级教程：R语言绝美云雨图！！](https://mp.weixin.qq.com/s/ZQrGisHKIiALZDxw5cEJRA)

![](https://files.mdnice.com/user/37191/bd7cee19-8bd6-4f83-a9c5-0f9547568f7a.png)


箱线图和小提琴图想必大家都不陌生，毕竟是显示数据分布最常用的图表了。

今天要给各位推荐一种将小提琴图、箱线图、抖动散点图三合一的高颜值组合图表！因其形状像正在下雨的云，顾名思义为云雨图！！

## 工具

9、[工具 | 谷歌学术搜索 PDF 阅读器](https://chromewebstore.google.com/detail/google-%E5%AD%A6%E6%9C%AF%E6%90%9C%E7%B4%A2-pdf-%E9%98%85%E8%AF%BB%E5%99%A8/dahenjhkoodjbpjheillcadbppiidmhp?utm_campaign=launch&utm_medium=blog&utm_source=scholar.googleblog.com&pli=1 "工具 | 谷歌学术搜索 PDF 阅读器")
![image](https://github.com/openbiox/weekly/assets/108639312/e76279a3-6bc3-4cae-a9e4-5f1cace37a78)
一个提升论文阅读体验的Chrome 插件。安装学术搜索阅读器后，就能在 Chrome 中以全新方式查看所有网站上的 PDF 文件。


10、[LLM | 大语言模型可视化网址](https://bbycroft.net/llm "LLM | 大语言模型可视化网址")

<img width="1133" alt="image" src="https://github.com/openbiox/weekly/assets/45822462/badb852e-6cfe-4afd-b7ba-1130d4276a16">

LLM Visualization这个网站主要提供了一个关于LLM（大型语言模型）的三维动画可视化。通过这个可视化，用户可能能够以直观的方式理解大型语言模型的结构和工作原理。


11、[VISION - 单细胞RNA-seq的signature分析和可视化](https://github.com/YosefLab/VISION "VISION - 单细胞RNA-seq的signature分析和可视化")

![](https://github.com/openbiox/weekly/assets/25057508/271c381e-f91f-4795-830d-bf80848c7321)

VISION通过选择描述细胞之间协调变异的基因特征，帮助解释单细胞RNA-seq（scRNA-seq）数据。虽然该软件只需要表达式矩阵和signature库（在线数据库中可用），但它也旨在通过利用预计算的维度缩小、轨迹推断或聚类结果来集成到现有的scRNA-seq分析管道中。此分析结果通过动态网络应用程序提供，该应用程序可以与合作者共享，而无需他们安装任何额外的软件。

## 资源

12、 [生物信息学中的 50 个常见问题](https://mp.weixin.qq.com/s/YTZvnEYmZNaOt1hr4rGLPg)


![](https://files.mdnice.com/user/37191/5e52c55b-2f53-45df-bef4-b8a5192adf2c.png)

13、[9 种权威的实验protocol查询网站](https://mp.weixin.qq.com/s/Y2sBFE9wIAVa_OXCKNu7WQ)

![](https://github.com/openbiox/weekly/assets/25057508/42ab9c2f-42f3-415f-8bc4-2940ed33321c)

14、[生信猿的Docker入门课1](https://mp.weixin.qq.com/s/FSD9_6w6U_2bitdD85N9Kw)

![image](https://github.com/openbiox/weekly/assets/45822462/58408890-e42e-4001-9029-2fe4b98eb52c)

本资源要面向生物信息学领域的读者，介绍了Docker技术的基本概念、优势、安全性问题以及如何在不同操作系统上安装和使用Docker。在最后文章提供了一些参考资料和书籍推荐，供读者进一步学习和了解Docker技术。
本文汇总了 9 种权威的实验protocol查询平台，有助于读者搜索和学习。


## 历史上的本周
- 2023 [生信爱好者周刊（第 76 期）人生是一个长板问题](https://mp.weixin.qq.com/s/8whkjFwCr2i_rvdR2-_K7Q)

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


![](https://files.mdnice.com/user/37191/484e56e7-6d4d-41a3-a70c-53e240bb2dcd.png)


（完）