<p align="center">
  <a href="https://matrixdata.io">
    <img src="https://matrixdata.io/assets/images/p_nav_logo.svg" alt="MatrixData logo" width=150 height=150>
  </a>

  <h3 align="center">MatrixData</h3>
</p>

## 官网地址

`https://matrixdata.io`

### 简介
<p>
Matrix Data由中国顶级量化IT团队开发打造, 向所有加密货币的量化投资者提供加密货币行情及区块数据服务. 我们已于2018年7月27日上线第一版, 首期提供各交易所实时行情与历史数据的免费调用服务.  作为深耕于区块链高频数据和长期历史数据的IT团队, 我们打造的Matrix Data平台每日数据增量约50G. 通过对数据的采集、比对、清洗、加工和存储, 我们致力于为用户提供高质量、低延迟、最全面的区块链数据服务,能满足不同用户在量化投资或应用开发过程中丰富多样的数据需求, 让投资者专注策略模型和交易, 让开发者专注应用研发. 
  </p>
<p>
数据种类：实时行情数据（盘口、逐笔、报价、K线）; 历史行情数据（盘口、逐笔、K线）; 加密货币指数（BB Index）; 公有链数据, 加密货币基本信息; 区块链资讯等, 详见API列表
  </p>
  <p>
数据输出方式：API接口;CSV格式下载
 </p>

```
MatrixData/
└── API/
    ├── 加密货币行情数据
    │   ├── K线数据
    │   ├── 实时盘口数据 
    │   ├── 实时Tick数据  
    │   ├── 交易平台交易对信息 
    │   ├── 逐笔数据
    │   └── 币种行情
    |
    ├── 加密货币行情数据
    │   ├── BBIndex全部指数数据
    │   ├── BBIndex指数成分数据
    │   ├── BBIndex指数基本信息数据 
    │   ├── BBIndex指数近期走势数据
    │   ├── BBIndex指数实时报价
    │   └── BBIndex指数历史K线数据
    |
    ├── 基本信息数据
    │   ├── 币种信息
    │   └── 交易平台信息
    |
    └── 公有链数据
        └── 公有链Account地址交易记录数据
```

### 版本更新

### V1.6.0
##### 更新日期: 2018.09.06
##### 更新内容:
新增：
ZB.COM, CoinbasePro, Lbank三家交易所ticker数据;
CoinbasePro, DigiFinex , BCEX三家交易平台交易对信息数据;
币种信息接口新增币种介绍内容;
数据规范页新增K线数据开始时间说明;
新增OKEx现货逐笔数据. 

### V1.5.0
##### 更新日期: 2018.08.31
##### 更新内容:
新增：
币种信息——新增1971个币种的基本信息;
交易平台信息——新增平台现有交易所的基本信息;
新增Token刷新方式;
主站首页加入了用户使用指南的Banner入口. 

### V1.4.0
##### 更新日期: 2018.08.24
##### 更新内容:
新增：
Gate.io 实时Tick 数据;
Bittrex 实时Tick 数据;
Gate.io 交易平台交易对信息.  

### V1.3.0 
##### 更新日期: 2018.08.17
##### 更新内容:
新增：
OKEx合约 基础信息数据;
OKEx合约 K线数据;
OKEx合约 逐笔数据;
OKEx合约 实时盘口数据;
OKEx合约 实时Ticker数据;
实时报价数据, 支持多个品种同时查询. 

### V1.2.0 
##### 更新日期: 2018.08.09
##### 更新内容:
新增：
OKEx 实时盘口数据;
Fcoin 实时报价数据;
Huobi 实时逐笔、实时盘口数据;
HitBTC 实时报价数据;
Bitfinex 历史K线、实时K线数据、实时报价数据;
Binance 实时逐笔数据. 



