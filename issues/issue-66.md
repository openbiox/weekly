---
comments: true
---


# 生信爱好者周刊（第 66 期）：退休越晚、寿命越短？有关系么

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [ShixiangWang/weekly](https://github.com/ShixiangWang/weekly "ShixiangWang/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区（语雀）」](https://www.yuque.com/shixiangwang/bioinfo "「生信周刊讨论区（语雀）」") | [「生信讨论区（Gitter）」](https://gitter.im/ShixiangWang/community "「生信讨论区（Gitter）」")

## 封面图



![](https://files.mdnice.com/user/37191/33bf8c13-f787-4815-8c1a-1765e5e52f96.png)

## 本周话题：[退休越晚、寿命越短？有关系么](https://mp.weixin.qq.com/s/GI_tVgR1dKKuHbGW8WBGdA)



![](https://files.mdnice.com/user/37191/8b4cc560-c321-4e6e-8304-f8acf3b43f8c.png)


>这两天，一则延迟退休的消息在网络上疯传，根据其中的说法，国家将于今年宣布渐进式延迟退休方案，到2025年正式实施，而到2055年前后，无论男女都将工作至65岁方可退休。看到这则消息，打工人们一片哗然。除了感慨“早日躺平”的梦想破裂外，还有不少人关注延迟退休可能带来的健康问题。这方面的焦点，是号称来自美国波音公司、洛克希德·马丁公司和福特汽车公司员工的真实数据，其中显示：退休越晚，寿命越短，尤其是员工工作满55岁后，每工作1年，平均寿命就减少两年。关于这个问题，你怎么看？


## 生信研究

1. [ Nat.Mach.Intell | ImageMol: 精准预测分子性质和药物靶标的自监督学习框架](https://mp.weixin.qq.com/s/s-ITjwqzEtCyqvUy9eJsyw)

![](https://user-images.githubusercontent.com/75790226/221393186-331b8139-fc96-45ff-a7d3-0b6725a848af.png)

2022年11月，湖南大学DrugAI实验室在Nature子刊《Nature Machine Intelligence》上发表名为”Accurate prediction of molecular properties and drug targets using a self-supervised image representation learning framework”的研究论文，提出了一种全新的分子表征框架——基于分子图像的自监督深度学习框架ImageMol。它通过在1000万个未标记的类药生物活性分子上进行预训练，实现了对分子性质和药物靶标的准确预测，开创了分子表征学习的新范式。

- 论文链接：https://www.nature.com/articles/s42256-022-00557-6

2. [ Transl Res | 肺癌靶向用药伴随诊断重大进展](https://mp.weixin.qq.com/s/I02J1aqn2_sSOmr8lxt_7A)

![](https://user-images.githubusercontent.com/13445428/221338913-d0020b4b-0cb4-4c9d-bde9-008ac6a47961.png)

河南大学安磊团队和郑州大学精准医学中心许红恩团队首次利用饱和突变扫描（DMS）技术系统研究了74389种表皮生长因子受体（EGFR）罕见变异突变对5种临床一线EGFR-酪氨酸激酶抑制剂（EGFR-TKI）靶向药的敏感性，该研究方法具有通用性，可以用于研究其他靶向抑制剂的敏感突变和抗药突变，推动肿瘤精准医疗的发展。

- 文章链接：https://www.translationalres.com/article/S1931-5244(22)00244-4/fulltext

3. [自然·医学：MSKCC发布肺癌液体活检重磅成果](https://mp.weixin.qq.com/s/6HyxOKt3HY6Apb49mFrCtQ)

![](https://user-images.githubusercontent.com/13445428/221339123-0c793aca-b397-489d-9721-2d60b40e5fe3.png)

纪念斯隆·凯特林癌症中心的研究验证了血液循环肿瘤DNA（ctDNA）阳性结果与非小细胞肺癌（NSCLC）患者的总生存率（OS）有关（HR=2.05，p＜0.001），且独立于临床病理特征和肿瘤代谢体积，接受ctDNA测序后匹配的靶向治疗的患者相比未接受的，OS更高。这项研究表明，ctDNA不仅可以指导治疗决策，它本身也具有预测预后的价值。

- 文章链接：https://pubmed.ncbi.nlm.nih.gov/36357680/

4. [Cell Reports Methods | 华为团队开发组合贝叶斯优化框架，进行抗体计算机设计](https://mp.weixin.qq.com/s/qfLnPIzcAtAgEijQRSgqtw)


![](https://files.mdnice.com/user/37191/f877096d-e3c5-4470-b64c-c0e46432070b.png)


华为诺亚方舟实验室、伦敦大学以及爱丁堡大学的研究团队开发了 AntBO，这是一种组合贝叶斯优化框架，利用 CDRH3 信任区对具有良好可开发性分数的抗体进行计算机设计。针对 159 种抗原的计算机实验表明，AntBO 是朝着实际可行的体外抗体设计迈出的一步。在对 oracle 的不到 200 次调用中，AntBO 建议抗体优于来自 690 万个实验获得的 CDRH3 的最佳结合序列。此外，AntBO 在不需要领域知识的情况下仅在 38 种蛋白质设计中发现了非常高亲和力的 CDRH3。
- 文章链接：https://doi.org/10.1016/j.crmeth.2022.100374

## 博文资讯

5. [走近单细胞RNA-seq | 内附单细胞测序支持资源](https://mp.weixin.qq.com/s/gQTTMzMCawKlgjZH-uK9nA)


![](https://user-images.githubusercontent.com/45822462/221193647-3b468835-de86-4dd2-adf5-930887bae649.png)

这篇10x Genomics官方的推文介绍了单细胞测序的基本概况，并附上了相关资源。


6. [负载均衡入门指南](https://linux.cn/article-15121-1.html?utm_source=rss&utm_medium=rss "负载均衡入门指南")

![](https://user-images.githubusercontent.com/25057508/220810422-925b40e7-7295-4543-972d-3bc42e671de4.png)

负载均衡是一个通用术语，指的是为了确保高效分配所管理的资源而做的事情。对于 Web 服务器的系统管理员来说，负载均衡通常意味着确保 Web 服务器软件配置了足够的工作节点来处理激增的访客。换言之，如果一个网站突然变得非常受欢迎，其访问者在几分钟内增加了四倍，那么运行服务器的软件必须能够响应每个访问者，并不能让任何访问者发现服务质量下降。

文章链接：https://linux.cn/article-15121-1.html?utm_source=rss&utm_medium=rss

7. [巧用 CSS 显示 HTML 源码](https://secretgeek.github.io/html_wysiwyg/html.html "巧用 CSS 显示 HTML 源码")

<img width="694" alt="image" src="https://user-images.githubusercontent.com/25057508/220812958-8a7fca4f-bbc6-4e83-9cee-46b364437cdf.png">

这个网页通过 CSS 在对 HTML 排版的同时，能够显示 HTML 源码。

8. [Jupyter Notebook 五大效率插件](https://mp.weixin.qq.com/s/SXze8cVcoiYXQKhyQNFbIQ)


![](https://user-images.githubusercontent.com/75790226/221393286-5dd93cfd-cfe4-4075-b877-52a0dd726770.png)

本文介绍了可以提升Jupyter Notebook 效率的五个插件：Table of Contents、Autopep8、variable inspector、ExecuteTime、Hide Code input。

## 工具

9. [20个必备的Python机器学习库](https://mp.weixin.qq.com/s/-x4nGQdLjFx83l_mMKcdWw)

![](https://user-images.githubusercontent.com/45822462/221193759-b3873b01-6632-4220-a577-c077fc390353.jpg)

本文介绍了自动机器学习AutoML中不同的编程语言提供的一些最常见的20个库。


10. [vscode-gptcommit |  在VSCode中自动生成git commit messages](https://mp.weixin.qq.com/s/-x4nGQdLjFx83l_mMKcdWw)

![](https://user-images.githubusercontent.com/75790226/221393348-1ea4e276-4e64-4eae-ae34-d753d6dc5d2e.png)

该项目利用GPT 模型，借助gptcommit for VS Code 来自动提交消息。

链接：https://github.com/pwwang/vscode-gptcommit

11. [wukong-robot](https://github.com/wzpan/wukong-robot "wukong-robot")

wukong-robot 是一个简单、灵活、优雅的中文语音对话机器人/智能音箱项目，还可能是首个支持脑机交互的开源智能音箱项目。
![image](https://user-images.githubusercontent.com/75790226/221394487-8a845d2d-ce46-428c-9a94-73b0fefd2c48.png)

链接：https://github.com/wzpan/wukong-robot

## 资源

12. [怎样良好度过以科研为职业的一生](https://mp.weixin.qq.com/s/tR6a21g8nJvCOvFfvvkU6g)

![](https://user-images.githubusercontent.com/13445428/221339648-d1014927-a905-43a4-a7e6-f5740f6269c9.png)

这是《返朴》公众号过往发表过的关于科研职业化的内容，有些内容值得学习。

13. [关于生物医药领域的一些信息源总结](https://atelfo.github.io/2022/03/19/the-best-way-to-follow-biopharma-news.html "关于生物医药领域的一些信息源总结")

<img width="1063" alt="image" src="https://user-images.githubusercontent.com/38637596/221359612-329e48b2-71f8-4a16-acb5-218bb2e1a575.png">

这篇博客讨论了保持了解生物制药行业最新消息的最佳方法。作者建议跟随可信的信息来源以获取准确可靠的新闻。这些来源可以包括行业专业出版物、监管机构和学术机构。作者还建议使用社交媒体平台，如 Twitter 和 LinkedIn，关注关键意见领袖、行业专家和专业组织。生物医药领域的从业者可以看看。


 14. [Epigenomics Workshop 2022](https://nbis-workshop-epigenomics.readthedocs.io/en/latest/index.html "Epigenomics Workshop 2022")
 
<img width="473" alt="image" src="https://user-images.githubusercontent.com/38637596/221359921-fca94af4-00af-4162-b40d-1d8e40f43c54.png">

2022年，瑞典国家生物信息学基础设施 (NBIS) 组织开设的免费Epigenomics workshop，包括DNA Methylation分析、ATACseq分析、CHIPseq分析，从原理到分析pipeline都有涉及，很适合自学。另外NIBS还会定期组织其它生信相关的教程，大家也可以关注一下。

链接：https://nbis-workshop-epigenomics.readthedocs.io/en/latest/index.html

15. [Python应该要会一点吧](https://mp.weixin.qq.com/s/2l_9CHxJGGHWw0zXV34y1A)

![](https://user-images.githubusercontent.com/25057508/220813169-0d604776-a18d-4a34-8636-0e9d94b4f2b2.png)


本文对 Python 的核心基础知识进行了梳理。
## 历史上的本周
- 2021 [【周刊】第 26 期：CRISPR的专利权](https://mp.weixin.qq.com/s/nygUhT4XX5Gah2VllpywZg)

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


![](https://files.mdnice.com/user/37191/484e56e7-6d4d-41a3-a70c-53e240bb2dcd.png)


（完）
