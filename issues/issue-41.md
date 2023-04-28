---
date: "2023-3-19"
comments: true
---

# 生信爱好者周刊（第 41 期）：人体是一个共生生态系统

> 从本周起，新增「历史上的本周」一栏。本周刊已运营 1 年，发布 40+ 期，希望给长期读者和搜索到的读者带去一些帮助。如果大家觉得质量还可以，请大家多多分享转发！

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo) | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community)

## 封面图

<img width="605" alt="image" src="https://user-images.githubusercontent.com/25057508/184833149-9f166f41-5635-4947-8b97-c2730ade0d57.png">

肠道菌群示意图（[via](www.pexels.com)）

## 本周话题：[人体是一个共生生态系统](https://mp.weixin.qq.com/s/vJ2RV3Qhgu3QUp2RJP3pYg)

本周话题来自[《碱基周报（第 007 期）：人体是一个共生生态系统》](https://mp.weixin.qq.com/s/vJ2RV3Qhgu3QUp2RJP3pYg)，对菌群感兴趣的可以详细阅读下。


![](https://files.mdnice.com/user/4331/9b8cf248-4a2c-4da3-b1b6-a30d2ab48e88.png)


> 这个星球的真正主宰是那些我们肉眼看不见的微生物，包括：真菌、细菌和病毒等。人类的身体大约由 30 万亿个细胞组成，但却容纳了超过100万亿个微生物，富集在我们的消化道、生殖道和皮肤等部位。这其中微生物最富集的地方是肠道，人体的大多数微生物都生活在这里，每立方厘米大肠中的细菌数量，比地球上的总人口还要多。

`ShixiangWang` - 看不到、被忽视的可能更重要，比如空气、交通、陪伴，还有肠道菌群！

## 生信研究

1、[Science | 19种癌症类型的体细胞非编码突变图谱](https://mp.weixin.qq.com/s/if7FSnI0C8-gQ9bLz0tY1Q)


![](https://files.mdnice.com/user/4331/337b6790-fc66-4c10-9252-38d471e2f4c3.png)

该研究构建形成了包括19种主要癌症类型基因组在内不同突变模式的全基因组概况图谱。研究结果表明，非编码突变与广泛的不同生物学过程相关，其在基因组中的位置对功能注释至关重要。该研究也为全面解释全基因组测序数据提供了蓝图，并为未来研究非编码突变在肿瘤发展中的作用奠定了基础，最终为非编码癌症基因组的转化研究和靶向治疗铺平道路。

论文链接：https://www.science.org/doi/10.1126/science.abg5601

2、[PNAS | 急性T淋巴细胞白血病基于全转录组分子分型](https://mp.weixin.qq.com/s/zqpwGRs-_1Pt-S4MO57Mig)


![](https://files.mdnice.com/user/4331/8d2d92a2-1ad2-4a03-a046-e72d3434fb23.png)

急性T淋巴细胞白血病（T cell acute lymphoblastic leukemia，T-ALL）是一类起源于造血系统的恶性肿瘤，成人患者预后较差。作者整合了707例T-ALL患者的RNA-seq数据进行分子分型，分为了10个分子表达亚型，绘制了T-ALL转录组全景图谱。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/35385357/


3、[NAR | SPENCER：肿瘤非编码RNA来源的短肽数据库](https://mp.weixin.qq.com/s/X0oCaqmo1oIfbg69IPThyA)


![](https://files.mdnice.com/user/4331/5f90770d-17f8-43fd-8780-b2e11bdd17a1.png)

近些年人们发现，有部分被定义的非编码RNA存在着阅读框，可以编翻译出一些短肽，而这些短肽的也在肿瘤发生发展中有着重要的功能。因此，系统研究肿瘤特异性非编码RNA来源的短肽，将会对理解肿瘤发生发展的机制提供新的视角。为此，来自中山肿瘤医院的生信团队开发了SPENCER 数据库（<https://spencer.renlab.org/>），收录了较为全面的ncRNA来源短肽的信息，并免费公布给大家使用。

- 论文链接：https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8728293/


4、[NBT | 单细胞多组学数据整合与调控推断新方法](https://mp.weixin.qq.com/s/JDHu1Cb4bhKVF_9dcMEgEQ)


![](https://files.mdnice.com/user/4331/a05ea3f0-7456-44db-8ec3-e8439a95a429.png)

本文提出了基于图耦联策略的深度学习整合单细胞多组学并进行调控推断的新方法-GLUE，该工作由北京大学/昌平实验室高歌课题组完成。

- 论文链接：https://www.nature.com/articles/s41587-022-01284-4


5、[Cancer Discovery | 癌症机器学习新算法REFLECT：基于协同突变特征预测癌症最佳治疗组合](https://mp.weixin.qq.com/s/7HnS_K-uqHaklmnCSUihgg)


![](https://files.mdnice.com/user/4331/a0d48157-2a65-4cfd-98a5-649608aa6b8f.png)

REFLECT平台集成了机器学习和癌症信息学算法来分析生物肿瘤特征，包括基因突变、拷贝数变化、基因表达和蛋白质表达畸变，并可识别常见的协同突变。通过REFLECT预测药物组合可以提高患者的受益比例。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/35412613/

## 博文资讯

6、[R 学习笔记：色彩](https://zhuanlan.zhihu.com/p/30407500)

![](https://files.mdnice.com/user/4331/34eac579-74a8-4f9a-a21f-7bbb9d8d1a36.png)

色彩空间 (color space) 是计算机上颜色的组成形式。常见的色彩空间有RGB、HSV、HCL等。grDevices包提供了色彩空间坐标与十六进制颜色间转换；RColorBrewer包提供 ColorBrewer 调色板；colorspace包提供更多色彩空间转换函数。

R包链接：
- https://www.rdocumentation.org/packages/grDevices/versions/3.6.2
- https://r-graph-gallery.com/38-rcolorbrewers-palettes.html
- https://cran.r-project.org/web/packages/colorspace/vignettes/colorspace.html


7、[brochure包绘制多页shiny](https://colinfay.me/brochure-r-package/)

本文介绍了brochure包及如何用它绘制多页Shiny。

```R
brochureApp(
  # First page
  page(
    href = "/",
    ui = fluidPage(
      h1("This is my first page"), 
      plotOutput("plot")
    ),
    server = function(input, output, session){
      output$plot <- renderPlot({
        plot(iris)
      })
    }
  ), 
  # Second page, without any server-side function
  page(
    href = "/page2", 
    ui =  fluidPage(
      h1("This is my second page"), 
      tags$p("There is no server function in this one")
    )
  )
)
```

8、[scMappR - 推断驱动差异基因表达的细胞类型：制造signature matrix](https://mp.weixin.qq.com/s/jKhst1jM1_BQwrQfm1HemQ)


![](https://files.mdnice.com/user/4331/5a4dfd35-421b-41ee-8034-32fc8c50a4ee.png)

本文介绍了通过scMappR构建cell-type signature matrix的过程。

- 论文链接：https://academic.oup.com/nargab/article/3/1/lqab011/6148840


9、[45 个 Git 经典操作场景，专治不会合代码](https://mp.weixin.qq.com/s/qBV69WEuIUhTA8eaMDmWFw)


![](https://files.mdnice.com/user/4331/8353147a-4906-4046-8313-e725ce6acd1e.png)

Git是目前世界上最先进的分布式版本控制系统，熟练使用Git已然成为程序员的一项必备技能，平常工作中合并代码部分大多人可能会使用Sourcetree这样牛X的客户端工具，但若想真正展示个人实力还需要掌握足够多的git命令的使用，本文整理了45个日常使用git合并代码的经典操作场景，基本涵盖了工作中的需求。


## 工具

10、[ar5iv - 一步告别arXiv公式排版错误，手机也能轻松看文献](https://zhuanlan.zhihu.com/p/466856865)


![](https://files.mdnice.com/user/4331/0f6c7bf5-545c-4b38-ac60-0e8fe5fb23cb.png)


ar5iv能够以现代HTML5格式显示预印本论文。ar5iv的使用非常简单，只要将网址中的arXiv中的X换成5再回车，页面就能自动跳转。



11、[Chrome生产力神器 Omni](https://zhuanlan.zhihu.com/p/467868743)


![](https://files.mdnice.com/user/4331/b15dd3e8-6bef-4d26-a794-eae26c36a2b5.png)


Omni是一个浏览器插件，能够让你的浏览器拥有Mac电脑一般的体验，最近在Github趋势榜和ProductHunt上已荣登榜首，这是一款集合了书签、历史记录、浏览标签、三位于一体的页面管理器，成为大受各种程序员、产品设计师的追捧的生产力工具！


12、[ambiorix - 受expression.js启发的R Web框架](https://github.com/devOpifex/ambiorix)


![](https://files.mdnice.com/user/4331/8a349839-e643-47dc-a456-2556d0e3fa95.png)




13、[Celda](https://github.com/campbio/celda)


![](https://files.mdnice.com/user/4331/e6d5a435-dfef-44d9-aa50-93f17e509a36.png)


Celda是一款基于贝叶斯分类模型作用于聚类单细胞RNA测序（ScRNA-Seq）数据的的套件。它能够执行“双聚类”，并同时将基因聚集到基因模块中，并将细胞分为细胞亚群。它还包含一种叫做Decontx的新型贝叶斯方法，可在没有空液滴信息的情况下在单个细胞中估算并消除RNA的污染。同时，还包括各种ScRNA-Seq数据可视化的功能。

- Github: <https://github.com/campbio/celda>
- Bioconductor manual: <http://bioconductor.org/packages/release/bioc/vignettes/celda/inst/doc/decontX.html>

14、[PHATE - 一种高维数据可视化工具](https://github.com/KrishnaswamyLab/PHATE)


![](https://files.mdnice.com/user/4331/3dc10836-5cdf-456d-87c0-d0367cf4a1bb.png)


PHATE has been implemented in Python >=3.5, MATLAB and R.

- 论文链接：https://doi.org/10.1038/s41587-019-0336-3


## 资源

15、[GNNs Recipe - 学习图神经网络GNNs的重要资源](https://github.com/dair-ai/GNNs-Recipe)


![](https://files.mdnice.com/user/4331/e3a7d869-6116-4534-af64-c5479dfd2868.png)



16、[图书 - Data Science in a Box](https://datasciencebox.org/)


![](https://files.mdnice.com/user/4331/074ea5d6-db8c-4d92-a10e-57988249f1e4.png)



## 历史上的本周

- 2021：[第一期：生信是什么](https://mp.weixin.qq.com/s/88ePFB6v-doCagIHX79FTg)

## 贡献者（GitHub ID）

「Openbiox 生信周刊」运维小队：

- `@ShixiangWang`
- `@kkjtmac`
- `@NiEntropy`
- `@He-Kai-fly`
- `@JnanZhang`
- `@Tomcxf`
- `@wangdepin`

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

