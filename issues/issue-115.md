---
date: 2024-03-17
comments: true
---

# 生信爱好者周刊（第 115 期）：罗莎琳德·富兰克林对DNA双螺旋结构的真实贡献

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://files.mdnice.com/user/38661/3fa5d148-f24f-4e90-83ef-a0390acc5969.png)
来源：https://www.dreamstime.com/

## 本周话题：

[Nature：揭开罗莎琳德·富兰克林对DNA双螺旋结构的真实贡献，她并非受害者，而是平等贡献者](https://mp.weixin.qq.com/s/hu1EkQxO7RhOdNZFw_xkRQ)
> 1953年4月25日，詹姆斯·沃森（James Watson）和弗朗西斯·克里克（Francis Crick）在 Nature 期刊发表了一篇开创性论文，这篇论文揭示了遗传物质DNA的双螺旋结构，从此开启了分子生物学时代。1962年，沃森、克里克和威尔金斯一起荣获了诺贝尔生理学或医学奖。
然而，一直有一个传言，DNA双螺旋结构这一划时代的伟大发现源于沃森在未获得罗莎琳德·富兰克林（Rosalind Franklin）同意或知晓的情况下看到了她拍摄的DNA的X射线图片，也就是著名的“照片51号”，这张照片也被认为是“分子生物学的点金石”。
如今，“照片51号”已经成为了代表富兰克林的成就和她遭受的不公待遇的象征。外界认为，富兰克林是一个优秀的科学家，但她未能分辨出自己拍摄的这张DNA的X射线图片所传达的关于DNA的信息，她在照片拍摄后几个月都没有意识到照片的重要性，直到沃森一眼看出其中蕴含的双螺旋结构信息。
所以，真实情况真的是这样吗？

`@JnanZhang`:“富兰克林对DNA双螺旋结构的贡献不容遗忘，但“DNA之母”绝不是富兰克林的全部注脚，富兰克林对科学的热爱，以及她对科学界女性的鼓舞，将在未来的历史长河中依然熠熠生辉。”

## 生信研究
1、[ Genome Biology | 探索跨单细胞的功能蛋白质协变的新方法](https://mp.weixin.qq.com/s/rTCTwkg_XXlO_75_K4EArQ)

![](https://files.mdnice.com/user/38661/fce94711-ce00-4145-941d-16a99e54fbcf.png)

本研究展示了nPOP，一种能够同时制备数千个单细胞的方法，包括裂解、消化和标记8-20nL体积的单细胞。nPOP实现了灵活、自动化和高度并行化的单细胞蛋白质组学样品制备。可以量化成千上万个单细胞的蛋白质协变，并揭示密切相关的细胞状态间功能协调的生物学差异。可在https://scp.slavovlab.net/nPOP 获得nPOP平台的支持。
- 论文链接：https://doi.org/10.1186/s13059-022-02817-5

2、[PNAS | 卢煜明/江培勇团队基于末端基序反卷积分析绘制cfDNA片段化图谱](https://mp.weixin.qq.com/s/3j_5qodCt7fGahcgutsUbQ)

![](https://files.mdnice.com/user/38661/4bf59945-5291-454c-b40c-34c6aa170e30.png)


细胞游离DNA（cfDNA）片段携带了大量与DNA核酸酶活性和起源组织有关的信息，其片段化是非随机的，部分由各种DNA核酸酶介导，能够形成特征性的cfDNA末端基序。已有研究表明，cfDNA末端基序有助于预测多种不同的疾病类型，或可作为监测治疗反应（核酸酶活性）的生物标志物。该研究通过对cfDNA的短末端核苷酸序列（称为末端基序）进行数学分析，发现了六种不同类型的cfDNA片段模式，其中几种模式与核酸酶相关，如DFFB、DNASE1和DNASE1L3。这些模式图谱揭示了cfDNA片段化过程，其异常可作为癌症和免疫疾病的标志物。

- 论文链接：https://www.pnas.org/doi/10.1073/pnas.2220982120

3、[Genome Med | 灵敏检测所有类型de novo突变！仅HiFi长读长测序即可生成全面的WGS数据](https://mp.weixin.qq.com/s/y7ldBCQWrxBLtIvrYYxOUg)

![](https://files.mdnice.com/user/38661/79236928-32b0-48a1-8a39-8f916f0c75ee.png)

研究团队仅通过HiFi长读长测序这一单一技术，构建了最全面的突变数据集，实现了准确的替换、indel、STR和SV检测。该技术的准确性甚至允许在所有不同变异水平上灵敏地检测DNM，并且还允许定相（phasing），有助于区分真阳性和假阳性DNM。
- 论文链接：https://doi.org/10.1186/s13073-023-01183-6

4、[Nature Communications | 国产单细胞转录组技术实现FFPE样本高性能检测](https://mp.weixin.qq.com/s/gV0-A9SMBgv5xBvRWFvCpQ)


![](https://files.mdnice.com/user/38661/b86de370-13b8-43f0-81f3-377f530bfdf3.png)


本研究发表了一种新的基于随机引物的高通量单细胞核测序技术snRandom-seq，并成功将其用于对FFPE样本的检测。snRandom-seq是一种适用于FFPE样本，且具有高灵敏度和全长特点的高通量snRNA-seq技术。

- 论文链接：https://www.nature.com/articles/s41467-023-38409-5

## 博文资讯
5、[英文 | 使用 slider 进行滚动汇总](https://themockup.blog/posts/2022-11-16-rolling-summaries-with-slider-in-r/index.html)

slider 是一个使用窗口函数进行滚动分析的软件包。“窗口函数”是从SQL中借来的一个术语，这意味着当逐步浏览数据时，一些函数会反复应用于数据的不同“窗口”。窗口函数应用的典型示例包括滚动平均数、累积和和更复杂的事物，如滚动回归。

- R 包：https://slider.r-lib.org/index.html 

6、[Creating interactive visualizations with {ggiraph} (with or without Shiny)](https://albert-rapp.de/posts/ggplot2-tips/17_ggiraph/17_ggiraph.html)

![](https://files.mdnice.com/user/38661/631be2c1-8006-4306-b1b9-f0c6f21864da.png)

在这篇博文中，你将学习如何使用`{ggiraph}`将 `ggplot` 变为交互式可视化图。

7、[Nature专题丨7篇研究论文聚焦肺癌进化的分子路径](https://mp.weixin.qq.com/s/iKdTbQ5i4vLbDsjKcQR3Ew)

![](https://files.mdnice.com/user/38661/168642a9-dfef-4418-a020-aeb4a5f93f8c.png)


Nature对非小细胞肺癌的分子进化特征、遗传因素、细胞水平变化以及相关治疗手段的发展进行的全面报道。

原文链接：
-  https://doi.org/10.1038/s41586-023-05729-x
- https://doi.org/10.1038/s41586-023-05776-4
- https://doi.org/10.1038/s41586-023-05783-5
- https://doi.org/10.1038/s41586-023-05706-4
- https://doi.org/10.1038/s41586-023-05771-9
- https://doi.org/10.1038/s41591-023-02230-w

- https://doi.org/10.1038/d41586-023-00934-0


## 工具
8、[https://github.com/sumatrapdfreader/sumatrapdf](https://github.com/sumatrapdfreader/sumatrapdf)

![](https://files.mdnice.com/user/38661/0d2ee756-7a97-438a-8b8e-3673fc9c4cf9.png)

SumatraPDF 是一款适用于 Windows 的多格式（PDF、EPUB、MOBI、CBZ、CBR、FB2、CHM、XPS、DjVu）阅读器。


9、[fastplotlib | 使用pygfx渲染引擎在WGPU上运行的下一代快速绘图库](https://github.com/fastplotlib/fastplotlib)

![](https://files.mdnice.com/user/38661/9c10cea6-4b32-4986-bf2f-3b1c20b66c69.png)

10、[https://github.com/nick-ulle/rstatic](https://github.com/nick-ulle/rstatic)

![](https://files.mdnice.com/user/38661/21574950-0b30-4f1e-8fcc-7b2606ffdc1f.png)

`rstatic`是一个能让 R 代码分析变得更简单的软件包。

 
## 资源
11、[Interactive Linear Algebra](https://services.math.duke.edu/~jdr/ila.html)

![](https://files.mdnice.com/user/38661/4d200250-b220-4b19-9064-f74ca2a8acd0.png)

这是一本线性代数入门教科书。

12、[https://github.com/rmcelreath/stat_rethinking_2023](https://github.com/rmcelreath/stat_rethinking_2023)

![](https://files.mdnice.com/user/38661/d8dcc6b1-e87f-4e1a-9544-ace7800b0727.png)
本课程教授数据分析，但重点是科学模型



## 历史上的本周
第 74期：[新技术的最大风险](https://mp.weixin.qq.com/s/vKXSfQZKtFLUzTAV7166Sw)

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

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

