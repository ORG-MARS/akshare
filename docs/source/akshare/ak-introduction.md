# [AkShare](https://github.com/jindaxiang/akshare) 概览
(本文档更新于 **2019-11-18**; 如发现库和文档相关问题, 请联系 [AkShare](https://github.com/jindaxiang/akshare) 的作者 **Albert King**: jindaxiang@163.com)

您也可以加入QQ群答疑解难: 326900231

<a target="_blank" href="https://shang.qq.com/wpa/qunwpa?idkey=aacb87089dd5ecb8c6620ce391de15b92310cfb65e3b37f37eb465769e3fc1a3"><img border="0" src="https://jfds-1252952517.cos.ap-chengdu.myqcloud.com/akshare/qq/akshare_md_fold_1569925684166.png" alt="AkShare官方" title="AkShare官方"></a>

## [AkShare](https://github.com/jindaxiang/akshare) 的介绍

首先要特别感谢 [FuShare](https://github.com/jindaxiang/fushare), [TuShare](https://github.com/waditu/tushare) 在代码和项目开发上对本项目提供的借鉴和学习的机会!

[AkShare](https://github.com/jindaxiang/akshare) 于 **2019-10-08** 正式发布, 请访问 [AkShare文档](https://akshare.readthedocs.io) 了解和查询数据接口！

[AkShare](https://github.com/jindaxiang/akshare) 是基于 Python 的开源金融数据接口库, 目的是实现对股票, 期货, 期权, 基金, 外汇, 债券, 指数, 数字货币等金融产品的基本面数据、实时和历史行情数据、衍生数据从数据采集, 数据清洗, 到数据落地的一套开源工具, 满足金融数据科学家, 数据科学爱好者在金融数据获取方面的需求. 

[AkShare](https://github.com/jindaxiang/akshare) 的特点是获取的是相对权威的金融数据网站公布的原始数据, 广大数据科学家可以利用原始数据进行各数据源之间的交叉验证, 进而再加工, 从而得出科学的结论.

**[AkShare](https://github.com/jindaxiang/akshare) 后续会基于学术论文和金融工程研究报告来添加更多指标, 提供相应的计算方法, 敬请关注.**

## [AkShare](https://github.com/jindaxiang/akshare) 的作者

**[Albert King](https://www.jfds.xyz/)** 致力于金融衍生品定价和价格预测、机器学习在金融领域的应用等研究.

<img src="https://jfds-1252952517.cos.ap-chengdu.myqcloud.com/akshare/icon/images.jpg" width = 20% height = 10% align = center/>

## [AkShare](https://github.com/jindaxiang/akshare) 的特色

[AkShare](https://github.com/jindaxiang/akshare) 主要改进如下:

1. Python 语法符合 [PEP8](https://www.python.org/dev/peps/pep-0008/) 规范, 统一接口函数的命名;
2. 支持 Python 3.7.3 及其以上版本;
3. 后续加入 [asyncio](https://www.python.org/dev/peps/pep-3156/) 和 [aiohttp](https://aiohttp.readthedocs.io/en/stable/) 做异步加速;
4. 持续维护由于目标网页变化而导致的部分函数运行异常问题;
5. 后续更新会主要集中在提供更多金融数据接口, 同时优化源代码;
6. 增加更多的网络数据采集接口:

    6.1 增加[奇货可查网站](https://qhkch.com/)数据接口, 提供奇货可查指数数据(开发完成);
    
    6.2 增加[智道智科网站](https://www.ziasset.com/)数据接口, 提供私募指数数据(开发完成);
    
    6.3 增加[99期货网](http://www.99qh.com/)数据接口, 提供大宗商品库存数据(开发完成);
    
    6.4 增加[商品期权](https://github.com/jindaxiang/akshare)数据接口, 提供商品期货数据(开发完成);
    
    6.5 增加[英为财情网站-全球指数](https://github.com/jindaxiang/akshare)数据接口, 提供全球股指与期货指数数据(开发完成);
    
    6.6 增加[英为财情网站-全球债券](https://github.com/jindaxiang/akshare)数据接口, 提供全球政府债券行情与收益率数据(开发完成);
    
    6.7 增加[中国外汇交易中心暨全国银行间同业拆借中心网站](http://www.chinamoney.com.cn/chinese/)数据接口, 提供中国银行间债券行情和外汇数据(开发完成);

    6.8 增加[英为财情网站-商品](https://cn.investing.com/commodities/)数据接口, 提供全球商品历史数据(开发完成);
    
    6.9 增加[金十数据网站](https://www.jin10.com/)数据接口, 提供全球宏观经济数据接口-中国宏观(开发完成);
    
    6.10 增加[金十数据网站](https://www.jin10.com/)数据接口, 提供全球宏观经济数据接口-美国宏观(开发完成);
    
    6.11 增加[金十数据网站](https://www.jin10.com/)数据接口, 提供全球宏观经济数据接口-欧洲、机构宏观(开发完成);

    6.12 增加[交易法门网站](https://www.jiaoyifamen.com/)数据接口, 提供交易法门-仓单有效期数据(开发完成);

    6.13 增加[和讯网网站](http://www.hexun.com/)数据接口, 提供股票-企业社会责任数据(开发完成);
    
    6.14 增加[和讯网](http://www.hexun.com/)数据接口, 提供美国-中概股行情及历史数据(开发完成);
    
    6.15 增加[交易法门网站](https://www.jiaoyifamen.com/)数据接口, 提供套利工具-跨期价差(自由价差)数据(开发完成);
    
    6.16 增加[新浪财经-期货](https://finance.sina.com.cn/futuremarket/)数据接口, 提供实时行情数据(开发完成);

    6.17 增加[新浪财经-港股](http://finance.sina.com.cn/stock/hkstock/)数据接口, 提供实时行情数据和历史行情数据(包括前复权和后复权因子);

    6.18 增加[新浪财经-美股](http://finance.sina.com.cn/stock/usstock/sector.shtml)数据接口, 提供实时行情数据和历史行情数据(包括前复权因子);

    6.19 增加[上海证券交易所-期权](http://www.sse.com.cn/assortment/options/price/)数据接口, 提供当日期权行情数据;
    
    6.20 增加[金十数据网站](http://www.sse.com.cn/assortment/options/price/)数据接口, 提供数字货币行情数据;

    6.21 增加[腾讯财经网站](http://stockapp.finance.qq.com/mstats/#mod=list&id=hk_ah&module=HK&type=AH)数据接口, 提供A+H股数据;

    6.22 增加[新浪财经-A股](http://vip.stock.finance.sina.com.cn/mkt/#hs_a)数据接口, 提供A股数据;

    6.23 增加[新浪财经-科创板](http://vip.stock.finance.sina.com.cn/mkt/#cyb)数据接口, 提供科创板数据;

    6.24 增加[银保监分局本级行政处罚](http://www.cbirc.gov.cn/cn/list/9103/910305/ybjfjcf/1.html)数据接口, 提供银保监分局本级行政处罚;

    6.25 增加[Realized Library](https://realized.oxford-man.ox.ac.uk/)数据接口, Oxford-Man Institute of Quantitative Finance; https://dachxiu.chicagobooth.edu/

    6.26 增加[FF Factors](http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html)数据接口, 提供多因子模型数据

    6.27 增加[腾讯财经](http://stockapp.finance.qq.com/mstats/#mod=list&id=ssa&module=SS&type=ranka)数据接口, 提供历史分笔行情数据(近2年)
    
    6.28 增加[金十数据](https://datacenter.jin10.com/market)监控数据接口, 提供基于 Websocket 的数据接口(基础版本);
7. 提供完善的接口文档, 提高 [AkShare](https://github.com/jindaxiang/akshare) 的易用性;
8. 希望您能参与 [AkShare GitHub](https://github.com/jindaxiang/akshare) 的维护与管理.

![](https://jfds-1252952517.cos.ap-chengdu.myqcloud.com/akshare/readme/mindmap/AkShare.png)

## [AkShare](https://github.com/jindaxiang/akshare) 的初衷

[AkShare](https://github.com/jindaxiang/akshare) 希望能为各位同仁提供一个多源金融数据的接口, 助力个人投资者、机构投资者、各大研究机构方便的搜集和整理关于金融产品, 金融衍生品等相关的数据. 

![](https://jfds-1252952517.cos.ap-chengdu.myqcloud.com/akshare/readme/index/stock_futures_index.png)

上图是利用 [AkShare](https://github.com/jindaxiang/akshare) 的 **get_zdzk_fund_index** 接口获取的[智道智科](https://www.ziasset.com/company/)发布的股票策略指数和管理期货策略指数.
可以看出股票策略的波动性大于管理期货策略, 而且从 2015 年至今, 管理期货策略能获得较稳定的收益.

传统的 CTA 策略以趋势为主, 但是自从 2017 年以来, 无论是长线还是短线的趋势策略都受制于商品波动率的降低, 面临了多多少少的回撤, 
同时市场也逐渐趋于机构化理性化, 因此在传统 CTA 策略的基础上加入基本面的因素显得迫在眉睫. 近几年各券商的研报陆续提出了许多依赖于趋势行情以外的有效信号, 它们的表现都与趋势策略有着很低的甚至负的相关性, 这样通过多种不同类型的信号对冲得到的策略, 就有机会在市场上取得非常棒的夏普率和稳定的收益. 

**上图调用 [AkShare](https://github.com/jindaxiang/akshare) 进行绘制的代码如下**

```python
import akshare as ak
import matplotlib.pyplot as plt

plt.rcParams['font.sans-serif'] = 'SimHei'
plt.rcParams['axes.unicode_minus'] = False

stock_df = ak.zdzk_fund_index(30, plot=False)  # 股票策略数据
futures_df = ak.zdzk_fund_index(32, plot=False)  # 管理期货策略数据

fig = plt.figure(111, figsize=(20, 10), dpi=300)
adjust_stock_df = stock_df["20150102":] / stock_df["20150102"] * 1000
adjust_stock_df.plot(linewidth=4)
adjust_futures_df = futures_df["20150102":] / futures_df["20150102"] * 1000
adjust_futures_df.plot(linewidth=4)
plt.title("智道智科股票策略和管理期货策略指数")
plt.legend()
plt.show()
```