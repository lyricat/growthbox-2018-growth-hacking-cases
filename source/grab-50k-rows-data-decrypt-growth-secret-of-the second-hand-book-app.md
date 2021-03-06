---
title: 抓取5万数据，解密“原价收+一点五折卖”的二手书小程序
date: 2018-09-29
---

大家好！这里是 yolo@增长黑盒。最近，为了深度研究增长，我们团队计划采购一大批书来进行学习。但是，这些书大多造价不菲，所以我决定：买二手的！

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A27-1538278204.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")


在各个[二手书](http://growthbox.net/growthhack/tag/%e4%ba%8c%e6%89%8b%e4%b9%a6/ "浏览关于“二手书”的文章") 平台比价的过程中，我无意中发现一个名叫“漫游鲸”的[小程序](http://growthbox.net/growthhack/tag/%e5%b0%8f%e7%a8%8b%e5%ba%8f/ "浏览关于“小程序”的文章") ：不但号称买书只要1.5折，竟然“原价回收”二手书！就在本月，漫游鲸已经获得了千万级融资。

这种“慈善式”的商业模式立刻吸引了我们的兴趣 – 如火如荼的二手书生意，如何在微信生态内找到新玩法？

所以，我们决定对这个产品进行了三个方向的研究：

1. 梳理二手书的商业模式，研究“原价回收”背后的玩法
2. 抓取50000条数据，分析漫游鲸的交易订单，并对比行业头部“多抓鱼”
3. 调查增长策略，分析漫游鲸如何在红海市场实现新用户增长

## 一、商业模式分析：如何做到“原价回收”

首先我们来了解一下移动端的二手书交易市场：

闲鱼和转转是移动端上比较早的二手买卖平台，二手书买卖只是其中一部分。这种撮合用户之间形成交易的模式也称之为C2C，我们暂定它为二手书交易1.0模式。缺点是用户可以随意定价，书的质量不稳定，交易的不确定性很多。

而破局者是多抓鱼，他们运营了一年并在不久前被腾讯注资，其模式可称之为2.0。

多抓鱼只切入了二手书交易，它会统一从用户那收书再卖书，这个模式也被称为C2B2C，对标的是日本的二手书领头羊 Bookoff。

由于是平台方介入，用户买书卖书体验的得到了提升，并做成了标准化的流程。比如扫码自动定价卖书、快递上门取书，同时还背靠微信生态加入了社交元素。

C2B2C 模式基本都是这套收书流程：

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A25-1538278204.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

此外，2.0模式跑通后，大玩家闲鱼和转转也都相继跟进了，新入场的小玩家还有主打“二手+图书社交”有温度的「熊猫格子」、北大创业帮力图打造的“社区书联网”「阅邻」、全民低碳环保阅读首倡者「渔书」等等。但是有温度加公益并不能作为商业模式，差异化和创新才是。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A26-1538278204.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

接下来，我们回归到今天的研究对象：漫游鲸。

它的商业模式跟我们上一篇分析的享物说可以说是异曲同工，比2.0模式的多抓鱼多了虚拟货币“书费”，我们暂定其为3.0模式好了。（注意：3.0模式不一定好于2.0模式，成王还是败寇交给市场定夺）

漫游鲸宣传的卖点是“原价收书，1.5折买书”，从用户角度看，这几乎是一笔无法拒绝的交易，毕竟其他平台上大致是1-3折收书，3-4折买书。

可是，真的有这种好事吗？再仔细阅读一下规则，发现原价收书其实是给到用户等额的“书费”（即虚拟货币），只能在平台内消费其他的二手书，并不能提现。消费二手书的时候，书费可以抵扣原价的85%。如果你没有书费，也可以用人民币按原价4-5折直接买二手书。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A23-1538278205.png "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A20-1538278205.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

从运营角度来说，书费模式对漫游鲸团队来说有三大优势：

1. 首先是书费不能提现，所以平台不用承担收书的资金压力；
2. 统一原价收书，避免了给书定价的环节，毕竟扫码动态定价似乎还是个挺复杂的技术活。
3.  书费还可以作为补贴发给用户，降低了获客成本，并引导用户第一次消费。除了卖书可以换书费，关注公众号、分享小程序邀请好友都可以免费获得书费。毕竟不是真金白银贴出去，所以补贴力度看上去还挺大。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A210-1538278205.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

个人觉得3.0和2.0模式的差别就在于：他们通过建立共识降低了用户的交易摩擦，同时引入不可提现的虚拟货币，极大降低了运营和营销成本，有更多的资源投入到仓储物流环节。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A210-1538278205-1.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

（左：多抓鱼仓库 天津； 右：漫游鲸仓库 成都）

在漫游鲸的价值观里：书不应该被贱卖，而应该被循环起来。于是大家开始玩一个基于出版社定价的以物换物游戏，平台大致上是抽了原价买书费用的15%保证生存。

如果对这些平台体验有疑问的话，可以看“超人评测”：多抓鱼、漫游鲸、转转二手书的详细测评（http://www.sohu.com/a/246709321_114778）

这种玩法说不定还可以举一反三下，例如原价收二手奢侈品可不可以？双倍价格收书行不行？（听上去已经不符合逻辑了。。。）

## 二、平台数据分析：如何估算交易量

那么，号称融资千万的产品究竟运营情况如何？对比2.0模式的先驱“多抓鱼”，漫游鲸的3.0模式又有什么差异化的地方？我们打开了各种抓包和爬虫软件，分别对多抓鱼和漫游鲸进行数据研究。

首先是多抓鱼，上来要夸一下，不愧是做了一年就被腾讯投资的公司。抓取1000条数据之后，我们的IP就被封号了，反爬虫机制相当敏感。更换IP后，我们陆陆续续抓了一万条可见数据。当然，多抓鱼的数据维度并不多，我们大致能够获得购买量、书籍详情等。

再者是漫游鲸，根据API接口分析，他们大概率是使用了第三方电商小程序，数据比较规整，也没有什么反爬机制。连续多天抓取所有可见的二手书信息，顺带连访问数，下单数，实际成交数（除去了退款数）的字段都抓了一下。为了研究字段的含义，我们还买了好几本书来挖掘规律，基本对应上了。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A24-1538278205.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

有必要再提一下，无论是多抓鱼还是漫游鲸都挺注重精益创业 – 低成本验证和不重复发明轮子都是增长黑客在创业初期经常使用的策略。比如多抓鱼一开始是用微信群加Excel来促成交易的，是一个标准的最小化可执行产品（MVP）。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A28-1538278205.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")
（图片来自职人社组织的分享，分享人是多抓鱼的联合创始人）

漫游鲸也是果断使用第三方saas平台来构建小程序，没有自己开发，专心发展业务。因为一个漂亮的小程序不能成为真正的商业壁垒，而背后的供应链和交易体系才是二手书平台的核心。

经过几天努力，我们抓取了多抓鱼9.21日的1W条数据，并跟踪采集了漫游鲸9.19，9.20，9.21，9.27，9.28五个时间点的数据，总计超过4W条。不过，毕竟两家的模式和成熟度有一定差别，我们只能先看看书籍和作者上的一些差异，由此来推断两个平台收书策略和受众群体的差异（由于两个平台的数据是抽样，所以不能反映全平台情况，仅供参考）。

### 1. TOP10 畅销书

从抽样数据中，我们分别找到了两个平台上10本销量最高的书。问了一些书迷朋友，多数人认为多抓鱼的畅销书更为常见，读过的较多；而漫游鲸畅销书的认知度就相对较低了。当然，数据还比较有限，没法横向对比两家，只能看个大概。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A28-1538278205-1.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

### 2. Top10作者

同时，我们也统计了销量最高的作者。这两个表格来看，多抓鱼Top10的作者比较为人所熟知；而漫游鲸Top10作者，基本都是儿童文学作家（杨红樱《淘气包马小跳》）或流行文学。结合漫游鲸的推广渠道（详情见后文），我们推测可能是冷启动时圈了某类特定群体，如宝妈、大学生等，所以这类用户在喜好上会有明显的偏向。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A28-1538278205-2.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

### 3. 豆瓣评分

从豆瓣书评平均分来看，多抓鱼8分，漫游鲸7.17分。有书迷朋友说，豆瓣7分是一本书值不值得看的一个标准，这么看的话，漫游鲸鱼刚好及格，多抓鱼还比较安全。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A23-1538278206.png "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A25-1538278206.png "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

前文提到，我们利用API接口挖掘出了商品浏览次数、加购物车、付款、退款等等数据。当然这个结果不一定准确，只能大概推测一下转化率和平台的体量。

漫游鲸的销量、库存和用户活跃度究竟如何呢？

我们分析了采集到的所有漫游鲸数据，得到如下结果：

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A22-1538278206.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

从9.19-9.21这三天的趋势来看，总销售、总库存和总量都是稳步增长的，但是为什么从9.27起出现了负增长？

问了弄清楚这个问题，我们首先确定一点：如果书卖光了，就会下架。那么，下架书的相关信息就抓取不到。这意味着，如果某本书在19号抓取到的历史销量是100本，若它在20号下架，那么它的历史销量就无法统计到20号的总销量中 – 即销量减少100本。

我们第一个推测是：因为图书上架需要人工处理，如果销售火爆，又逢节假日，库存清理上架就会跟不上。所以API接口显示的数据就无法及时更新。也就是说，这些书“只出不进”，公司的员工们来不及把新书上架，原来的书已经都卖光了。

不过，再仔细思考一下，我们的统计口径可能有点问题。

二手书交易是双边市场，可以类比成“蓄水池”模型，有进有出的状态就意味着“流动性”，也就是每天有新书上架和旧书下架（ps：这里要注意，下架是指数据库里“Total”清零，但清零并不意味着卖出去了），如下图：

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A29-1538278206.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

通过该图可以看出，书的种类都稳定在7000-8000之间，有4500种左右的书与前一天保持一致，新上架书的种类和下架种类也相对稳定。而这个总量模型才是考虑到流动性的、较为准确的模型。

所以，我们调研了四个时间点都在“在架上”的书，一共1406种。拿这些“稳定”产品的历史销量作为样本，再预估平台整体的销量情况。

这1406种的库存记录是5330本，平台声称自己有10万本书。再看这稳定的1400种书销售额的变化，统计出来每天平均销售30本。如果说1400种是具有代表性的随机抽样，那么粗略估计每天可以卖出约562本左右（30/5330*100000=562本，这也只是我们的估算，准确数据还是看官方）。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A21-1538278206.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

同样是这批稳定的1400种书，我们还分析了一下漫游鲸购书的转化数据。这次为了确保统计口径一致，我们抽取了截至9.19当天的历史数据画了个转化漏斗，来看看漫游鲸的购买路径。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A25-1538278206.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

最终转化率为3.33%，根据一份2015年中国电子商务研究中心的报告“多数电商的转化率只有0.5%左右”。虽然数据是老了点，但可以看出漫游鲸的最终转化率要远高于行业平均转化，漏斗的每个步骤还是比较完善。

我们认为，二手市场的盈利模式大致可以表达为如下的公式：

```
收入=流转频次x差价=流转频次x（售价-回收价）
```

基于这个假设，流转频次和差价越大越好。漫游鲸成本0元，售卖为书原价的15%，只要书能卖出去，平台即可获利，所以保持高流转率是平台盈利的关键。

据统计，平台书原价的平均价格是31，那么大致可以推算一下每天卖书的收入

> 按书费抵扣：560\*31\*15%=2604
> 按直接买：560\*31\*50%=8680

所以平台每天的收入应该在2604-8680元之间。

当然，这只是我们粗略的估算，具体数据是多少还是要听漫游鲸自己怎么说。

## 三、增长策略分析：如何获取新用户

根据我们观察，漫游鲸从未进行任何大规模的营销活动，仅仅在媒体上取得了一些融资曝光。另外，漫游鲸的创始人也不是“网红”或者“大V”，仅仅在之前做过一个图书交换的微信群，自带流量非常有限。

另一方面，根据新榜平台的数据，成立仅4个月的漫游鲸，公众号粉丝量竟然能达到70多万 – 发表的文章还不足10条，而文章单篇阅读量已经从几千涨到了5万以上。当然，这些流量的快速增长完全能够转化到业务上，前面的数据已经可以证实。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A20-1538278207.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

但是，我们调查了常见的获客渠道，如：知乎、百度贴吧、微博等等，却发现漫游鲸在这些渠道的表现非常冷清。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A210-1538278207.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

大家都看的出来，二手书市场的竞争已经相当激烈了。一个既没有怎么投放广告，也没有大佬站台的小程序，在几个月的时间内就能做到这个规模，突破二手书交易2.0模式。

那么，漫游鲸究竟是靠什么方式来带动新用户增长的？交易量持续增长，又是依靠什么策略呢？

考虑到漫游鲸的产品是小程序，那么它一定很依赖微信生态内的用户获取。按照这个逻辑，我首先想到的是常见的公众号软文推广。

首先，我们在搜狗微信搜索中查询“漫游鲸”这个关键字，果然找到了若干篇软文。随后，我们将软文的标题再次进行搜索，终于发现了其中的奥秘：

原来，漫游鲸从5月份开始，就通过软文的形式在众多公众号进行投放。最近拿到千万融资的时候，更是加大了推广力度。粗略统计，漫游鲸投放的范围有上百个不同的公众号，软文形式也有5种以上，循环投放。转化的方式也非常简单：文末放置二维码，扫描后直接关注漫游鲸服务号，引流涨粉。

另一种形式则是常见的“荐号”，一篇文章推荐多个公众号，漫游鲸服务号二维码放在第一个，扫码即可关注公众号，大概率是以CPA或CPC方式进行结算。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A28-1538278207.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

再仔细观察一下投放渠道，其中不乏“白熊事务所”、“淘高考”、“中学生语文作文”、“熊叔英语”、“读者”这类的号，基本上可以分为：求职、学生和读书三类，推送到需要读书的学生党和自我驱动力强的长期阅读者手中，这让他们获得了大量精准的用户。

不过，漫游鲸上为何有这么多童书，我们还没完全弄清楚 – 或许是职场类的公众号有大量年轻妈妈在关注。

除此之外，漫游鲸还找了一些精准的KOL合作推送。在8月30日就和旅游博主“大西洋鳗鱼”做了场送书活动，送了一波号称是“旅游圣经”的孤独星球纸质书，由漫游鲸提供的。大西洋鳗鱼的粉丝大多来自知乎和微信公众号，是一群受教育程度较高的用户 。这篇文章阅读接近2万，粉丝互动积极，留言显示大家通过这次活动对“漫游鲸”平台认知度高。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A24-1538278207.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

从某个BD资源网站上，我们也可以看到漫游鲸正在长期寻找流量主合作，并表示“每天都会投放”。由此可以看出，漫游鲸很可能也在微信群等渠道进行了投放，获得了部分增量 – 这也是小程序常见的起量方式。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A21-1538278207.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

但是在大家的印象中，这种策略似乎非常烧钱。漫游鲸到底付出了多少营销成本呢？

想要弄清楚这个问题，我们必须知道漫游鲸投放一篇软文的价格是多少。碰巧的是，我的一位朋友正好在9月接到了漫游鲸的合作，发布了它们的软文 – 一口价，差不多是0.6元一个阅读，不考虑转化效果，大概是以CPM定价的。

总体来看，漫游鲸投放的公众号阅读量普遍在3000以内，一篇文章价格不到2000元。上百个号一起投，外加阅读量上万的KOL，花费恐怕要在十几万以上 – 不过相对于千万融资额，这点营销费用也不过分。相比于投放一个价值几十万的大号头条，漫游鲸选择大规模投放性价比较高的小号矩阵，精准地触达“求职者”、“学生”这一群体，且能够保证多轮滚动投放，在项目刚起步的时，这种“精益投放”的效果看起来更加明显。

下面问题就来了：只获取新用户不是真正的增长，还需要在后续环节中激活用户并产生留存，最终完成商业变现。漫游鲸公众号粉丝再多，不能转化到业务也没用。那它究竟是如何引导公众号新粉丝开始使用自己的小程序产品？

我们观察发现，不同公众号发布的软文，文末的漫游鲸二维码竟然不一样！这便是微信服务号的特殊能力 – 「带参数的二维码」 ：关注服务号可以触发不同的回复，并且可以追踪每个渠道进来的粉丝数量，既可以根据渠道差异推送不同的营销活动，又可以持续追踪和优化渠道投放效果。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A23-1538278207.jpeg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

这样看来，扫码关注后回复的消息，便是漫游鲸激活并转化用户的关键手段，也是增长黑客常常提到的新用户引导（onboarding）流程。根据多次测试，发现其回复的内容主要有三种：

### 1.关注即送30元书费（现在调整成20了）

通过数据分析我们发现，漫游鲸上原价书的平均价格是31元，这恰好和赠送的书费相近；想把这30元书费都用掉，那么购买的书的定价应该在35元以下（35=30÷85%）；从统计结果看，35元及其以下的书占了全部书籍的71.8%。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A25-1538278207.jpeg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

这意味着，只要你关注服务号，就能1.5折买到平台上大部分的书，用户被赋能，积分在平台内不换成书就成了沉默成本，不如赶紧换成知识；而对于漫游鲸来说，收书0成本，卖出最少可赚原价的15%，所以只要书流转起来就有得赚，所以当然要送书。

### 2.以送会员的名义引导加客服号

这条链接模拟微信推送告知用户“漫游鲸会员”的福利，如送100元书费、买书折上折等，最后把用户引导到加客服号小水母。虽然现在会员福利领取已经结束，不清楚加客服号的下一步操作是什么，但是一般社群运营流程都是加客服、送会员、拉群运营。

观察发现，已经有超过13000人访问这个页面 – 形成数千人的社群完全没有问题。微信群、个人号的触达效率自然要比服务号高。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A22-1538278207.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

### 3.新手指南漫画

这篇新手指南推送是最近才推出的，简单的Onboarding，漫画形式简单有趣，用户体验非常不错。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A20-1538278207-1.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

最近，临近十月一长假，漫游鲸也搞了新一轮营销活动：书费可以直接购书，而无需支付15%的人民币费用，可谓是完全免费拿书了。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A29-1538278207.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

## 四、总结：小程序和微信生态

### 1. 专注拉新的小程序

最后我们稍微总结并发散一下：

按照我们的推算，漫游鲸大概每天能出售500本书；根据另一篇多抓鱼的采访来看，他们可以每天卖2000本。

但不要忘记还有大量的仓储物流费用，二手书肯定不会是个挣钱的生意。即便如此，他们仍然受到了资本的热捧，可能因为亚马逊等电商都是靠卖书起家的吧，让人产生了一定的幻想。

纵观小程序的数据，不难看出目前小程序留存困难，盈利能力有限。但是毫无疑问，因为背靠微信熟人网络，所以拉新比APP要容易很多。同时，随着移动互联网设备在三、四线甚至更下沉的地方普及，APP用户教育成本高，而“简单易学、即插即用”的小程序，恰好满足了他们的需求。

所以小程序毫无疑问是拉新优先的，留存和盈利只能顺其自然了。反正小程序肯定会进一步放开限制， 等到用户习惯形成、入口和唤醒进一步开放，提升留存和盈利将不是问题。

现在就是比拼卡位加上积累数据，同时快速的用户增长以及DAU也是资本最关心的一些数据，VC就算看不明白未来的前景，也会考虑先布局起来。

回归小程序本身，既然要靠熟人网络拉新那么分销、拼团、砍价、诱导分享、利益诱惑之类的手段自然是不可或缺的。

虽然做产品没有必火的公式，但最近我们看到持续增量比较快的产品，似乎都有一些共性：免费送物，积分换购，甚至金钱补贴。例如“享物说”用小红花交换闲置物品、“步步换”用步数兑换礼品、“漫游鲸”用书费买书，派派等小程序直接送钱。

其中不少都涉及到了积分或者虚拟货币，这样的好处在于：

* 用积分替代金钱作为交易媒介，减少交易摩擦。
* 由于积分只能作用在对应的平台上，增加了用户迁移成本，自然能把用户留存在平台上。
  

同时积分又天然是低成本裂变拉新的诱饵，可以让用户快速感受到平台的价值。

### 2. 微信生态

再聊聊微信生态，在这里我们可以描述一下微信生态里的其他角色。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A21-1538278208.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

全部都用上才能发挥小程序最大的威力，你在快速增长又带社区属性的小程序上基本都可以发现这些元素。

综合来看，积分、小程序、微信生态这三件法宝在AARRR增长模型中，给产品带来了很多增长的可能性。

![抓取5W数据，解密「原价收+1.5折卖」的二手书小程序-增长黑盒 - 增长黑客专用工具箱 - 增长黑客社区](http://growthbox.net/wp-content/uploads/2018/09/%E5%A2%9E%E9%95%BF%E9%BB%91%E5%AE%A22-1538278208.jpg "抓取5W数据，解密「原价收+1.5折卖」的二手书小程序")

Acquisition获客：

小程序有多个传播渠道和入口，目前已知的小程序入口就有微信直接搜索，附近的小程序，小程序分享，小程序服务消息，QQ浏览器搜索，小程序固定桌面，公众号广告。据说可以统计出8大类，60多项，在这里就不详细展开了。

Activation激活：

小程序“即插即用”，上手不困难、不需要学习成本，能让用户快速地体验产品，感受产品带来的aha moment；当然，在基于微信生态的前提下，把小程序推荐给你的朋友也在把产品介绍给你的时候，承担了一些onboarding的工作，让体验更加顺畅。

Retention留存：

积分或者经济系统，乃至游戏化的形式都将会承担起了小程序留存的工作，同时打通上方的微信生态也是留存的关键。你必须要让用户在多个地方看见你，抢占他的注意力。

Revenue变现：

微信生态好处就在于支付方便，极大地提升了临门一脚的转化率。同时给与用户补贴的时候，用户也快速提现，感受到金钱刺激。

Referral推荐：

[积分制度](http://growthbox.net/growthhack/tag/%e7%a7%af%e5%88%86%e5%88%b6%e5%ba%a6/ "浏览关于“积分制度”的文章")、小程序和微信生态相互配合，共同作用于推荐的环节。积分是分享天然的诱饵，比转发领奖品这样繁复的步骤更加直接；小程序承担起让分享更简洁的作用，用户可以从小程序直接进入到商品页面或游戏页；微信生态里好友多，信任感强，可以大大增加推荐的成功率。

尽管如此，在微信小程序生态里，一切都得摸着石头过河，甚至连支付宝和百度都在大力推广自家的小程序。

而作为创业者，唯一能做的就是有价值的增长，剩下的一切都会水到渠成。

![](assets/2019-03-04-20-52-05.jpg)

## 参考资料：

https://mp.weixin.qq.com/s/omPx8na_3-ISHEdW5lwoeA
https://www.zhihu.com/question/283685278
http://news.sina.com.cn/o/2018-01-26/doc-ifyqyqni3206272.shtml
https://www.jianshu.com/p/86c21c79d1aa
https://zhuanlan.zhihu.com/p/42825982