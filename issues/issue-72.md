---
date: 2023-04-20
comments: true
---

# 生信爱好者周刊（第 72 期）：把时间当作朋友

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图


![](https://files.mdnice.com/user/4331/c8cfabed-ac84-4042-9d2b-c6a3d29ea66d.png)

AI获奖画作《太空歌剧院》

## 本周话题：[把时间当作朋友](https://github.com/xiaolai/time-as-a-friend)

本周的话题来自李笑来的图书《把时间当作朋友》，认为人生的成长在于“思考”和“累积”。感兴趣的读者不妨购买或者通过上面的GitHub链接免费阅读。

![](https://files.mdnice.com/user/4331/4fc2202c-e979-4902-8ebe-b1b47942f9b3.png)


> 这本书的主旨非常简单：时间是不可能被管理的。必须开启心智，看清楚，想明白：问题出在我们自 己身上。而我们所面临的问题，与时间、管理或时间管理都没有多大的关系。解决方案只有一个，那就是“一切都靠积累”。深信积累的力量，时间就是你的朋友，否则，它就是你的敌人。


`@ShixiangWang` - 人生就是时间，它很严肃但每个人又不得不面对。“有所思”才能“有所悟”，“有所悟”方能深入理解自己个人的欲望或目标，然后通过时间的累积去积攒自己对于这个世界独一无二的认知。把时间当作朋友，善待它，也让它帮助你找到自己的路。



## 生信研究

1、[Science | Jeff Gore团队揭示复杂生态系统中涌现的相变](https://mp.weixin.qq.com/s/UJ6F7UqHUMo1Bz4goLb5tw)


![](https://files.mdnice.com/user/4331/e580f44f-0a56-4d6e-bcca-d81960602226.png)


生态学致力于理解自然生态系统中的多样化的物种和复杂的动力学行为，然而科学家长期缺乏描述和预测生物多样性和生态动力学的统一框架。MIT物理系的胡脊梁和Jeff Gore等科学家结合理论和微生物群落实验，证明只需要掌握少量群落尺度的控制变量，就可以预测复杂生态系统的行为。热力学描述大量气体分子的行为只需要温度和压强等少数涌现的状态变量，而不需要知道每个分子的坐标和速度。Jeff Gore等人在生态网络中发现了类似的粗粒化描述方法，他们的实验和理论结果表明，只需要知道物种数量和平均种间相互作用强度这两个粗粒化参数，就可以预测生态群落中涌现的动力学行为以及相变。物种数量和平均种间相互作用的增加会导致群落在三个涌现的动力学相之间发生相变，从所有物种稳定共存相，转变到部分物种稳定共存相，最终转变到物种数量随时间持续振荡相。他们还发现高物种多样性和群落持续震荡之间存在正反馈。相关成果10月6日发表于Science杂志最新一期。

- 论文链接：https://www.science.org/doi/10.1126/science.abm7841
- 官方报道：https://www.science.org/content/article/powerful-physics-tool-could-help-scientists-understand-complex-ecosystems

2、[Nature Communications | TidyMass: 一个面向对象的LC-MS数据可重复分析计算框架](https://mp.weixin.qq.com/s/EkhOXPMVNNqBQkZHi2g3JA)


![](https://files.mdnice.com/user/4331/e2fcb032-80c4-4805-a78b-ecddd1de9598.png)

可重复性、可追溯性和透明度(Reproducibility, traceability, and transparency)一直是LC-MS数据分析的长期存在的问题。虽然现在已经开发了多种工具，但是他们仍然存在着局限性。因此，我们开发了 tidyMass项目(https://www.tidymass.org/)，tidyMass是一个基于R语言的综合计算框架，可以实现LC-MS数据的可追溯、可共享和可重复的数据处理和分析工作流程。TidyMass是一个共享底层设计理念、语法和数据结构的R包生态系统，它提供了一个全面的、可重现的和面向对象的计算框架。模块化架构使tidyMass成为一个高度灵活和可扩展的工具，其他用户可以改进并与其他工具集成以定制自己的管道。

- 论文链接：https://www.nature.com/articles/s41467-022-32155-w.pdf

3、[Genome Biology | 癌症突变组学特征数据冗余普遍存在](https://mp.weixin.qq.com/s/sW2GUuvXtddz5ZrWe03aEw)


![](https://files.mdnice.com/user/4331/ba776c42-ad9f-493e-a410-c27d6a4187a2.png)

美国科罗拉多大学医学院的研究团队分析了TCGA泛癌症图谱中的组学数据类型，并评估其作为癌症基因突变的多变量功能读数（readouts）的作用。分析结果表明，相对于癌症类型校正基线，基因表达数据能够对大多数基因的突变状态提供良好的预测；对于多数基因而言，多种数据类型几乎具有同等有效的预测能力。与使用单一数据类型的性能最高的模型相比，将数据类型组合到单个多组学模型中进行突变预测的方法几乎没有性能优势。这一研究结果对未来指导癌症功能基因组学的研究具有深远意义。

- 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02705-y


4、[Nature Methods | 自由探索4D核组数据——马坚团队发布Nucleome Browser平台](https://mp.weixin.qq.com/s/CJrYxeruRZr92hlIsUkwVw)

![](https://user-images.githubusercontent.com/45822462/230411263-e3cdface-d8d1-488b-8bee-a77544d40403.png)

由美国卡内基梅隆大学计算机科学学院马坚团队开发的Nucleome Browser是一由多个Web组件构成，用户根据其需求对其数据进行可视化操作的平台。通过该平台，用户可以充分利用不同类型的4D核组数据和不同的3D表观基因组学数据集，是为最终确定基因组结构和染色质构象如何调节健康和疾病中的基因组功能提供有力的工具。

- 论文链接：https://www.nature.com/articles/s41592-022-01559-3



## 博文资讯

5、[国家癌症中心：2023年最新发布全国各省癌症高发地图](https://mp.weixin.qq.com/s/8VVrJgKKdi2z_TR7dInUIg)


![](https://files.mdnice.com/user/4331/ba88dd10-9a88-4eb1-b816-64b2d14c3756.png)


3月22日，《中华肿瘤杂志》发表国家癌症中心、中国医学科学院肿瘤医院的重磅文章，公布2016年中国恶性肿瘤流行数据，首次提供各省主要癌谱流行情况。

这份报告根据全国各肿瘤登记处上报至全国肿瘤登记中心的2016年恶性肿瘤登记数据，估计2016年中国恶性肿瘤流行特征。纳入符合数据质控标准的487个登记处数据。按性别、城乡、年龄分层计算不同肿瘤的发病率和死亡率。结合中国人口数据，估计2016年中国恶性肿瘤发病、死亡情况。

结果显示：中国当前的主要恶性肿瘤包括肺癌、结直肠癌、胃癌、肝癌、女性乳腺癌等，前5位恶性肿瘤发病约占全部新发病例的57.27%。肺癌、肝癌、胃癌、结直肠癌、食管癌是主要的肿瘤死因，约占全部肿瘤死亡病例的69.25%。


6、[编译代码时动态地链接库](https://linux.cn/article-14690-1.html)

编译软件在你如何运行你的系统方面给你很大的灵活性。LD_LIBRARY_PATH 变量，以及 GCC 的 -L 和 -l 选项，是这种灵活性的组成部分。

7、[深度学习优化入门：Momentum、RMSProp 和 Adam](https://mp.weixin.qq.com/s/33z1Hyz_8NAJHEGY6JXxWQ)


![](https://files.mdnice.com/user/4331/cb6cee59-740a-4808-bade-a14d40ce62b2.png)


这篇文章介绍了 3 种基于梯度下降法来解决病态曲率同时加快搜索速度的方法。

8、[Visual Studio Code 引入 “远程隧道” 功能](https://mp.weixin.qq.com/s/30F0HiimbzI2RYExCdtNRQ)


![](https://files.mdnice.com/user/4331/1f1db77f-89a7-4feb-987d-ad4afe5f9e7b.png)


“远程隧道” 功能 是 VS Code 1.74 版本的一个主要特性，它可以让用户通过远程隧道功能，从任何设备、任何地方安全地访问自己的机器和 VS 代码。远程隧道功能可以让用户在不需要 SSH 的情况下，通过 vscode.dev 或 VS Code 桌面客户端，创建一个到任何机器的连接，例如远程桌面、虚拟机或 WSL 发行版。

用户可以通过三种方式启用远程隧道访问功能：

1. 从帐户菜单或命令面板中选择打开远程隧道访问，这需要在远程计算机上安装 VS Code，并使用 GitHub 账户登录。
2. 从安装了 VS Code 并位于 PATH 上的计算机运行 code tunnel 命令，这可以是远程桌面、虚拟机或 WSL 发行版。这个命令会下载并启动 VS Code 服务器，并创建一个到它的隧道。
3. 下载新的 VS Code CLI，并运行 ./code tunnel 命令，这适用于无法在远程计算机上安装 VS Code 的情况，例如锁定的机器或 VM。

- 官方文档：https://code.visualstudio.com/blogs/2022/12/07/remote-even-better


## 工具

9、[marktext | 简单优雅的 Markdown 编辑器](https://github.com/marktext/marktext)


![](https://files.mdnice.com/user/4331/aebce2f9-aa6b-48f7-9c76-ab1e3da0476e.png)

免费、开源、多平台支持！


10、[基于空间和单细胞转录组学数据的转录分布预测和细胞类型解析整合方法的评测](https://github.com/QuKunLab/SpatialBenchmarking)

![](https://user-images.githubusercontent.com/45822462/230411401-207882c6-e350-49ba-a0c9-f235feade958.jpg)

11、[DeepLinc | deep-learning framework for landscapes of interacting cells](https://github.com/xryanglab/DeepLinc)

DeepLinc 是一种用于从单细胞空间转录组数据中进行全新重建细胞相互作用景观的工具。DeepLinc 提供以下实用工具：（1）从不完整和嘈杂的预定义细胞相互作用集中学习；（2）去除假阳性局部相互作用并重建现有相互作用；（3）恢复和重新生成更加无偏见和完整的细胞相互作用景观，包括近距离和远距离相互作用；（4）评估细胞类型之间相互作用的过度或不足表达；（5）提取与细胞相互作用相关的潜在特征；（6）识别多细胞域，以提供组织结构组织的信息。

12、[rex：R语言友好的正则表达式工具](https://github.com/r-lib/rex)


![](https://files.mdnice.com/user/4331/c1f6b698-8cf7-4529-a7db-965f27da3adc.png)

正则表达式是非常强大的功能，但其代码通常很不已读。rex这个R包可以允许你以人类可读的方式构建复杂的正则表达式。但是现在有了chatGPT，正则表达式貌似没有以前那么困难了。

13、[MuSiCal | 突变特征分析工具](https://github.com/parklab/MuSiCal)


![](https://files.mdnice.com/user/4331/adbd2652-0726-42d1-84e7-229eecc91b64.png)

MuSiCal 一款基于Python 3.7环境下的突变特征分析工具。作者提供了Jupyter Notebook 示例脚本，赶快去体验一下MuSiCal 的功能。

- example scripts：https://github.com/parklab/MuSiCal/blob/main/examples

14、[tickle | 在基本的 R 中轻松创建用户界面](https://github.com/coolbutuseless/tickle)

![](https://files.mdnice.com/user/4331/5c4eabce-6904-4696-b3a7-181ae4ee3366.png)

{tickle} 是一个用于在基本的 R 中创建用户界面的包。

该软件包旨在提供：

1. 类似于 shiny 的简化 UI 创建过程。
2. 现代外观的默认视觉效果。
3. 更多文档，以帮助创建常见的 UI 元素，而无需求助于在线 tcl/tk 文档。
4. 一种访问低级 tcl/tk 结构的方法，以实现复杂的效果和自定义。****

## 资源

15、[免费好用的ChatGPT镜像站点](https://github.com/xx025/carrot)

本资源整理了70多个好用的ChatGPT镜像站点，在近日大规模封号情况下大家可以尝试一下。

16、[6 个机器学习可解释性框架！](https://mp.weixin.qq.com/s/R1ke2YGK675vd7_UlsyuNw)


![](https://files.mdnice.com/user/4331/05630458-b857-419b-8a52-8190f5d57b95.png)

随着人工智能的发展为了解决具有挑战性的问题，人们创造了更复杂、更不透明的模型。AI就像一个黑匣子，能自己做出决定，但是人们并不清楚其中缘由。

建立一个AI模型，输入数据，然后再输出结果，但有一个问题就是我们不能解释AI为何会得出这样的结论。需要了解AI如何得出某个结论背后的原因，而不是仅仅接受一个在没有上下文或解释的情况下输出的结果。在本文中，将介绍6个用于机器学习可解释性的Python框架。

17、[icons | 网络图标库](https://github.com/mitchelloharawild/icons)


![](https://files.mdnice.com/user/4331/ca218d3d-6012-41af-a62c-27d119041921.png)


icons包可以让用户在报告、演示和应用中轻松地添加网络图标。它集成了许多来自网络的流行图标库。比如：Font Awesome 、Academicons、Simple Icons、Google’s Material Design、Octicons、Feather Icons、Bioicons 等。

## 历史上的本周

- 第 31 期：[Openbiox 生物信息学社区 2022 拟开展项目，正式招募 ！](https://mp.weixin.qq.com/s?__biz=MzA5NjAyMzU1OA==&mid=2247490131&idx=1&sn=d72a20ec473e557fd57d758d68253063&chksm=90b73f3aa7c0b62c029e998800df73702243e417202637a3a08632960b4f8e276408310394b6&scene=178&cur_album_id=2042658844287336450#rd)

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

