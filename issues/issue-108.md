---
date: 2024-01-14
comments: true

---

# 生信爱好者周刊（第 108 期）：肿瘤微生物组是污染，还是新突破

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/34023/3d68eef9-30a1-4bce-a8b3-9bd1b2e5990e.png)


来源：[Microbiome and cancer](https://www.cell.com/cancer-cell/fulltext/S1535-6108(21)00446-3)

## 本周话题：[肿瘤微生物组是污染，还是新突破？](https://mp.weixin.qq.com/s/S1IzLRK-xIQcoHB74dfX_g)

> 近年来，许多研究先后发现肿瘤内存在微生物，包括细菌、真菌等，并且还发现不同的肿瘤内存在不同的细菌特征。科学的发展常常伴随着质疑，这些肿瘤内的微生物是真实存在的吗？这究竟是一场来源于污染的闹剧，还是技术突破带来的新发现？
>
> 从胎盘中有无微生物的争议到肿瘤内是否存在微生物的思辨，都在提醒着我们要警惕低/微量微生物样本，并积极开发标准化方法来生成和分析微生物组测序数据，以更好地促进这一领域的发展。

`@NiEntropy` - 肿瘤微生物组是指与肿瘤相关的微生物群落，肿瘤微生物组可以通过多种机制影响肿瘤的发生、发展和治疗反应。肿瘤微生物组的组成和功能受到多种因素的影响，如宿主的基因、生活方式、饮食、抗生素等。研究肿瘤微生物组的特征和作用，有助于揭示肿瘤的发病机制，为针对肿瘤微生物开发治疗靶点提供依据。

## 生信研究

1、[CancerProteome | 癌症蛋白质组图谱资源](https://mp.weixin.qq.com/s/A3Za3XKMvOE3JzxlipYO-w)


![](https://files.mdnice.com/user/34023/474da3a0-bde2-42f3-b6f0-b2287ead2a50.png)


作者收集并重新分析了公开的基于质谱的原始癌症数据集，包括21种癌症类型的7406个样本，涉及31 120种蛋白质和4111种微蛋白，以及84 257个翻译后修饰（PTM）位点。作者还整合了已知的癌症基因、药物相关信息、功能富集分析、蛋白质相互作用和临床相关性等数据，以揭示蛋白质在癌症发生发展中的作用。



- 论文链接：https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10767844/
- 数据库链接：http://bio-bigdata.hrbmu.edu.cn/CancerProteome

2、[The Lancet | 基于血液的多癌早期检测筛查癌症的可行性](https://mp.weixin.qq.com/s/vGmL43F7E9Ae_IzHSbhowg)


![](https://files.mdnice.com/user/34023/f25876ef-b78f-4bfa-bd14-4206fd5836d5.png)

发表在顶级医学期刊The Lancet上的题为“Blood-based tests for multicancer early detection (PATHFINDER): a prospective cohort study”的文章，报道了前瞻性队列研究PATHFINDER的最终研究成果，探讨了GRAIL的MCED用于癌症筛查的临床可行性。结果显示，MCED不仅可以在三个月时间内为大多数参与者提供诊断解决方案，缩短了患者的癌症确诊时间，其检测结果还有助于改善阳性患者的后续临床检查路径。

> **该研究使用的MCED可以检测细胞游离DNA（cfDNA）中的癌症特异性DNA甲基化模式，并预测癌症的组织来源。该检测在循环细胞游离基因组图谱（CCGA）中已进行开发并验证，结果表明，靶向甲基化的MCED检测从一次抽血中检测出了50多种不同癌症类型的甲基化信号，并准确预测了1435名参与者中1273人的癌症信号组织来源。**

- 文章链接：https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(23)01700-2/fulltext



3、[Nature Communications | 全基因组测序解析肿瘤的“过去”和“现在”](https://mp.weixin.qq.com/s/aWbHxvdrw5vHnG2B76kjOg)


![](https://files.mdnice.com/user/34023/d7d469c2-3a4c-4c33-9d97-01518a52cb72.png)


研究人员分析了从癌前病灶巴雷特食管 (Barrett’s esophagus，简称BE) 到早期食管腺癌 (esophageal adenocarcinoma，简称EAC) 的过程中单倍型特异DNA拷贝数 (haplotype-specific DNA copy numbers) 的变化，发现了在食管腺癌中DNA拷贝数变异的复杂性和异质性始于癌前细胞基因组的不稳定性。该项研究首次在临床样本中将单倍型特异DNA拷贝数变异模式与基因组不稳定性相关的生物学机制联系起来，并详细地阐明了基因组不稳定性是如何驱动肿瘤进化的。

- 论文链接：https://www.nature.com/articles/s41467-023-41805-6



## 博文资讯

4、[《人类遗传资源管理条例实施细则》](https://mp.weixin.qq.com/s/cNqCqvy61FAUtOW2Kg1GLQ)


![](https://files.mdnice.com/user/34023/ba3de748-9081-495b-a51c-27b1e8344ec5.png)

- 政策解读：https://www.most.gov.cn/xxgk/xinxifenlei/fdzdgknr/fgzc/zcjd/202306/t20230601_186417.html



5、[Annals of Medicine专刊：抗癌药物在肿瘤免疫微环境中的作用](https://mp.weixin.qq.com/s/skly05PW-DA9i3wkyspGmA)



![](https://files.mdnice.com/user/34023/858a8d09-92e0-48b2-a751-ce10b2b57151.png)


来自**Annals of Medicine**的专刊，专刊强调抗肿瘤药物对肿瘤免疫微环境的影响，探讨化疗、靶向治疗、免疫检查点抑制剂（ICI）治疗的肿瘤患者TME的变化和潜在的挑战，通过对TME变化的新认识，为抗肿瘤药物的联合治疗或抗肿瘤药物耐药提供理论依据。内容涉及受放疗/化疗和免疫治疗影响的TME的最新进展，包括但不限于：

1. 肿瘤患者或用抗肿瘤药物治疗的人源化小鼠模型的免疫微环境的变化研究；
2. 通过单细胞测序探索抗肿瘤药物治疗后肿瘤免疫微环境中免疫细胞的新功能亚群和功能分析；
3. 研究不同抗肿瘤药物对免疫微环境影响的差异（如顺铂、吉西他滨、伊立替康等）;
4. 研究同一药物对不同肿瘤类型对应的免疫微环境的影响差异；
5. 研究抗肿瘤药物对肿瘤和免疫微环境中微生物平衡的影响;



6、[All of Us项目公布近25万个全基因组序列数据](https://mp.weixin.qq.com/s/NfdxRQhIl4TszMiaZbik2Q)


![](https://files.mdnice.com/user/34023/bb1e5c12-d8eb-43d1-8aad-d132bce44597.png)


近日，美国All of Us研究项目最新发布了约25万个全基因组序列数据，用于广泛的研究用途。迄今为止，该项目已获得超过413,450名参与者的信息。除了全基因组序列，还包括来自调查、电子健康记录、物理测量和Fitbit设备的数据。其中，大约45%数据是由自我认同某个种族或族裔群体的个人捐赠，这些种族或族裔群体在医学研究中代表性不足。





## 工具

7、[用Bypy直接下载百度云盘文件到服务器](https://mp.weixin.qq.com/s/BpZvblDIvUF97Y1EyEyqPA)

文章介绍了如何利用 Bypy 下载百度云文件，对于一些频繁使用百度云的读者可能有所帮助。

```sh
module load miniconda 
conda create --prefix bypy
source activate /path to bypy/bypy
conda install bypy
```

- 项目地址：https://github.com/houtianze/bypy

8、 [markdown-resume | 在线简历排版工具](https://github.com/mdnice/markdown-resume "markdown-resume | 在线简历排版工具")


![](https://files.mdnice.com/user/34023/08aac869-280a-4f5a-bf4b-62875d8fa138.png)


markdown-resume是一款支持 Markdown 和富文本的在线简历排版工具。

- 工具地址：https://resume.mdnice.com/

9、[shiny.molstar ｜ 大规模分子数据的可视化工具包](https://github.com/Appsilon/shiny.molstar "shiny.molstar ｜ 大规模分子数据的可视化工具包")


![](https://files.mdnice.com/user/34023/26634a58-f686-42be-99bf-9a137b9fd030.png)



10、[OmicVerse | 基于Python的转录组分析](https://omicverse.readthedocs.io/en/latest/ "OmicVerse | 基于Python的转录组分析")



![](https://files.mdnice.com/user/34023/3e22597b-e156-4bd6-9091-282774e5212b.png)


Omicverse 是一个基于 Python 的多组学分析库，可以用于批量和单细胞 RNA-seq 数据的分析。

- github：https://github.com/Starlitnightly/omicverse/
- 教程：https://omicverse.readthedocs.io/en/latest/



## 资源

11、[推荐初学者阅读的最佳生物信息学书籍](https://twitter.com/tangming2005/status/1674772338770866176 "推荐初学者阅读的最佳生物信息学书籍")

> 1/ Data Analysis for the Life Sciences [https://buff.ly/3PysKjV](https://t.co/4Tqa20DVmw "https://buff.ly/3PysKjV")  if you use [#rstats](https://twitter.com/hashtag/rstats?src=hashtag_click "#rstats"), that's the best one to start
>
> 2/ Computational Genomics with R
>
> 3/ Bioinformatics Data Skills [https://buff.ly/3PADAWE](https://t.co/aKZ8LZY7aD "https://buff.ly/3PADAWE")  It covers unix commands, git, work with remote machines, Bioconductor, project organization, etc. It was an excellent read for me!
>
> 4/ Practical computing for biologist [https://buff.ly/3E8gLlT](https://t.co/uDTLDsdpk9 "https://buff.ly/3E8gLlT")  by Steven H.D Haddock and Casey W. Dunn .This was the first book that I used to learn unix, regex and python.

tangming大佬推荐给初学者阅读的最佳生物信息学书籍。



12、[GWASLab | TwoSampleMR](https://gwaslab.org/2021/11/14/twosamplemr/ "GWASLab | TwoSampleMR") 


![](https://files.mdnice.com/user/34023/fdbf54a1-f3a6-4d74-a17c-773b299861d6.png)


本资源是一个关于孟德尔随机化（Mendelian randomization，MR）的学习笔记，主要介绍了两样本MR（Two sample MR）的基本原理和操作方法。





13、[Biomamba的在线工具合集](https://mp.weixin.qq.com/s/WisFLJfTuhKyIeldoU98ZQ)


![](https://files.mdnice.com/user/34023/b5dd6a19-0657-49cb-8c35-b3ecf3ea0323.png)

由Biomanba开发的各种在线小工具，部署在自建的服务器上，不限制访问速度和数量，可以尝试使用。


## 历史上的本周

-  第67期：[你是如何活用ChatGPT给你打工的？](https://mp.weixin.qq.com/s/l-o3gxyc0AyBiHU76utDbA)

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

