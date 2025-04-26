---
date: 2025-04-26
comments: true
---
# 生信爱好者周刊（第 164 期）：德日学者称中国学术界更偏好“内循环”

这里记录每周值得分享的生信相关内容，周日发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

## 封面图

![](https://files.mdnice.com/user/77986/d0fcee4b-4c13-42b8-bf35-4e5093932321.jpg)

## 本周话题：[德日学者称中国学术界更偏好“内循环”](https://mp.weixin.qq.com/s/qD045WcKJ-wvLu9mPMx0JQ)

我国各学科最具影响力期刊论文数量、高水平国际期刊论文数量及被引用次数继续保持世界第1位，但研究者发现中国排名前10%的论文有62%的引用来自国内。

`@Wangcy-rachel`:中国排名前10%的论文大部分引用来自国内，说明这些论文在国内学术界得到了广泛关注和认可，但这些高水平论文在国际上的影响力相对有限。

## 生信研究

1、[Leukemia｜针对儿童癌症的液体活检Panel仅需1mL血浆即可检测多种不同基因组改变](https://mp.weixin.qq.com/s/aWOlHqNZ0b7pCbbnqMSO_Q)


![](https://files.mdnice.com/user/77986/fbd114b6-0bc2-4ee0-84f5-601a9134b68f.png)

研究开发了一种针对儿童癌症细胞游离DNA样本中不同体细胞基因组变异的深度测序方法PeCan-Seq，该方法可通过DNA捕获Panel对儿童癌症相关的357个基因进行深度测序，以从头检测染色体拷贝数变异（CNA）和单基因变异。

- 文章链接：https://www.nature.com/articles/s41375-024-02461-x

2、[Cell | 全面绘制人类健康与疾病蛋白质组图谱](https://mp.weixin.qq.com/s/CXJRHO8cLR5vb7FxAzrxjg)

![](https://files.mdnice.com/user/77986/1301fe22-65f5-481d-a571-25d5139e6b1e.png)

文章全面绘制了人类健康与疾病蛋白质组图谱，并结合人工智能大数据分析方法构建了疾病诊断预测模型以及发现了26个药物治疗新靶点，为精准医学的实施提供了重要科学依据。

- 文章链接：https://www.cell.com/cell/fulltext/S0092-8674(24)01268-6

3、[Nat Commun∣AI驱动的肽从头测序精准算法π-PrimeNovo](https://mp.weixin.qq.com/s/jzehYaZXuV_IRq2o-Ps-KQ)

![](https://files.mdnice.com/user/77986/5b6a64f6-c16e-46f5-a160-d35ec2ed7f52.png)

文章研发了首个基于非自回归模型的肽从头测序算法π-PrimeNovo，它彻底颠覆了传统的自回归生成方式，实现了一次性生成整个序列的能力。通过Transformer的自注意力机制，π-PrimeNovo能够让每个氨基酸在生成过程中同时参考序列中其他位置的信息，从而充分捕捉氨基酸之间的双向依赖关系，显著提高了预测准确性。

- 文章链接：https://www.nature.com/articles/s41467-024-55021-3
- 软件链接：https://github.com/PHOENIXcenter/pi-PrimeNovo

## 博文资讯

4、[R语言画图 | 换个风格绘制森林图](https://mp.weixin.qq.com/s/eu963MXPKHsXkyfFBGpZuQ)

![](https://files.mdnice.com/user/77986/82f98b30-bbd3-4a64-96c2-3362ffe2c51a.png)

本文介绍了利用ggplot2绘制森林图的方法。

5、[如果不断要求 AI 改进代码会怎样](https://minimaxir.com/2025/01/write-better-code/ "如果不断要求 AI 改进代码会怎样")

![](https://files.mdnice.com/user/77986/201e92d4-2c01-428b-82b4-ee37b11a1fb7.jpg)

OpenAI添加了DALL-E 3生成图像的功能，意在为用户提供基于LLM的基本图像绘制，并允许用户不断要求模型“让它更X”，其中X可以是任何东西。

6、[长期这样吃饭，全身炎症上升，痴呆风险增加!](https://mp.weixin.qq.com/s/g4p9b9HKBDFhUXUUbENLsQ)


![](https://files.mdnice.com/user/77986/90d66262-e7d8-4c20-a0f3-19b2522055a9.png)


有研究通过长达22.3年的随访，对1487名受试者进行了深入研究发现：频繁促炎饮食会显著提高痴呆症的发病风险。

## 工具

7、[原始数据下载专题 | 用iSeq下载原始测序数据](https://mp.weixin.qq.com/s/TDpljP6TiuTmyXn07c5rjA)


![](https://files.mdnice.com/user/77986/3d85a11b-411f-4513-877d-fc13582a4670.png)

推文中介绍了如何使用iSeq下载原始测序数据，iSeq可用于从GSA, SRA, ENA, 和 DDBJ数据库下载原始数据和元信息。

- github地址：https://github.com/BioOmics/iSeq

8、[gitbutler | 跨平台 Git GUI 软件](https://gitbutler.com/ "gitbutler | 跨平台 Git GUI 软件")

![](https://files.mdnice.com/user/77986/278fbcb7-c7bb-47e5-859a-d41c03fcd027.png)

9、[cOmicsArt | 可定制的组学分析工具](https://mp.weixin.qq.com/s/zi1twfSj1HyiXtg0Xj9d6Q)

![](https://files.mdnice.com/user/77986/1aa5e16e-e580-4944-bd91-83d9b9dae561.png)

推文分享了一款用于常规组学分析的工具cOmicsArt，cOmicsArt目前支持常规转录组、蛋白组+代谢组三类常见组学，常规的分析内容均包含，并支持将分析的数据及R代码导出。

- 工具链接： https://icb-dcm.github.io/cOmicsArt/

## 资源

10、[张泽民院士单细胞文章专题汇总](https://mp.weixin.qq.com/s/3vRtpiP_jJM0-Hv-Ew0yPQ)

![](https://files.mdnice.com/user/77986/0e00b060-5aa5-498c-b520-8b2b450a3c25.png)
>张泽民实验室致力于用前沿的基因组学和生物信息学技术来解决癌生物学中的重要问题，结合计算（干）和实验（湿）方法来揭示肿瘤发生、微环境和对药物响应中的系统变化和具体遗传因素，以推进癌症免疫治疗和靶向治疗的发展。首先，用单细胞测序技术来研究肿瘤微环境。第二，将尖端生物信息学方法应用到癌基因组学大数据，发现新型癌症靶点和标记物。第三，开发原创性的生物信息学工具。归纳总结，张泽民团队代表性工作主要是三个方向：①肿瘤微环境各类细胞单细胞图谱；② 肿瘤免疫治疗图谱；③ 生信工具。

该推文汇总了张院士团队长期在单细胞领域的工作进展。

11、[AI、大模型、深度学习、算法与生物学（Evo、GENERator）及单细胞和空间转录组 相关文献、讲座和软件列表](https://mp.weixin.qq.com/s/nEp0KZpKdCHNQn4R-B0tQA)


![](https://files.mdnice.com/user/77986/ceb35aeb-5c06-4679-bd40-3c65eddb4c61.png)


推文分享了AI、大模型、深度学习、算法与生物学有关的相关文献、讲座和软件列表。

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
- `@Wangcy-rachel` - 王春阳
- `@zoe3251` - 舒晨阳

## 订阅

这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://files.mdnice.com/user/77986/5f5b8e89-0bcf-4cfc-9a5f-7f24fe01666e.png)

（完）
