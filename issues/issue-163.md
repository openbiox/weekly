---
date: 2025-04-11
comments: true
---

# 生信爱好者周刊（第 163 期）：美国公共数据库对中国科研人员禁用

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413102411509.webp)

迄今为止最大的脑图 - [图源](https://github.com/openbiox/weekly/issues/2516)


## 本周话题：美国公共数据库对中国科研人员禁用

> 中美在数据和技术领域的紧张关系加剧，美国于2024年底推出了针对跨境数据的新规，并将在2025年开始实施。该新规旨在限制中国等“受关注国家”获取美国人的敏感个人数据，这对中国科研人员使用美国的公共医学和学术数据库可能带来重大影响。

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413102603046.webp)

> 涉及大量美国人健康/基因信息的数据库（如SEER, TCGA, dbGaP等）在新规下对中国几乎封闭，而以公开文献和统计为主的资源（如PMC, ClinicalTrials.gov, CDC数据）仍然开放。介于两者之间的是一些已经公开但含匿名个体数据的资源（如GEO, 部分NIH数据），目前看大概率继续开放，但需关注政策动向。

`@ShixiangWang`: 协作共享有时比想象中艰难。万事万物都遵循着动态的平衡。之前是全世界分析M国数据，就政策导向看，以后会产生一些相对的数据孤立。个人观点，长久看，对M国也未必是好事。我们国家也确确实实需要有真正意义上类似 TCGA 的计划，而不是坐地分钱。



## 生信研究

1、[Science | 5'端单细胞测序绘制CD4+T细胞双向转录增强子多模态图谱](https://mp.weixin.qq.com/s/ADBS94ZfE2-FcBA60zqGdw)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413102926464.png)

团队利用5’端单细胞RNA测序方法构建T细胞双向转录增强子多模态图谱，同时开发了ReapTEC方法，实现高核苷酸分辨率和高灵敏度鉴定btcEnhs，捕获真正的增强子区域。

- 论文链接：https://www.science.org/doi/10.1126/science.add8394

2、[Nat Methods | 系统性评估11种空间组学技术](https://mp.weixin.qq.com/s/0Wh_VyKSIvH3Y9LQW1B_RA)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413103509895.webp)

基于测序空间转录组技术（sST）的快速发展改变了在空间背景下测量基因表达的能力，被Nature Methods评为2020年的年度技术。然而技术的发展应该关注哪些指标，如何对这些技术进行标准化的多维度评估和比较，尚未有清晰的解决方案。为了解决技术标准不清晰，评估方案混乱等问题，研究团队对 11 种 sST 方法进行了全面比较（包括 10X Genomics Visium（基于 poly-A 和基于探针的两种方法）、DynaSpatial、HDST、BMKMANU S1000、Slide-seq V2、Curio Seeker（Slide-seq 的商业版本）、Slide-tag、Stereo-seq、PIXEL-seq、Salus 和 DBiT-seq）。他们使用具有明确形态的参考组织来评估它们的性能。研究建立了一套具有不同组织结构特征的标准参考组织，包括胚胎小鼠眼睛、成年小鼠海马区和嗅球。在进行统一的组织块制备和切片后，他们使用11种sST方法对这些组织进行了空间转录组学分析，生成了一个跨平台的数据集（称为cadasSTre），以便直接比较空间分辨率、分子捕获效率和分子扩散。

- 论文链接：https://www.nature.com/articles/s41592-024-02325-3



3、[Nat Med｜AI驱动的血液WGS ctDNA检测平台——MRD-EDGE，可高灵敏度预测癌症复发](https://mp.weixin.qq.com/s/WA9Q5aAJwHROFPOWe6jPgQ)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413103044300.png)

团队开发了一种由机器学习驱动的血浆全基因组测序（WGS）ctDNA信号富集平台——“MRD-EDGE”，可以极高敏感度监测肿瘤负荷。

- 论文链接：https://www.nature.com/articles/s41591-024-03040-4



## 博文资讯

4、[我学习基因组学深度学习的4步法](https://divingintogeneticsandgenomics.com/post/how-i-am-learning-deep-learning/)

Ming Tommy Tang 在文章中介绍了学习的4步经验，涵盖了具体的学习资料，主要步骤如下：

- Step 1, get a high-level understanding
- Step2, code it out!
- Step 3, apply it to real biological examples
- Step 4, apply the learning to a real project



5、[揭开ggplot惰性求值的神秘面纱](https://yjunechoe.github.io/posts/2022-03-10-ggplot2-delayed-aes-1/)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413105148902.png)

探索 after_stat() 的逻辑，一窥 ggplot 内部机制。



6、[华盛顿大学蛋白质设计研究所创新之道及其对生命科学新型研发机构建设的启示](https://mp.weixin.qq.com/s/ejnX8mVWtZ5bxtFfApRWAA)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413103336048.png)

文章介绍了华盛顿大学蛋白质设计研究所的历史沿革与创新成就，分析了蛋白质设计研究所创新特点，总结了有关生命科学新型研发机构建设的启示。



## 工具

7、[zotero-actions-tags | 自定义 Zotero 工作流程](https://github.com/windingwind/zotero-actions-tags)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413105339309.png)

8、[玉竹](https://github.com/hefengbao/yuzhu)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413105551042.png)

玉竹是一套简洁的内容管理（博客、微博客）、财务管理（记账）系统。

- 示例：https://www.8ug.icu/



9、[文捕 | 博客内容一键解析下载工具](https://www.blog-keeper.com/)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413105657950.png)



## 资源

10、[canvasxpress ｜ 深入数据分析和无缝集成的JavaScript库](https://canvasxpress.org/index.html)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413110217410.png)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/20250413105847443.png)


以交互式和可扩展的视觉呈现更快地转换数据。有对应 R 包 binding：https://github.com/neuhausi/canvasXpress 。


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