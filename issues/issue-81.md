---
date: 2023-06-24
comments: true
---

# 生信爱好者周刊（第 81 期）：好人情结

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图

![](https://files.mdnice.com/user/43254/0cc7a191-e021-4522-8767-fa96b9a3a049.png)

韦伯望远镜的第一张照片，发布于2022 年 7 月 12 日，这张来自于世界上目前最强大的太空望远镜的照片预示着人类进入宇外探索的新时代。

## 本周话题：好人情结

> 有一种心理疾病叫“取悦症”（Disease to Please），也就是常说的“讨好型人格”，意思很好理解，就是不自觉地想要讨好别人，取悦别人，满足别人的要求，行为被一种“好人情结”左右。

@kongjianyang：生活中想做一个与人为善的人本无可厚非，但是如果是一味的讨好则很可能伤害自身。要适度的做到内心坚强，不要为了赢得别人的认可或者好感而一味的讨好别人。

## 生信研究

1、[DeepPseudoMSI: 使用深度学习对pseudo-质谱图像分析用于精准医学](https://mp.weixin.qq.com/s/l9BupbaiUuu3-vK8G_ePaA)


![](https://files.mdnice.com/user/43254/53501061-0076-40d3-9be4-ce6ab130893b.png)


发表在生物信息学top杂志Briefing in Bioinformatics上的文章。该项工作开发了基于深度学习的pseudo质谱图像(deepPseudoMSI)，可以将 LC-MS 原始数据转换为pseudo- MSI(质谱图像图像)，然后通过深度学习对其进行处理,从而用于精准医学。通过真实数据验证，deepPseudoMSI优于传统的LC-MS处理方法。

- 文章链接：https://academic.oup.com/bib/advance-article/doi/10.1093/bib/bbac331/6659741?searchresult=1

2、[CAP | 免疫治疗患者的dMMR、MSI检测指南](https://mp.weixin.qq.com/s/jKkDDOmkeZRUr46x74WDtg)


![](https://files.mdnice.com/user/43254/a8db96e7-611d-446f-866c-ba907537b36c.png)


美国病理学家协会（CAP）最近提醒医务工作者，为了更好地指导患者选择免疫治疗方案，要慎重选择检测dMMR或MSI的方法。CAP的专家小组对于不同的检测方法（包括免疫组化（IHC）、PCR和下一代测序（NGS））的优缺点和推荐，以及针对不同的癌症类型的建议。文章强调了这些检测方法并不是完全可互换的，而且在某些癌症类型中，目前还缺乏足够的证据来支持使用NGS来检测dMMR或MSI。

- 文章链接：https://www.precisionmedicineonline.com/molecular-diagnostics/cap-weighs-dmmr-msi-assays-immunotherapy-patient-selection

3、[Nature Methods | 基于DNA序列的单细胞ATAC-seq卷积神经网络建模](https://mp.weixin.qq.com/s/GiNClxWRYnB55VPSZIlcSg)

![](https://files.mdnice.com/user/43254/1fae4c41-ac7f-4f1c-b90c-9bdfb0bb6c28.png)

单细胞ATAC-seq（scATAC）在研究表观遗传景观中的细胞异质性方面具有巨大前景，但由于数据高维性和稀疏性的特点，scATAC的分析仍然面临重大挑战。为此，作者提出了一种基于DNA序列的卷积神经网络方法(scBasset)来对scATAC数据进行建模。实验表明，通过利用可及性峰值下的DNA序列信息和神经网络模型的表达能力，scBasset在scATAC和单细胞多组数据集的各种任务中展现了最先进的性能，包括细胞类型识别、scATAC去噪、数据集成和转录因子活性推断。

- 论文链接：https://www.nature.com/articles/s41592-022-01562-8


## 博文资讯

4、[关于bioRxiv文章的解读](https://centuryofbio.com/)


![](https://files.mdnice.com/user/43254/29d3fa27-27b6-4ac3-baca-355414b8b7dc.png)


一位斯坦福的博士定期更新生物医药领域的最新进展，非常有启发。

5、[ggThemeAssist | 鼠标交互修改ggplot2图形主题参数](https://mp.weixin.qq.com/s/8O9BM-x1YQx4HOKRmcMYkw)

![](https://files.mdnice.com/user/43254/95d66470-f8b7-44aa-b76d-04dd72bb72c4.png)


ggThemeAssist是一个R语言的包，它可以帮助用户在RStudio中轻松地定制ggplot2图形的主题。用户只需要在RStudio中选择一个ggplot2对象，然后点击“Addins”菜单中的“ggThemeAssist”，就可以在一个交互式的窗口中调整图形的各种元素，如标题、坐标轴、图例、背景、颜色等。用户可以实时地看到图形的变化，并且可以复制或插入生成的代码到脚本中。我强烈推荐你试一试ggThemeAssist包，个人感觉学了这个包直接秒杀GraphPad Prism， 你一定会喜欢上它的！

- 工具链接：https://github.com/calligross/ggthemeassist

6、[micromamba的安装使用](https://mp.weixin.qq.com/s/MWq8zTzlG1W3FGyBx7mkXg)

![](https://files.mdnice.com/user/43254/421b4514-4f55-4657-b5a1-2db61b4f3a10.png)

Micromamba 是一个轻量级的 Python 环境管理器和包管理器，它是 Miniconda 的替代品。它的目标是提供一个更快速、更小巧的选择，用于管理 Python 环境和安装第三方软件包。这篇文章简单记录了`micromamba`的安装过程。

## 工具


7、[workflowr：管理和分享重复性研究的R包](https://workflowr.github.io/workflowr/)

![](https://files.mdnice.com/user/43254/41e2be9a-e304-43a5-babd-18eed7cc2676.png)


workflowr包能够帮助研究人员进行有效的项目管理、进行可重复性研究、协作和分享自己分析结果。workflowr 结合了文字编程（knitr 和 rmarkdown）和版本控制（Git，通过 git2r）来生成一个包含时间戳、版本化和记录结果的网站。任何 R 用户都可以快速轻松地采用工作流程。

- 工具链接：https://github.com/workflowr/workflowr

8、[Observable Plot：用于探索性数据可视化的JavaScript库](https://observablehq.com/plot/)

![](https://files.mdnice.com/user/43254/da746599-2a94-4db9-a755-67fdaa5f913d.png)


一款可以用来做数据化可视化的JavaScript库，做出来的图形都很精美，可以尝试下。

- 工具链接：https://observablehq.com/plot/what-is-plot

9、[le-git-graph：将 git graph 添加到 GitHub 网站的浏览器扩展](https://github.com/NirmalScaria/le-git-graph)


![](https://files.mdnice.com/user/43254/101eed19-1a6d-4bdf-95f3-2a2360ab6869.png)

一款可视化任何GitHub库的git graph的浏览器扩展

- 工具链接：https://github.com/NirmalScaria/le-git-graph



## 资源


10、[SingleR | 自动化细胞类型注释](https://bioconductor.org/books/release/SingleRBook/)

![](https://files.mdnice.com/user/43254/9c73a58b-44b5-40a9-9263-493971d53d12.png)

SingleR是一个R语言的包，它可以将新的单细胞数据与已知的参考细胞类型进行比较，根据表达谱的相似度，为每个新细胞分配一个参考类型。这样可以避免手动地对单细胞数据进行聚类和注释，节省时间和精力，提高准确性和可重复性。教程从SingleR的动机和方法描述开始，然后通过一些实例数据，展示了如何使用SingleR的不同模式和选项，以及如何进行注释结果的诊断和评估。

- 教程链接：https://bioconductor.org/books/release/SingleRBook/


11、[洛克菲勒大学的在线生物信息训练教程](https://rockefelleruniversity.github.io/)


![](https://files.mdnice.com/user/43254/ac9de9a1-6210-42e5-81f4-839929c5ddde.png)


洛克菲勒大学的生信团队提供的在线培训课程，培训涵盖 ChIP-seq 和 RNA-seq 分析、数据可视化和 R/Bioconductor 编程等主题。

- 教程链接：https://rockefelleruniversity.github.io/

12、[Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/)

Cookiecutter 是一个强大的模板工具。Cookiecutter Data Science提供了对数据科学项目的初始化，方便构建相关的分析项目，会生成大体如下的目录结构：

```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- Make this project pip installable with `pip install -e`
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
```


## 历史上的本周

- 第 41 期：[人体是一个共生生态系统](https://mp.weixin.qq.com/s/m7DFJZ_xEA0vFtJbd0d9Dg)

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

![](https://files.mdnice.com/user/38661/17812364-5134-43ba-92cf-0be6aff405e8.png)

（完）

