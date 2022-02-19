# 生信爱好者周刊（第 18 期）：过去50年最重要的统计学思想是什么？

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

GitHub 粉们可以通过 Watch 仓库的 Release（提前）关注发布内容。

讨论区的帖子[《谁在招人？》](https://github.com/ShixiangWang/weekly/issues/2)，提供生信深造和就业信息，欢迎访问或发布学位攻读/工作/实习等岗位。

[「本期专用讨论区」](https://github.com/ShixiangWang/weekly/issues/456)

## 封面图

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645279725781-iShot2022-02-19%2022.08.24.png)

（[via](https://pixabay.com/zh/photos/animal-puppy-dog-canine-pet-4085255/)）

## 本周话题：[过去50年最重要的统计学思想是什么？](https://mp.weixin.qq.com/s/_FuXZHmwTunEZ1kGgeoRSA)

图灵奖得主、“贝叶斯网络之父”Judea Pearl在Twitter上分享了一篇新论文“What are the most important statistical ideas of the past 50 years?”（过去50年中最重要的统计思想是什么？）

这篇论文由哥伦比亚大学统计学教授Andrew Gelman和阿尔托大学计算机科学系副教授Aki Vehtari所著，他们根据自己的研究和文献阅读经验总结出了过去半个世纪以来最重要的8个统计思想，并表示：“它们是独立的概念，涵盖了统计方面不同的发展。这些思想都在1970年前的理论统计文献和各个应用领域的实践中就已经出现。但是在过去的五十年中，它们各自已经发展到足以成为新事物的程度。”

他们认为，过去半个世纪中最重要的统计思想是：反事实因果推理，基于bootstrapping（自助抽样法）和基于模拟的推理，超参数化模型和正则化，多层模型，泛型计算算法（generic computation algorithms），自适应决策分析，鲁棒推理和探索性数据分析（未按时间顺序，排序不分先后）。

## 生信科技动态

1、[2021年度“中国生物信息学十大进展”公布](https://mp.weixin.qq.com/s/yUPY0XoHHqZb4dJkC7nCUg)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645279951685-image.png)

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645279963729-image.png)


2、[第八届全国计算生物学与生物信息学学术会议暨生物医学大数据与人工智能大会](https://mp.weixin.qq.com/s/Dvg4-UIm2SXRQpbjjikt5g)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645280021020-image.png)

**时间和会议形式**

- 会议时间：2022年4月7-10日
- 会议形式：线下
- 会议地点：广东省广州市华钜君悦酒店

**组织机构**

- 主办单位：中国生物工程学会计算生物学与生物信息学专业委员会
- 承办单位：
  - 中山大学中山眼科中心
  - 中山大学中山医学院
  - 南方医科大学
- 协办单位：中国计算机学会生物信息学专委会

3、[Nature Communications | 超低频变异低深度检测技术——QBDA，助力MRD液体活检实现精准定量](https://mp.weixin.qq.com/s/uwM2ANd9BPIVb7jWLkqDig)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645280179894-image.png)


阅尔基因的科学家和MD Anderson癌症研究中心合作在知名期刊Nature Communications上发布了一项可对低于0.01%VAF的体细胞突变进行精确定量的研究。团队通过将分子标签技术与抑制探针置换扩增（BDA）等位基因富集技术相结合，发明了新的定量BDA（QBDA）方法，克服了BDA的潜在偏差，实现了更为精准的VAF定量。与同类技术相比，QBDA仅需6~20ng的DNA起始量，同时测序深度降低了10倍以上。 

4、[Nature Communications | 单细胞差异分析方法评测](https://mp.weixin.qq.com/s/dUedBCozMqmpL8ptXmf1HA)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645280258712-image.png)

本研究使用18个已发表的“金标准”数据集，评测了14个目前常用的差异分析方法，pseudobulks方法要优于single-cell分析方法，指出现在的很多发表的差异分析方法是错误的，会有太多的假阳性。

## 文章

1、[cnetplot拿来画关系型数据怎么样？](https://mp.weixin.qq.com/s/4fFt0-sjjwa18tG5qoeXHw)

本文介绍了使用自定义的数据绘制cnet图形。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645280410378-image.png)

2、[Quicker动作推荐](https://mp.weixin.qq.com/s/dBXkvaoXkYPSnTls1CS41g)

最近接触到的一个Windows效率工具，大家感兴趣可以看看。从设计和一些插件应用来看还是蛮好玩的。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645280511440-image.png)

3、[双面IFN-γ：抗癌又促癌](https://mp.weixin.qq.com/s?__biz=Mzg2OTczNjI0OQ==&mid=2247489298&idx=1&sn=0393e0fed1b70de903cbcee19b76ddb7&source=41#wechat_redirect)

IFN-γ致癌和抗癌两面性，取决于环境和他作用的靶细胞。


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645280666802-image.png)


## 工具

1、[factoextra : Extract and Visualize the Results of Multivariate Data Analyses](https://github.com/kassambara/factoextra)

一个常见的多维分析一站R包。网上介绍的推文很多。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645280724741-image.png)

2、[rTorch: PyTorch的R接口](https://github.com/f0nzie/rTorch)

该包提供PyTorch特性并附加一些R的支持特性。

3、[distant - remotely edit files and run programs](https://github.com/chipsenkbeil/distant)

4、[pbapply: adding progress bar to '\*apply' functions in R](https://github.com/psolymos/pbapply)

使用方式很简单：

```r
out <- if (requireNamespace("pbapply", quietly = TRUE)) {
   pbapply::pblapply(X, FUN, ...)
} else {
   lapply(X, FUN, ...)
}
```


## 资源

1、[命令行常用工具的替代品](https://mp.weixin.qq.com/s/gkPbQTyhAHwYrpzJjftJVQ)


![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/2022-2-19/1645281107743-image.png)


程序员离不开命令行，许多经典命令是每天必用的，比如ls和cd。

虽然它们很好用，但是由于历史原因，往往也有一些缺点，比如用法不符合直觉、难以配置，有些速度也不快。

这些年，它们的替代品开始出现，而且越来越多，大家开始尝试使用现代语言，重新实现这些经典命令。本文总结一下这些替代品，其中有些真的很不错，值得你在自己的计算机上安装。

2、[老程的转录组](https://mp.weixin.qq.com/mp/appmsgalbum?action=getalbum&__biz=MzUzMTEwODk0Ng==&scene=1&album_id=1749887454125293572&count=3#wechat_redirect)

这是一系列基于常用软件以及一些新开发的软件进行RNA-seq数据分析的推文，希望不仅能为大家入门RNA-seq数据分析有所帮助，更能够从中挖掘到与众不同的信息。


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

| ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440597.jpg) | ![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109171440452.jpg) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://gitee.com/ShixiangWang/ImageCollection/raw/master/png/202109101438292.jpg)

（完）

