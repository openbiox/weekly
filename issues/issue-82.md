---
date: 2023-07-02
comments: true
---


# 生信爱好者周刊（第 82 期）：一种新的数字表示方法 Posits

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图


![](https://files.mdnice.com/user/4331/f920825e-60d6-4cf4-8142-2a25c8cac631.png)


森林小屋-[图源](https://demo-zh.photoprism.app/library/browse#&gid=1&pid=101)。

## 本周话题：[一种新的数字表示方法 Posits](https://mp.weixin.qq.com/s/4G86KD9Jk8-QKgDAcfObLA)


![](https://files.mdnice.com/user/4331/2af6ceb9-2097-4f8a-a687-8402202b61b0.png)

训练许多现代 AI 工具背后的大型神经网络需要真正的计算能力：例如，OpenAI 最先进的语言模型 GPT-3 需要惊人的数亿次操作来训练，并且花费了大约 500 万美元的计算时间。工程师们认为他们已经找到了一种通过使用不同的数字表示方式来减轻负担的方法。这些数字，称为 posits，被提议作为对当今使用的标准浮点算术处理器的改进。而现在，研究人员开发了第一个在硬件中实现 posit 标准的处理器内核，并表明，与使用标准浮点数进行计算相比，基本计算任务的精度逐位提高了四个数量级。

`@ShixiangWang`: 机器学习正在深度革新基于逻辑和人类设计的计算机底层构架，这意味着以后任何人使用的电子设备都有可能存在着机器学习的硬件设计应用。这是资源配置的优化，生物信息学从业者如何参考类似的设计去进行核心算法/软件的优化将来可能是一个前沿领域。


## 生信研究

1、[Science | 果蝇全生命周期的单细胞图谱 Aging Fly Cell Atlas](https://mp.weixin.qq.com/s/mu8STUgFHZLyN7m2kJTTgQ)


![](https://files.mdnice.com/user/4331/1b066202-7b04-4532-835f-9f30116c3dc9.png)

果蝇从卵到成虫的存活时间称为果蝇寿命。它受温度和食物供应等环境因素的影响，一般为 10 至 50 天。Aging Fly Cell Atlas 是黑腹果蝇不同生命周期的单核转录组图谱，揭示了雄性和雌性果蝇一生中多数组织的变化。研究团队还开发了衰老时钟模型，发现核糖体基因表达是一个保守的年龄预测因子，并且细胞类型特异性的衰老模式可以用来衡量生物年龄。

- 文章链接：https://www.science.org/doi/10.1126/science.adg0934
- 数据库：https://hongjielilab.org/afca/


2、[Science | 智慧之图：人类多器官单细胞转录组学图谱](https://www.science.org/doi/10.1126/science.abl4896)


![](https://files.mdnice.com/user/4331/af6f3878-d636-4d9f-bdd2-fe3222057afa.png)

《智慧之图》是人体超过400种细胞类型的分子参考图谱。智慧之图联盟利用单细胞转录组学技术，对来自24种组织和器官的近50万个细胞的信使RNA分子进行了测量。这些数据为我们提供了关于人类基因组构成如何用于在人体内创建独特细胞类型的全新洞见。除了创建了这些细胞类型的详细分子定义外，该图谱还揭示了人类生物学的许多其他方面，包括同一基因如何在不同细胞类型中发生不同剪接，不同组织中共享的细胞类型如何在其身份上有微妙差异，以及免疫系统的克隆如何在多个组织之间共享。

- 论文链接：https://www.science.org/doi/10.1126/science.abl4896

3、[Science | OpenCell - 用于人类细胞组织制图的内源性标记](https://www.science.org/doi/10.1126/science.abi6983)


![](https://files.mdnice.com/user/4331/31c82f4f-f1e3-4d03-8439-1f2fa8ac75f1.png)


提高对蛋白质在人体细胞内如何组织的理解，将增强我们对细胞功能的系统级理解。Cho等人使用CRISPR技术以接近内源性的量表达了1000多种不同的蛋白质，其标记既可以对其位置进行荧光成像，也可以对相互作用的蛋白质伴侣进行免疫沉淀和质谱分析。大规模数据在交互式网站上提供，通过机器学习进行聚类和分析。这些研究强调了RNA结合蛋白的不寻常特性，并表明蛋白质定位是非常具体的，可以预测功能。

- 论文链接：https://www.science.org/doi/10.1126/science.abi6983

4、[Nature Communications | 比较纳米孔直接RNA测序的RNA修饰检测](https://www.nature.com/articles/s41467-021-27393-3)


![](https://files.mdnice.com/user/4331/08ca2026-1149-48bc-876e-3e0db9168507.png)


大多数利用纳米孔dRNA-seq数据检测RNA修饰的软件都无法避免使用Tombo的结果。但Tombo并不适合最新的fast5格式。作者开发的Nanocompore，通过利用nanopolish的结果进行RNA修饰检测来解决这个问题。

- 论文链接：https://www.nature.com/articles/s41467-021-27393-3

5、[Cell Genomics | De novo提取算法SigProfilerExtractor在癌症基因数据中发现4种新突变特征](https://mp.weixin.qq.com/s/jqDYlezxmFhIBKQsW3NKbg)


![](https://files.mdnice.com/user/4331/01262da8-d580-49b8-b5e3-2bbe4cd443af.png)


SigProfilerExtractor和其他13个突变特征提取工具在34个不同场景中的比较表明，SigProfilerExtractor对噪音具有很强的鲁棒性，并且突变特征De novo提取方面优于所有其他计算工具。将SigProfilerExtractor应用于全基因组泛癌分析项目（PCAWG）发布的2778个全基因组测序（WGS）和19184个全外显子组测序（WES）数据，揭示了四种新的突变特征。

- 论文链接：https://doi.org/10.1016/j.xgen.2022.100179


## 博文资讯

6、[gtExtras：协助gt包创建美观表格的R包](https://themockup.blog/posts/2022-06-13-gtextras-cran/)


![](https://files.mdnice.com/user/4331/4e46eceb-c8f6-487b-80be-25ca0f421d98.png)


`gtExtras`是一款协助`gt`包创建美观表格的R包，除了内置的7种表格主题，用户还可以自定义主题。除此之外，使用该包还能在表格内添加一些图标或者图像，甚至可以在表格内绘制一些简单的条形图或者数据分布图，是一款非常强大的表格可视化包。

7、[Aspera for HTS Data TurboDL | 自动化批量从 ENA|GSA 高速下载 fastq/SRA 数据](https://mp.weixin.qq.com/s/pJBNy77sDHVXlLB7ssXlSA)


![](https://files.mdnice.com/user/4331/c7a53c4c-8b90-424a-9e5d-d560e1e12983.png)




8、[跨越生物信息学“数据鸿沟”，解码基因储存的奥秘](https://mp.weixin.qq.com/s/EghQw5Fykxab7l4XPm4Pbg)

在大数据、人工智能和高性能计算逐渐融合的趋势下，面临海量生物数据的生物信息学领域虽然存在着“数据鸿沟”，面临着诸多挑战，但也为行业发展带来新的机会。


## 工具

9、[PRIMUS | 单细胞数据整合包](https://mp.weixin.qq.com/s/in2ju7wIAKVrdSk5jGxjPg)


![](https://files.mdnice.com/user/4331/78866d14-c100-43a0-8a5d-6e1ba3c6023f.png)

PRIMUS是一种能够同时考虑数据来源（如患者、样本、数据集）特定的组分和技术噪声，从 scRNA-seq 数据中发现细胞表型的整体聚类方法。PRIMUS 采用双线性泊松回归模型，将表达数据分解为明确的干扰因素、未定义的细胞表型以及它们对应的转录组学特征。

- github：https://github.com/KaiyangZ/PRIMUS


10、[shinybones](https://github.com/datacamp/shinybones)


![](https://files.mdnice.com/user/4331/b8bdf3aa-e5cd-4037-b8b4-b9c30ccdcf47.png)

shinybones是一个R包，它提供了一种非常固执己见的方式来组织大型、多页的闪亮仪表板。它允许用户专注于按照最小的约定集为每个页面构建独立的模块，并将所有涉及在仪表板中布局它们的样板代码放在一个简单的YAML配置文件中。


11、[groundhog](https://github.com/CredibilityLab/groundhog)


![](https://files.mdnice.com/user/4331/372bc862-0497-440f-829a-785bc549fae0.png)

groundhog通过将 library（pkg） 替换为 groundhog.library（pkg，date） 来重现 R 脚本.
groundhog.library（） 可以加载在 CRAN 上选定日期可用的包及其依赖项。如果需要，其会自动安装软件包，
而且安装将保留（而不是替换）该包的现有其他版本。与此同时，所有操作系统和 R 版本都可安装/加载相同的包版本。


12、[MutScape | 一个用于探索癌症基因组中突变景观的分析工具包](https://github.com/anitalu724/MutScape)


![](https://files.mdnice.com/user/4331/850b25c5-b1c3-4fc4-929c-b3421afc57eb.png)


一个用户友好的Python工具包，它提供了一个全面的管道，可以轻松地探索基于队列的突变特征，用于研究癌症基因组学。

13、[alist | 一个支持多存储的文件列表程序](https://github.com/alist-org/alist/blob/main/README_cn.md)


![](https://files.mdnice.com/user/4331/15746ef1-d3b5-486f-b1af-eae61065beed.png)


`alist`是一个支持多种存储，支持网页浏览和 WebDAV 的文件列表程序，由 gin 和 Solidjs 驱动。支持docker安装，可以在全平台使用。

14、[sunmao-ui](https://github.com/smartxworks/sunmao-ui/blob/develop/docs/zh/README.md)


![](https://files.mdnice.com/user/4331/f0e48934-7135-4a76-9814-90c9b8a9e896.png)


Sunmao(榫卯)是一个前端低代码框架。通过 Sunmao，您可以轻松将各种前端 UI 组件库和自己开发的前端组件，封装成低代码组件库，从而搭建您自己的低代码 UI 开发工具，使前端开发变得如榫卯般严丝合缝。

15、[PyOxidizer](https://github.com/indygreg/PyOxidizer)

PyOxidizer是一个用于生成嵌入 Python 的二进制文件的实用程序。 其首要目标是使复杂的包装和分发问题变得简单，以此让程序维护者可以专注于构建应用程序，而不是在构建系统和打包的工作中耗费精力。

16、[FreeTube](https://github.com/FreeTubeApp/FreeTube)


![](https://files.mdnice.com/user/4331/53e8e574-99e4-4a6f-944d-8b314a50acb3.png)


FreeTube 是一款开源的桌面 YouTube 播放器，在构建时充分考虑了隐私。使用时可以自动跳过所有广告，无需帐户即可订阅频道，并且可以防止 Google 使用 cookie 和 JavaScript 跟踪您。软件可用于 Windows、Mac 和 Linux平台。

17、[giscus](https://github.com/giscus/giscus)


![](https://files.mdnice.com/user/4331/3286fa57-8c02-4197-9969-53d328067213.png)


利用 GitHub Discussions 实现的评论系统，让访客借助 GitHub 在你的网站上留下评论和反应吧！本项目深受 utterances 的启发。（weekly网站的评论系统就是基于giscus做的）

- 开源。🌏
- 无跟踪，无广告，永久免费。📡 🚫
- 无需数据库。所有数据均储存在 GitHub Discussions 中。:octocat:
- 支持自定义主题！🌗
- 支持多种语言。🌐
- 高可配置性。🔧
- 自动从 GitHub 拉取新评论与编辑。🔃
- 可自建服务！🤳



## 资源

18、[zola | 静态站点生成器](https://github.com/getzola/zola)



![](https://files.mdnice.com/user/4331/9600e32e-8111-43e0-90e0-5813fb46d797.png)

一个类似 hugo 的工具，但 hugo 是 golang 构建的，而 zola 是使用 rust 构建的。

- 网站：https://www.getzola.org/

19、[根据 RNA 测序数据进行T细胞受体库重建和分析](https://mp.weixin.qq.com/s/qg01zt-MU9xo3bsnDHPTKg)


![](https://files.mdnice.com/user/4331/11ef16e5-8f40-4a09-bf94-0b424e95a44a.png)


这里介绍了一个分析 TCR 的 nextflow 流程。

- 链接：https://github.com/ConesaLab/TCR_nextflow


20、[openverse | 创意作品库](https://openverse.org/)


![](https://files.mdnice.com/user/4331/81258025-1cf8-4824-a778-31c1a8e91327.png)

Openverse是一个免费的创意作品库，包括超过7亿张照片、图像和音频，所有内容都是在创意共享许可证下或属于公共领域的，可以自由使用。


## 历史上的本周

- [第 42 期：极简主义的胜利](https://mp.weixin.qq.com/s/rr0DUxUMpnt26e9ZG2Memg)

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

