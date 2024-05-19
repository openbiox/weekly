---
date: 2024-05-12
comments: true
---

# 生信爱好者周刊（第 123 期）：Hello GPT-4o

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly)），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions)

## 封面图


![](https://files.mdnice.com/user/4331/c5b5c826-e675-4d7f-be6d-199d73aedc1c.png)

[Decoding Bio](https://www.decodingbio.com/p/biobyte-076-alphafold3-engineering?utm_campaign=email-half-post&r=2j9u3n&token=eyJ1c2VyX2lkIjoxNTMzMDM5NzEsInBvc3RfaWQiOjE0NDQ2NzA1OSwiaWF0IjoxNzE1MjU3MDEyLCJleHAiOjE3MTc4NDkwMTIsImlzcyI6InB1Yi0xMDc5NDk4Iiwic3ViIjoicG9zdC1yZWFjdGlvbiJ9.ZqjsL6GEodsNVP4Iv61KCUUMm84u6nkQ48jRaPLtfco&utm_source=substack&utm_medium=email)


## 本周话题：[Hello GPT-4o](https://gpthanghai.com/posts/gpt/gpt4o.html)


![](https://files.mdnice.com/user/4331/38a44652-3c37-490d-8613-6da17163e228.png)

5 月 14 日凌晨 OpenAI 举办了首次「春季新品发布会」。此次发布会最大的亮点就是新旗舰模型 GPT-4o 的推出，其中「o」是 “omni（全能）”的意思。GPT-4o 可以接受文本、音频和图像的任意组合作为输入，并生成文本、音频和图像的任意组合输出，且这些内容的反馈都是实时的，因此使用 GPT-4o 就像和真人进行互动那样轻松自然。

比如实时语音交互，之前 ChatGPT 的进行语音对话会有几秒的延迟，中间的等待时间总让人觉得不自然。而 GPT-4o 能在 232 毫秒内响应音频输入，平均响应时间为 320 毫秒，与人类在对话中的响应时间相近。并且即使是面对回答被突然中断、多人同时谈话等复杂的情况，GPT-4o 也能完美理解。

`@shixiangwang`：感觉 AI 迭代的节奏相当快，还没回过神，新的技术已经不再新。

## 生信研究

1、[Science | 肿瘤浸润 B 细胞图谱](https://mp.weixin.qq.com/s/SoshQhvceQ4D8KWJHNMtKw)


![](https://files.mdnice.com/user/4331/20b59229-673d-411a-acfc-6c74932b0d45.png)

本研究全面分析了20种癌症类型中的B细胞。研究发现，肿瘤浸润B细胞的响应分为生发中心（GC）样和滤泡外（EF）两类。GC样响应的Bm cells与有效的抗肿瘤免疫和良好的预后相关，而EF响应的AtM B cells 则与免疫抑制和较差的预后相关。

- 论文链接：https://pubmed.ncbi.nlm.nih.gov/38696569/


2、[NAR | 世界上首个基于荧光图像数据的单细胞多组学数据库——iSMOD](https://mp.weixin.qq.com/s/kqYj2PqcHT18E_5-C-tpYQ)

![](https://files.mdnice.com/user/4331/8c17c975-baec-4024-b3e2-d3f476d19d15.png)

本研究报道了世界上首个基于荧光图像数据的单细胞多组学数据库iSMOD。随着多组学数据的激增，整合现有数据以供后续研究使用变得关键。iSMOD数据库集成了多个公共数据库的基因、物种、蛋白、细胞类型及探针信息，收录了23,288篇相关文献的荧光原位杂交(FISH)图像数据,包括空间基因组、转录组和蛋白质组数据。iSMOD的建立有助于整合和利用日益增长的成像多组学数据,促进相关研究的发展。

- 论文链接：https://academic.oup.com/nar/article/51/16/8348/7223586?login=false

3、[Nature Communications | 甲基化检测新算法可利用HiFi测序准确检测基因组单倍型5mC](https://mp.weixin.qq.com/s/M3LLDGstzm2JbgNifA8ORA)


![](https://files.mdnice.com/user/4331/4ef2fae4-b148-4abd-91d4-bb5ce4b9d05e.png)

DNA甲基化作为表观遗传的一种重要形式，在染色质结构和组织水平上的生物过程中起主要作用。近年来三代测序技术（牛津纳米孔测序和PacBio单分子实时测序）的迅速发展为DNA甲基化，尤其是为DNA 5mC的检测带来了新的机遇。本研究研究基于PacBio HiFi测序技术，提出了可准确检测全基因组单倍型5mC的方法和流程，并开发了相应的软件ccsmeth和ccsmethphase。

- 论文链接：https://doi.org/10.1038/s41467-023-39784-9


## 博文资讯


4、[BWA 对比针对较大基因组的并行计算和性能优化](https://mp.weixin.qq.com/s/q-SCYEKhZhEArzRmBirC-Q)


![](https://files.mdnice.com/user/4331/fb6ce57d-fdca-42e6-97d2-00c4966198db.png)

本文分享 BWA 软件的使用方法与流程简介，同时讨论针对大规模参考基因组的并行计算和性能优化方式，比如小麦等参考基因组复杂庞大的情况，利用切分片段和多线程技术快速进行序列比对，并补充 BWA 处理较大参考基因组的几种方法。


5、[警惕某些公司临床前数据造假](https://mp.weixin.qq.com/s/D-YyBrwuyLaoIc_Au6whfQ)


![](https://files.mdnice.com/user/4331/8529234b-d966-45b5-beb7-cbb25bace568.png)

文章讨论了一家国内某公司的ADC药物在临床前和临床研究中存在数据造假嫌疑。

6、[GENESPACE优雅的绘制基因组共线性图](https://mp.weixin.qq.com/s/LW0q4vadLJFdIMpdwG8gNQ)


![](https://files.mdnice.com/user/4331/221c3e69-f42a-45c1-b03c-b0fddf3370d7.png)

本文介绍一个用于多个基因组的共线性和直系同源模式分析及可视化的R包「GENESPACE」。



## 工具

7、[tidytof ｜ 一种可扩展和可重现的高维cytometry数据分析的整洁框架](https://mp.weixin.qq.com/s/T1LA0Y1HL5OS31dejo7JnA)


![](https://files.mdnice.com/user/4331/5a5b3d06-8bea-4803-90e2-873eff864bf0.png)


尽管已经开发出许多分析高维细胞数据的算法,但这些算法的软件实现仍然高度定制化——这意味着探索一个数据集需要用户学习每个数据处理步骤所需的独特的、互操作性差的软件语法。为解决这个问题，作者开发了tidytof，一个开源的R软件包,用于使用越来越受欢迎的“整洁数据”接口分析高维细胞数据。

- 工具链接：https://github.com/keyes-timothy/tidytof


8、[comut | 基于python的热图绘制](https://github.com/vanallenlab/comut?tab=readme-ov-file)


![](https://files.mdnice.com/user/4331/bf56a686-a5c9-4576-9fd1-bbec2b1eb5e2.png)


9、[Pegasus ｜ 分析数百万个单细胞转录组的工具](https://github.com/lilab-bcb/pegasus)


![](https://files.mdnice.com/user/4331/e4facfa4-ab10-4698-8ff8-f6ea97b76a64.png)


它是一个命令行工具、python软件包和基于云的分析工作流程的基础。

## 资源

10、[中级编程课程](https://iprogramming.bacpop.org/)


![](https://files.mdnice.com/user/4331/29d1f377-3ecb-4331-b166-f7dc3dc37afd.png)


“中级编程”课程，旨在帮助提高生物信息学/计算生物学研究生和博士后的编程技能。

## 历史上的本周

- 生信周刊第 82 期：[一种新的数字表示方法 Posits](https://mp.weixin.qq.com/s/T0RSBCEi-BxqFIfkXpvB0g)

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
- `@donghongyu2020`（董弘禹）
- `@DrRobinLuo`（罗鹏）

## 订阅

这个周刊每周日发布，同步更新在微信公众号「优雅R」（elegant-r）上。

微信搜索“优雅R”或者扫描二维码，即可订阅。

![](https://cdn.nlark.com/yuque/0/2022/png/471931/1648306398708-897e7ad4-6008-40f8-9200-ddee834b09a7.png)

（完）

