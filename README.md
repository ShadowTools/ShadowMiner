# ShadowMiner

矿工软件, 支持ALPH(ALEPHIUM)/BEAM/CFX(Conflux)/ERG(Ergo)/ETC(Ethereum Classic)/ETHF(Ethereum Fair)/ETHW((Ethereum Pow)/IRON(Iron fish)/KAS(Kaspa)/KLS(KARLSEN)/RVN(RavenCoin)币种, 支持GMiner/lolMiner/NBMiner/TrexMiner内核, 支持NVIDIA GPU, 抽水管理模式(抽水加密/抽水拦截/反抽水), 支持超频参数搜索, 加密转发, 流量信息及份额显示

<img width="1076" height="612" src="https://github.com/ShadowTools/ShadowMiner/blob/main/ShadowMiner.JPG?raw=true"/> 

#### 配套软件:
* 代理: <a href="https://github.com/ShadowTools/ShadowProxy">https://github.com/ShadowTools/ShadowProxy</a>
* 矿工: <a href="https://github.com/ShadowTools/ShadowMiner">https://github.com/ShadowTools/ShadowMiner</a>
* 群控: <a href="https://github.com/ShadowTools/ShadowProxy">https://github.com/ShadowTools/ShadowMonitor</a>

## 功能:
* 支持Windows系统
* 支持NVIDIA GPU
* 支持ALPH/CFX/ERG/ETC/ETHF/ETHW/IRON/KAS/RVN币种
* 支持GMiner/lolMiner/NBMiner/TrexMiner内核
* 支持内核抽水管理
* 支持在线获取超频参数
* 支持网络日志显示
* 支持图表统计显示
* 支持SOCKS5代理
* 支持开机自启动
* 支持禁用系统更新
* 支持设置虚拟内存
* 支持流量统计
* 支持Ping延迟测试
* 更多内容见软件

## 安全:
* 支持SSL/TLS加密模式
* 支持SSL/TLS+二次加密转发模式
  1. 使用私有口令二次加密出口数据(包括抽水地址与数据), 避免信息泄露
  2. 灵活修改目标矿池地址
  4. 支持SOCKS5代理
  5. 需配合ShadowProxy使用, 定期自动更新代理端证书
* 支持抽水管理
  1. 允许模式: 建议配合加密转发使用(加密转发内核抽水数据，避免信息泄露)
  2. 拦截模式: 屏蔽抽水连接(可能会导致部分内核工作异常)
  3. 返还模式: 返还抽水

## 透明:
* 网络日志信息全显示
  1. 加密方式
  2. 矿池与转发地址
  3. 抽水比例与份额
  4. 流量统计信息
  5. 低费率 <0.5%

## 使用说明

解压后运行ShadowMiner.exe
### 安全建议
* 排序:
  * 矿池: SSL/TLS > 非SSL/TLS
  * 代理: 加密转发 > SSL/TLS代理 > 直连
  * 使用SOCKS5代理可增加安全性
* 非SSL矿池, 推荐加密转发模式(单独的SSL/TLS代理安全性差且无法加密内核抽水链接)
* 若使用ShadowProxy(SSL/TLS代理或二次加密代理), 推荐打开证书周期更新功能
* 推荐的组合:
    1. SSL/TLS矿池 + 加密转发 + SOCKS5代理
    2. SSL/TLS矿池 + 加密转发
    3. SSL/TLS矿池 + SSL/TLS代理
    4. SSL/TLS矿池 + 直连
* Mail: shadowtools8@gmail.com
