---
date: 2024-04-14
comments: true
---
# 生信爱好者周刊（第 119 期）：科学家首次改造了真核生物超过50%的基因组

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图


![](https://files.mdnice.com/user/37191/fc73bfd9-4d23-45cf-b202-33a1c48d4328.jpg)


## 本周话题：[科学家首次改造了真核生物超过50%的基因组](https://mp.weixin.qq.com/s/Wl_ru4wHRvxWnyD3mXNnyQ)

>据《自然》新闻（Nature news）消息，2023年11月8日，合成酵母基因组计划（Sc2.0）的研究人员在《细胞 》（Cell，论文1，论文2）和《细胞基因组学》（Cell Genomics）上发表了3篇研究，表示制造出了一种基因组中超过50%的DNA序列均是合成的酿酒酵母菌株。酿酒酵母的遗传信息存储在16条染色体上，而新菌株的6.5条染色体都是在实验室中编辑并合成的，此外还有一条染色体是由经过编辑的DNA片段拼接而来。

## 生信研究

1、 [Nature Communications | 数字病理＋人工智能：四亿细胞图谱解析乳腺癌生态型](https://mp.weixin.qq.com/s/huGPdbd1ZZPw-A0pEsoCNg)

![](https://files.mdnice.com/user/37191/e91ccf8f-1b82-43b2-b4b3-a7145df35234.png)


2023年10月25日，智慧医疗研究院徐军教授团队与复旦大学附属肿瘤医院邵志敏教授团队合作的论文《单细胞形态和拓扑图谱揭示了乳腺癌的生态系统多样性》的论文在英国《自然》旗下《自然·通讯》杂志在线发表。在国家自然科学基金重大研究计划的支持下，由复旦大学乳腺外科与病理科以及智慧医疗研究院人工智能等多学科团队深度合作，融合机器学习、数学图论、数字图像处理等多学科知识，首创肿瘤单细胞形态与拓扑学分析算法（sc-MTOP），绘制了包含4.1亿个细胞的乳腺癌单细胞图谱，全面刻画了乳腺癌生态系统多样性，为数字病理与人工智能赋能乳腺癌精准诊疗提供了全新的视角。

- 论文链接：https://www.nature.com/articles/s41467-023-42504-y

2、 [Cell System | 系统地评估21种用于疾病基因发现的分子网络](https://mp.weixin.qq.com/s/RgSzJRVL56GcOh1EKUBUcw)

![](https://files.mdnice.com/user/37191/f05caea6-cf68-4586-90ae-69553d637d41.png)

基因网络在规模和数量上都在迅速增长，这就提出了哪个网络最适合特定应用的问题。在本篇文章中，研究团队评估了21个人类全基因组相互作用网络恢复通过文献整理、基因表达谱或全基因组关联研究确定的446种疾病基因集的能力。虽然所有网络都有一定的恢复疾病基因的能力，但他们观察到STRING、ConsensusPathDB和GIANT网络的性能范围很广，总体性能最好。一个普遍的趋势是，性能随网络规模的大小而变化，这表明新的交互发现目前超过了误报的有害影响。修正大小后，研究人员发现DIP网络提供了最高的效率(每次交互的价值)。在这些结果的基础上，研究团队创建了一个既高效又高性能的简约复合网络。这项工作为人类疾病研究中分子网络的选择提供了一个基准。

- 论文链接：https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5920724/


3、[Science | 空间组学新方法解析淋巴细胞克隆架构](https://mp.weixin.qq.com/s/PPzRFRRzhfxx72Jo2qPAfg)`

![](https://files.mdnice.com/user/37191/a6577429-415b-4180-9e5a-060476104625.png)


瑞典卡罗林斯卡学院(Karolinska Institutet) Jeffrey E. Mold等研究人员开发Spatial VDJ（spatial transcriptomics for variable, diversity, and joining sequences），在空间转录组的基础上，通过富集T细胞与B细胞抗原受体序列，更灵敏捕捉全长（具体指完整的CDR3 (complementarity determining region 3)序列）的TCR与BCR，从而在正常免疫组织以及肿瘤组织同时解析T、B细胞克隆分布（长读长版本）、空间转录组以及病理图片。

- 论文链接 1： C. Engblom et al., “Spatial transcriptomics of B cell and T cell receptors reveals lymphocyte clonal dynamics,” Science (80-. )., vol. 382, no. 6675, Dec. 2023, doi: 10.1126/science.adf8486.
- 论文链接 2： P. L. Ståhl et al., “Visualization and analysis of gene expression in tissue sections by spatial transcriptomics,”Science (80-. )., vol. 353, no. 6294, pp. 78–82, Jul. 2016, doi: 10.1126/science.aaf2403.


4、[Genome Biology | CREaTor: 零样本学习预测细胞类型特异的基因表达顺式调控模式](https://mp.weixin.qq.com/s/_n-LLN1t0iXhrRzzt6YyXw)


![](https://files.mdnice.com/user/37191/da437f73-8620-4274-b9e4-83b6d81d04cb.png)


发表在Genome Biology上的这个CREaTor（Cis-Regulatory Element auto Translator）层次深度学习模型通过监督学习任务，利用靶基因近邻的顺式调控元件序列和功能基因组学特征，预测靶基因在特定细胞中的表达水平。该模型在ENCODE项目的19个人类组织和细胞系的近2百万数据对上进行了训练，并在未见过的细胞类型中进行了准确的基因表达预测。CREaTor的零样本学习能力和跨细胞类型建模能力使其成为研究顺式调控规律的有力工具，可用于系统性预测各类细胞的基因调控模式。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-03103-8

## 博文资讯

5、[谷歌大杀器终于来了，最大规模Gemini震撼发布：真超GPT4，三大版本，手机直接可用](https://mp.weixin.qq.com/s/q8IEFgNwPxrqTd1V4UGRVw)

![](https://files.mdnice.com/user/37191/3688f738-9dae-4096-aa3a-c8c737e6bbe1.png)

迄今为止规模最大，能力最强的谷歌大模型来了。

2023年 12 月 6 日，谷歌 CEO 桑达尔・皮查伊官宣 Gemini 1.0 版正式上线。

这次发布的 Gemini 大模型是原生多模态大模型，是谷歌大模型新时代的第一步，它包括三种量级：能力最强的 Gemini Ultra，适用于多任务的 Gemini Pro 以及适用于特定任务和端侧的 Gemini Nano。

6、[英国生物样本库（UKB）向全球开放50万人全基因组测序数据](https://mp.weixin.qq.com/s/wNZv8zl_OnHg1UpK3gTcZg)


![](https://files.mdnice.com/user/37191/7918c9f7-f268-4a48-bfde-81435ffa7161.png)


近日，英国生物样本库（UKB）表示已经向全球经批准的研究人员开放了其50万参与者的全基因组测序（WGS）数据。这是有史以来最雄心勃勃的同类项目代表了迄今为止世界上最大的单一测序数据集。该数据集有潜力为主要常见病的病因提供新见解，并指导潜在治疗靶点的选择。

这一大规模的WGS数据，结合UKB现有数据和生物样本，将带来非凡的生物医学创新，包括更有针对性的药物发现和开发、发现数千种致病的非编码基因变异、加速精准医疗、理解疾病的生物学基础。 


7、[密码子的探索发现过程](https://mp.weixin.qq.com/s/Q_RxDXtaDne8KKLBwRlHCA)


![](https://files.mdnice.com/user/37191/f710e129-f3b7-469d-bba8-9dd619c02d07.png)


本文解读和介绍 1961 年发表的经典论文，作者是著名的Francis Crick及其同事们，这篇文章一共解决了四个重要问题：密码子由三个碱基组成、密码子不重叠、序列起始于特定密码子、密码子表是简并的。

喜欢推文作者的最后的点评：

>在那个人们对遗传信息究竟如何存储都还知之甚少的年代，PCR实验和自动测序仪都尚未诞生，更别提如今各种纷繁复杂、强大无比的生物分子精确操作技术，就在这样的“原始”条件下，他们延续了1953年DNA双螺旋结构发现所带来的激动人心，通过整合当时不同实验室的探索成果，结合理论推导，并设计巧妙的实验加以验证，最终提出了至今仍然成立的密码子学说。

- 论文链接：https://www.nature.com/articles/1921227a0

8、[2023年，CRISPR基因编辑领域10大研究，张锋实验室遥遥领先](https://mp.weixin.qq.com/s/8x9LsseY6MY0LqwYOCIGoA)

![](https://files.mdnice.com/user/37191/d1772080-a66a-470a-ae80-a37567b1cf6f.png)

本推文总结了2023年CRISPR基因编辑领域的十大研究进展，这些进展涵盖了新型CRISPR系统的开发、改造、治疗应用和安全性研究等多个方向。


## 工具

9、[HMF Tools | 全基因组、靶向DNA和全转录组分析套件](https://github.com/hartwigmedical/hmftools)

![](https://files.mdnice.com/user/37191/47ff5c1c-e13e-4ba5-a054-08fe4a28726e.png)

这里是哈特维格医疗基金会（Hartwig Medical Foundation）提供的一套工具集，用于分析基因组学数据。这些工具被用于该基金会的全基因组、靶向DNA和全转录组分析流程中。


10、[A Crash Course in Kubernetes](https://blog.bytebytego.com/p/a-crash-course-in-kubernetes?utm_source=substack&utm_medium=email)


![](https://files.mdnice.com/user/37191/9b1c2ea3-d4bb-41f8-ad1f-64377987715f.png)


Kubernetes 是云服务的杀手级应用，本文介绍了它的核心概念与结构。



11、[Photo to Anime](https://photo-to-anime.com/en)


![](https://files.mdnice.com/user/37191/1f71c895-d662-4ee6-b373-2ee73c6bc5f5.png)


Photo to Anime是一款AI驱动的在线动漫创作软件，可以毫不费力地将图片转换为迷人的卡通风格艺术，无需艺术或编码技能。


## 资源

12、 [advanced-shiny](https://github.com/daattali/advanced-shiny)


这份文件包含了作者经常使用或很多人询问的各种shiny技巧的集合。每个文件夹都包含一个完整的功能性Shiny应用程序，这些应用程序演示了如何在Shiny中执行非琐碎的任务。

13、[获取生信数据存档库源信息]()

以下是一些经典生信数据存档库及其源信息

- [GEOfetch](https://geofetch.databio.org/en/latest/)

- [bioconductor package GEOquery](https://bioconductor.org/packages/release/bioc/html/GEOquery.html)

- [ffq: Fetch metadata information from databases.](https://github.com/pachterlab/ffq)

- [pysradb:a python package to query next-generation sequencing metadata and data from NCBI sequence read archive.](https://github.com/saketkc/pysradb?ck_subscriber_id=2105433013&utm_source=convertkit&utm_medium=email&utm_campaign=CITEseq%20tutorials%20and%20how%20to%20download%20GEO%20data/metadata%20-%2012504128)

- [GEOparse](https://github.com/guma44/GEOparse)

- [MetaSRA: normalized sample-specific metadata for the Sequence Read Archive
SRA-explorer This tool aims to make datasets within the Sequence Read Archive more accessible.](https://www.biorxiv.org/content/10.1101/090506v1?ck_subscriber_id=2105433013&utm_source=convertkit&utm_medium=email&utm_campaign=CITEseq%20tutorials%20and%20how%20to%20download%20GEO%20data/metadata%20-%2012504128)

- [fetchngs](https://github.com/nf-core/fetchngs)

- [fastq-dl](https://github.com/rpetit3/fastq-dl)

14、[Sketchfab | 3D和增强现实（AR）在线平台](https://sketchfab.com/)

<img width="1091" alt="image" src="https://github.com/openbiox/weekly/assets/45822462/08dd5ac7-86c0-4ae7-a755-05d1acce3208">

Sketchfab 是一个3D和增强现实（AR）在线平台，它提供了一系列的工具和服务，让3D内容创作者、开发者和爱好者能够管理、分发、协作、展示和交易3D模型和AR体验。



## 历史上的本周
- 2023 [生信爱好者周刊（第 78 期）霸凌是平庸科学家登上顶峰的手段](https://mp.weixin.qq.com/s/9nndftVUzYx6_LkBpx4b1g)

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