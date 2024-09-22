---
date: 2024-09-22
comments: true
---

# 生信爱好者周刊（第 141 期）：那些早逝猝死的学术青年才俊们

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221136761.png)



## 本周话题：[那些早逝猝死的学术青年才俊们](https://mp.weixin.qq.com/s/OHasS9jFyH4vmEjNe7ZODQ)

学术青年才俊早逝现象频发，近年不断地在某个时间节点引起[热议](https://mp.weixin.qq.com/s/AR1DsBQb7XQ0gt6HL3p5Hg)。写这个话题也是希望大家（包括自己）在忙碌之余，多关注自己的身体和心理健康。国庆节也马上要到了，提前预祝大家长假快乐，工作顺利！身体健康是任何幸福的基础，好好活着最重要。

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221139089.webp)



## 生信研究

1、[Cell Research | 14国科学家联合发文，倡议开展人类基因组计划二期，让精准医疗惠及全球](https://mp.weixin.qq.com/s/P85nsEVCJprflxDpKdGRJw)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221122929.png)

Cell Research 近期发表一项重要的科学倡议 - 人类基因组计划二期(HGP2)。由14个国家的科学家联合发起，该计划旨在推动全球精准医疗的发展,让更多人受益于基因组学研究成果。HGP2的主要目标包括:对全球1%人口进行基因组测序、构建多样化的人类基因组图谱、推动多组学研究等。这将有助于深入了解人类遗传变异与疾病的关系，为精准医疗提供重要基础。文章详细阐述了实现这一宏大目标面临的挑战，包括经济、组织、基础设施等方面，并提出了相应的解决方案。

- 论文链接：https://www.nature.com/articles/s41422-024-01026-y



2、[Nature Methods | 环状RNA检测工具的评估报告以及使用指南](https://mp.weixin.qq.com/s/6YWGLQjzluvBMSyYWgfd_Q)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221126113.webp)

环状RNA分子(circRNAs)的检测通常基于使用计算工具处理的短读RNA测序数据。已经开发了许多这样的工具，但是缺少与正交验证的系统比较。因此，OncoRNALab联合了众多国际知名环状RNA研究大咖，建立了一项circRNA检测工具基准研究，其中16种工具检测了三种深度测序的人类细胞类型中超过315,000种独特的circRNA，并使用三种正交方法验证了1516种预测的环状rna。这项研究对未来circRNA的检测和验证提出了宝贵的建议。

- 论文链接：https://www.nature.com/articles/s41592-023-01944-6



3、[Nat Med | 斯坦福医学院利用医疗 Twitter 进行病理图像大模型分析](https://mp.weixin.qq.com/s/J08bPfwGXaCA4oi5A_DdsA)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221122383.webp)

斯坦福医学院利用医疗Twitter数据开发病理图像大模型的创新研究。研究团队构建了名为OpenPath的大规模病理图像-文本数据集，并在此基础上训练了PLIP多模态AI模型。PLIP展现出优秀的零样本学习和迁移学习能力，在多个病理图像分类任务中表现出色。此外，PLIP还能实现灵活的图像检索,具有重要的教育和知识共享价值。这项研究充分利用了公开的医疗信息资源，为医疗AI的发展提供了新思路，具有重要的理论和应用价值。

- 论文链接：https://www.nature.com/articles/s41591-023-02504-3

## 博文资讯

4、[2023年 “全球最具创新力” 的10家生物科技公司](https://mp.weixin.qq.com/s/QtlShfjBUrUJ3rBWwFM2vA)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221127452.webp)

知名媒体《快公司》（Fast Company）公布了“全球最具创新力的10家生物科技公司名单”，称这些公司正使医疗和基因测序更快得向前发展。在这份名单当中，包含了在DNA测序、细胞分离等科技做出亮眼突破的新锐，也有旨在改善现有CAR-T与基因编辑疗法、优化现有药物开发流程的多家创新公司。这些最具创新力的公司所开发的技术预示着生物科技界的发展方向。

- Ultima Genomics：打破100美元全基因组测序的天花板
- 10X Genomics：在特定的空间和时间上检测基因活性
- DNAnexus：在国家范围内管理测序数据
- Akadeum：为CAR-T疗法开发快速细胞分离技术
- Ispecimen：为科学家提供难以获取的研究样本
- Abcam：开启抗体生产的新时代
- Colossal Biosciences：恢复已灭绝物种的存在
- Recursion：除去药物发现中的人类偏倚因素
- Emulate：开发器官芯片以替代动物实验
- Metagenomi：识别创新基因编辑工具



5、[他山之石可以攻玉：生物序列数据如何输入neural networks？](https://mp.weixin.qq.com/s/AGypU-aKMSXgaJ1YY7IDHg)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221124334.webp)

文章以DNA和蛋白质序列为例，详细讲解了one-hot编码、kmer+词嵌入等常用的序列表示方法，并给出了相应的PyTorch代码实现。作者不仅解释了基本概念，还提供了完整的数据处理和模型构建流程，让读者可以快速上手实践。对于想要将深度学习应用于生物序列分析的研究人员来说，这篇文章提供了宝贵的技术指导和启发。虽然内容简明扼要，但覆盖面广，是一篇难得的入门级教程。



6、[OpenHPC 社区宣布正式支持 openEuler](https://mp.weixin.qq.com/s?__biz=MzkyMjYzNjU0Ng==&mid=2247507573&idx=1&sn=bfc0063133f4655a7dd258a5a79e3193&source=41#wechat_redirect) 

![图片](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221154961.webp)

OpenHPC是Linux基金会项目，其使命是提供开源HPC软件组件和最佳实践的参考集合，从而降低部署，升级和使用现代HPC方法和工具的障碍。



## 工具

7、[Marsilea | Python的生物数据可视化](https://mp.weixin.qq.com/s/5-SQy7A9D1QKA4D0aQhkRQ)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221155941.webp)

> Marsilea的名字来源于四叶草的拉丁语，而四叶草与composable visualization最终组合形成的图像相似。

 

8、[Viash | 从脚本到流程](https://viash.io/)

![](https://viash.io/images/ViashIllustration.svg)



9、[gradio ｜ 使用Python构建和共享令人愉快的机器学习应用程序](https://github.com/gradio-app/gradio)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221133805.png)



## 资源

10、[zlibrary | 世界最大电子图书资源库](https://z-lib.id/)

![](https://weekly-1301043367.cos.ap-shanghai.myqcloud.com/202409221134334.png)



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

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）