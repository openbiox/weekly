---
date: 2023-09-10
comments: true
---

# 生信爱好者周刊（第 92 期）：医疗反腐的困境和选项

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

> 祝各位读者老师教师节快乐！

## 封面图


![](https://files.mdnice.com/user/4331/7eca0523-0c64-4242-93ad-8470621337e3.png)

韩国宣布将在首都首尔，建造世界最大的无辐摩天轮。[via](https://mymodernmet.com/seoul-ring-hubless-ferris-wheel/)

## 本周话题：[医疗反腐的困境和选项](https://mp.weixin.qq.com/s/YbDtlZZQV1E1AoSbQwMfaw)

> 中国医疗反腐的困难在于：怎么对待大专家、科室和医院领导。
也就是说，所谓“千里驹”和“害群之马”，在中国医疗界很有可能实际重叠率不低。
容易争论“千里驹”中到底有多少“害群之马”，但很难争议“害群之马”中有多少“千里驹”，后者的比率恐怕很高。
四十年来积累的结果，导致这个比率有可能高到难以做到：全部清除害群之马，而同时保留足够的千里驹。
万一因为千里驹被反腐而出现不得不去监狱看病/做手术的景象，可能对大家（医疗界内外）都比较尴尬？

`@ShixiangWang` - 屠龙少年，成为恶龙，屡见不鲜。今年我们通过新闻资讯看到了很多医院的领导们落马，可见当下腐败的严重和国家的决心。肃清毒瘤固然重要，但我觉得更应该深思的是为什么它们会存在？会长期存在？肃清后恢复会复发？每个人都有着内心的阳光面和阴暗面，塑造良好的文化、良好的环境让人心向阳而生，可能需要更为长期的实践。


## 生信研究


1、[Nature | 肿瘤细胞染色体不稳定性导致免疫逃逸](https://mp.weixin.qq.com/s/j38rxnVExlGUio9nIexg8w)


![](https://files.mdnice.com/user/4331/1e0fb45d-7a94-46bd-af26-a57444abaf8e.png)

本研究利用全新的基于单细胞RNA测序数据的细胞间交互作用分析手段ContactTracing，分析具有不同染色体不稳定性水平的小鼠和病人肿瘤的肿瘤微环境，发现负责感受细胞质内DNA的天然免疫通路的慢性激活促进了免疫逃逸和肿瘤转移。具体而言，肿瘤细胞的染色体不稳定性造成了Sting的慢性激活。有趣的是，这种Sting通路的慢性激活并没有引发与肿瘤免疫清除相关的干扰素通路，而是通过ER stress机制，进而导致肿瘤的免疫逃逸。这一发现为针对肿瘤细胞染色体不稳定性的治疗方案提供了理论基础，同时也提示了肿瘤细胞中Sting通路激活与免疫系统之间的关系比最初预计的更加复杂。这也为Sting激活剂在临床试验中未能达到预期的效果提供了可能的解释。与此同时，ContactTracing算法的开发充分利用了复杂样品中细胞的异质性，为单细胞RNA测序数据分析提供了全新的工具和思路。这将有助于更深入地了解细胞间相互作用的复杂性，从而推动医学研究和治疗的进展。

- 论文链接：https://www.nature.com/articles/s41586-023-06464-z

2、[Cell Discovery | 缺血性脑卒中患者全基因组测序分析](https://mp.weixin.qq.com/s/Jfmz85yEGpsRuq7ULsLlBg)


![](https://files.mdnice.com/user/4331/9ecd18d0-fa72-4b50-b37e-1cb6e578883e.png)

近期发表在Cell Discovery上的文章，报道了一项来自中国10241例缺血性脑卒中患者的全基因组测序和分析研究。研究团队通过深度全基因组测序鉴定了这些个体中的13.55亿个高质量变异,并通过随后的关联分析揭示了10个新的基因位点与脑卒中相关性状之间的联系,为未来研究脑卒中机制、新的治疗靶点提供了线索。这是迄今为止针对中国脑卒中患者队列进行的最大规模的全基因组研究,极大丰富了人们对中国群体遗传结构和自然选择的了解。

- 文章链接：https://www.nature.com/articles/s41421-023-00582-8

3、[Cell | 基于35种癌症类型构建首个泛癌真菌微生物组图谱，揭示癌症与微生物相互作用](https://mp.weixin.qq.com/s/hxyPe8TZhrTOfSzyAUZU0w)


![](https://files.mdnice.com/user/4331/a0f7696a-4d60-4a8c-a7ec-f7fe622af9f5.png)

以色列魏茨曼科学研究所领导的研究团队全面表征了组织和血液中的35种癌症的真菌群落，构建出首个泛癌真菌微生物组图谱。研究团队将真菌群落与匹配的细菌组和免疫组进行比较，发现两者共存的双结构域生态系统，通常具有许可性而非竞争性的微环境和独特的免疫应答。临床评估结果表明了组织和血浆分枝杆菌群的预后和诊断能力，即使在I期癌症中也是如此，并且与菌群具有协同预测性能。

- 论文链接：https://doi.org/10.1016/j.cell.2022.09.005

4、[Nature Communications | devCellPy:对复杂的多层单细胞转录组数据进行自动注释的机器学习管道](https://mp.weixin.qq.com/s/lwt-Ix5NNGOT20-KJgfFaQ?poc_token=HCcB-2SjI1ZGcnOyJD7Znco18DYt-b1GopLNr_T3)


![](https://files.mdnice.com/user/4331/b2293085-5c10-4795-ab16-8b69e0eecf79.png)

在单细胞RNA测序分析中，由于细胞表现出复杂的多层身份或过渡状态，导致对数据集的精确注释成为主要挑战。devCellPy作为一个高度精确的机器学习工具能自动预测跨复杂注释层次结构的细胞类型，可推广到任何scRNA-seq数据集。随着大规模发育细胞图谱的发展，devCellPy将提供资源来帮助识别跨平台和物种的细胞类型，特别是在注释良好的参考数据集中显示复杂的多层注释方案。

- 论文链接：https://www.nature.com/articles/s41467-022-33045-x
- 工具链接：https://github.com/devCellPy-Team/devCellPy

5、[Cell Reports | DeepFavored: 揭示适应性突变与疾病易感性关联](https://mp.weixin.qq.com/s/3BWk1ABYAtwfTC8FM0DWvA)


![](https://files.mdnice.com/user/4331/9b7fcadf-e4ba-4167-8bf2-7cd6e1d4d4d1.png)


中国南方医科大学朱浩教授团队开发了DeepFavored ，可以用于识别有利突变、搭便车突变和普通突变。在东亚（CHB）、欧洲（CEU）、非洲（YRI）三个人群的分析中，发现有利突变和搭车突变在GWAS位点的比例明显高于普通突变，是为适应性进化和疾病易感性间的平衡关系分析提供了证据。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/36103812/


## 博文资讯


6、[“基因组与AI：一作面对面”开放投稿啦！](https://mp.weixin.qq.com/s/bF6Fv_3Txzu7qj4ZDb4wsA)


![](https://files.mdnice.com/user/4331/3c089513-4f4f-48f7-a36f-42024bb8ec58.png)

“基因组与AI”一作面对面论坛致力于将一作面对面打造成一个青年学子的共同成长的家园。从现在开始，“基因组与AI：一作面对面”论坛邀请所有信心和勇气的学生、博士后以及青年研究人员来分享自己工作。

7、[harmony、不harmony，这是个问题](https://mp.weixin.qq.com/s/gaKGiYKlrjan-0HMWfv_6g)


![](https://files.mdnice.com/user/4331/c7b02220-17a2-4d40-97a7-81f315f1cb63.png)

本文通过具体实例介绍了harmony基本原理、harmony后可能导致的问题以及相应的解决方法。


8、[临床试验数据共享的十条(并非如此)简单规则](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010879)

- Rule 1: Abide by local legal and regulatory data protection requirements
- Rule 2: Anticipate the possibility of clinical trial data-sharing before obtaining funding
- Rule 3: Declare your intent to share data in the registration step
- Rule 4: Involve research participants
- Rule 5: Determine the method of data access
- Rule 6: Remember there are several other elements to share
- Rule 7: Do not proceed alone
- Rule 8: Deploy optimal data management to ensure that the data shared is useful
- Rule 9: Minimize risks
- Rule 10: Strive for excellence.

9、[Windows下新装R的极简指南](https://mp.weixin.qq.com/s?__biz=MzI5NjUyNzkxMg==&mid=2247492636&idx=1&sn=9c37a414c222af04946fce8fec342ebf&chksm=ec40555bdb37dc4d4c0b8a29075c9d620867ede47a3370c29233f790822b024b5b4add605d38&scene=21)


![](https://files.mdnice.com/user/4331/0b0c2ce4-c9f5-48f3-843d-82a4d5f5e583.png)


来自Y叔公众号的文章，主要记录了他在Windows下使用scoop安装R以及在vscode里面使用R的一些步骤。Scoop是Windows的命令行安装程序，是一个强大的包管理工具。可以试着用用看。


## 工具


10、[Highcharts](https://www.highcharts.com/demo)


![](https://files.mdnice.com/user/4331/6555a24b-79e7-4328-aa18-a9d4e0229d22.png)

让开发人员可以轻松地为web和移动平台创建图表和仪表板。适用于Javascript、Angular、React、VueJS、iOS、R、。net、Python等。(涉及许可协议)

11、[elvis](https://github.com/ThinkR-open/elvis)

{elvis}包的目标是通过提供原生的tryCatch()机制，在{shiny}包中提供更安全的render*和observe*。

例如下面的示例：

```r
output$plot <- try_renderPlot({
    stop("a")
  },
  errorHandler = function(e){
    showNotification("There was an error in the plot")
  }
)
```

基本思想是给所有函数加上try_前缀，这样就更容易将旧代码移植到{elvis}包。

12、[CNAViz | 肿瘤DNA测序数据分割网页工具](https://github.com/elkebir-group/cnaviz)


![](https://files.mdnice.com/user/4331/7fe12ec5-d229-4482-b82c-ea9bfc7f5c14.png)


一个非常直观的工具，让用户可以对肿瘤DNA测序数据进行交互式的分割，查看和编辑分割结果，以及查看分割的统计信息和驱动基因。

- 教程：https://github.com/elkebir-group/cnaviz/blob/master/docs/Tutorial.md

13、[aliyunpan](https://github.com/tickstep/aliyunpan )


![](https://files.mdnice.com/user/4331/3accdb2e-eeae-4a3e-9ae3-1bae4ca210fc.png)

阿里云盘CLI。仿 Linux shell 文件处理命令的阿里云盘命令行客户端，支持JavaScript插件，支持webdav文件协议，支持同步备份功能。


14、[configr | 在R中生成、修改常用配置文件参数的R包](https://github.com/Miachol/configr)


![](https://files.mdnice.com/user/4331/370f8751-4ae2-491f-97a6-18cce6938dd3.png)

R包'configr'支持对多种配置文件格式：'JSON'、'INI'、'YAML'和'TOML'，通过相应的函数可以对上述文件进行操作。

## 资源


15、[Diving into Genetics and Genomics](http://crazyhottommy.blogspot.com/)


![](https://files.mdnice.com/user/4331/7d4d9d9e-af4f-45d0-80ca-a733e62bed51.png)


计算生物学大佬Ming Tang的博客，涉及生物信息学、数据科学、免疫学、单细胞分析等多个主题，他分享了一些有用的资源、工具、书籍和教程，以及一些自己的心得和经验。他还有一个自己的书籍《潜入遗传学与基因组学》，可以帮助想要学习计算生物学的人。

- 书籍：https://divingintogeneticsandgenomics.com/

16、[各大PD-1管线经FDA批准的时间线](https://public.tableau.com/app/profile/cancer.research.institute/viz/2018-12-07PD-1approvaltimeline_15722879001770/PD-1approvallandscape)


![](https://files.mdnice.com/user/4331/667571b7-5072-4897-be64-56592c4ea021.png)

本资料整理不同肿瘤类型中PD-1药物经FDA批准的时间线，点击相应的点还能看到更加详细的药品等信息。

## 历史上的本周

- 第 52 期[真正的“科技与狠活”：全球首个人工“优选基因”的“完美婴儿”马上2岁啦！](https://mp.weixin.qq.com/s/GpuJX6ifmA2_Infq-i_MUw)

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

