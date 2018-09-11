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

    ├── 公有链数据
        └── 公有链Account地址交易记录数据
```


