---
date: 2024-03-03
comments: true
---

# 生信爱好者周刊（第 113 期）：空间分析技术照亮肿瘤微环境研究

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

>欢迎大家来到龙年的第一期。为更合理和及时地处理每期的内容，我们将招募 3-4 位新的成员加入，如果大家对本周刊感兴趣，请将个人简介和想法发送到 <w_shixiang@163.com>。

## 封面图


![](https://files.mdnice.com/user/4331/0f5c3d10-4383-4446-a704-844b7afae50e.png)


图片来源：https://nanostring.com/blog/why-spatial-biology/

## 本周话题：[空间分析技术照亮肿瘤微环境研究](https://mp.weixin.qq.com/s/J2H5lDjzMiOrC2_SbrzKug)

>肿瘤微环境（TME）由许多不同的细胞和无细胞成分组成，它们共同驱动肿瘤的生长、侵袭、转移和对治疗的反应。肿瘤微环境的微观系统在介导肿瘤复杂现象（例如肿瘤进展和对治疗的反应）方面起着至关重要的作用。空间解析方法的最新技术进步有望捕捉TME的复杂性。这些方法可以检测组织标本中多种蛋白质和转录本的表达，同时保留组织结构。近年来，技术发展提高了空间和分子分辨率，使我们对肿瘤微环境的理解越来越清晰。

`ShixiangWang` - 新的测序检测和方法技术在不断革新基础研究的方向和领域。在肿瘤异质性方面，微环境的空间解析将为肿瘤观察带来新的视角，但个人愈加感受到一种矛盾，即基础研究的高精度和临床应用的可及性可能在演变成一种越行越远的联系。

## 生信研究

1、[Science | 单细胞多组学技术揭示三维基因组与基因表达的关系](https://mp.weixin.qq.com/s/KlFbDy9wFEYhLHfw7PrrXw)

![](https://files.mdnice.com/user/4331/d9e54270-3f4c-4cd1-8246-5edf5f7faf27.png)

本文报道了一种新型单细胞多组学技术HiRES（Hi-C and RNA-seq employed simultaneously），首次基于测序方法实现了在单细胞水平对转录组和三维基因组的同时检测。

- 论文链接：https://www.science.org/doi/10.1126/science.adg3797

2、[Nat Biotechnol | 多模态深度学习新模型联合高通量计算遗传筛选新方法，可准确预测不同细胞类型的染色质构象](https://mp.weixin.qq.com/s/XLbmOJahBIt-xLQj7K5xrQ)


![](https://files.mdnice.com/user/4331/e84f6d63-b849-4469-b467-1b7fb2df9abf.png)

研究团队开发了新型多模态深度学习模型C.Origami，以预测特定细胞类型的染色质构象，并基于遗传筛选原理提出了全新的高通量计算遗传筛选方法（in silico genetic screening，ISGS），可鉴定细胞类型特异性功能基因组元件，助力发现新的染色质构象调控机理。在正常和重排基因组中，C.Origami均实现了对细胞类型特异性染色质组织的精准预测，表明其可作为未来3D染色质组织研究的高通量平台选择。

- 论文链接：https://www.nature.com/articles/s41587-022-01612-8


3、[Nat Biotechnol | 从宏基因组文库中高效检索目标序列的新方法](https://mp.weixin.qq.com/s/Lv_-YWYt0DSvM_4i62x6Zg)


![](https://files.mdnice.com/user/4331/33eac4f4-2aac-4f78-9544-3ab37587240c.png)

宏基因组是环境微生物群落中所有微生物物种基因组的集合，且包含数千万个独特的克隆，数量庞大，但绝大部分微生物的不可培养性使微生物多样性的研究以及开发利用受到了限制。一直以来，从大型宏基因组文库中靶向检索克隆使用的是基于多步稀释和聚合酶链式反应(PCR)的筛选方法，此方法费时费力。虽然CRISPR/Cas技术已被用于检索克隆目标基因序列，但还未被验证能从复杂的宏基因组库中检索序列。该文章提出了一种适用于研究宏基因组微生物多样性的新方法——利用核酸酶缺陷型 Cas9 (dCas9)构建的反选择中断回路( CRISPR counter-selection interruption circuit，CCIC)，该方法将PacBio HiFi测序与CRISPRi技术结合，可从复杂文库中高效检索目标克隆，加速基因组信息的挖掘，为研究宏基因组微生物多样性提供了更多的可能性，并有望扩展到合成生物学等重要领域。

- 论文链接：https://doi.org/10.1038/s41587-022-01531-8

4、[Nature Cancer | 基于WES数据的新分析方法PhylogicNDT，可推断缺乏癌前病变癌症的早期遗传进展](https://mp.weixin.qq.com/s/AN4Yujc9rrOzmQx6z_g2Zw)

![](https://files.mdnice.com/user/4331/11fa20ae-4b70-4fd5-a3fb-bf322e8c0feb.png)

该研究通过分析原发性肿瘤全外显子组测序（WES）数据，来推断癌症早期遗传进展。研究团队开发了一种名为“PhylogicNDT”的分析方法，这是一套集成工具，使用连贯的概率框架重建克隆架构和遗传事件顺序。通过PhylogicNDT，研究团队验证了人类乳头瘤病毒阴性（HPV-）头颈部鳞状细胞癌（HSCC）的遗传进展，并对缺乏恶性癌前组织的HPV+ HSCC进行了评估，发现了未知的遗传进展，确定了早期驱动因素。综上，PhylogicNDT可以建立先前未知、无法获得癌前组织等癌症的早期遗传进展，有助癌症早期检测和预测的实验模型及方法的开发。

- 论文链接：https://www.nature.com/articles/s43018-023-00533-y
- 代码链接：https://github.com/broadinstitute/PhylogicNDT


## 博文资讯

5、[跨肿瘤医护全流程的分子检测正进入临床实践，且每年增速20%以上](https://mp.weixin.qq.com/s/hsxaEs0iKzrgX2k_PAaFKw)


![](https://files.mdnice.com/user/4331/9583f80d-398c-47d9-9a05-218713ef62c0.png)


ARK Invest推出了一年一度的BIG IDEAS 2023颠覆式创新14大主题，涵盖了人工智能、数字货币、电动车、卫星轨道空间等领域，其中也包括我们感兴趣的精准疗法和分子诊断两个领域。由于收集、测序和理解生物数据的成本正在急剧下降，多组学技术为研究、治疗和健康提供了前所未有的 DNA、RNA、蛋白质和健康数据的访问权限，解锁了不同的应用场景，包括针对癌症、罕见疾病和慢性病的新型精准疗法，包括可编程生物学的能力，包括设计和合成具有跨行业应用的新型生物结构，尤其是农业和食品生产。

而在DNA 测序方面，特别需要指出的是，深度神经网络可帮助实现更准确的长读长 DNA 测序。比如，Pacbio和谷歌在这方面的合作，先是将神经网络算法用于读取基因组数据，最近又直接在长读长测序仪中构建AI专用计算硬件，实现低于1000美元的长读长基因组。整体上，神经网络已经将长读长 DNA 测序的错误率降低了59%。

6、[如何对单细胞中的基因表达进行相关性分析？](https://divingintogeneticsandgenomics.rbind.io/post/how-to-do-gene-correlation-for-single-cell-rnaseq-data-part-1/)


![](https://files.mdnice.com/user/4331/a9395adf-865f-4859-9c71-c73b816e7e9a.png)

本文提供了对单细胞RNA测序数据进行基因相关性分析的教程。通过具体实例探讨了CD3D和CD4基因之间的相关性，并通过散点图等可视化展示了分析结果。

- 推文后续：https://divingintogeneticsandgenomics.com/post/how-to-do-gene-correlation-for-single-cell-rnaseq-data-part-2-using-meta-cell/

7、[深度学习需要掌握的 13 个概率分布](https://mp.weixin.qq.com/s/k5QSELqB0bbn96fZ1OHeuQ)



![](https://files.mdnice.com/user/4331/859ff23f-b37c-4b5d-ad25-02388ceaed2f.png)



Github上一个对深度学习的概率分布的总结。

- Github: https://github.com/graykode/distribution-is-all-you-needgithub.com

8、[跟着iMeta学做图｜ggplot2绘制相关性分析线面组合热图](https://mp.weixin.qq.com/s/I_XvmoURCxp_pRb0mwLtvA)


![](https://files.mdnice.com/user/4331/c67dd78a-4b00-4f2a-8b78-661f7cb8b04c.png)


相关性热图 (Correlation Heatmap) 的使用在微生物组研究中非常普遍，尤其是线面组合的相关性热图，其中的相关性热图通常表示环境因子间的Pearson相关系数，连线则表示物种组成与各环境因子的Mantel相关性。本文将讲解和探讨如何基于ggplot2绘制线面组合的相关性热图。

9、[贝叶斯 RStan 包入门教程](https://mp.weixin.qq.com/s/Kklq2TpajCBrCUUIagckIw)


![](https://files.mdnice.com/user/4331/5974a784-90a3-4010-9811-39441d661cb6.png)

这是文章作者在学习 stan 时发现的一篇相关文章，很适合初学者。

## 工具

10、[Reference Extractor | 从带有 Zotero 和 Mendeley 的 Word 中提取参考文献](https://rintze.zelle.me/ref-extractor/)

![](https://files.mdnice.com/user/4331/79d7bee0-cc2c-42c0-bd55-f4bcacdf224c.png)

Reference Extractor是一个免费的用于从Microsoft Word和LibreOffice文档中提取Zotero和Mendeley参考文献的工具。这个工具可以将引用保存为CSL JSON、BibTeX或RIS格式，或者以APA风格呈现的参考文献列表。

11、[AutoGPT！GitHub3.6万+标星，解决复杂任务全程无需人类插手](https://mp.weixin.qq.com/s/hWzCknuzX3Kmf9eIyGrrUQ)

![](https://files.mdnice.com/user/4331/21f39966-d19c-4b84-a934-640fb1cdedf1.png)

AutoGPT的横空出世，一举将AI进程推向了新高度——自主人工智能。

- Github链接：https://github.com/Significant-Gravitas/AutoGPT


12、[fastq-dl | 从ENA和SRA下载FASTQ数据的工具](https://github.com/rpetit3/fastq-dl)


![](https://files.mdnice.com/user/4331/537380a6-9d34-4267-9a8a-4cad6b494371.png)

fastq-dl 是可以从ENA或SRA数据下载FASTQ数据的开源工具。它通过输入ENA/SRA相关文件编号（如研究、样本、实验等编号），查询ENA以确定相关数据，并为每个结果下载FASTQ文件。该工具支持多种运行合并选项，并提供了详细的使用说明和安装方法，旨在简化研究人员从这些公共数据库中获取数据的过程。

13、[ClusterMQ ｜发送R函数调用作为集群作业](https://github.com/mschubert/clustermq)

```r
# load the library and create a simple function
library(clustermq)
fx = function(x) x * 2

# queue the function call on your scheduler
Q(fx, x=1:3, n_jobs=1)
# list(2,4,6)
```

支持LSF、SGE、Slurm、PBS/Torque。

14、[BISCUT-py3 ｜ Breakpoint Identification of Significant Cancer Undiscovered Targets](https://github.com/beroukhim-lab/BISCUT-py3)

![](https://files.mdnice.com/user/4331/105bccf6-4b11-43fc-91a1-8dd63484059f.png)

GISTIC2 作者开发的新型变异检测算法。

- 关联文章：[Nature | 基于超1万例癌症样本分析，揭示染色体非整倍体如何驱动癌症进展](https://mp.weixin.qq.com/s/VuqwgDxnaOHpZji3uV33UQ)

15、[无道词典](https://github.com/ChestnutHeng/Wudao-dict)


![](https://files.mdnice.com/user/4331/01d2086f-879d-4b79-b743-963635b0970a.png)

无道词典，是一个简洁优雅的有道词典命令行版本。支持英汉互查的功能，包含释义、词组、例句等有助于学习的内容。


## 资源

16、[大模型物种进化图](https://mp.weixin.qq.com/s/DKk6UydkLN2URDDAXYaffQ)

![](https://files.mdnice.com/user/4331/c497e0ec-6d84-4c64-90d4-3f3553d0e16c.png)

- 论文：https://arxiv.org/abs/2304.13712

17、[17 个免费托管后端代码的网站工具](https://mp.weixin.qq.com/s/AbOTLIBUF_tKgrhYqb0B-Q)

![](https://files.mdnice.com/user/4331/d9eece58-03bb-460f-bf2f-98b3ed4cb8ee.png)

本文将分享17 个热门站点，这些站点能够免费托管用户的后端代码。

18、[scRNAseq analysis notes from Ming Tang](https://github.com/crazyhottommy/scRNAseq-analysis-notes)

![](https://files.mdnice.com/user/4331/93d0aedf-9a30-4cb6-8176-184ce89c12ae.png)


## 历史上的本周

- 第 72 期：[把时间当作朋友](https://mp.weixin.qq.com/s/RS-aMsBim61rCzGV7Y0agw)

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

