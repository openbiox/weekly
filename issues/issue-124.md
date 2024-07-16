---
date: 2023-05-26
comments: true
---
# 生信爱好者周刊（第 124 期）：《Cell》癌症研究五十年：十大要点总结

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/37191/803879dc-55e5-49e7-99d4-ecbe8f23c8ac.jpg)

## 本周话题：[《Cell》癌症研究五十年：十大要点总结](https://mp.weixin.qq.com/s/FUoTFUmKoaX7l1M6cL2tOA)

>《细胞》杂志近期发表标题为“五十年来癌症研究的进展”，强调了过去五十年中癌症研究领域的重大进步，着重说明了我们对癌症的理解和治疗方式是如何演变的

## 生信研究

1. [Cell | 崔亚/李蔚团队利用33万全基因组测序数据揭示人类跨族群串联重复序列扩张的遗传奥秘](https://mp.weixin.qq.com/s/_2IJjAzowi2bx9IeeCEu1g)

![](https://files.mdnice.com/user/37191/2581c044-a349-433f-a8e1-e5db3b01ca1d.png)

TR-gnomAD项目开创性地构建了一个涵盖338,963个人类全基因组测序样本的串联重复扩展参考图谱，其中39.5%为非欧洲血统样本，体现了重要的遗传多样性。该研究利用先进的生物信息学工具如ExpansionHunter和GangSTR，准确识别和分类串联重复，并开发了创新的串联重复差异分数来量化不同人群间的差异。TR-gnomAD不仅为遗传病的诊断和解读提供了宝贵的资源，揭示了特定串联重复扩展与疾病的关联，还强调了在全球多样化背景下研究人类基因组变异的重要性。此项目标志着精准医学发展的重要里程碑，为未来串联重复和遗传疾病的研究奠定了研究基础。

- 论文链接：
https://www.cell.com/cell/fulltext/S0092-8674(24)00252-6

2. [Science | 维生素D通过改变肠道细菌，提高抗癌免疫力](https://mp.weixin.qq.com/s/GYZxCBz0MLGAErBsleqTSQ)

![](https://files.mdnice.com/user/37191/50a05a7b-7065-4204-96ec-4992bb96a4fc.png)


2024年4月25日《Science》上发表了重磅研究，维生素D可以通过改变肠道微生物群，提高身体对癌症的免疫力。研究团队发现，富含维生素D的饮食可以促进一种名为脆弱拟杆菌的肠道细菌生长，从而增强小鼠抑制肿瘤生长的能力，并提高免疫检查点抑制剂的疗效。该研究揭示了维生素D、肠道微生物和癌症免疫之间的重要联系，为预防和治疗癌症提供了新的思路。研究人员分析了大规模人群数据，发现较低的维生素D水平与较高的癌症风险相关，而较高的维生素D水平则与更好的癌症免疫治疗反应和更高的生存率相关。这一发现强调了维生素D通过肠道细菌影响免疫系统的重要性，为通过饮食干预改善癌症治疗效果提供了令人兴奋的可能性。

- 论文链接：
https://www.science.org/doi/10.1126/science.adh7954

3. [bioRxiv | 第一个完全由AI生成的CRISPR-Cas基因编辑器！](https://mp.weixin.qq.com/s/yjOg6Kw-sCKnpUto1sKc5w)

![](https://github.com/openbiox/weekly/assets/42094537/856dece9-8e04-4cda-80c7-7786be76c4b6)

人工智能蛋白质设计公司Profluent.bio于近日发布了一项突破性成果——全球首个由AI完全设计的CRISPR-Cas基因编辑器OpenCRISPR-1。该编辑器在人类基因组上展现出与常用的SpCas9相当的编辑效率和更高的特异性，但序列却有超过400个突变的差异。Profluent通过在大规模CRISPR数据集上训练大语言模型，极大拓展了已知CRISPR家族的多样性，并优化了生成的核酸酶及其配套sgRNA的活性。这一里程碑式的进展开启了AI设计基因编辑工具的新时代，有望加速基因编辑技术在研究和临床应用中的发展。

- 参考：
https://www.businesswire.com/news/home/20240422399482/en/Profluent-Successfully-Edits-Human-Genome-with-OpenCRISPR-1-the-World%E2%80%99s-First-AI-Created-and-Open-Source-Gene-Editor

  https://doi.org/10.1101/2024.04.22.590591

  https://www.profluent.bio/blog/editing-the-human-genome-with-ai

4. [Genome Medicine｜构建NK/T细胞淋巴瘤分子分型系统](https://mp.weixin.qq.com/s/viAwPkop_l80Zfof9ztu-Q)

![](https://github.com/openbiox/weekly/assets/25057508/4d66c1ef-c4a2-440f-bdf3-fff0553eed77)

本研究发现，与初治NK/T细胞淋巴瘤（NKTCL）患者相比，复发/难治患者碱基水平及结构水平变异（SNVs、INDELs、CNVs、SVs）均显著增加，特别是复杂结构变异事件如染色体碎裂、局部扩增等在复发/难治NKTCL中显著富集，体现了基因组不稳定性在NK/T细胞淋巴瘤进展演变中所发挥的重要作用。进一步通过整合基因组特征，研究团队构建了一套新的NK/T细胞淋巴瘤分子分型系统（C0-C4），对应该分子分型系统各不同亚型的基因组突变及及临床预后特征，为今后的NK/T细胞淋巴瘤精准临床诊疗提供有价值的指导。

- 论文链接：https://genomemedicine.biomedcentral.com/articles/10.1186/s13073-024-01324-5

## 博文资讯

5. [李飞飞团队发布《2024年人工智能指数报告》：10大趋势，揭示AI大模型的“喜”与“忧”](https://mp.weixin.qq.com/s/ohRWJ7wMfHEb8XBRk3xhPA)

<img width="508" alt="a3f18b876fd4ebb9cf2b2630e592eb7" src="https://github.com/openbiox/weekly/assets/73527555/216625f4-3eec-402c-a5d7-21ef83a9dab9">

斯坦福大学李飞飞领导的人工智能研究所（Stanford HAI）团队发布了《2024年人工智能指数报告》，这份报告全面追踪了2023年全球人工智能的发展趋势，并指出了当年AI行业的10大主要趋势，包括AI在特定任务上超越人类、产业界主导AI研究、模型训练成本上升、美国成为顶级AI模型的主要来源国、缺乏对大型语言模型（LLM）责任的标准化评估、生成式AI投资激增、AI提升工作质量和生产力、AI推动科学发现等方面。报告还强调了AI技术进步带来的社会影响和政府在推动和监管AI发展中的积极角色。

6. [智源研究院中文互联网语料库 CCI 2.0 开放，打造大模型数据“共建-共享”新模式](https://mp.weixin.qq.com/s/hn3rEYQDJWqoE0-uyPoxBQ)

<img width="492" alt="ba8a7c5621786bbc078a434bfb6ff71" src="https://github.com/openbiox/weekly/assets/73527555/f74a4f1c-6d8c-474a-8ab8-b2f4188e9ff0">

在中关村论坛年会数据安全治理与发展论坛上，智源研究院发布了规模约500G、涵盖1.25亿个网页的中文互联网语料库CCI 2.0，该数据集经过严格的清洗和过滤，确保了高质量和合规性。智源研究院还联合多家企业建立了“共建-共享”的数据运营方式和首个数据集平台，制定了数据共享清洗过滤规范，并推动了行业专用数据集的建设，如医疗行业的MDH-Patho病理图像数据集。未来，智源研究院将继续推动高质量、安全的中文数据集的建设，提升数据处理的效率和质量，并秉承开源开放精神，加速中国高质量中文数据资源的有效利用。


7. [图灵奖得主辛顿：坐学术冷板凳的30年](https://mp.weixin.qq.com/s/uIdyCB98mvHAWf0t56p94g)

![](https://github.com/openbiox/weekly/assets/25057508/ad241f67-5de3-4e94-9692-3dd7a1e2a387)

本文介绍辛顿的人生经历，每一大佬身后都有令人敬佩的精神。

8. [卷积神经网络（CNN）基础知识整理](https://mp.weixin.qq.com/s/ic6RuzcbEjwOYt2oC6B-WA)

![](https://files.mdnice.com/user/37191/7e4c2ca8-fb0c-405a-a81a-6e68ac9388fa.png)

本推文总结了一些常见的卷积神经网络知识。


## 工具

9. [AFFiNE｜下一代全功能知识操作系统](https://mp.weixin.qq.com/s/yPKphzFM_9sxWNE6oqh8tg)

![](https://github.com/openbiox/weekly/assets/25057508/f418f67d-b879-4647-abb1-f2d6aa635f93)

AFFiNE 不仅仅是一个工具，它是一个能够塑造你工作方式的伙伴。从文档创建到任务管理，再到视觉协作，AFFiNE 提供了一个全面、灵活且高度可定制的解决方案。

10. [Microsoft Loop | 微软推出的新型团队协作平台](https://mp.weixin.qq.com/s/GexayY63jGF6P4GYEtT4fw)

<img width="1457" alt="image" src="https://github.com/openbiox/weekly/assets/45822462/7d18f910-67f5-470e-ba19-568a4f303be6">

Microsoft Loop是微软新推出的团队协作平台，它通过跨应用同步、AI辅助协作、实时编辑与沟通、灵活的任务管理以及多平台支持等核心功能，提升了团队的协作效率。Loop特别适合项目管理、内容创作和远程工作等场景，其与Microsoft 365的紧密集成、直观用户界面和跨平台灵活性是其主要优势。然而，它也存在依赖于Microsoft生态系统、隐私和安全问题以及新用户学习曲线等潜在缺点。尽管如此，随着Loop的不断迭代，它有潜力成为未来团队协作的关键工具。

11. [Lettura | 一款 Rust 编写的极简主义的桌面 RSS 阅读器](https://mp.weixin.qq.com/s/6wLSoTSTODQ9kWP5QlUSfQ)

![](https://github.com/openbiox/weekly/assets/45822462/4d54172c-1438-490e-9d15-4e9d9f294436)

Lettura是一款基于Rust和Tauri技术的免费开源桌面RSS阅读器，适用于Windows、Mac和Linux系统。它以极简主义设计和无广告的干净界面，为用户提供了简单直观的阅读体验。Lettura支持跨平台同步阅读进度，提供定制化选项，并允许用户离线阅读文章。用户可以通过GitHub下载或自行编译安装Lettura，轻松添加和管理RSS源。这款阅读器特别适合追求简洁、高效阅读方式的用户。

- 工具链接：https://github.com/zhanglun/lettura


## 资源

12. [中国大学矢量校徽合集](https://www.urongda.com/ "中国大学矢量校徽合集")

<img width="918" alt="image" src="https://github.com/openbiox/weekly/assets/25057508/96106166-85d1-4377-8699-20ad72e1c31b">

该网站收集整理全国各大高校的矢量校徽资源，提供高清大图和矢量图源文件免费下载。

13. [WORKSHOP: Single cell RNAseq analysis in R](https://zenodo.org/records/10042919 "WORKSHOP: Single cell RNAseq analysis in R")

<img width="1142" alt="image" src="https://github.com/openbiox/weekly/assets/45822462/bdfbf815-3182-4673-9398-1d09bc6335a1">

本资源是由澳大利亚生物共享联盟（Australian BioCommons）举办的WORKSHOP中使用的培训材料，其中展示如何使用R包Seurat进行单细胞分析，包括数据质量控制、分析和探索。将讨论每个步骤的原因，涵盖读取计数数据、质量控制、筛选、归一化、聚类、UMAP布局和识别聚类标记，并探索可视化单细胞表达数据的不同方法。

- 资源链接：https://zenodo.org/records/10042919

14. [awesome-genome-visualization](https://cmdcolin.github.io/awesome-genome-visualization/?latest=true "awesome-genome-visualization")
<img width="1125" alt="40a8e7171a66dfd5e6c362d22447212" src="https://github.com/openbiox/weekly/assets/73527555/295cb25a-5bd0-4176-abe4-52383fba12b1">

该网站收集了一系列有趣的基因组可视化工具及其代码地址，包括各种图（气泡图、热图、火山图等等）的实现代码，助力研究者们快速画图。

## 历史上的本周
- 2023 [生信爱好者周刊（第 83 期）2022 Science年度十大科学突破](https://mp.weixin.qq.com/s/wPyEVdhlGXENSIlao_vG_Q)

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