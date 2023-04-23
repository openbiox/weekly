# 生信爱好者周刊（第 74 期）：新技术的最大风险

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/ShixiangWang/weekly/discussions "「生信周刊讨论区」")

## 封面图
![image](https://user-images.githubusercontent.com/13445428/232670012-21bb1d19-6c14-415f-888f-f513dc8a6629.png)
[图片：印度的第一家苹果商店](https://indianexpress.com/article/technology/tech-news-technology/apple-mumbai-delhi-stores-india-opening-8549861/ "图片：印度的第一家苹果商店")

## 本周话题：[新技术的最大风险](https://mp.weixin.qq.com/s/IS4XveCr2w1poEY2NvK29w)


>我记得，有人做过研究，企业软件的成本，只有20%是早期的开发成本，剩下的80%都是后期的维护和更新成本。很多的新技术，看上去可以节省前面20%的开发成本，但可能大大增加后面80%的维护成本。

`@kongjianyang`：企业应优先选择经过考验、长期维护良好的老技术用于长期项目，而不是追求时髦的新技术，以避免增加维护成本和风险。虽然新技术有其创新性和乐趣，但在需要长期维护的项目中使用未经考验的新技术是非常冒险的。因此，选择技术时应该注重项目需求，而非个人兴趣。可能这也是为什么很多大型药企的统计分析还是依赖于SAS语言的一个原因。

## 生信研究


1、[Genome Biolog | 全新衰老理论，衰老是我们身体的软件设计缺陷所致，表观遗传改变是关键](https://mp.weixin.qq.com/s/u6d0Zo3QCrb2qVQKyo15Yg)

![](https://user-images.githubusercontent.com/45822462/233752421-c4728dcb-4f40-482d-ba58-ab6e19806f04.png)

Genome Biology 期刊发表了题为：Ageing as a software design flaw 的综述论文提出了关于衰老的新观点：衰老主要是我们身体“软件设计缺陷”的结果。文章中的一些观点与著名抗衰老研究学者、哈佛大学 David Sinclair教授在Cell中提出的“表观遗传才是衰老的主要驱动力”非常契合。
 
 - 论文链接：https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-02888-y
 

2. [Nat Commun发表肿瘤空间转录组数据辅助分析工具——SpaCET，可准确预测细胞空间分布](https://www.nature.com/articles/s41467-023-36062-6 "Nat Commun发表肿瘤空间转录组数据辅助分析工具——SpaCET，可准确预测细胞空间分布")

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202304190953184.png)

近日，美国国家癌症研究中心姜鹏团队在***Nature Communications***发表了题为“Estimation of cell lineages in tumors from spatial transcriptomics data”的文章，并详细介绍了团队自主开发的计算模型——SpaCET（Spatial Cellular Estimator for Tumors）。SpaCET可以预测肿瘤ST数据中每一个空间位置的细胞成分，解决了肿瘤异质性、组织密度变化、免疫细胞完整性和细胞谱系间共线性的挑战。经验证，SpaCET在横跨7种癌症类型的8个肿瘤ST数据集中的预测性能优于其他方法。此外，SpaCET还可提供肿瘤进展相关潜在细胞间互作分析功能。

- 论文链接：https://www.nature.com/articles/s41467-023-36062-6

3、[首个男性健康单细胞数据库网站MHA正式上线啦](https://mp.weixin.qq.com/s/8ALABuGtO0ASCJmuBKNAsA)
![image](https://user-images.githubusercontent.com/108639312/233349107-d09e8a2d-105f-40b2-b719-63fa60fe1527.png)

MHA数据库目前版本整合了2类物种（人、小鼠）、4种组织器官（睾丸、前列腺、附睾/输精管、阴茎海绵体）生理发育或相关疾病的单细胞转录组数据，共有9大数据集。数据的分析、处理由赵亮宇博士（具有男性健康相关生物学背景）与赵艺凡工程师（具有多年生物信息学数据处理经验）合作完成，保证了结果的专业性与准确性。网站提供了中英文双语的帮助信息，访问者可方便地查阅单个或多个基因，在各类男性特有器官中的细胞表达情况，或在生理与病理过程中的变化情况。

- 论文链接：https://onlinelibrary.wiley.com/doi/10.1111/andr.13402

4、[Nat Genet | DeepNeo预测MHC II人类肿瘤表位新景观](https://www.nature.com/articles/s41588-022-01273-y "Nat Genet | DeepNeo预测MHC II人类肿瘤表位新景观")

![](https://kaikaihe.oss-cn-beijing.aliyuncs.com/image/202304190954074.png)

2023年1月9日，韩国科学技术院、宾得医疗**Jung Kyoon Choi**和**Dae-Yeon Cho**与韩国成均馆大学医学院**Se-Hoon Lee**研究小组合作在Nature Genetics杂志上发表题为MHC II immunogenicity shapes the neoepitope landscape in human tumors的研究论文，这篇文章通过使用36000多个免疫原性测定结果，开发了一种鉴定pMHC的新方法DeepNeo，该方法预测了MHC II和MHC I的新表位，这些新表位不仅能够结合MHC蛋白的免疫原性，而且还能够刺激T细胞反应性免疫原性，对免疫检查点阻断有反应，同时证明了MHC- II限制性自然免疫对于癌症的重要性。

- 论文链接：https://www.nature.com/articles/s41588-022-01273-y

5、[PNAS | 基于肿瘤代谢生物标志物的多癌症液体活检方法](https://mp.weixin.qq.com/s/Z6_YIp7NtaENPd9s8PLcHA)

![](https://user-images.githubusercontent.com/13445428/232961868-b54d5a93-f037-4979-8d08-3cb217470fbe.png)

瑞典查尔姆斯理工大学的科研人员在PNAS上发表了题为“Noninvasive detection of any-stage cancer using free Glycosaminoglycans”的文章。研究团队分析了不同癌症类型的糖胺聚糖组（GAGomes），并开发了一种高通量超高效液相色谱结合三重四极质谱（UHPLC-MS/MS）方法来检测游离的GAGomes。该研究纳入了来自1,260名癌症或健康受试者的2,064份样本，证明了GAGomes作为14种癌症类型MCED的肿瘤代谢生物标志物的潜力，并开发了三种基于尿液和血浆GAGomes的机器学习模型，可以检测任意癌症。与新兴的基于DNA的MCED检测相比，该方法能更灵敏地检测出无症状健康人群中I期癌症患者。

- 论文链接：https://www.pnas.org/doi/10.1073/pnas.2115328119

## 博文资讯

6、[NF-κB：维持免疫稳态的核心](https://mp.weixin.qq.com/s/vlo8ZprNn1JXAqW0BKRvgQ)

![image](https://user-images.githubusercontent.com/13445428/232962546-29cb4bb2-2576-4d48-9e64-11e405400899.png)

这篇公众号文章简单回顾了NF-κB的两条激活通路：经典通路和替代通路，以及NF-κB通路在维持免疫稳态中的核心功能。

7、[用R语言10分钟上手神经网络模型](http://blog.fens.me/r-nn-neuralnet/ "用R语言10分钟上手神经网络模型")

![](https://user-images.githubusercontent.com/45822462/233752447-b4d04fa3-5d9c-40de-a2a5-c2c6665e0575.png)

本文从实操开始介绍了运用R语言进行神经网络neuralnet建模应用的过程。

8、[肿瘤新抗原mRNA疫苗mRNA-4157/V940+PD-1抗体联合辅助治疗高危黑色素瘤防止术后复发，获得FDA的突破疗法认证](https://mp.weixin.qq.com/s/rJcyvnDYDuATekFP7DSHJw)

![](https://user-images.githubusercontent.com/25057508/233772171-39c70dce-d6a0-430d-8b44-49c8f9b0230e.png)

mRNA-4157为一种个性化肿瘤疫苗，靶向患者的特异性突变，编码最多至34种新生抗原。mRNA-4157可以激活肿瘤新生抗原的特异性T细胞，进而杀伤肿瘤细胞。mRNA-4157在一期临床中证明可以诱导新生抗原特异性CD8 T细胞的增殖。

9、[特征筛选还在用XGB的Feature Importance？试试Permutation Importance](https://mp.weixin.qq.com/s/IBqBl6XROplWz5ECc0wTaA)

![](https://user-images.githubusercontent.com/108639312/233348929-7e4ff498-c480-4b6e-90e4-9625c75f3b11.jpg)

特征筛选是建模过程中的重要一环。基于决策树的算法，如 Random Forest，Lightgbm, Xgboost，都能返回模型默认的 Feature Importance，但诸多研究都表明该重要性是存在偏差的。是否有更好的方法来筛选特征呢？Kaggle 上很多大师级的选手通常采用的一个方法是 Permutation Importance。通过本文，你将通过一个 Kaggle Amex 真实数据了解到，模型默认的 Feature Importance 存在什么问题，什么是 Permutation Importance，它的优劣势分别是什么，以及具体代码如何实现和使用。

## 工具

10、[NAdiff 首发 | 让你的RNA-Seq下游分析变得更简单](https://mp.weixin.qq.com/s/7_bSaVSiRTcPciY6oEkEDA)

![](https://user-images.githubusercontent.com/13445428/232963575-da6d69d3-9266-41cf-a1f1-a651fae64635.png)

这是一款由农心生信工作室开发的可用于RNA-Seq下游分析的shiny APP，可以让用户通过友好的web界面轻松完成一系列分析。包括筛选差异表达基因、对差异表达基因进行功能富集分析和注释以及对相关结果进行可视化。

- 工具链接：https://nongxinshengxinapp.shinyapps.io/rnadiff/

11、[github-code-viewer 浏览器插件 | 更快更简单地访问 GitHub](https://github.com/febaoshan/edge-extensions-github-code-viewer "github-code-viewer 浏览器插件 | 更快更简单地访问 GitHub")

![](https://user-images.githubusercontent.com/25057508/233772316-a247fff2-2509-4b69-bd82-3d7d05f70c07.png)


12、[Arxiv Search | 最新arxiv文章推送](https://github.com/goodnlp/all-you-need-is-arxiv-search "Arxiv Search | 最新arxiv文章推送")

![](https://user-images.githubusercontent.com/97931116/233580066-972feea5-e9e4-40f0-9fad-083903fccc02.png)

基于arxiv的论文搜索和分析的平台，可以基于网站或者微信公众号，帮你检索不同学科的最新文章。该平台用到的arxiv是一项免费分发服务和一个开放存取档案库，收录了物理学、数学、计算机科学、定量生物学、定量金融、统计学、电气工程和系统科学以及经济学领域的 2,242,699 篇学术文章。本网站上的材料未经 arXiv 同行评审。。

- 网站：https://www.arxiv.dev/


## 资源

13、[Friends Don't Let Friends Make Bad Graphs](https://github.com/cxli233/FriendsDontLetFriends "Friends Don't Let Friends Make Bad Graphs")

![](https://user-images.githubusercontent.com/25057508/233772676-bd413581-aa11-4224-8a33-3cc7b8a51843.png)


「Friends Don't Let Friends Make Bad Graphs」是一系列R绘图文章，介绍关于数据可视化中好与坏实践。非常值得读者以适合自己的速度阅读和探索下。

14、[R语言学习中遗漏的内容](https://rstats.wtf/ "R语言学习中遗漏的内容")

![](https://user-images.githubusercontent.com/97931116/233580107-a5dc2a63-0625-4246-8d4e-54979ffd2eaf.png)


一个关于R语言的全面工作流程的教程，目标是让有一定R和RStudio经验的自学者能够改进他们的R习惯，提高效率和自主性。涵盖了以下主题：

保存源代码和空白状态、项目导向的工作流程、安全的路径操作、如何命名文件、分析的API、个人R管理、了解你的R安装、R启动、维护R、安装源码包、所有的失败、调试R代码、阅读源码和复现问题。

- 教程链接：https://rstats.wtf/

15、[通过vitae包制作、维护个人简历](https://github.com/mitchelloharawild/vitae "通过vitae包制作、维护个人简历")

<img width="872" alt="截屏2023-04-22 08 39 36" src="https://user-images.githubusercontent.com/45822462/233752546-e472343b-47f5-4989-a048-52c339c3729a.png">

- 资源链接：https://github.com/mitchelloharawild/vitae

## 历史上的本周

- 第33期：[生信爱好者周刊（第 33期）：科研与生活](https://mp.weixin.qq.com/s/BLQQlZzIom_vbM0LD0OoDQ)

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

