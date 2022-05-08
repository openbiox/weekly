# 生信爱好者周刊（第 28 期）：华大Stereo-seq系列成果揭秘超高分辨率生命全景时空图谱

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo)

Stereo-seq芯片工作原理及小鼠胚胎发育时空转录组图谱。（[via](https://mp.weixin.qq.com/s/X5tzRGy3MxqywcoQgwsdmw)）

## 封面图


![](https://files.mdnice.com/user/4331/7fdfcddf-0ac8-48a0-9b1f-32a6aa067549.png)


## 本周话题：华大Stereo-seq系列成果揭秘超高分辨率生命全景时空图谱


![](https://files.mdnice.com/user/4331/1248661d-4c84-448f-9b4f-b39cec854769.png)


国际顶级期刊Cell和子刊Developmental Cell，上线了4篇应用Stereo-seq技术的研究文章，揭示其在小鼠、斑马鱼、果蝇、拟南芥等模式生物中的应用成果，其中Cell文章详细介绍了Stereo-seq技术原理和细节。此外，Cell出版社官网还特设专题网页（<https://www.cell.com/consortium/spatiotemporal-omics>），展示了以上4篇文章及4篇应用Stereo-seq技术的BioRxiv预印成果，包括食蟹猴脑时空组图谱、蝾螈脑再生时空图谱、实体瘤时空组图谱等。

相较国际同类技术，Stereo-seq通过时空捕获芯片，结合原位RNA捕获，实现了500 nm的分辨率，同时捕获面积可达13cm x 13cm，成为全球首个同时实现“纳米级分辨率”和“厘米级全景视场”的技术，且实现了基因与影像同时分析。与当前其他技术相比，在相同的精度下，Stereo-seq具备更灵敏和更强的mRNA捕获能力。该技术作为新时代的分子 “显微镜”，为重新认知器官结构、生命发育、物种演化和定义人类疾病提供了底层工具，将推动继显微镜和DNA测序技术以来的生命科学领域第三次科技革命。 

## 生信科技动态

1、[Nature | 基因突变不是随机的](https://mp.weixin.qq.com/s/K7pS54wHtu7V0apFU4rw6w)


![](https://files.mdnice.com/user/4331/d7345d79-d06a-49f0-8fe0-bd3501b6611e.png)


自20世纪上半叶起，突变的随机性就一直是生物演化理论的重要基础。这个观点如同生物学领域的公理，对于生物学家建立演化模型、理解遗传多样性产生了深刻影响。现在，这个经典的观点受到一项全新研究的有力挑战。

在一篇发表于《自然》杂志的论文中，一支国际研究团队通过对模式植物拟南芥的研究提出，突变的诞生不是完全随机的，相反，突变出现的区域有着明显的规律性。这个发现从根本上改变了我们对于生命演化的理解，并且有望帮助科学家培育具有更优良性状的作物，甚至帮助人类对抗癌症。

2、[Nature Communication｜基于2万余个肿瘤体细胞突变谱，揭示年龄对肿瘤突变数量及进化时间的影响](https://mp.weixin.qq.com/s/vU15-tZGP1MCG3GwGA9SZg)


![](https://files.mdnice.com/user/4331/6eb4db7c-de3a-45a7-b9fa-a2ba980eb64f.png)


该研究通过分析来自TCGA、AACR GENIE和PCAWG三个项目中的数据，揭示了年龄对肿瘤中的突变数量（每年每兆碱基0.077个突变）及其进化时间的影响，绘制了具有临床意义的与年龄相关癌症体细胞突变图谱。

3、[Nature | slide-DNA-seq - 自带GPS的测序技术](https://mp.weixin.qq.com/s/xvgT8-CtA6Gl0IevihnuAg)

![](https://files.mdnice.com/user/4331/9d7f6e12-ee3d-400a-9eb4-c99d9fff9c07.png)

该研究推出的slide-seq，可以在一个直径3毫米的视野内，以10微米的分辨率，对每不同位置的聚苯乙烯珠子，添加对应空间位置的条形码，标记空间位置，之后通过PCR扩增，实现DNA原位测序。在每个阵列中，包含2万到4万个柱子，每个珠子中，可以检测到的DNA序列，约为165-421个。

4、[2021年人工智能研究成果盘点](https://mp.weixin.qq.com/s/H4SxKi8uCTVyaVb-Dy-xOQ)


![](https://files.mdnice.com/user/4331/ec6cf01a-81ae-41fd-8d0b-3a9ed3710cea.png)


## 文章

1、[GitHub，版本控制与协作](https://julia.quantecon.org/software_engineering/version_control.html)

本文介绍如何使用GitHub进行版本控制与协作。

2、[通俗科普文：贝叶斯优化与SMBO、高斯过程回归、TPE](https://mp.weixin.qq.com/s/n6eThkg20Sj9ipLr9h8W_Q)

> 贝叶斯优化是AutoML中的重要概念，近年来变得很火热。作为一种重要的基于先验的调参/策略选择技术，贝叶斯的应用范围也很广。但这个概念对于初次接触的同学可能较难理解，经过数天的论文研读、博客/教程/代码查阅，有了这篇科普文，也手绘了一些示意图，希望尽量在一篇文章内、通俗易懂地讲清楚什么是贝叶斯优化。

3、[Nature综述 | 免疫检查点的十年之旅](https://mp.weixin.qq.com/s/jOiBMOD60ZkBZHrKgfqRnw)


![](https://files.mdnice.com/user/4331/89143867-c3e1-48e5-9aa0-64a5a8a615bb.png)


## 工具

1、[conflicted - An alternative conflict resolution strategy for R](https://github.com/r-lib/conflicted)

R经常存在同名函数，会造成计算问题，最常见的就是`filter()`和`select()`函数。conflicted包提供了一种解决策略，一旦出现重名就报错，这样提示你一定要指定函数的包名。

```r
library(conflicted)
library(dplyr)

filter(mtcars, cyl == 8)
#> Error: [conflicted] `filter` found in 2 packages.
#> Either pick the one you want with `::` 
#> * dplyr::filter
#> * stats::filter
#> Or declare a preference with `conflict_prefer()`
#> * conflict_prefer("filter", "dplyr")
#> * conflict_prefer("filter", "stats")
```

2、[report - bridge the gap between R’s output and the formatted results contained in your manuscript](https://github.com/easystats/report)

report根据最佳实践指南(如APA的风格)自动生成模型和数据框架的报告，确保结果报告的标准化和质量。


![](https://files.mdnice.com/user/4331/77bbc1a8-1e86-45e0-83dd-4b4e706404f8.png)

3、[pdfcpu - a Go PDF processor](https://github.com/pdfcpu/pdfcpu)

一个处理PDF文件的命令工具。


![](https://files.mdnice.com/user/4331/0e7afe33-ce55-499d-8500-4c6ef13b1710.png)


4、[gtreg - Regulatory Tables For Clinical Research with 'gtsummary'](https://github.com/shannonpileggi/gtreg)

```r
library(gtreg)
gtsummary::theme_gtsummary_compact()
#> Setting theme `Compact`

tbl_ae <- 
  df_adverse_events %>%
  tbl_ae(
    id_df = df_patient_characteristics,
    id = patient_id,
    ae = adverse_event,
    soc = system_organ_class, 
    by = grade, 
    strata = trt
  ) %>%
  modify_header(all_ae_cols() ~ "**Grade {by}**") %>% 
  bold_labels()
```


![](https://files.mdnice.com/user/4331/2a68ddc2-f827-4852-b7b9-8b007c662c82.png)

5、[parsermd - R Markdown 提取器]()

方便对R Markdown文件进行编程控制。

```r
(rmd = parsermd::parse_rmd(system.file("minimal.Rmd", package = "parsermd")))
#> ├── YAML [4 lines]
#> ├── Heading [h1] - Setup
#> │   └── Chunk [r, 1 opt, 1 lines] - setup
#> └── Heading [h1] - Content
#>     ├── Heading [h2] - R Markdown
#>     │   ├── Markdown [6 lines]
#>     │   ├── Chunk [r, 1 lines] - cars
#>     │   └── Chunk [r, 1 lines] - <unnamed>
#>     └── Heading [h2] - Including Plots
#>         ├── Markdown [2 lines]
#>         ├── Chunk [r, 1 opt, 1 lines] - pressure
#>         └── Markdown [2 lines]

as_tibble(rmd)
#> # A tibble: 12 x 5
#>    sec_h1  sec_h2          type          label      ast           
#>    <chr>   <chr>           <chr>         <chr>      <rmd_ast>     
#>  1 <NA>    <NA>            rmd_yaml_list  <NA>      <yaml>        
#>  2 Setup   <NA>            rmd_heading    <NA>      <heading [h1]>
#>  3 Setup   <NA>            rmd_chunk     "setup"    <chunk [r]>   
#>  4 Content <NA>            rmd_heading    <NA>      <heading [h1]>
#>  5 Content R Markdown      rmd_heading    <NA>      <heading [h2]>
#>  6 Content R Markdown      rmd_markdown   <NA>      <rmd_mrkd [6]>
#>  7 Content R Markdown      rmd_chunk     "cars"     <chunk [r]>   
#>  8 Content R Markdown      rmd_chunk     ""         <chunk [r]>   
#>  9 Content Including Plots rmd_heading    <NA>      <heading [h2]>
#> 10 Content Including Plots rmd_markdown   <NA>      <rmd_mrkd [2]>
#> 11 Content Including Plots rmd_chunk     "pressure" <chunk [r]>   
#> 12 Content Including Plots rmd_markdown   <NA>      <rmd_mrkd [2]>

rmd_select(rmd, by_section("Content"))
#> └── Heading [h1] - Content
#>     ├── Heading [h2] - R Markdown
#>     │   ├── Markdown [6 lines]
#>     │   ├── Chunk [r, 1 lines] - cars
#>     │   └── Chunk [r, 1 lines] - <unnamed>
#>     └── Heading [h2] - Including Plots
#>         ├── Markdown [2 lines]
#>         ├── Chunk [r, 1 opt, 1 lines] - pressure
#>         └── Markdown [2 lines]

rmd_select(rmd, by_section(c("Content", "*"))) %>%
  rmd_select(has_type(c("rmd_chunk", "rmd_heading")))
#> └── Heading [h1] - Content
#>     ├── Heading [h2] - R Markdown
#>     │   ├── Chunk [r, 1 lines] - cars
#>     │   └── Chunk [r, 1 lines] - <unnamed>
#>     └── Heading [h2] - Including Plots
#>         └── Chunk [r, 1 opt, 1 lines] - pressure

rmd_select(rmd, "pressure")
#> └── Chunk [r, 1 opt, 1 lines] - pressure

rmd_select(rmd, 1:3)
#> ├── YAML [4 lines]
#> └── Heading [h1] - Setup
#>     └── Chunk [r, 1 opt, 1 lines] - setup
```

5、[ggdistribute - A ggplot2 Extension for Plotting Unimodal Distributions](https://github.com/iamamutt/ggdistribute)

ggdistribute包是绘制后向或其他类型的单峰分布的扩展，这些单峰分布需要覆盖关于分布间隔的信息。它利用ggproto系统扩展ggplot2，提供额外的“geoms”、“stats”和“position”。扩展与现有的ggplot2层元素集成。


![](https://files.mdnice.com/user/4331/aa2edffd-8e0c-48b4-b0dc-33d549ab539f.png)

6、[cannonball - 定量方法论和统计学相关函数工具](https://github.com/janhove/cannonball)

`plot_r(): Draw different scatterplots with the same correlation coefficient`


![](https://files.mdnice.com/user/4331/8651db58-cb3f-4c5d-94df-35de00c28107.png)


## 资源

1、[Shiny开发者系列访谈](https://shinydevseries.com/interview/)


![](https://files.mdnice.com/user/4331/60463165-8193-4300-8db9-e8eda4cae822.png)


2、[21年研究肿瘤的这十篇高分综述](https://mp.weixin.qq.com/s/nZwaMh1pSA3msIJYaQgr_A)


## 赞赏

如果你想要支持本周刊，可以对推文进行赞赏或者提供的支付宝/微信二维码打赏。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648291334186-bd3390be-c83c-4396-aabd-ca39f588c15d.png)

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

