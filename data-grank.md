# Grank 分析

# Grank 分析


在2018年，我们针对国内的开源项目进行了观测和数据研究，并进行了初步的分析[^2018os]。

在刚刚过去的 2019 年，我们使用相同的工具，进行了又一次的迭代、观测和分析，这一次，我们在去年的基础之上，加入了更多的分析唯独，引入了小企业、个人的开源项目，让整个数据覆盖到足够多的数据。

> 由于精力有限，未必能覆盖到所有的开发者，如果你希望自己被放在整个方案中统计，可以联系我[^mail]添加您的数据统计

由于数据分析方法未做大的变更，您可以在附录1中获取到

## 数据结果

### 分析方案

由于软件开发项目的迭代周期、研发难度有所不同，放在一个榜单内评比对于各项目来说，略显不公，因此，我们将参与分析的开源项目切分为以下四个类目，开源项目在同一类目下进行对比，具体分为以下四个类目：

1. **大前端类**：包括 iOS、Android、Web 大前端，主要为 Library
2. **服务端类**：包括 Java、Rust、PHP，主要为 Library 、Middleware
3. **工程类**：不限制语言，主要为可直接交付给C 端客户使用的项目，不作为开发工具参与到开发流程中。
4. **文档类**：主要是各类型的文档项目。

> 对于项目分类有任何建议，都可以通过邮箱[^mail]联系我

### 大前端类分析结果

#### 榜单情况



![](https://postimg.aliavv.com/mbp/6mpra.png)

#### 项目点评

**[ant-design/ant-design](https://github.com/ant-design/ant-design)**

这是一个“服务于企业级产品的设计体系”，是由蚂蚁金服体验技术部采用 React 封装的一套组件库。同时，也是去年的 Grank 评分的第一名。

![](https://postimg.aliavv.com/mbp/izwmu.png)

Ant-Desgin 项目在整体的大方向上于去年并没有太大的区别，甚至从数据的角度上来，2019 年 Ant-Design 有更多的数据更新，保持其一贯优秀的活跃度与社区化程度。

**[tencent/omi](https://github.com/tencent/omi)**

Omi是一个基于 Web Components 并支持 IE、小程序端的前端跨平台框架。

![](https://postimg.aliavv.com/mbp/hf0jy.png)

从数据上来看， Omi 项目的活跃度从 2018 年 9 月开始，有大幅度提升，并在 2019 年年初达到了数据的顶峰。在社区化程度方面，从 2019 年年中开始，其社区活跃度出现了下降的趋势，猜测可能是其在内部拥有了更大的话语钱，致使更多的企业内部开发者开始参与到 Omi 项目的开发。

**[elemefe/element](https://github.com/elemefe/element)**

Element 是由饿了么前端团队开源的 Vue UI 框架。

![](https://postimg.aliavv.com/mbp/8879l.png)

从项目活跃上看， Element 近年来的更新乏力，略显颓势。整个项目开始逐渐走向减少维护的阶段。

### 服务端类分析结果

#### 榜单情况

服务端类型在总榜排行占据前 100 名的项目有 50 个，占据了整个榜单的半壁江山，其中，PingCAP 公司与 Apache 基金会的项目直接占据了前五名的份额。

![](https://postimg.aliavv.com/mbp/gcpn7.png)



#### 项目点评

**[pingcap/TiDB](https://github.com/pingcap/tidb)**

TiDB 项目是 PingCAP 公司的明星项目，是一款定位于在线事务处理/在线分析处理融合型开源数据库产品。

![](https://postimg.aliavv.com/mbp/hjl7b.png)

从数据上来看，TiDB 项目近年来的活跃度不断攀升，与之成为鲜明对比的，是其项目的社区活跃度的不断下降。不过，PingCAP 是业界非常典型的开源企业，其协作模式是所有开发人员通过 Github 进行协作，对于合适的开发人员，PingCAP 会选择提供其 Offer，允许其远程办公，以这样的方式来吸收社区的优秀开源力量，其社区化程度不断下降也实属正常。毕竟，优秀的开发者都被 PingCAP 转化为正规军，也不失为一个好的方法。

**[tikv/tikv](https://github.com/tikv/tikv)**

TiKV 是一个支持事务的分布式 Key-Value 数据库，同样也是 PingCAP 的明星产品

   ![](https://postimg.aliavv.com/mbp/jfryn.jpg)

从数据上看，Tikv 近些年的社区化程度一直在上下波动，不过考虑到其是在 TiDB 出现后的产品，有可能延续了 PingCAP 公司将开发者收归己有的习惯，出现波动实属正常。不过，虽然出现了波动，但其社区化程度始终处在 80% 以上，依然有大量的社区开发者为 TiKV 贡献代码。

从活跃度上来看，TiKV 的数据活跃度整体不错，在今年年底，TiKV 举办了一次[性能挑战赛](https://mp.weixin.qq.com/s/lyae8nwZ6i_V2STwacf6tA)，因此出现了大幅度的活跃度暴涨。

**[apache/skywalking](https://github.com/apache/skywalking)**

SkyWalking 是由吴晟老师主导的项目，从 2017 年开始，进入 Apache 孵化器孵化，于 2019 年 4 月结束孵化，成功成为 Apache 顶级项目。

![](https://postimg.aliavv.com/mbp/hpobz.png)

Skywalking 项目的活跃度存在大小月的情况，会出现明显的的波峰、波谷出现，但整体项目活跃度一直不错。


### 工程类分析结果

#### 榜单情况

在总榜排行前 100 名的项目中，共有 2 个项目，具体如下：

![](https://postimg.aliavv.com/mbp/swjxk.png)

#### 项目点评

**[RSSHub](https://github.com/DIYgod/RSSHub)**

RSSHub 是一个帮助用户将各种各样的内容转化成 RSS 的工具，今年也是他的第一次上榜，RSSHub 以 23 的活跃度积分位列榜单 12 名。

![](https://postimg.aliavv.com/mbp/y9hvj.png)

作为一个个人项目，RSSHub 可以说做的是非常棒了，而且，RSSHub 的社区化做的非常好，一直处在高位， 拥有 300 位 Contributors。

**[studygolang/studygolang](https://github.com/studygolang/studygolang)**

![](https://postimg.aliavv.com/mbp/lw44f.png)

studygolang 项目是 studygolang.com 网站的源码，其整个社区都是基于这样的一种开源模式的方式进行维护，让整个项目的活跃度优于一些传统的开发项目，这种开源和社区协作的模式，值得其他开发者学习。

#### 工程类榜单总结

工程类的榜单略显清冷，这可能源自于 Grank 的评分标准和工程类的特性。Grank 仅分析 Star 数在 1000 以上的项目，绝大多数的工程类都会因为 Star 不够而被过滤掉。而剩下的项目，则会因为需求的完全而停止维护，不得不说，这也是为什么工程类往往很难有特别出名的，一个项目的设计、可拓展性，深深的影响着工程类项目的发展。

### 文档类榜单

#### 榜单情况

在总排行前 100 名的项目中，共有 8 个文档类型的项目，具体如下：

![](https://postimg.aliavv.com/mbp/1py2l.png)

#### 项目点评

**[tencentyun/qcloud-documents](https://github.com/tencentyun/qcloud-documents)**

![](https://postimg.aliavv.com/mbp/mvk42.png)

此项目为腾讯云文档，一个令人惊讶的项目，拥有 543 个 Contributor 和 119441 个 commits ，平均更新频次为 5 分种/次，有非常惊人的高频维护，估计是腾讯云将其整个文档放置在 Github 上进行开放协作，同时，所有的内部合作，都需要通过 Github 来完成。

**此项目虽然活跃度高，由于项目的贡献指南并未说明，绝大多数开发者没有明确的规范参与到项目的更新。**

**[lctt/translateproject](https://github.com/lctt/translateproject)**

![](https://postimg.aliavv.com/mbp/3v0ij.png)

此项目为归属 Linux 中国旗下的翻译组主仓库，该项目拥有 464 名 contributor 和 47776 个 commits 以及 1.5k star ，平均更新频次为 2 小时，更新频次较高。

**此项目拥有完善的贡献说明，对于新手开发者来说，更加的友好，对于无法参与到开发阶段的开发者，可以考虑从翻译开始。**

**[xitu/gold-miner](https://github.com/xitu/gold-miner)**

![](https://postimg.aliavv.com/mbp/2kbup.png)

此项目为掘金翻译计划的官方 Repo ，来自社区的开发者们在一个 Repo 上协作，贡献自己的翻译文章，该项目拥有 417 名 Contributors 和 9754 个 Commits，以及超过 24.9K 的star。

#### 文档类榜单总结

文档类项目在总榜前100名中占据了 8 个席位，其中前两个项目 *qcloud-documents* 和 *translateproject* 更是拥有不俗的贡献量，其项目活跃度非常的可观。在所有的文档项目中，有3个翻译组项目；4个文档项目；1个文章推荐类的项目，总体来说，企业与社区各占据一半的席位。

这样的数据，也让我们看到，企业越来越关注开源，以及其背后的价值，企业开始尝试以开源的方式，来完成企业工作的协作，也不失为一个好方法


### 总体项目榜单

以下为所有项目分析结果中取前100名的榜单

![](https://postimg.aliavv.com/mbp/bsquk.png)

#### 总榜结果分析

![](https://postimg.aliavv.com/mbp/e8zgq.png)

今年前100项目中服务端项目占据了半壁江山，剩下一大部分则由大前端领域占领，文档类和工程类合计占比 10%；


## 数据点评

### 持续卓越的开源项目

- **pingcap/tidb**: TiDB 是一个非常活跃，有价值的项目，同时，其协作方式，值得国内的企业、开源团队学习。通过向开源社区征集贡献，从而发现更多社区人才，发展其商业公司。
- **ant-design/ant-design**：ant-design 是 2018 年的 Grank 第一名，在 2019 年的数据中，虽然未能在总榜中斩获榜首，但在大前端榜单中，依旧占据了第一名的位置，而且与第二名的距离较大，可以期待，2020 年， AntDesign 的持续活跃。


### 值得关注的开源新星

- **tencent/omi**: Omi 是 2018 年腾讯发布，2019 年迅速成长的新项目，发布仅一年，就牢牢的占据了前端榜单的第二名，获得了 33.76 的活跃积分，高于老牌项目 Element，仅次于 Ant Design
- **diygod/rsshub**:RSSHub 是极为活跃的个人项目，即使在 总榜，也占据了第 14 名的名次，活跃度超过了诸如 weex、ice、zent 等项目，如果长期保持下去，rsshub 有望成为榜单的前10名，甚至冲击前五名。

## 附录 1 研究方法综述

Grank 是本报告制定的一个指数，用于综合评估一个开源项目、开源组织的健康程度。

**Grank 模型介绍**

我们认为，一个健康的开源项目应该体现为以下两个方面：

- 项目的活跃度趋势
- 项目的社区化（去中心化）程度

而这两个方面分别有多个因素组成：

**活跃度和活跃度趋势**

项目的活跃度，我们定义为项目的提交数、 拉取请求数和贡献者数（其它数据，如代码行数、文件数、issue 数、 fork 数、star 数，要么是权重相对低得多，要么是代表意义不够确定，此处忽略不计入模型）。

但是，对于不同的项目，其横向比较其活跃度，或有不同的活跃度形态，或不具备可比性。很难说一个项目比另外一个项目的提交数高，而拉取请求（PR）数低代表的确切含义。因此我们不认为对不同项目的这些数据进行绝对值的比较有太多的科学意义。

所以，我们认为一个项目本身的活跃度变化的趋势和幅度，会更有项目间比较的意义。

如果以三维空间来描述一个项目的活跃度，以提交数、拉取请求数、贡献者数为三维，可以确定在某个时间点某个项目的坐标，那么计算一段时间内，该坐标点的移动轨迹和速率，可以真实的反映该项目的活跃度趋势。

考虑到按周工作的作息时间的普遍影响，我们以一个工作周作为一个时间采样点，然后计算连续的几周内该坐标的移动速率。这反映了该项目的发展速度。

**社区化程度**

开源诞生于社区，繁荣于社区，根植于社区，虽然现在大型组织、商业公司也纷纷投身于开源生态，但是我们认为，开源项目的生命力仍然在于社区。我们并不否认机构、商业公司对开源的巨大贡献和影响力，但是如果一个开源项目变成了一家或几家大企业的私人游戏，其必然失去开源项目的生命力，它或许会在商业上取得成功，但是那个成功不是开源项目的成功模式。

因此，我们认为需要有一个评估开源项目的社区化（去中心化）程度的指标。项目（尤其是软件项目）的一个重要属性是开发人员的社区化身份，因此，我们以实际向项目贡献了代码的人员的社区化离散程度来评估项目的社区化程度。

每个参与项目开发的人员均有其身份属性，这个身份可能是企业雇佣身份，也可能是社区志愿者身份。我们通过对项目的提交中的提交者数据进行收集，然后根据开发人员的身份信息、邮件后缀等依优先级来判断其所属身份。然后对这些信息进行聚类，以一个离散评估模型来评估该数据集的离散程度。

虽然项目越中心化，其发展风险越高，但是，并不是社区化程度越高的项目就越健康，过于离散的项目也容易出现项目分裂、迭代缓慢等问题。这显然是存在一个适当的区域。

通过上述两个指数，我们可以对项目进行象限划分，以“项目活跃度”和“社区化程度”为两个象限轴。



## 附录 2 数据采集方式与时间

数据采集方式：基于 Github  Developers API V4 进行数据抓取

数据采集工具: http://github.com/lctt/grank

数据抓取时间范围： 2017 年 1 月 1 日 ～ 2019 年 12 月 09 日


[^2018os]: https://kaiyuanshe.cn/2018-China-Open-Source-Report/chapter-dataanalysis/grank.html 
[^mail]: xiqingonzi+grank@gmail.com