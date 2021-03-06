---
title: TokenLife 周报 2W | 基本面正在悄然变化
date: 2018-11-04
category: tokenLife
---

TokenLife 每周分享，记录过去一周，我看到的值得分享的数字货币市场所见所得，每周日发布。

上周 BTC 行情一直维持着 200 美金的震荡幅度，并没有很大的波动出现。 ETH 同样在 200 美金横向缩量盘整。这种价格会给我们供求极度平衡的错觉，但往往这种形态持续的时间越长，就越会消磨掉人们的意志，而且变盘也就会越激烈。

经过 10 月 11 号与 10 月 15 号的多空双杀，双方都不太想冒然发起进攻，市场需要等待一个

契机才会选择方向。

10/26~11/04 本周韩国与香港都放松了对数字货币的政策，虽然未看到短期价格的影响，但长远来看这些都将会推动数字货币投资的普及。

## 见闻

### 过去一年时间数字货币与传统市场相关性

![相关性](https://trello-attachments.s3.amazonaws.com/5aceaf1164c86a15f5956cda/5bd47bc286e02c59ef0f5c42/3affac27e17594885168064bec89c17f/image.png) 

右边倒数四列从左到右依次是：

*   SPX 标普 500 指数
*   VIX 芝加哥期权交易所市场波动率指数
*   GLD 黄金 ETF 指数
*   TNX 十年债券指数

评判标准

*   0.5 to 1: 强正相关
*   0.3 to 0.5: 中等正相关
*   0.1 to 0.3: 弱正相关
*   -0.1 to 0.1: 没有线性关系
*   -0.1 to -0.3: 弱负相关
*   -0.3 to -0.5: 中等负相关
*   -0.5 to -1.0: 强负相关

### 比特币白皮书发布十周年

[李笑来翻译版本](https://github.com/xiaolai/bitcoin-whitepaper-chinese-translation)
[原版](https://bitcoin.org/bitcoin.pdf)
一起重温比特币的白皮书。

### ETH 代币转换为 EOS 网络代币方案

基于 off-chain 代码实现的轻量级 ETH -> EOS 跨链方案**eos21**
[sheos-org/eos21: Teleport your ERC20 tokens to EOS](https://github.com/sheos-org/eos21).

该项目提供了一套方案，能够把 ETH 上的 ERC20 代币转到 EOS 网络上，实现思路很巧妙，很简单的跨链思路，实现步骤为：

*   ERC20 token 转移到黑洞地址，并附上所有者的 EOS 公钥和特殊标志。
*   使用链下代码监听黑洞地址的特殊标志交易，确权交易。
*   并在 EOS 网络上发送同等数量的代币给声明的 EOS 账户。

这样 EOS 社区通过代币转移方案来吸引更多的老项目从 ETH 切换到 EOS 开发，这显然对 EOS 更加有利。 不过这个方案有一个问题，代币的销毁是完全不可逆的，而且如果项目方的社区不买账，则会面临着共识分裂的风险。

另外，这个项目的发方是一个名为 shEOS 的组织，完全由女性成员主导，值得关注。

### 稳定币的战争才刚刚开始

 ![市值对比](http://upload-images.jianshu.io/upload_images/56077-8f7bab9ce0869409.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240) 

从上图看到，自 10 月 14 日的恐慌以来， USDT 的市值占比在逐渐减少，其他稳定币占比开始增加。 造成这种趋势的主要原因是加密货币交易所 Bitfinex 流出了大约 7.8 亿 USDT 到 Tether Treasury 的商业钱包，而 Bitfinex 与 Tether 都受相同的 CEO 和所有者控制。 USDT 从九月的 28 亿供给回落至现在的 19 亿，Tehter 难道不知道这是在给竞争对手提供机会吗，他这么做的原因只有一个 —— 遇到大额赎回。

 ![交易所交易量](http://upload-images.jianshu.io/upload_images/56077-7091f41841d52b97.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240) 

很多投资者还不太习惯使用除 USDT 之外的稳定币，这种路径依赖也成为了目前 USDT 的竞争壁垒。 同时我们看链上交易的数据也能发现，USDT 依然是最强王者，但情况已经开始慢慢发生变化。

 ![链上转账数量](http://upload-images.jianshu.io/upload_images/56077-08f752f6561e5165.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240) 

 ![收快递一般的签名](http://upload-images.jianshu.io/upload_images/56077-5eb7c0836c284384.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240) 

Tether 终于公布了银行的细节信息，看起来是有人收到了一份不需要确认收货人的快递，从文件细节中能发现， Tether 能够将 USDT 保持在锚定美元的状态，只不过这次信息披露是为了维护Tether 的「锚定」而出现，如果没有发生 10 月 14 日的狙击，Tether 似乎也没有公布信息的动力，而现在更多的稳定币团队加入了竞争，惊动了这条「鲶鱼」，数字货币的世界里，终于上演了「良币驱逐劣币」的一幕，这让笔者相信，这个熊市里或许会发生更多比「创始人声讨狗庄割韭菜，解锁大量代币砸盘」还要有意思的事情。

最近也看到一些消息，南非国家使用数字货币作为电子支付手段，他们大多数人没有银行账户，更愿意使用移动电子支付，这些使用习惯有助于数字货币或区块链技术在这些国家落地，而稳定币也将是最大的受益者。

### 韩国市场交易量逐渐增加

韩国市场似乎在 2017 年的牛市之后极少受到国内媒体的关注，但是韩国朋友仍然没能放弃数字货币的投资，交易量已经慢慢起了变化。

![数字货币交易量](https://trello-attachments.s3.amazonaws.com/5aceaf1164c86a15f5956cda/5bd47bc286e02c59ef0f5c42/145afd23c4feeb473ab373ec1ae90fda/image.png) 

数字货币在韩国市场交易量从 18年 10 月初逐渐增加。

[Cryptocurrency Trading Volume in South Korea Soars - Bitcoinist.com](https://bitcoinist.com/cryptocurrency-trading-volume-in-south-korea-soars/)

韩国财政服务委员会声明，不会限制银行为本地数字货币交易所提供金融服务。韩国的数字货币交易所可以为投资者的数字资产购买保险，Bithumb, Upbit, Gopax, Korbit, Coinone 和其他的交易所将会受益。这也解释了为什么上图中韩国数字货币交易量逐渐放大的趋势。

[Korea’s Finance Minister Approves Banks Working With Crypto Exchanges](https://www.ccn.com/koreas-finance-minister-approves-banks-working-with-crypto-exchanges/)

## 工具

### coinlib 每日图表

 ![token & crypto flow](http://upload-images.jianshu.io/upload_images/56077-79d0a1dd1bff966b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240) 

来自 coinlib 的统计图表，清晰地看到法币与数字货币的流向，这里我们可以清楚的看到过去的 24 小时法币和数字货币的流向，也能知道目前资金青睐的币种是哪些。

韩国朋友更喜欢 EOS 和 BCH 还有 ZCash

另外 coinlib 提供了一些实用工具

 ![流动性统计](http://upload-images.jianshu.io/upload_images/56077-88aa3314a98403e3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240) 

coinlib 通过公式对数字货币流动性进行了评级分类：

> Assessing a coin's liquidity
*   Good: coins with high volume, traded in many exchanges [119 coins]
*   Moderate: coins with moderate volume traded in not that many exchanges [419 coins]
*   Low: coins with low volume traded in few exchanges [481 coins]
*   Very Low: coins with very low volume traded in very few exchanges [4240 coins]

*   好（绿）：高成交量，可以在多个交易所交易 （119-2.3%）
*   一般（灰）：成交量一般，并不是在很多交易所交易 （419~8%）
*   低（黄）：成交量低，只在几个交易所交易 （481-9.1%）
*   差（橘）：成交量低，在很少几个交易所交易 （4240-80.6%）

### 神秘的卧龙先生

在海外币圈有一位活跃的中国数字货币玩家[Wolong (@GameOfDeception) | Twitter](https://twitter.com/GameOfDeception)，它曾发表过一篇关于「Whale watching」策略的文章，阐述自己如何识别出 smart money 并一步步成为 smart money 操纵狗狗币市场的。

他总结出了主力操纵市场的手段，分别为

*   建立位置
*   打压价格
*   测试拉升
*   拉升出货
*   低位震荡
*   重新分发
*   砸盘退出

各个阶段的手法和目的感兴趣的可以去看 steemit 上的原文 [Wolong: The Game of Deception (unedited version) — Steemit](https://steemit.com/bitcoin/@joseph/wolong-the-game-of-deception-unedited-version)

文章结尾阐述了他操作狗狗币时候的策略和思路，当然这些内容未经考证，仅供我们学习参考。

### 实时更新的仓位统计表

 ![position sheet](http://upload-images.jianshu.io/upload_images/56077-e8e640b97f5de28d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240) 

[position sheet](https://docs.google.com/spreadsheets/d/1ah7s47VOuIIng6fUYqRkclmVTiy33GYMahWXQq84teQ/edit#gid=519058888)

来自一位 twitter 网友开发的数字货币交易统计工具，可以通过 google 插件获取 coinmarketcap 中的实时数据，计算得出当前持仓的数字货币价格。 供各位参考，熟悉 EXCEL 的朋友也可以在这个基础上继续改善。

## 摘录

> "Whale watching" is a trading strategy of monitoring the trades of the most influential or wealthy investors, known as "whales". "Whales" refers to traders with significant bankrolls that their actions impact heavily on the markets. The purpose of this book is to trade in the shadow of the smart money, understanding how market manipulation works, and become profitable by understanding.
> 
> 「观鲸」策略是监控具有大体量资金的投资者，往往他们具有影响市场的能力，这本书的目的就是在主力资金的影子下交易，领悟他们是如何操作市场，并从这些领悟中赚钱。—— 卧龙

---

> "If you know your enemies and know yourself, you will not be imperiled in a hundred battles" - Sun Tzu 知己知彼百战不殆 —— 孙子

--- 

> Common mistakes traders make
> 
> *   trade every day, every hour, every candle, every move
> *   they don’t develop a trading plan
> *   their entry & exit is random
> *   they become slaves of the markets
> *   they don’t sleep good
> *   they have no “patience”
> Successful traders do the opposite
> 
> 交易者通常犯下的错误：
> 
> *   无时无刻不在交易
> *   他们不开发自己的交易计划
> *   随机入市出市
> *   成为市场的奴隶
> *   不好好休息
> *   没有耐心
> 
> 成功的投资者相反


加入免费知识星球获取更加实时的推送，包括不限于，市场观察，技术分析，数据解读，优质文章推介等等。

 ![知识星球](http://upload-images.jianshu.io/upload_images/56077-b0fa40a32bb3e659?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)








