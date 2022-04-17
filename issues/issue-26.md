# 生信爱好者周刊（第 26 期）：CRISPR的专利权

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo)

## 封面图

![](https://files.mdnice.com/user/4331/f7520639-5d0e-45e7-a155-16a76e1a9140.jpeg)

[via](https://twitter.com/NatRevImmunol/status/1502227036445847554/photo/1)


## 本周话题：[CRISPR的专利权](https://mp.weixin.qq.com/s/iAIOpUfW5DwIzuHel4fq8A)

在围绕CRISPR基因编辑技术的专利纠纷中，美国专利商标局已经确定博德研究所团队是第一个发明CRISPR-Cas9来编辑人类细胞并用于制造药物的团队，而不是诺奖得主 Jennifer Doudna 和 Emmanuelle Charpentier 所属的CVC团队。

这一裁决意味着，在美国运营的做CRISPR基因编辑相关的公司，如果之前仅获得CVC团队的专利授权，包括CVC团队自己的 Intellia Therapeutics、CRISPR Therapeutics 等等，将不得不与博德研究所团队进行专利谈判。


![](https://files.mdnice.com/user/4331/aa505389-e54c-4282-aebd-e5699eb9d5b6.png)



## 生信科技动态

1、[Nature Methods | Micro-Meta App: 基于社区规范收集显微镜元数据的交互式工具](https://www.nature.com/articles/s41592-021-01315-z)


![](https://files.mdnice.com/user/4331/0d0a0cc3-4401-42e5-976a-840a0f26f9dd.png)


为了质量、解释、再现性和共享价值，显微镜图像应附有用于产生它们的条件的详细描述。Micro-Meta App是一款直观、高互操作性的开源软件工具，是在4D核组(4DN)联盟的背景下开发的，旨在促进相关显微镜元数据的提取和收集，除了大大减轻质量保证的负担，该应用程序的视觉特性使其特别适合于培训目的。

2、[Cancer Cell | 多组学揭示黑色素瘤免疫治疗响应因素—IFNγ和肿瘤突变负荷TMB](https://mp.weixin.qq.com/s/0n1oZ6rKuKjdt6RrU79wJQ)


![](https://files.mdnice.com/user/4331/89a9d05f-7632-4dbd-99ab-c452e58a7ca4.png)

这项研究利用多组学以及临床样本信息揭示肿瘤突变负荷与IFNγ通路可作为预测黑色素瘤患者接受免疫治疗收益的关键因素，也提示对于不响应患者仍需进一步研究。

3、[Nature Cancer | 张泽民/韩为东合作揭示anti-PD-1免疫治疗在肺癌中的作用机制](https://mp.weixin.qq.com/s/7y-wAE-s4WcQa5YqqwJq9A)


![](https://files.mdnice.com/user/4331/741007f6-daf3-48ba-ba05-f5c7c9e7b397.png)


之前斯坦福大学Howard Chang研究组提出了克隆替代（clonal replacement）的概念，认为治疗后肿瘤中的肿瘤特异T细胞的克隆型都是新出现的。而该研究发现，在肺癌治疗的过程中，新的克隆和之前存在的克隆都会被招募到肿瘤中进而发挥功能。针对这一现象，研究人员提出了克隆复兴（clonal revival）的概念，拓展了clonal replacement的模式。该研究的科学发现揭示了anti-PD-1疗法在肺癌中的作用机制，为开发新的临床检测与治疗手段提供了新的思路。


## 文章

1、[解读 Julia 的 2021：逐步迈向主流编程语言]()


![](https://files.mdnice.com/user/4331/d2ce2615-b062-456d-8d88-5f6b96928515.png)

在过去的 2021 年，Julia 编程语言社区依然保持了高速发展。据统计，目前 Julia 的全球总用户量已超过一百万，有一万多家公司和一千五百多所高校下载和使用了 Julia。此外，一些世界名校，如北京大学，MIT、Stanford 和 Berkeley 等，已经在教学中使用 Julia 语言。

作为一门动态编译型语言，Julia 一方面给予我们像 Python 一样的开发效率，另一方面又给予我们像 C/C++ 一样的执行效率，因此吸引了大量优化算法、微分方程、自动微分、量子计算、机器学习等计算领域的研究者。目前 Julia 语言已经逐渐成熟和稳定，我们有理由相信未来随着 Julia 生态的进一步成熟，Julia 的优势能够更进一步地发挥出来。

2、[PyCaret | 几行代码搞定机器学习建模](https://mp.weixin.qq.com/s/TxFMDROzS0Z33j6XxP4JjQ)

从本质上来看，PyCaret 是一个 Python 库，封装了多个机器学习库和框架，如 sci-kit-learn、XGBoost、Microsoft LightGBM、spaCy 等等。包括 6 个模块，支持有监督和无监督模型的训练和部署，分别是分类、回归、聚类、异常检测、自然语言处理和关联规则挖掘。每个模块封装特定的机器学习算法和不同模块均可以使用的函数。用户可以根据实验类型，将模块导入环境中。

3、[机器学习算法优缺点对比（汇总篇）](https://mp.weixin.qq.com/s/n0pvDC_aE8RzRSBndqPllw)

本文的目的，是务实、简洁地盘点一番当前机器学习算法。

## 工具

1、[abess: Fast Best-Subset Selection in Python and R](https://github.com/abess-team/abess)

abess 库的目标是解决一般的最佳子集选择，即找到预测器的一个小子集，这样得到的模型预期具有最高的准确性。最佳子集的选取具有重要的科学研究和实际应用价值。例如，临床医生想要根据一些重要基因的表达水平来了解病人是否健康。

![](https://files.mdnice.com/user/4331/200b3023-0bea-4ed7-b0d4-5c5f05a388d0.png)

2、[citr: RStudio Addin to Insert Markdown Citations](https://github.com/crsh/citr)

citr提供了函数和RStudio插件来搜索bibtex文件，以创建和插入格式化的Markdown引用到当前文档中。

![](https://files.mdnice.com/user/4331/90941eda-7c70-4701-b2f9-9fda6a0bb06a.png)

3、[causal-learn：基于Python的因果发现算法平台](https://mp.weixin.qq.com/s/6ugyoAsXlT_aaROgqefiog)

Causal-learn用Python实现了CMU开发的基于Java的Tetrad因果发现平台（WAIC2020 SAIL 之 L奖），并进一步加入新的算法和功能。其中包含了因果发现的经典算法与API，并且提供了模块化的代码，以方便研究者实现自己的算法。Causal-learn所有模块均基于Python实现，从而避免了传统因果发现库对R/Java的依赖，为Python开发者提供便利。

![](https://files.mdnice.com/user/4331/8fb454af-725d-4673-a48a-6a11a5f2d991.png)

4、[{statsExpressions}: Tidy dataframes and expressions with statistical details](https://indrajeetpatil.github.io/statsExpressions/)

statsexpression包有两个关键目标:

- 为使用整洁的数据进行统计分析提供一致的语法(以管道友好的方式)
- 为绘制函数提供统计表达式(预先格式化的文本内统计结果)。

![](https://files.mdnice.com/user/4331/cbacc3bc-6372-4d25-9bcb-2396646cfdfd.png)

5、[broadinstitute/gistic2 - 软件官方仓库](https://github.com/broadinstitute/gistic2) 


## 资源

1、[LitVar | 突变相关文章检索工具](https://mp.weixin.qq.com/s/MVGFahqpnAqGtuQrmefL9g)


![](https://files.mdnice.com/user/4331/f0450cce-b36f-44a9-ac3b-54390b45aba3.png)

2、[coding-for-economists](https://github.com/aeturrell/coding-for-economists)

3、[Current best-practices in single-cell RNA-seq: a tutorial](https://github.com/theislab/single-cell-tutorial)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648291334186-bd3390be-c83c-4396-aabd-ca39f588c15d.png)

感谢以下读者往期的赞赏：

- iCanHelp

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

