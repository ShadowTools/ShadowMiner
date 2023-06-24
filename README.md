# ShadowMiner

矿工软件, 支持ERG(Ergo)/ETC(Ethereum Classic)/ETHF(Ethereum Fair)/ETHW((Ethereum Pow)/KAS(Kaspa)/RVN(RavenCoin)币种, 支持GMiner/lolMiner/NBMiner/TrexMiner内核, 支持NVIDIA GPU, 支持抽水管理模式(抽水加密/抽水拦截/反抽水), 自动超频, 加密转发, 网络信息及抽水份额显示

<img width="1076" height="612" src="https://github.com/ShadowTools/ShadowMiner/blob/main/ShadowMiner.JPG?raw=true"/> 

#### 配套软件:
* 代理: <a href="https://github.com/ShadowTools/ShadowProxy">https://github.com/ShadowTools/ShadowProxy</a>
* 矿工: <a href="https://github.com/ShadowTools/ShadowMiner">https://github.com/ShadowTools/ShadowMiner</a>
* 群控: <a href="https://github.com/ShadowTools/ShadowProxy">https://github.com/ShadowTools/ShadowMonitor</a>

## 功能:
* 支持Windows系统
* 支持NVIDIA GPU
* 支持ERG/ETC/ETHF/ETHW/KAS/RVN币种
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
  3. 返还模式: 抽水返还用户(部分币种/内核支持)

## 透明:
* 网络日志信息全显示
  1. 加密方式
  2. 矿池与转发地址
  3. 抽水比例与份额
  4. 流量统计信息

## 费率:
  * <0.5%
### Note:
费率公开透明, 在网络日志可实时查看费率, 地址, 加密方式及份额

## 使用说明

解压后运行ShadowMiner.exe
### 安全性建议
* 安全排名:
  * 矿池: SSL/TLS矿池 > 非SSL/TLS矿池
  * 代理: 加密转发代理 > SSL/TLS代理 > 直连
  * 叠加SOCKS5代理使用可增加安全性
* 若使用非SSL矿池, 推荐使用加密转发模式(SSL/TLS代理安全性差且无法加密抽水数据, 导致信息泄露)
* 若使用ShadowProxy(SSL/TLS代理或二次加密代理), 请打开证书周期自更新功能
* 推荐的组合:
    1. SSL/TLS矿池 + 加密转发 + SOCKS5代理
    2. SSL/TLS矿池 + 加密转发

----------------------------------------------------------------------------------------------

## 版本更新说明:
V1.0.0:
  1. 支持Windows系统
  2. 支持NVIDIA GPU
  3. 支持ERG/ETC/ETHF/ETHW/KAS/RVN币种
  4. 支持GMiner/lolMiner/NBMiner/TrexMiner内核
  5. 支持内核抽水管理
  6. 支持在线获取超频参数
  7. 支持网络日志显示
  8. 支持图表统计显示
  9. 支持SOCKS5代理
  10. 支持开机自启动
  11. 支持禁用系统更新
  12. 支持设置虚拟内存
  13. 支持流量统计
  14. 支持Ping延迟测试
  15. 更多内容见软件
