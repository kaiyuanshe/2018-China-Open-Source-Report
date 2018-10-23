### 第三篇 洞察篇

#### 3.1 驱动开源背后的重要力量

**引子**

你有没有觉得开源就像有着魔力般的存在？不仅让人对它的产生发生好奇之心，连它的背后运转的过程更是谜一样存在，令人欲罢不能。来自互联网的某个人或某个小团队，发起了一个项目（多数时候是软件），以自由的名义，竟然改变了世界的发展的轨迹，它们有 Linux Kernel 软件项目、Wikipedia 知识、大数据分布式计算算法、人工智能之机器学习、区块链之加密货币等等。

以下内容，尝试从工程、方法论的角度阐释开源背后的驱动力所在。

开源软件和软件本身比较起来，还算是个“年青人”，正是处于蓬勃向上的嗷嗷叫的时光。1998 年，Bruce Perens 和 Eric S. Raymand 联手创建了开放源代码促进会，正式的将开源软件定义公布于世，成为独立于自由软件之外的一股力量。于是，一个试图平衡商业和热爱自由的程序员之间的张力的理念诞生了，从此一发不可收拾，直到今天，成为了整个互联网和基础设施软件的中流砥柱。

**社区是什么？**

毫无疑问，现代软件的复杂程度已经超越了任何单个个人的智力和技能的极限，它就像世界上其它的复杂事物一样，需要多人协作来共同完成。

我们以 Linux 为例，简单聊一下社区。

Linux 系统是一门公共的匠艺，Linux 程序的内核是对所有人开放的，任何人都可以采用和修改它；许多人奉献了大量的时间去完善它。再去近距离的观察它，你甚至为发现它的非人格性。例如，在 Linux 的 IRC 里，你无法推断 aristotle@mit.edu 是男是女；重要的是 aristotle@mit.edu 对讨论有所贡献。邮件列表中会经常看到 “你怎么可以怎么做”，“这个问题太糟糕”，就现在的职业伦理来说，这对于在一家企业工作中是完全不可思议的事情。

虽然近来 Linus 要无限期休假，要反思 Linux 开发过程中自己的一些言语。但是要知道，这个社区就是依靠这样的风格，成功的运行了 27 年。

我们不必去定义具体的社区是什么，如果你非得严谨的去考察一下，不妨阅读一下《社区的艺术》一书。这里只想说明的是，开源项目由社区所开发、运营、宣传、接受反馈、进行设计和优化等等全部的工作，由来自全球各个角落，要完成某件事，或者是为了把事情做好而做好，去**协作**完成既定的目标。

社区的重要性是不言而喻的！但是社区是一种社会现象，它本身的发展需要治理。一个活跃的、开放的、友好的社区是项目极为重要的部分。

**基金会的来龙去脉**

我们已经看到开源不再是被孤立的集体或与世无争的了：开源的商业化和普及化引来了一些公司和大企业的投资和参与。但随之而来的问题就是，在这些项目中商业化和社区的兴趣之间的冲突日益的计划，尽管开源有太多精明的参与者。

>  在开源和商业利益的十字路口，问题日益严峻的是有关权威、真实性和文化的问题。

> ——Nathen Harvey, Information Week

Nathen Harvey 在 Information Week 中的文章中指出了三个问题：

> **“项目应该由商业的赞助商驱动还是外围的贡献者驱动？商业利益是否应该凌驾于社区的意愿之上？该如何以及在哪里为商业实体和开源社区之间划上一个明确的界线？**”

于是软件基金会成立了！知名的有：

* Apache 软件基金会
* Linux 基金会
* OpenStack 基金会
* 自由软件基金会（FSF）
* Creative Commons
* Eclipse 基金会
* Internet Systems Consortium (ISC)
* Mozilla 基金会
* 开源促进会（OSI）
* 软件自由法律中心（SFLC）
* ......

正如[《精心布局的开源》](http://www.ocselected.org/posts/opensource/open_by_design/)一文中所称，开源软件基金会所带来的开放治理实践，其回答了有关开源中的影响、所有权、领导力、以及制定决策。每一个项目都会在独立和商业贡献者参与的纠结成长之路，我们相信通过厂商中立的开放治理，能够打造一个精英式的技术开发实践，都会让开源作为事实上的开发模式而持续有力发展，无论对于商业的还是非商业的实体。

不可否认的事实是，开源软件获得良好的发展，中立的环境是最佳的选择，那么非盈利性质的基金会是所有的选择中最为妥善的。于是，开源项目相关的基金会崛起！连大名鼎鼎的好莱坞都成立了 [The Academy Software Foundation (ASWF)](https://www.aswf.io/about/)。

**三大基金会风格对比**

以下内容，尽可能尝试精简提炼，而且均在发展中，此表格也会与时俱进，保持常新。

![enter image description here](https://images.gitbook.cn/17fa84d0-d3b7-11e8-b055-6fdf72668cfc)


**结语**

驱动开源的力量有众多，COSCon 的调查更加注重其社会性的因素：协作与治理，以上便是我们的解释。

参考文章：

1. [《Apache 是如何运转的》](http://www.ocselected.org/posts/foundation_introduce/how_apache_works/)
2. [《CNCF 是如何运转的》](http://www.ocselected.org/posts/foundation_introduce/how_cncf_works/)
3. [《OpenStack 基金会治理指南》](https://docs.openstack.org/contributors/common/governance.html)

#### 3.2 开源发展的历史——企业参与情况

**单一厂商的开源项目限制了项目社区的发展**

为什么越来越多的公司愿意将他们的项目捐赠给国际顶级开源软件基金会呢？以下的数据提供了一些线索：

单一厂商的大型项目多受限于某种无形的“玻璃天花板"，如 [MySQL](https://github.com/mysql/)、[Qt](https://github.com/qt/)、[OpenOffice](https://github.com/apache/openoffice)、[Mono](https://github.com/mono/mono)、[JBoss](https://github.com/JBoss) 等，这些单一厂商项目平均不到 200 名开发者，且日均代码提交小于 100 次；而全球九大开源软件基金会的顶级项目均有超过 1000 名开发者，且日均代码提交大于 100 次。这揭示了基金会治理模式的优越性。而与社区协作来开发开源项目的厂商表述，其透过开源基金会的项目社区的开发投资回报约为他们自己单一厂商项目的 5 倍。

**非营利性基金会助力社区与业务增长（以 Apache 为例）**

[Henrik Ingo](http://openlife.cc/blogs/2010/november/how-grow-your-open-source-project-10x-and-revenues-5x) 在他的研究 “[如何让你的开源项目成长 10 倍而营收成长 5 倍？](http://openlife.cc/blogs/2010/november/how-grow-your-open-source-project-10x-and-revenues-5x)” 一文里显示了大规模的社区 （通常来自于非营利的开源软件基金会），意味着更大的潜在市场（蓝色），更大的潜在市场意味着更多的买单的客户 (绿色），更多的代码贡献者（橙色）意味着更多的客户需求得以满足，从而形成正向循环。

这也是目前国内许多企业选择捐赠开源项目、加入或资助国际顶级开源软件基金会（如 ASF）的主要原因之一。**下文将以目前全球最大的软件基金会 Apache 软件基金会（以下简称 ASF）为例，**做进一步阐述。

![enter image description here](https://images.gitbook.cn/6306fa40-d41a-11e8-80d1-917ffa8847fa)

##### **Apache 软件基金会**（[Apache Software Foundation](http://www.apache.org/)）

![enter image description here](https://images.gitbook.cn/90e42870-d41a-11e8-80d1-917ffa8847fa)

ASF 是目前全球最大（[运营最多开源项目及其社区，多达 196 个项目委员会，6,513 位提交者](https://apachecon.com/acna18/presentations/0507bc27d5a26ce75.zip)），同时也是最成功的软件基金会。ASF 是依美国非营利慈善组织条例 501(c)(3) 设立的软件基金会，其成立宗旨是为了公众利益而提供软件。ASF 完全由志愿者构成，每年由所有个人会员（截至 2018 年 10 月有 730 名个人会员）选举董事，没有任何商业机构可以进入董事会或任何项目委员会。ASF 在 2018 年预期接受捐赠的金额约为 150 万美元，这和 ASF 的年度运营费用大致相同，由于 ASF 为志愿组组成，只有极少数的全职人员，因此主要的经费用于基础设施以运营数以百计的开源项目。

其他一些依据美国非营利商业联盟组织条例 501(c)(6) 条例而成立的基金会，如 Linux 基金会，则为机构会员制，通常是顶级赞助机构会员有机会进入董事会或是各种技术决策委员会（TSC）。Linux 基金会在 2018 年预期会员赞助费及其他收入 (如培训，会务收入等) 的金额可能将近一亿美元左右。

**Apache 之道**（[The Apache Way](http://theapacheway.com)）

ASF 以其独特的治理模式 - Apache Way 强烈地吸引了众多开源项目与社区加入。那么，什么是 Apache Way 呢？Apache 软件基金会董事 Shane Curcuru 做出了一些说明：

* 慈善（Chariy）：ASF 的使命是为了公众利益而提供软件。
* 社区（Community）：众人拾柴火焰高，社区大于代码。
* 共识（Consensus）：透过讨论而获得足够好的共识，远比投票好。
* 功绩（Merit）：根据个人贡献获得认可，贡献得越多，就有更多发言权，从而贡献更多。
* 开放（Open）：决策公开透明。任何决策如果没有在公开的邮件列表中讨论过，那么就等同没有发生过。
* 务实（Pragmatic）：采用务实而商业友好的 Apache 开源许可协议.
* 商标（Trademarks）: 一旦成为 ASF 顶级项目（TLP），即受到ASF商标保护，减少诉讼风险。
* 中立（Vendor Neutral）: 开源项目与社区贡献完全以个人身份参与，不涉及个别厂商利益。

**ASF 孵化器**（[Apache Incubator](http://incubator.apache.org/)）

Apache 孵化器目前有 52 个孵化项目，由于申请者众多，门槛也不断提高。目前国内已经有一些项目进入孵化器，或者已经毕业成为顶级项目。略述于后。

![enter image description here](https://images.gitbook.cn/32b02410-d41b-11e8-80d1-917ffa8847fa)

**立足中国、贡献全球**

自 2014 年 10 月成立以来，[开源社](http://www.kaiyuanshe.org/)秉持 “带进来、走出去” 的使命感，持续不懈地助力开源项目与社区立足中国，贡献全球。

2009 年 ASF 曾经在中国办过一次小型的路演，6 年之后的 2015 年 10 月，开源社和 ASF 携手举办了“[2015 Apache 中国路演](https://mp.weixin.qq.com/s?__biz=MzA5MTA2NDA5MQ==&mid=211757032&idx=1&sn=48b923fcd8e4467128f55dd331b69676&mpshare=1&scene=1&srcid=1011UJwKAfRzPGu0onOV4cwQ#rd)”，邀请了当时的 ASF 主席 Brett Porter、总裁 Ross Gardler、董事会成员 David Nalley 及多位 ASF 顶级项目大神等莅临，为中国的开源项目进军 ASF 点燃了星星之火，造就了燎原之势；

2016 年起，开源社主办的中国开源年会（COSCon）皆以立足中国、贡献全球为主题，邀请国际各大基金会及国际大神们参与盛会，力求实现“带进来、走出去”的使命。

从 2015 年到 2018 年，开源社也不断地与多个国内的项目社区进行合作推广，助力源自中国的开源项目。

我们一起见证了中国的开源项目，由 2015 年的三个 ASF 孵化项目或顶级项目，拓展到了目前的 12 个，从目前新增的 ASF 项目绝大多数由大企业（如华为、阿里巴巴、百度等）捐赠的趋势来看，国内的大企业已经开始意识到单一企业发展开源项目与社区的”玻璃天花板“局限性，从而付诸行动捐赠、资助或加入开源软件基金会，以加速发展其开源项目与社区的优势。

**源自中国的 ASF 项目**（截至 2018 年 10 月 20 日）顶级项目 (TLP - 6)：

* [Apache CarbonData](https://carbondata.apache.org/)
* [Apache Eagle](http://eagle.apache.org/)
* [Apache HAWQ](http://hawq.apache.org/)
* [Apache Kylin](http://kylin.apache.org/)
* [Apache RocketMQ](http://rocketmq.apache.org/)
* [Apache ServiceComb](http://servicecomb.incubator.apache.org/)（预计 2018 年 10 月毕业为顶级项目）

孵化项目（Incubating - 6）：

- [Doris](http://doris.incubator.apache.org/)（原 Palo）
- [Dubbo](http://dubbo.incubator.apache.org/en-us/)
- [ECharts](http://echarts.incubator.apache.org/)
- [Griffin](http://griffin.incubator.apache.org/)
- [Skywalking](http://skywalking.apache.org/)
- [Weex](http://weex.apache.org/)


![enter image description here](https://images.gitbook.cn/d68e36d0-d41b-11e8-80d1-917ffa8847fa)


依照上图的时间线，简述一些由华人或是本土公司推动开源并走向顶级国际基金会软件基金会的历程：


> eBay中国：[https://github.com/ebay](http://https:/github.com/ebay)

* [Apache Kylin](http://kylin.apache.org/)：第一个由华人主导的 Apache 项目，2014 年 10 月正式于 eBay 开源，11 月进入 ASF 孵化器，2015 年 11 月毕业成为 ASF 顶级项目。2016 年由 Kylin 项目负责人韩卿 Luke 及李扬创建了 Kyligence 公司（上海跬智： [https://github.com/kyligence](https://github.com/kyligence)）。值得一提的是韩卿 Luke 本人也为推动更多本土优质项目进入 ASF 尽心尽力，也曾志愿担任 RocketMQ 等孵化项目的导师。
* [Apache Eagle](http://eagle.apache.org/)：2015 年 10 月进入孵化器，2017 年 01 月毕业成为 ASF 顶级项目；
* [Apache Griffin](http://griffin.incubator.apache.org/)：2016 年 12 月进入孵化器


> Pivotal: [https://github.com/pivotalsoftware](https://github.com/pivotalsoftware)

Pivotal 开源 HAWQ，2015 进入 ASF 孵化器，2016 年 HAWQ 项目创始人常雷博士创立了偶数科技，2018 年 08 月 HAWQ 毕业成为 ASF 顶级项目：

- [Apache HAWQ](http://hawq.apache.org/)


> 华为：[https://github.com/Huawei](https://github.com/Huawei)

* [Apache CarbonData](https://carbondata.apache.org/)：2015 开源，2016 年 06 月进入 ASF 孵化器，2017 年 04 月毕业，成为首个中国公司捐赠的项目进入 ASF 孵化器，也是[第一个毕业的本土原生的 ASF 顶级项目](https://mp.weixin.qq.com/s?__biz=MzA5MTA2NDA5MQ==&mid=2655310830&idx=1&sn=7df5aeb201a0c103c0c70c9a2e6edbe8&chksm=8bb2619abcc5e88c040e6b464b8fa0bc84834e5214e469c0e1ed959503c3b375e09feac8648a&scene=0)。
* [Apache ServiceComb](http://servicecomb.incubator.apache.org/)：2017 年 12 月进入孵化器

> 阿里巴巴：[https://github.com/alibaba](https://github.com/alibaba)

截至目前为止，阿里巴巴开源了 100 多个项目，2016 年及之后开源了 Ant Design、Hilo、Weex、Freeline、Macaca、AliSQL、EGG、ApsaraCache、Sentinel、OpenMessaging 等。其中几个项目捐赠给全球最大的软件基金会 Apache Software Foundation：

* [Apache RocketMQ](http://rocketmq.apache.org/) （顶级项目）：2016 年 11 月进入 ASF 孵化器，2017 年 09 月毕业
* [Apache Weex](http://weex.apache.org/)（孵化中）：2016 年 12 月进入 ASF 孵化器
* [Apache Dubbo](http://dubbo.incubator.apache.org/en-us/)（孵化中），2018 年 02 月进入 ASF 孵化器
* Pouch：后更名为 PouchContainer，2017 年 11 月在 2017 中国开源年会 （COSCon'17）宣布开源

此外，阿里巴巴公司也积极地加入或赞助了多个国际开源软件基金会及社区，如 Apache Software Foundation、Linux Foundation、CNCF、MariaDB、FSF、NTF 基金会、ISC 社区等。


> 百度：[https://github.com/baidu](https://github.com/baidu) 也有诸多开源项目，其中：

* ECharts：2018 年 03 月加入 ASF 孵化器
* Doris（原 Palo）：2018 年 07 月加入 ASF 孵化器

同时，百度公司也积极地加入或赞助了多个国际开源软件基金会，如 Apache Software Foundation、Linux Foundation、CNCF 等。


> [Apache Skywalking (Incubating)](http://skywalking.apache.org/)

2017 年  12 月进入 ASF 孵化器，是国内目前唯一成功进入国际软件基金会的由个人（非公司）主导的开源项目。


除了上述公司及个人，腾讯也积极开源，并且选择了不同的捐赠方向，进军国际。


> 腾讯：[https://github.com/Tencent](https://github.com/Tencent)，正式开源 56 个项目（截至 2018 年 06 月）

* Tars.js：2017 年开源，2018 年 06 月捐赠给 Linux Foundation
* TSheer：2018 年 06 月捐赠给 Linux Foundation

**其他国内开源先锋**

除了上述领头羊，国内也有许多企业开源了多个项目，略述于下 （依字母顺序排列）：

- 360：[https://github.com/qihoo360](https://github.com/qihoo360)

> evpp、SpriteJS、GoReporter、zendAPI、Atlas MySQL、Firekylin、Excelize、phptrace、Learning、DroidPlugin、HustStore、Pika、ThinkJS、Nova.js、Poseidon、RePlugin、QConf、logkafka、elog、Kmemcache

- 滴滴：[https://github.com/didi](https://github.com/didi)

> VirtualAPK、cube-ui、mand-mobile、gendry、DDMQ、Pile.js、thinkjs、pika、phptrace

- 大众点评：[https://github.com/dianping](https://github.com/dianping)
- 豆瓣网：[https://github.com/douban](https://github.com/douban)
- 京东：[https://github.com/CHINA-JD](https://github.com/CHINA-JD)

> Speedy、Taro UI、Hydra、Nerv、Overwatch

- 网易：[https://github.com/netease](https://github.com/netease)
- 唯品会：[https://github.com/vipshop](https://github.com/vipshop)
- 小米：[https://github.com/xiaomi](https://github.com/vipshop)

**顶级国际软件基金会有哪些国内顶级企业加入/赞助？**

我们从另外一个角度来看国内企业捐赠、赞助、加入国际软件基金会的状况：

[Apache Software Foundation (ASF)](http://www.apache.org)：

1. 白金：[腾讯云](https://cloud.tencent.com/?lang=en)
2. 黄金：[华为](https://www.huawei.com/en/)
3. 白银：[阿里云](https://www.alibabacloud.com/)、[百度](http://www.baidu.com/)、[浪潮](http://en.inspur.com/)

[Cloud Native Computing Foundation ](https://www.cncf.io/)（CNCF - [云原生计算基金会](https://mp.weixin.qq.com/s?__biz=MzA5MTA2NDA5MQ==&mid=2655311429&idx=1&sn=70439708e22a97ab30efe12e75851b07&chksm=8bb26431bcc5ed27be07d7b41df0ed21d0767d4406a901782a82189459f276f1ef15ef758088&mpshare=1&scene=1&srcid=1008oCHTAjuJkfxVJwPnLIjD)）：

1. 白金：[阿里云](https://www.alibabacloud.com)、[华为](https://www.huawei.com/en/)、[京东](http://www.jd.com/)
2. 黄金：[百度](http://www.baidu.com/)、[腾讯云](https://cloud.tencent.com/?lang=en)、[中兴](https://www.zte.com.cn/global/)
3. 白银：[九州云](http://www.99cloud.net/)[灵雀云](http://www.alauda.cn/)、[博云](http://www.bocloud.com.cn/en/index.html)、[七牛](https://www.qiniu.com/)、[时速云](https://www.tenxcloud.com/http:/www.alauda.cn/)、[中国移动](https://www.chinamobileltd.com/en/global/home.php)、[易捷行云](https://www.easystack.cn/)、[酷栈](https://cstack.net.cn/)、[道客](https://www.daocloud.io/)、[易保](https://www.ebaotech.com/)、[浪潮](http://en.inspur.com/)、[平安科技](http://tech.pingan.com/en/index.html)、[滴滴](https://www.didiglobal.com/)

[Linux Foundation (LF)](https://www.linuxfoundation.org/)：

1. 白金会员：[华为](https://www.huawei.com/en/)、[腾讯](https://www.tencent.com/zh-cn/index.html)
2. 黄金会员：[阿里云](https://www.alibabacloud.com/)、[百度](http://www.baidu.com/)
3. 白银会员：[九州云](http://www.99cloud.net/)、[中国移动](https://www.chinamobileltd.com/en/global/home.php)、[中国电信](https://www.chinatelecom-h.com/en/global/home.php),[ 中兴](https://www.zte.com.cn/global/)、[联想](https://www.lenovo.com/ca/en/)、[招商银行](http://english.cmbchina.com/)、[中信集团](https://www.group.citic/)、[中证信用](http://www.chinacsci.com/)、[易保](https://www.ebaotech.com/)、[平安科技](http://tech.pingan.com/en/index.html)、[滴滴](https://www.didiglobal.com/)、[浪潮](http://en.inspur.com/)、[京东](http://www.jd.com/)、[七牛](https://www.qiniu.com/)、[时速云](https://www.tenxcloud.com/)、[一铭软件](http://www.emindsoft.com.cn/)、[易捷行云](https://www.easystack.cn/)、[酷栈](https://cstack.net.cn/)、[道客](https://www.daocloud.io/)、[华大基因](http://www.genomics.cn/en/navigation/show_navigation?nid=64)、[亿阳信通](http://www.boco.com.cn/comwelcome.htm)、[万向](http://www.wanxiang.com.cn/en/)、[链链](http://www.chainconnected.com/)、[智链](https://www.chainnova.com/)、[趣链](https://www.hyperchain.cn/)、[超算科技](http://www.coos.ai/)、[中标软件](http://www.cs2c.com.cn/http:/tech.pingan.com/en/index.html)..

[Open Stack Foundation](https://www.openstack.org/)：

1. 白金会员：[华为](https://www.huawei.com/cn/)、[腾讯云](https://intl.cloud.tencent.com/)
2. 黄金会员：[九州云 (99Cloud) ](http://www.99cloud.net/)、[中国移动](https://www.chinamobileltd.com/en/global/home.php)、[中国电信](http://www.ctsi.com.cn/)、[中国联通](http://www.chinaunicom.com.cn/)、[中兴](https://www.zte.com.cn/global/)、[易捷行云 (EasyStack](https://www.easystack.cn/))、[烽火科技](http://www.fiberhomegroup.com/cn/)[浪潮](http://en.inspur.com/)

[MariaDB Foundation](https://mariadb.org/)：

1. 白金会员：[腾讯云](https://intl.cloud.tencent.com/)、[阿里云](https://www.alibabacloud.com/)
2. 黄金会员：[腾讯游戏](http://game.qq.com/)

[Free Software Foundation](https://www.fsf.org/)：Patrons（赞助者）[阿里巴巴](https://www.alibabacloud.com/)

**国外顶级企业的开源历程**

毋须辩驳的是，开源起源和崛起于西方，很多顶级的基金会均是在美国注册的，而且有非常多的成功经验可以学习和借鉴，开源社不忘初心，坚持“带进来、走出去”的使命 ，除了助力国内企业更加了解开源，了解治理，携手发展与推广开源项目及社区之外，也将国际各大开源软件基金会积极地引进国内，同时也持续不断地撰文和翻译，将国外大厂与顶级开源软件基金会的成功经验与案例传播给中国的企业与社区，已解决他们心中的疑惑，从而能稳健而坚定地走出自己的开源之路。

以下一些链接和内容简介供大家参考：

- [Dropbox](https://mp.weixin.qq.com/s?__biz=MzA5MTA2NDA5MQ==&mid=507827611&idx=1&sn=4e4dfdb306a67615d57ee282d2973c14&chksm=0bb267ef3cc5eef941977583badbf30712839e3ff8fb80cb1ff1fb708e8b920a1ecbb8217dee&scene=18) 的开源进化史 (翻译)

本文言简意赅的介绍了Dropbox从使用开源到拥抱开源到贡献开源的历程。

- [GitHub](https://mp.weixin.qq.com/s?__biz=MzA5MTA2NDA5MQ==&mid=2655311437&idx=1&sn=312e345490c927c657a541febc6bceb3&chksm=8bb26439bcc5ed2f1fdfb0b31c8cab2a90b3bc72328f56d20c9510a1e48fb00a2d73db0b1ff1&scene=0) 开源指南系列（1~8、翻译）

事无巨细的介绍了开源应该做什么？无论是企业还是个人，均能从此系列中获益。

- [Microsoft](https://mp.weixin.qq.com/s?__biz=MzA5MTA2NDA5MQ==&mid=2655311068&idx=1&sn=b54c41273c2112ebb0fc9217412118e6&chksm=8bb266a8bcc5efbe76f753509cd6aff93f59781adf5c6a8a585cd3bba606200f444ee7d04279&scene=0) 的开源成功计划

软件巨头是如何进行逆向转型的，从视开源为对手到彻底拥抱！
这里要特别值得和大家说明的是，微软同时也是[第一个国际企业捐赠开源项目给中国的开源社区](https://mp.weixin.qq.com/s?__biz=MzA5MTA2NDA5MQ==&mid=2655311206&idx=1&sn=edfab6401bb27f5c29dc876a49e0b27c&chksm=8bb26712bcc5ee040a740c0e8976bf27a35ee9340a71412e761f9c008298f7f94fb1607f410e&scene=0)

- [Salesforce](https://mp.weixin.qq.com/s?__biz=MzA5MTA2NDA5MQ==&mid=2655311203&idx=1&sn=cfdac322ba71b1e5e6b44f084523d74e&chksm=8bb26717bcc5ee01e7d67f7ed794adb77d13cefcc4d7b88f18ef03eccca0391a08b2d112b5f7&mpshare=1&scene=1&srcid=10080WrmraGvGmuwoaCJi9W5) 的开源故事（翻译）

SaaS 云计算服务公司的楷模拥抱开源的故事。

- [Autodesk](https://github.com/todogroup/guides/blob/master/casestudies/autodesk.md) 的开源故事（英文）

Autodesk 也有开源部门。

- [CapitalOne](https://github.com/todogroup/guides/blob/master/casestudies/capitalone.md) 在规范的环境中开源（英文）

作为一家积极拥抱互联网金融的银行，怎能错过开源这条康庄大道？

- [Comcast](https://github.com/todogroup/guides/blob/master/casestudies/comcast.md) 的开源故事（英文）

顾名思义即可。

- [Facebook](https://github.com/todogroup/guides/blob/master/casestudies/facebook.md)（英文）

默认开源的互联网公司，即使出现许可协议风波也无伤大雅。

- [Oath](https://github.com/todogroup/guides/blob/master/casestudies/oath.md) 的开源故事（英文）

Yahoo！的开源故事，谁都知道Hadoop来自哪里。

- [Redhat](https://github.com/todogroup/guides/blob/master/casestudies/redhat.md) 开源及标准团队 - 红帽如何衡量开源成功（英文）

这就是红帽开源文化的“管中窥豹”之举。