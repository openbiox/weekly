
# 生信爱好者周刊（第 77 期）：科研成果被截胡抢发

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions "「生信周刊讨论区」")

## 封面图


![](https://files.mdnice.com/user/34023/097d5611-1257-4979-ab60-a2262f24ba3a.png)


来源：Ling Li 海星骨架

## 本周话题：[科研成果被截胡抢发](https://mp.weixin.qq.com/s/Xj-c6t1WNcWkzTiwWtQ3Ag)

> 一篇关于科研剽窃的新闻报道，讲述了一名博士生的研究成果被博士后抢先发表的事件，以及导师为其讨回公道的过程。

`@NiEntropy`：科研剽窃是指在科学研究中，未经原作者同意或未明确引用，擅自使用他人的创意、数据、方法、结论等，作为自己的研究成果发表或申请专利的行为。博士后剽窃博士生的研究成果，不仅侵犯了博士生的劳动成果和创新精神，也违背了导师和同事之间的信任和合作，造成了严重的心理伤害和学术纠纷。这种行为是不可容忍的，应该受到严厉的惩罚和谴责。

## 生信研究

1、[Briefings in Bioinformatics | 最大的生物医学可视化疾病—靶标知识图谱平台eTSN](https://mp.weixin.qq.com/s/3Al7zdEu43zTbTPG1WHu4g)


![](https://files.mdnice.com/user/34023/9d1adac5-a2f5-4714-aa20-599a3229e1ef.png)


e-TSN(the explorer for Target Significance and Novelty,)是由华东理工大学药学院上海市新药设计重点实验李诗良/李洪林团队搭建的一个基于生物医学文本挖掘的可视化疾病—靶标知识图谱平台。该平台对200多万篇生物医学全文文献中疾病-靶标关系数据进行提取，生成与药物-靶标-疾病相关的知识图谱，通过可视化表示，可为疾病提供潜在靶标谱，为靶标提供疾病谱，并关联已有和在研药物数据库，为寻找合适的靶点这一难点问题提供了实用的解决方案，同时也为数据驱动的靶点临床决策和新药研发立项提供了线索和理论依据。

- 论文链接：https://doi.org/10.1093/bib/bbac465
- 平台链接：http://www.lilab-ecust.cn/etsn/

2、[Nature Medicine | 多染色深度学习模型可用于结直肠癌的预后和预测](https://mp.weixin.qq.com/s/8OLiHmCU2rA1uzs8TOQRVg)


![](https://files.mdnice.com/user/34023/6b6095e1-f1ab-43f8-a5c6-fce08c5a3fc2.png)


本文构建了一个可利用人工智能确定1000多名患者IS（AImmunoscore, AIS）的多染色深度学习模型（MSDLM），该模型具有很强的预后能力，优于其他基于临床、分子和免疫细胞的参数，还可用于预测直肠癌患者对新辅助治疗的反应，是一种能够为临床医生提供基于肿瘤免疫微环境的有价值的决策工具。多染色组合模型中表现最好的组合是CD4、CD8、CD20和CD68，定义 “无复发”的最重要的免疫细胞亚型依次是CD8+T细胞和B细胞，而对“复发”分类贡献最大的是CD68+单核-巨噬细胞，这些发现与在CRC和其他实体癌中的已知作用完全一致。此外，之前的工作表明IS不仅可用于预后，它在直肠癌的新辅助治疗中也具有预测价值。

- 论文链接：https://www.nature.com/articles/s41591-022-02134-1

3、[Bioinformatics | 宏基因组物种组成分析软件KMCP](https://mp.weixin.qq.com/s/ixB8bcqyAWaaWBusFGjwtQ)


![](https://files.mdnice.com/user/34023/ce3900b0-73eb-43fc-8d9e-6d9548c0a960.png)


 日益增加的微生物参考基因组促进了宏基因组物种组成分析准确性的提高，同时也对宏基因组物种组成分析软件的建库效率、数据库大小、分析时间带来了严峻的挑战。此外，大多数软件主要关注细菌、古菌和真菌，而缺少对病毒群落的关注。研究团队推出了KMCP，一个新的基于k-mer的宏基因组物种组成分析软件。它将参考基因组分割成多个相同大小的区块，并将每个区块的k-mer存储在修改和改进的COBS索引中用于序列的快速搜索。KMCP通过结合k-mer相似性和基因组覆盖信息来减少基于k-mer的宏基因组分类和物种组成分析软件的高假阳性。基于模拟和真实数据的基准测试显示，KMCP虽然比其它软件运行时间更长，但是KMCP不仅能在原核生物和病毒群落上准确地分析物种组成，还能在低深度临床样本中提供高可信度的病原微生物检测结果。

- 论文链接：https://doi.org/10.1093/bioinformatics/btac845

4、[Nat Genet发表大规模多组学研究结果，揭示上百种结直肠癌相关新遗传风险因素](https://mp.weixin.qq.com/s/AooeZ1iuDXvJJ0NNmBFqgQ)


![](https://files.mdnice.com/user/34023/f26e1f4d-ef51-4969-a03d-96b9ca640e4a.png)


由弗雷德·哈钦森癌症研究中心的研究人员对10万余例结直肠癌（Colorectal cancer，CRC）病例、15万余例欧洲和东亚血统的对照组进行了全基因组关联研究（GWAS）荟萃分析，确定了100多个与CRC密切相关的新遗传风险因素。这项研究是迄今为止对结直肠癌常见遗传风险因素进行的最大、最全面的研究。该研究成果可以帮助临床医生更准确地预测、确定患CRC风险较高的患者，以便其能够接受早期筛查，对患者实施更加精准的治疗方案。

- 论文链接：https://www.nature.com/articles/s41588-022-01222-9

## 博文资讯

5、[自上而下的因果关系：数学结构与观察者](https://mp.weixin.qq.com/s/kM8IVwCyuKLsfACVWiG_sA)


![](https://files.mdnice.com/user/34023/73316f2d-1db2-4ab2-b13f-3ec4e5894d24.png)


这篇文章讨论了自上而下因果关系的两个方面，乔治·埃利斯（George Ellis，著名物理学家与复杂系统学者）对这一复杂概念进行了令人信服的解释。这篇文章很大程度上同意埃利斯的总体信息，但可能对某些细节的理解略有不同。作者是在广泛的经验主义背景下阐明了这一信息。

- 文章链接：https://link.springer.com/chapter/10.1007/978-3-030-71899-2_3

6、[Nature Reviews Cancer：未来10年肿瘤精准治疗的6个未解之谜](https://mp.weixin.qq.com/s/roamMnYHbfLhlE-y2CmvAA)


![](https://files.mdnice.com/user/34023/7a506b68-58db-4250-a444-d4b1b3d4fbfd.png)


思考问题的熊解读 6 大未解之谜：

- 治疗是否和时间有关？
- 有害突变何时致病？
- 突变是否具有组织偏好？
- 应该靶向哪个肿瘤克隆？
- 肿瘤科医生应该多了解他们的患者？
- 何时进行免疫治疗？

7、[徐瑞华教授：2022十大消化道肿瘤临床研究进展、待解决问题](https://mp.weixin.qq.com/s/W_GLBSBYhrpAw0AY6ZI6Sw)


![](https://files.mdnice.com/user/34023/36ddb8bf-eaf3-4908-bbb4-0a5f0385dfd0.png)


本文由中山大学肿瘤防治中心内科徐瑞华教授团队撰文，文中回顾了食管癌、胃癌和结直肠癌治疗领域的进展及有待解决的问题。

8、[2022单细胞关键意见领袖的关键文章](https://mp.weixin.qq.com/s/Kcte6O-8RCnxXKrJT7jwHg)


![](https://files.mdnice.com/user/34023/f060adab-9842-4fea-b3b0-63166785c95f.png)


生活的细节，靠近了看仿佛散落海滩的贝壳，七零八落，当我们把视角拉长一些，这一颗颗串起来，就是一串串有迹可循的珍珠项链，不可方物。
当我们把2022以春夏秋冬这样铺展开来，历历在目的往事，以某种逻辑连结，2022不再只是一个数字，有了故事也有了温度。2022年单细胞课题怎么样？单细胞技术接下来会往哪个方向发展？更多组学？更高通量？让我们跟随单细胞大佬2022年发表的文章，看未来已来。

## 工具

9、[imgpalr｜从任何图片中创建调色板](https://github.com/leonawicz/imgpalr "imgpalr｜从任何图片中创建调色板")


![](https://files.mdnice.com/user/34023/ef4ae946-ae4d-4f32-bd6f-811a67aa371c.png)


imgpalr包可以很容易地从图像文件创建调色板。

- 工具链接：https://github.com/leonawicz/imgpalr

10、[monocle3 | 单细胞轨迹分析](https://github.com/cole-trapnell-lab/monocle3 "monocle3 | 单细胞轨迹分析")


![](https://files.mdnice.com/user/34023/a7c19412-8843-4f94-a058-cac55eb0f737.png)


Monocle 3是一个用于分析单细胞基因表达的工具包 ， 可以执行三种主要类型的分析：

1.聚类、分类和计数细胞。单细胞 RNA-Seq 实验可让您发现新的（可能罕见的）亚型 细胞。2.构建单细胞轨迹。在开发中， 疾病，在整个生命过程中，细胞从一种状态过渡到另一种状态。3.差异表达分析。表征新细胞 类型和状态始于与其他更好理解的细胞的比较。

- 工具链接：https://github.com/cole-trapnell-lab/monocle3

11、[clustergrammer | 矩阵可视化交互工具](https://github.com/MaayanLab/clustergrammer "clustergrammer | 矩阵可视化交互工具")


![](https://files.mdnice.com/user/34023/bcc20e3f-7c5d-4365-b2bd-cc801fb931fc.png)


Clustergrammer是一个基于Web的工具，用于将高维数据（例如矩阵）可视化为交互式和可共享的分层集群热图。Clustergrammer的前端是使用D3.js构建的，它的后端则由Python构建。Clustergrammer 产生高度交互式的可视化，能够直观地探索高维数据，并具有多种生物学特异性特征，以促进基因级生物数据的探索。

- 工具链接：https://github.com/MaayanLab/clustergrammer

12、[EnhancedVolcano | 火山图](https://github.com/kevinblighe/EnhancedVolcano "EnhancedVolcano | 火山图")


![](https://files.mdnice.com/user/34023/c59eada5-e9df-4558-b395-9885017cd69a.png)


火山图是一种常见的用于可视化差异表达基因的方法。EnhancedVolcano是一个高度可定制化的R包。采用其默认模式也可以快速做出美观的火山图。

- 工具链接：https://github.com/kevinblighe/EnhancedVolcano

## 资源

13、[孟德尔随机，十大文章汇总](https://mp.weixin.qq.com/s/-A4YULhlfV4Q3K8jBsN2Og)

![](https://files.mdnice.com/user/34023/caef68ae-f56a-4a32-9dc5-773351980047.png)


孟德尔随机化研究已成为当下又一个发文热点，本文总结了从今年年初开始关于这个方向的十多篇文章，为入门学习该领域的研究提供了既往文献基础。

14、[prompt 写作指南](https://boostpixels.com/guide "prompt 写作指南")


![](https://files.mdnice.com/user/34023/76611466-4bb3-4b5c-bae7-9ef6e82560d5.png)


这是一篇针对BoostPixels引擎的生成式AI的prompt教程，具有参考价值。

- 资源链接：https://boostpixels.com/guide

## 历史上的本周

第 36 期：[“费钱、费力、不费脑”是中国该提倡的科研吗？](https://mp.weixin.qq.com/s/RL_V-GsJM6wF9xTcNcvdZA)

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


![](https://files.mdnice.com/user/34023/e80e4a48-f85e-44c9-b6a2-243692f2647c.png)


（完）
