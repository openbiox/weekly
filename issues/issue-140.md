---
date: 2024-09-14
comments: true
---

# 生信爱好者周刊（第 140 期）：七年：一个皖北大学生的一生

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![[中国的载人飞艇 AS700](https://www.sohu.com/a/802511112_121873449)](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141508464.png)


## 本周话题：[七年：一个皖北大学生的一生](https://mp.weixin.qq.com/s/oRXMj7O9rMoJlsiGXLt8iA)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141544298.webp)

相传，人体细胞每七年就会更新个遍。在这个意义上，七年就是一辈子。文章的作者周运来在个人公众号回顾了在校园和工作的两个七年。

- `@ShixiangWang` - 还是借用前辈先贤的话。无论你遇见谁，他都是在你生命中该出现的人。无论发生什么事，那都是唯一会发生的事。不管事情开始于哪个时刻， 都是对的时刻。已经结束的，就已经结束了。你坐在这里，读着这些文字，我也相信绝非巧合。



## 生信研究

1、[Nature | 肿瘤空间组学图谱用于预测乳腺癌免疫治疗的反应](https://mp.weixin.qq.com/s/B605Sxmy70RzyrQYvdKJUA)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141513001.webp)

免疫疗法改变了实体瘤的治疗，但其在乳腺癌中的最佳应用仍不明确。三阴性乳腺癌（TNBC）缺乏激素受体和人类表皮生长因子2（HER2）表达，是一种需要新疗法的侵袭性亚型乳腺癌。在 TNBC 中，针对程序性死亡蛋白 1（PD-1）和程序性细胞死亡配体 1（PD-L1）之间相互作用的免疫检查点阻断（ICB）试验表明，一些患者可从中获益，但目前缺乏可靠的生物标志物来识别应答者。尽管多细胞组织预处理可能表明ICB是否可以增强免疫反应，但ICB如何重塑组织结构以实现这一点仍然模糊不清。在治疗前、治疗中和治疗后对肿瘤进行连续取样可以发现治疗引起的重塑，但这在常规临床实践中具有挑战性，因此治疗期间的组织动态与反应之间的关系尚不清楚。
2024年9月6日，剑桥大学H. Raza Ali课题组以及意大利San Raffaele医院Giampaolo Bianchini课题组在Nature发表了一篇题为“Spatial predictors of immunotherapy response in triple-negative breast cancer”的研究论文，通过绘制 TNBC 原位多细胞肿瘤生态系统图，发现了关键的 ICB 反应预测因子，并表明 ICB 能明显重塑肿瘤结构。

- 论文链接：https://www.nature.com/articles/s41586-023-06498-3



2、[Nat Genet | 鉴定同源长非编码RNA的新方法](https://mp.weixin.qq.com/s/PT9tq0A2oIycvG0KeGO90A)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141515999.webp)

长非编码RNA（lncRNA）的发现和表征是过去几十年分子生物学领域的重大进展。已有研究成果表明，lncRNA在发育、肿瘤等多种生理和疾病过程中发挥调控作用，但目前绝大多数lncRNA 的功能仍然未知。通过鉴定不同物种间同源的lncRNA，可以筛选出在进化过程中保守的lncRNA，这些lncRNA也更可能具备重要的功能。但是，由于lncRNA的序列保守性较低，传统的序列比对方式只能鉴定出极少的不同物种间同源的lncRNA。例如，在斑马鱼和人类上万的lncRNA基因中，通过序列比对只能找到几十个序列保守的同源lncRNA。因此，不管是从lncRNA的理论还是技术方面考虑，目前都亟需一种新的方法来鉴定不同物种之间的同源lncRNA。2024年1月9日，清华大学张强锋、北京大学汪阳明、席建忠研究团队合作在Nature Genetics上发表题为Computational prediction and experimental validation identify functionally conserved lncRNAs from zebrafish to human的研究论文。该工作开发了一套新的计算流程，在包括人类、小鼠、斑马鱼在内的8种脊椎动物中，鉴定保守的同源lncRNA，工作同时开发了基于CRISPR的基因敲除和回补筛选系统，通过实验验证了所鉴定的同源lncRNA在不同物种中的保守功能，为该领域的研究提供了新的思路。

- 论文链接：https://www.nature.com/articles/s41588-023-01620-7

3、[Cell Research | 基于单分子测序平台的单细胞多组学测序技术](https://mp.weixin.qq.com/s/AyShdareIRdfeu4JcNCfEA)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141518790.webp)

2023年9月12日，北京大学生物医学前沿创新中心 （BIOPIC）汤富酬课题组在Cell Research上发表了题为scNanoCOOL-seq: a long-read single-cell sequencing method for multi-omics profiling within individual cells的论文，首次报道了名为scNanoCOOL-seq的单细胞多组学测序技术。该技术整合了三代测序平台 (单分子测序平台) 和 scCOOL-seq原理，能够实现在一个单细胞中同时精准检测基因组(拷贝数变异)、DNA甲基化组、染色质可及性以及转录组等多个组学层面的信息。

- 论文链接：https://www.nature.com/articles/s41422-023-00873-5



## 博文资讯

4、[从KM到Cure Models：常用生存分析方法的优缺点](https://mp.weixin.qq.com/s/wGXTv3yj-eo7uKEIjPageg)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141522511.png)

生存分析是一种用于研究个体生命长度或事件发生时间的统计方法。在许多领域中，如医学、社会学、经济学和工程学等，生存分析被广泛应用于分析个体的生存时间，并研究相关因素对生存时间的影响。通过生存分析，我们可以评估特定因素对个体生存的影响，并预测未来事件的概率。

本文旨在介绍生存分析的基本原理、常用的统计方法以及在实际应用中的一些注意事项。首先，我们将介绍生存函数和生存曲线的概念，以及其与死亡率和风险的关系。然后，我们将介绍常用的生存分析方法，包括Kaplan-Meier方法和Cox比例风险回归模型等。



5、[国际测试委员会发布人工智能百年人才榜](https://mp.weixin.qq.com/s/VxLhPJ08wI195Fq9KL5Fbg)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141528935.webp)

只以贡献论英雄，从1943年至今的人工智能领域成果中，由多位独立科学家遴选出100多项代表性成果，在确定主要贡献者的基础上产生人工智能领域百年人才榜、国家榜、机构榜。其中图灵奖获得者Yoshua Bengio荣登榜首，美国在国家榜上获得首位，谷歌在机构榜上排名第一。



6、[lr2rmats | 基于Snakemake的基因注释工具](https://mp.weixin.qq.com/s/LBa1k2qHZIs1EIlYlYGAMA)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141522700.png)

lr2rmats是一个基于Snakemake的轻量级管道，用于结合第三代长读长和第二代短读长RNA-seq数据生成增强的基因注释文件，通过它可以用于rMATS软件进行差异选择性剪接分析。lr2rmats支持多样本和多种数据格式，并且可以在Linux/Unix系统上运行。安装和运行lr2rmats需要一些依赖软件，如minimap2、STAR、samtools、bedtools和Snakemake。用户可以通过配置文件config.yaml来指定输入输出文件和参数。该工具旨在提高转录组数据分析的效率和准确性。

- 软件地址：https://github.com/Xinglab/lr2rmats

7、[疼痛](https://mp.weixin.qq.com/s/X-lpo2GEhx0yt9_J59e8Gg)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141530676.webp)

关于疼痛的科普。在疼痛医学界，它被公认为是继呼吸、脉搏、血压、体温之后的第五个“生命体征”。



## 工具



8、[wikiprofiler | 基因表达数据映射至WikiPathways的工具](https://mp.weixin.qq.com/s/1NOlsMvmL5F5vMpq0qttJQ)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141524328.webp)

wikiprofiler的R包可以将基因表达数据（如基因的倍数变化）映射到WikiPathways上进行可视化展示。该包的设计灵感来源于ggplot2，使用管道操作符%>%或|>来进行操作。wikiprofiler包最近被发布到CRAN上，方便用户安装和使用。

本文还通过示例展示了从富集分析结果中获取通路ID，然后使用wpplot()函数生成图表，并通过wp_bgfill()添加背景色，最后使用wp_shadowtext()增加带阴影的文本以提高可读性。这个包旨在简化数据映射和可视化过程，目前功能还在不断完善中。



9、[Zulip | 一个开源的团队协作工具](https://github.com/zulip/zulip)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141526232.png)

Zulip是一个开源的团队协作工具，它结合了基于主题的线程和邮件聊天的优点，旨在提高远程工作的生产力和愉悦感。它支持实时和异步对话，目前被财富500强公司、主要开源项目以及其他组织广泛使用。

- 工具地址：https://zulip.com/



10、[datasette ｜用于探索和发布数据的开源多工具](https://github.com/simonw/datasette)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141534940.svg)





## 资源

11、[refgenie](https://refgenie.databio.org/en/latest/)

![](https://refgenie.databio.org/en/latest/img/refgenie_logo_light.svg)

Refgenie 是一个参考基因组管理器。

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409141538120.png)





## 历史上的本周

- [生信爱好者周刊（第 100 期）：朋友好](https://mp.weixin.qq.com/s/8rK_PQjbwkzLNpHGR9OVxw)



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