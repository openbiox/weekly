---
date: 2023-08-26
comments: true
---

# 生信爱好者周刊（第 90 期）：性别视角下的中国科研人员画像

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/43254/15f0fab3-d75b-493c-abce-ddbf17117202.png)

野生动物喝水照片

## 本周话题：性别视角下的中国科研人员画像

>《性别视角下的中国科研人员画像》是首部以性别视角研究中国科研生态、多维度分析和展现中国女性的科学参与度、贡献度和影响力的报告。研究表明，中国科研领域的性别差异逐步改善，女性科研人员在科研参与度、职场竞争力等方面都取得了进步，各学科领域中的性别差异也在逐步弱化，女性在生命科学和医学领域表现更出色。相对而言，在科研产出和基金资助等方面，女性仍低于男性，可见消弭科研领域的性别差异任重而道远。

@kongjianyang：女性科研人员在科研领域内一般会面临更多的挑战，,如家庭责任、隐性歧视、资源和晋升机会缺乏等。改善这种性别不平等的现象需要整个社会的更多努力，例如制定反歧视政策、增加女性科研资源、建立弹性评价机制等。

## 生信研究

1、[Plos computational biology | CNVkit: 靶向DNA测序的全基因组拷贝数检测和可视化](https://mp.weixin.qq.com/s?__biz=MzkzMTM0NTcyNw==&amp;mid=2247483704&amp;idx=1&amp;sn=0ff55194ca2a692ed6a3a47607442b35&amp;chksm=c26d2568f51aac7eab001b2bdd6c33f4957ff6b306c00b473acf9bb1a3406f161f0b6844e6a7&token=387766894&lang=zh_CN#rd)


![](https://files.mdnice.com/user/43254/096c466b-40dd-4190-a82f-91cbe201d358.png)


生殖细胞拷贝数变异 (CNV) 和体细胞拷贝数改变 (SCNA) 在综合征和癌症中具有重要意义。大规模并行测序越来越多地用于从测序数据中读取深度的变化推断拷贝数信息。然而，这种方法在靶向重测序的情况下存在局限性，这会在选择用于富集的区域之间留下覆盖空白，并引入与目标捕获和文库制备效率相关的偏差。加利福尼亚大学旧金山分校（UCSF）的Boris C. Bastian团队在Plos computational biology提出了一种拷贝数检测方法，在软件包 CNVkit 中实现，该方法使用靶向读取和非特异性捕获的脱靶读取来平均推断整个基因组的拷贝数。这种组合在目标区域实现了外显子水平的分辨率，并在较大的内含子和基因间区域实现了足够的分辨率，以识别拷贝数的变化。

- 论文链接：https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004873



2、[Nature｜首个高质量二倍体人类参考基因组！PacBio、Nanopore、Bionano、Hi-C技术各显神通](https://mp.weixin.qq.com/s/rSjwTRB8RkdPtbtIH6NtKQ)


![](https://files.mdnice.com/user/43254/49363595-ee6d-40e6-ac13-ef8f7e4237cd.png)


近日，国际人类泛基因组参考联盟 （HPRC）在Nature上发表了题为“Semi-automated assembly of high-quality diploid human reference genomes”的文章，报道了其评估结果。研究人员确定了目前可以实现最完整和最准确的二倍体基因组组装的基因组测序和组装方法组合，且人工整理的工作量最小；组装了第一个高质量的二倍体参考基因组；发现了更多单倍型之间的遗传变异，约48%的蛋白质编码基因在单倍型间存在非同义氨基酸变化，其中中心粒区多样性最高。为实现自动化、完整、无错的二倍体基因组组装，研究人员还确定了需要改进的部分。总之，该研究为大规模组装接近完整的二倍体人类基因组提供了基础，能捕获从单核苷酸到结构重排的全局遗传变异。

- 文章链接：https://www.nature.com/articles/s41586-022-05325-5

3、[Nucleic Acids Res. | scHumanNet:用于研究疾病基因细胞类型特异性的单细胞网络分析平台](https://mp.weixin.qq.com/s/4IwRtPM1ysbUPa-cjZ8knQ)

![](https://files.mdnice.com/user/43254/3af1744b-41af-4a24-9a37-c3839c25fed5.png)


本文介绍由哈佛医学院的Martin Hemberg和韩国延世大学生命科学与生物技术学院生物技术系的Insuk Lee共同通讯发表在Nucleic Acids Research的研究成果：单细胞生物学面临的一个主要挑战是识别细胞类型特异性基因功能，这可能会大大提高精准医学的水平。基因的差异表达分析是一种流行但不充分的研究方法，需要补充与细胞类型相关的功能。因此，作者提出了单细胞网络分析平台scHumanNet，用于解决人类不同基因功能的细胞异质性。scHumanNet是基于HumanNet参考相互作用组构建细胞类型特异性基因网络(CGN)， 它在单细胞转录组数据上构建的CGN比其他方法显示出更高的细胞环境功能相关性。此外，基于跨细胞类型网络紧致性的基因信号的细胞反褶积揭示了与T细胞相关的乳腺癌预后标志物。scHumanNet还可以利用CGN的中心性对与特定细胞类型相关的基因进行优先排序，并确定CGN在疾病和健康状况之间的差异中心。作者通过揭示乳腺癌预后基因GITR的T细胞特异性功能效应，以及抑制神经元特异性自闭症谱系障碍基因的功能缺陷，证明了scHumanNet的有效性。

- 文章链接：https://academic.oup.com/nar/article/51/2/e8/6814446






## 博文资讯

4、[R软件包生态系统依赖沉重性分析](https://mp.weixin.qq.com/s/3n7s8ZEOwjLaLuENi3sakQ)

![](https://files.mdnice.com/user/43254/628af33f-c6fc-4966-a399-02345ce18013.png)


顾祖光发表在软件工程期刊Journal of Systems and Software上的文章，主要探讨了R软件生态系统包依赖的复杂性和脆弱性。文章提出了一个新的度量指标"依赖重量"(dependency heaviness),用来量化一个上游包(parent package)向下游包(child package)独特贡献的额外依赖数量。通过网络分析方法找出了主要传送重依赖的顶级包和关键路径。结果表明,很少数量的顶级包独占了系统中大部分的依赖关系,这使生态系统变得更易受这些顶级包失败的影响。文章内容很长，但是值得一读。


5、[深度梳理 | 各大肿瘤免疫疗法优劣、临床、上市和全球布局](https://mp.weixin.qq.com/s/b43GeaeyZR4QYZ2PUDqXiw)


![](https://files.mdnice.com/user/43254/3240b51d-27af-4b4d-a577-982597a64b2c.png)


文章概括介绍了五种主流的抗肿瘤免疫疗法,包括免疫检查点抑制剂(ICIs)、细胞疗法(TILs、TCR-T和CAR-T)以及肿瘤疫苗。分别介绍了这几种免疫疗法在全球和国内的上市情况以及临床研发进展。特别提到了一些知名产品如信迪利单抗、特瑞普利单抗、奕凯达等。对比总结了这几类免疫疗法的优势和局限。比如ICIs广泛适应但依赖率较低，T细胞疗法依赖率高但适应症窄等。最终指出抗肿瘤免疫已成为重要治疗手段之一,各类免疫疗法都有其应用前景,未来重点在于寻找更优的靶点和联合模式。

6、[PacBio MAS-Seq -- 开启肿瘤单细胞研究新时代](https://mp.weixin.qq.com/s/ediUSG6A3Sulw6KUdIVLcw)


![](https://files.mdnice.com/user/43254/5eae41cf-d0d2-47b3-bc45-70aba678dbc8.png)


目前绝大部分的单细胞 RNA 测序都是基于 NGS 测序平台完成的，由于 NGS 测序短读长的原因，转录本均需要片段化后进行测序，只能得到转录本的各端的信息，得到的测序数据只能提供细胞内基因水平的表达信息，缺少可能对疾病或生物功能发挥十分关键作用的重要异构体多样性等信息。
为解决以上问题，PacBio 推出了 MAS-Seq 试剂盒，通过将短的 cDNA 进行串联建库的方式连接起来再进行HiFi测序，从而解决了长读长单细胞 RNA 测序的通量瓶颈。MAS-Seq 的发布，将使单细胞转录组研究从基因研究推进到转录本异构体的新领域，而近期，瑞士苏黎世联邦理工学院研究团队创新性地采用了与 MAS-Seq 类似的实验策略，测序得到了基于 PacBio 的全长 scRNA-seq 数据，与传统基于 NGS 的 scRNA-seq 测序相比，在测序成本差不多的情况下，获得了足够的单细胞全长转录本数据，通过分析发现 PacBio 全长单细胞转录组不仅可以对细胞类型进行准确的鉴定，同时还能发现二代单细胞转录组无法测到的融合基因表达，患者特异性和肿瘤组织特异性的 isoform 选用偏好性，以及能够发现更多外显子结合位点。这些信息的获取，为研究肿瘤的发生发展、克隆演化，提供了进一步探索的基础。


## 工具

7、[rconfig | 在命令行管理R配置](https://github.com/analythium/rconfig "rconfig | 在命令行管理R配置")

```sh
export USER=Jane

Rscript --vanilla test.R deploy \
  -f rconfig-prod.yml \
  -j '{"trials":30,"dataset":"full-data.csv"}' \
  --user.name $USER \
  --verbose
# List of 6
#  $ trials     : int 30
#  $ dataset    : chr "full-data.csv"
#  $ cores      : int 1
#  $ user       :List of 1
#   ..$ name: chr "Jane"
#  $ description: chr "This is a multi line\ndescription."
#  $ verbose    : logi TRUE
#  - attr(*, "trace")=List of 2
#   ..$ kind : chr "merged"
#   ..$ value:List of 4
#   .. ..$ :List of 2
#   .. .. ..$ kind : chr "file"
#   .. .. ..$ value: chr "/Users/Peter/git/github.com/analythium/rconfig/inst/examples/rconfig.yml"
#   .. ..$ :List of 2
#   .. .. ..$ kind : chr "file"
#   .. .. ..$ value: chr "/Users/Peter/git/github.com/analythium/rconfig/inst/examples/rconfig-prod.yml"
#   .. ..$ :List of 2
#   .. .. ..$ kind : chr "json"
#   .. .. ..$ value: chr "{\"trials\":30,\"dataset\":\"full-data.csv\"}"
#   .. ..$ :List of 2
#   .. .. ..$ kind : chr "args"
#   .. .. ..$ value: chr "deploy --user.name Jane --verbose"
#  - attr(*, "command")= chr "deploy"
#  - attr(*, "class")= chr "rconfig
```

8、[Windows Terminal](https://github.com/microsoft/terminal "Windows Terminal")


![](https://files.mdnice.com/user/43254/60f1053e-a1de-4bb2-8d8e-029780e8d084.png)


Windows 终端程序是一款新式、快速、高效、强大且高效的终端应用程序，适用于命令行工具和命令提示符，PowerShell和 WSL 等 Shell 用户。主要功能包括多个选项卡、窗格、Unicode、和 UTF-8 字符支持，GPU 加速文本渲染引擎以及自定义主题、样式和配置。

9、[Scoop：Windows平台最好用的软件管理器](https://scoop.sh/ "Scoop：Windows平台最好用的软件管理器")


![](https://files.mdnice.com/user/43254/60c20258-08d4-4490-82e8-7e5baf7afeee.png)


Scoop是一款适用于Windows平台的命令行软件（包）管理工具。简单来说，就是可以通过命令行工具（PowerShell、CMD等）实现软件（包）的安装管理等需求，通过简单的一行代码实现软件的下载、安装、卸载、更新等操作。其灵感来源于macOS的Homebrew。


## 资源

10、[Kaggle Solutions](https://farid.one/kaggle-solutions/ "Kaggle Solutions")


![](https://files.mdnice.com/user/43254/419972de-24fc-46bb-96a0-5e11fd07cfde.png)


正如其名称所示，这份仓库包含了过去Kaggle竞赛中所有顶级选手分享的可用的解决方案和想法。这个列表会在每场比赛结束后立即更新，并允许你搜索过去Kaggle竞赛的解决方案和想法。




11、[prompt 绘图标签](https://tags.novelai.dev/ "prompt 绘图标签")


![](https://files.mdnice.com/user/43254/ffac4886-87d5-40b0-9f58-ec8b7f888206.png)



12、[ith.Variant：从多样本测序数据中确定体细胞突变的pipeline](https://github.com/SunPathLab/ith.Variant "ith.Variant：从多样本测序数据中确定体细胞突变的pipeline")


![](https://files.mdnice.com/user/43254/474a44d3-e72c-45cd-861c-04061504e6c1.png)


由SunPathLab团队在GitHub上开源的用于从多样本基因组测序数据中调用体细胞变异的pipeline，管道包含了对Illumina测序数据的处理、质控、比对等模块，主要的变异调用模块使用了Mutect2、Scalpel等工具。还包含了对变异进行注释、过滤、汇总统计等后处理流程。提供了docker的使用选项。

## 历史上的本周

[生信爱好者周刊（第 50 期）：顶级1区期刊宣布：明年起将不再拒稿！](https://mp.weixin.qq.com/s/FraY1GvPlnPHKLRFh9iAQw)

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

![](https://files.mdnice.com/user/38661/17812364-5134-43ba-92cf-0be6aff405e8.png)

（完）


