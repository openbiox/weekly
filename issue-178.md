---
date: 2025-12-10
comments: true
---
# 生信爱好者周刊（第 178 期）：为何肿瘤空间分布至关重要

这里记录值得分享的生信相关内容，每半月发布。

本杂志开源（GitHub: [openbiox/weekly](https://github.com/openbiox/weekly "openbiox/weekly")），欢迎提交 issue，投稿或推荐生信相关内容。

[「生信周刊讨论区」](https://github.com/openbiox/weekly/discussions "「生信周刊讨论区」")

# 封面图


![](https://files.mdnice.com/user/151230/0f0bcd52-1088-470c-bc11-a7bb99d23dca.jpg)


# 本周话题：[Why tumour geography matters — and how to map it](https://www.nature.com/articles/d41586-024-03830-3)

> 探究肿瘤组织样本在分子尺度上的空间分布的技术正在推动癌症研究的革命，但是庞杂的技术让人感到困扰.
# 生信研究
1、[稀疏基因组学：大规模基因组分析的新范式”](https://mp.weixin.qq.com/s/wvhS0yjOE4mgrX6iMC20OQ)

![](https://files.mdnice.com/user/151230/2bc9e862-e9f0-4b3b-8ce9-1bd86f0e0c71.png)

随着基因组测序数据呈指数级增长，现有的计算发放在寻找相似的基因组序列上显得力不从心。为了解决这个问题，文章提出稀疏基因组学的概念，其通过排除基因组序列中的大量碱基，生成更短、更稀疏的序列，从而减少计算负载和内存占用。这种方法能够加速基因组分析，能在保持高准确性的前提下，显著减少存储空间的需求。
- 论文链接：https://doi.org/10.1038/s41467-024-55762-1

2、[iMetaOmics | 同济/上海交大-开发支持群体分组分析的宏基因组测序综合分析软件](https://mp.weixin.qq.com/s/Nsx8H5ukuHoOopSA-cSP7g)

![](https://files.mdnice.com/user/151230/aa8d1163-3dda-4727-a39b-acd12fc683bd.png)


该软件是一个针对宏基因组鸟枪法测序的综合分析软件，同时包含了群体分组分析。它包括14个模块，拥有超过50个功能，与现有的17种宏基因组鸟枪法测序（whole-metagenome shotgun sequencing，WMGS）工具相比，因其全面性而脱颖而出。OUTPOST为多组实验设计和基于荟萃分析的生物标志物鉴定引入了创新方法。
- 论文链接：https://onlinelibrary.wiley.com/doi/abs/10.1002/imo2.29

3、[Nature Genetics | 整合分析揭示三维基因组与DNA、RNA和表观遗传改变之间在转移性前列腺癌中的相互作用！](https://mp.weixin.qq.com/s/H1cJqTJDYlWC_vj4aabldg)

![](https://files.mdnice.com/user/151230/2d1606cc-474b-4fb4-97b2-f461217170e2.png)


该研究通过深度 WGS、WGBS、RNA-seq等多种全基因组方法对 80 例 mCRPC 活检样本进行了分析，并揭示了癌症中常见的基因组、表观基因组和转录组改变与基因组三维拓扑结构之间的相互作用。
- 论文链接：https://doi.org/10.1038/s41588-024-01826-3

4、[Nature子刊：量子计算的风，吹到了KRAS](https://mp.weixin.qq.com/s/dIZrVaKQL-xZ93vxVy4q6Q)

![](https://files.mdnice.com/user/151230/cc7a0d4c-64d4-4b84-9f08-de2cca07058b.png)


2025年1月22日发表在Nature Biotechnology杂志上的一项研究中，英矽智能与来自多伦多大学、圣裘德儿童研究医院等机构的科学家们将量子计算模型与经典计算模型和生成式人工智能相结合，通过对庞大数据集的训练、生成和筛选，探索更广泛的化学可能性，发现了靶向“不可成药”癌症驱动蛋白KRAS 的新颖分子。该研究首次展示了量子计算和人工智能在变革药物发现流程方面的潜力。
- 论文链接：https://www.nature.com/articles/s41587-024-02526-3

# 博文咨询
5、[有偿论文“捉虫”：发现已发表论文中的错误可获得奖励 |《自然》职场](https://mp.weixin.qq.com/s/TrR3yQFIJWSAMzPT3dtUWg)

![](https://files.mdnice.com/user/151230/311be99c-0ed5-46b5-bcf6-427b2c98b2d2.png)

- 原文链接：https://www.nature.com/articles/d41586-024-02681-2

关于科学界的自我纠错能力，Malte Elson直言："我们目前处理错误的方式是无效的。"ERROR项目是一个旨在系统性检测并纠正已发表心理学论文中错误的计划，通过向评审员支付报酬来检查高影响力论文的代码、统计分析和引用错误，并向提供数据和配合的作者提供补偿。项目优先选择高引用论文以扩大影响，并希望建立一种可推广的模式。目前面临作者参与度低、数据获取困难和寻找合格评审员等挑战，团队正寻求扩展至其他学科（如人工智能和医学），并呼吁研究资助机构为错误评审提供资源支持，认为系统性审查能提高科研经费的效益。

6、[样本量，最低要多少？](https://mp.weixin.qq.com/s/6F-uK98IQZ7nNOxUkNcxPw)

![](https://files.mdnice.com/user/151230/993596e0-ac52-49f7-8c17-1ca8c242ee61.jpg)


几乎所有人在数据分析中都关心一个问题，即样本量最低要多少。2020年发表在《PLOS ONE》的一篇题为《A solution to minimum sample size for regressions》的文章论述了在一般线性回归和meta 回归中，最低样本量应该是多少，模型结果就既能反映数据的实际格局，又具有较高的可重复性。

- 论文链接：https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0229345

7、[盘点：2024年全球十大畅销药物](https://mp.weixin.qq.com/s/UTKHMLr0G0YC0rKJHtDHjA)

![](https://files.mdnice.com/user/151230/b6c06ca3-2ad8-4577-8f8a-9020f19bdd30.jpg)


BioSpace盘点了2024年销售额最高的10大医药产品。

- 原文链接：https://www.biospace.com/business/10-best-selling-drugs-of-2024-rake-in-billions-amid-exclusivity-threats
# 工具
8、[Docker Image Puller](https://github.com/topcss/docker-pull-tar/ "Docker Image Puller")


Docker Image Puller 是一个方便的工具，用于从 Docker 仓库拉取镜像，支持国内镜像源加速和多架构支持。该工具采用 MIT 许可证，开放源代码，方便用户根据需要进行定制和扩展。


9、[开源AI数字人 AIGCPanel](https://github.com/modstart-lib/aigcpanel/ "开源AI数字人 AIGCPanel")


![](https://files.mdnice.com/user/151230/1622d4f0-6f70-48b6-9cef-75b85fba3479.png)

AigcPanel 是一个简单易用的一站式AI数字人系统，小白也可使用。 支持视频合成、声音合成、声音克隆，简化本地模型管理、一键导入和使用AI模型。

10、[医学研究者必备！这款R包让你的数据分析能力飙升](https://mp.weixin.qq.com/s/AGVP8x-k1GnNWihUJDVe-w)


![](https://files.mdnice.com/user/151230/787030ec-f698-4e81-a305-e4215f3dbee1.png)


MedicalData是一个专为医学领域打造的数据练习题库，包含15个医学数据集，从几百年前的坏血病研究到最新的新冠检测数据，覆盖经典案例与现代临床试验。其核心目标是帮助医生、护士、药师、医学生等从业者，通过R语言实践可重复研究。

# 资源
11、[硬核基础科研系列汇总](https://mp.weixin.qq.com/s/RtbDdZr6xKn2ZRror-jI-g)

推文汇总了细胞与分子生物学，分子克隆，qPCR等基础的科研知识。


12、[国家生物信息中心 - 数据库清单](https://mp.weixin.qq.com/s/Sea8cvVzDq0NH9fuZJf-aw)

- 网站链接：https://www.cncb.ac.cn


![](https://files.mdnice.com/user/151230/cb5310ac-f3b9-4368-a92f-43c7ef9aae13.jpg)

国家生物信息中心 是我国生物信息领域的核心平台，致力于推动生物大数据的统一汇交、集中存储与安全共享，为科学研究和成果转化提供坚实支撑。

# 贡献者（GitHub ID）
「Openbiox 生信周刊」运维小队：
- @ShixiangWang（王诗翔）
- @kkjtmac（阚科佳）
- @NiEntropy（赵启祥）
- @He-Kai-fly（何凯）
- @JnanZhang（张佳楠）
- @Tomcxf（陈啸枫）
- @wangdepin（王德品）
- @kongjianyang（空间阳）
- @donghongyu2020（董弘禹）
- @DrRobinLuo（罗鹏）
- @Wangcy-rachel（王春阳）
- @zoe3251（舒晨阳）
- @yanbin85 （严彬）
- @MadDERt（王章宇）

# 订阅
这个周刊每周日发布，同步更新在微信公众号「生信协作组」（elegant-r）上。

微信搜索“生信协作组”或者扫描二维码，即可订阅。

![](https://files.mdnice.com/user/146141/3e7099c5-ec08-41c5-8f41-34d0d58bbd71.png)
（完）
