---
date: 2024-07-21
comments: true
---

# 生信爱好者周刊（第 132 期）：985青年教授自爆学术不端？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232401819.png)

[图源](https://centuryofbio.com/p/summer-hiatus)

## 本周话题：985青年教授自爆学术不端？

近期，施某，一位29岁的清华大学年轻教授，曾获得GHwanren计划青年拔尖人才荣誉，疑似在文中自曝自己学术不端和论文造假的行为。

相关报道链接：

- https://www.toutiao.com/w/1804204667989059/?log_from=f1781a90126ae_1720677473761
- https://www.toutiao.com/w/1804185933273162/?log_from=e135ac27b6b59_1720677368225

`@ShixiangWang` - 目前看这种反讽式的自曝不是来自本人，但不管如何，内容有多少可信度，可能值得相关机构进行查验。

## 生信研究

1、[Nature | 印明柱团队发表泛癌时空多组学成果](https://mp.weixin.qq.com/s/Zb8SoPja9Z6fI0BBhB8YUg)

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232456807.png)

肿瘤血管生成是癌症的一个关键特征，它被诱导以帮助肿瘤获取维持生长所需的营养物质和氧气。与正常血管相比，肿瘤血管显示出渗透性增加、形态不规则且组织结构较差。内皮细胞（ECs）和壁细胞（MCs）是直接参与肿瘤血管生成的主要成分。EC亚群异质性高，且ECs可塑性使其成为抗血管生成治疗（AATs）靶点。在临床前研究中，将AAT与肿瘤免疫疗法相结合已被证明能产生更强的抗肿瘤效果。本研究利用单细胞转录组、空间转录组技术生成了31种癌症血管图谱（单细胞分辨率），描绘了肿瘤血管复杂性，并对抗血管生成疗法具有潜在的临床意义。

- 论文链接：https://www.nature.com/articles/s41586-024-07698-1

2、[Genome Biology | scCDC:单细胞RNA测序污染修正的新方法](https://mp.weixin.qq.com/s/3E3u1xEIiyUoSXqtgQ0Bag)

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232542381.png)

>单细胞和单核转录组测序（scRNA-Seq/snRNA-Seq）已被普遍用于对细胞异质性的研究。而此类研究强烈依赖于数据的可靠性。然而，在进行单细胞测序的过程中，实验溶液环境中的游离RNA（即ambient RNA）会对被测细胞产生系统性的干扰，导致细胞内源基因的表达水平测定失真，形成数据污染。此问题已被多个研究组关注，且已有若干算法被开发出来修正污染数据。在本研究中，浙江大学爱丁堡大学联合学院（ZJE）王超尘研究组使用了多份具有不同干扰水平的实际数据集和模拟数据集，对这些去污染方法的修正效果进行了深入的分析，发现这些方法在多个数据集中存在校正不足或过度校正的问题。

为了更好地解决这一问题，研究团队开发了一种名为scCDC的新策略，有效地消除了环境RNA分子的系统性干扰。和已有的方法相比， scCDC方法的优点在于，它能够率先识别出导致强干扰的基因，并专门修正这些基因的表达水平，从而在修正高污染基因的同时，避免了对其他基因的过度修正。此外，scCDC能够与已有的修正方法共同应用，从而实现更加精确和全面的污染修正效果。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03284-w

3、[Genome Biology｜基于长读长RNA测序鉴定RNA编辑位点的新算法L-GIREMI](https://mp.weixin.qq.com/s/7KaflLeNjrZ4XZXcJbgx0g)

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232626449.png)

研究团队提出了一种无需基因组信息即可在长读长RNA-seq中检测和分析RNA编辑位点的新方法——L-GIREMI。L-GIREMI可有效地处理测序错误和reads偏差，并使用基于模型的方法对RNA编辑位点进行评分；能够分析单个RNA分子的RNA编辑模式、多个RNA编辑事件的共现情况以及检测等位基因特异性RNA编辑。该方法为研究长读RNA-seq中的RNA核苷酸变异提供了新的机会。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-03012-w



## 博文资讯

4、[Cell ｜ 近50年，癌症研究的那些里程碑事件](https://mp.weixin.qq.com/s/Cmjei-h5iMfKKB4JxdlQzg)

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232653963.png)

近50年来，癌症研究的进展不仅深化了我们对其起源、演变和脆弱性的理解，还促进了更早期和更准确的诊断及药物开发，挽救了数百万人的生命。本文将回顾近50年，癌症研究的那些里程碑事件，并展望令人激动的未来发展。

5、[回归工具属性，测序的全面“药”化！](https://mp.weixin.qq.com/s/5FJhGm_PhLRfLBKsE0KI5A)

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232721882.png)

本文从基因组针对和药物方面对测序进行了工业化解读。

6、[漫谈生物统计——宾夕法尼亚大学李洪哲教授](https://mp.weixin.qq.com/s/8NG5tiL9tQjFZh4Gu10c-A)

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232759616.png)

>随着生物医学领域的发展以及科学技术不断进步，日益丰富的数据为生物统计带来新的机遇及挑战。生物统计内容广博，不仅包括传统医学领域的药物实验设计与临床分析，也涉及目前火热的遗传基因组学数据分析、电子病历、精准医学，以及越来越受重视的公共卫生及环境领域。美国的生物统计经历了几十年的发展已建立成熟的职业体系，多数顶尖大学也都设立了生物统计系，为制药公司、FDA、科研机构输送了大量优质人才。然而，中国高校完整系统的生物统计项目依旧屈指可数，相关科研及产业转化也非常薄弱。鉴于目前国内生物统计发展滞后，认识和宣传非常不足，这次访谈我们邀请了宾夕法尼亚大学生物统计系李洪哲老师，从他的职业体验出发向读者介绍生物统计。


## 工具

7、[Positron，新一代数据科学IDE（R+Python+...）](https://mp.weixin.qq.com/s/TPFl07tbEPP0I8gtvxv4iQ)

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232852696.png)

RStudio 母公司（改名叫 Posit）正在构建的下一代数据科学 IDE，Positron（正电子）。

8、[collie ｜ mini 的订阅器](https://github.com/parksb/collie)

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232924636.png)

9、[plane | 开源项目管理工具](https://github.com/makeplane/plane)

![](https://cdn.jsdelivr.net/gh/shixiangwang/cdn/img/image-20240721232957017.png)

## 资源

10、[生物信息学系列汇总](https://mp.weixin.qq.com/s/jbwJ4Mhlwr5A5eMGBC9bBg)

观科研公众号提供的系统生物信息学系列推文，值得读者阅读学习。



## 历史上的本周

- 第 89 期：[视频学习胜过读书吗？](https://mp.weixin.qq.com/s/oGzJ4i9QxEM5GbBhNgsl6w)

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

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）