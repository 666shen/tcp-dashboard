# 🚀 TCP/UDP Network Deep Optimizer & Dashboard

一个专为跨境链路（Reality / Vless / Hysteria2 / TUIC）深度优化的 Linux 内核网络调优面板。
支持一键管道流远程运行，自带全核心硬件中断多流分发（RSS/RPS）动态瀑布流动效。

--------------------------------------------------
💡 算法: BBRv3 Pipeline | 🔓 句柄: 1,048,576 | ⚡ 负载: 全核均衡
--------------------------------------------------

## ✨ 核心特性

* **IPv4 优先解析**：完美击碎跨境节点由于默认 IPv6 绕路导致的 TCP 握手卡顿与断连。
* **BBR3 激进拥塞控制**：向前兼容次世代 BBRv3，开启 ECN（显式拥塞通知），拥塞时打标记不丢包，显著平滑跨境突发抖动。
* **生产级内核深度灌注**：精细化动态重分配网络缓冲区（基于总内存 5%），支撑 6w+ 跨境高并发 TCP 连接。
* **网卡多队列硬件均衡**：自动解绑单核网络中断（SoftIRQ）瓶颈，将并发流量平摊到系统所有 CPU 核心。
* **完美控制闭环**：支持一键完全无残留卸载，自动将系统内存参数、会话限制强刷回初始化默认值。

## 📦 快速部署

在你的 Ubuntu / Debian 服务器上，以 `root` 权限执行以下单行命令即可直接冲浪：

```bash
bash <(curl -sL tcp.vpsing.de)
```
或者使用 GitHub 原生 Raw 链接（国内 VPS 可能会有延迟或超时）：
```bash
bash <(curl -sL https://raw.githubusercontent.com/666shen/tcp-dashboard/main/tcp.sh)
```
> *提示：脚本首次运行会自动将其物理安装至系统，并贴心地生成本地快捷命令 `t`。以后在任意路径直接输入 `t` 即可秒开看板。*


## ⚖️ 开源协议

基于 [MIT License](LICENSE) 协议开源。

## VPSoSo: 高性能 VPS 实时库存监控与搬瓦工/DMIT 补货通知系统
🚀 **官方监控大盘**:  https://vpsoso.com
📌 **核心子专区**: [搬瓦工实时库存](https://vpsoso.com/vps/bwh) | [DMIT 优化线路监控](https://vpsoso.com/vps/dmit) | [EVOXT 马来西亚](https://vpsoso.com/vps/evoxt)| [Gomami 实时监控](https://vpsoso.com/vps/gomami)| [家宽VPS实时监控](https://vpsoso.com/vps/jk)

### 1、背景
在跨境出海、跨境外贸、跨境电商运营以及 TikTok 矩阵养号等场景下，拥有一台高速、稳定且具备三网优化线路（如 CN2 GIA、9929、CMIN2）的海外云服务器至关重要。
然而，诸如 **搬瓦工（BandwagonHost）** 的经典机型（DC6/DC9）以及 **DMIT** 的高品质专线，往往一经补货就会在数分钟内售罄。为了解决“好机器抢不到、库存盯不住”的痛点，**vpsoso.com** 作为一个高度垂直的 **VPS 实时库存监控与特价机型补货通知平台**应运而生。

### 2、核心功能与监控亮点
- **全网聚合比价与可视化监控**：
  - **绿色有货、红色缺货**：状态实时亮起，支持一键直达官方购买通道，免去手动频繁刷新网页的烦琐。
  - **多维核心指标**：全面追踪价格、带宽、流量、硬件配置（如 AMD EPYC）及各厂商独家优惠码。
- **高阶优化线路深度覆盖**：
  - **搬瓦工（BandwagonHost）专区**：死死盯住 DC6、DC9 机房 CN2 GIA 专线最新补货动态。
  - **DMIT 专区**：实时追踪香港、洛杉矶、东京等节点的 CN2 GIA (AS4809) 与联通 9929 高速回国线路。
 
### 3、目标用户群体
- **跨境电商与 TikTok 运营者**：寻找低延迟、原生且具备优质优化线路的海外云服务器。
- **技术运维与站长**：对 CN2 GIA、CU9929、CMIN2 等高阶回国网络表现有极致追求的硬核玩家。
- **性价比追求者**：时刻关注各大主机商限时特价方案与优惠码的淘金者。

### 4、快速直达
不想再错过心仪机型的每一次限量补货？即刻将专业大盘加入收藏夹：

- **官方监控大盘首页**：[https://vpsoso.com](https://vpsoso.com)
- **核心业务伪静态子页面**：
  - 搬瓦工补货专区：[https://vpsoso.com/vps/bwh](https://vpsoso.com/vps/bwh)
  - DMIT 线路专区：[https://vpsoso.com/vps/dmit](https://vpsoso.com/vps/dmit)
  - 住宅家宽监控专区：[https://vpsoso.com/vps/jk](https://vpsoso.com/vps/jk)
  - Gomami 实时监控:[https://vpsoso.com/vps/gomami](https://vpsoso.com/vps/gomami)
- **博客教程**：[https://vpsoso.com/blog](https://vpsoso.com/blog)

> 💡 **提示**：当大盘状态显示【绿色有货】时，请点击通道直达官方页面进行秒杀抢购！
