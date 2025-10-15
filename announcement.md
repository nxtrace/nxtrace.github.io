**[维护通知]**  
**影响范围**: NextTrace API 全球所有区域服务会暂时中断  

**开始时间**: 10.15.2025 9:50 UTC+8  
**结束时间**: 10.15.2025 10:50 UTC+8  

**维护时间最长将持续**: 1h(期间择机停运，最长持续不超过)  
**地点**: LAX, LAX2, HKG, BER  

**API故障修复及更新**

_10.15.2025 9:42 UTC+8_  
_by @tsosunchia_  

# 历史公告

**[情况通报]**  
已知的问题: 由于上游故障，NextTrace API服务降级，请耐心等待上游修复。    
  
_9.17.2025 14:30 UTC+8_  
_by @tsosunchia_  

-----------------

**[测试通知]**  
最近对 NextTrace 一些底层的代码坐了较大的变更，提升了速度，解决了一些陈年 bug  
比如 mpls 的显示、延迟计时在一些情况下不准确、 macOS 下 tcp trace 最后一跳无法获取、 windows 下支持 tcp/udp trace 等等  

考虑到其中的风险，目前版本需要较长时间的beta测试，欢迎反馈问题（附件为最新 beta 测试的预编译 BIN ）  

[Release]  
https://github.com/nxtrace/NTrace-V1/releases  

_9.14.2025 17:22 UTC+8_  
_updated by @tsosunchia_  

-----------------

**[软件更新]** NextTrace v1.4.2 已发布  
相比v1.4.0:  
 - add support for geoip data from ipdb.one by in b5673b6  
 - add support for custom source ports and optimize some code in PR#85  
 - 变更：FastTrace 增加上海/广州单独测试选项 in 0f8a646  
 - 整合：LEOMOEAPI 的 SNI 改用 api.nxtrace.org in 3defedd  
 - chore(deps)  

[Release]  
https://github.com/nxtrace/NTrace-core/releases/tag/v1.4.2  

_7.27.2025 12:20 UTC+8_  
_by @tsosunchia_  

-----------------

**[维护通知]**  
**影响范围**: NextTrace API 全球所有区域服务会暂时中断  

**开始时间**: 2.1.2025 18:30 UTC+8  
**结束时间**: 2.1.2025 21:30 UTC+8  

**维护时间最长将持续**: 2h(期间择机停运，最长持续不超过)  
**地点**: LAX, LAX2, HKG, BER  

**API故障修复及更新**

_2.1.2025 16:15 UTC+8_  
_by @tsosunchia_  

-----------------

**[维护通知]**  
**影响范围**: NextTrace API 全球所有区域服务会暂时中断

**开始时间**: 11.10.2024 15:30 UTC+8  
**结束时间**: 11.10.2024 17:30 UTC+8

**维护时间最长将持续**: 2h(期间择机停运，最长持续不超过)  
**地点**: LAX, LAX2, HKG, BER

**API例行维护**

_11.10.2024 15:33 UTC+8_  
_by @kernelcrashdump_  

-----------------

**[维护通知]**  
**影响范围**: NextTrace API 全球所有区域服务会暂时中断

**开始时间**: 9.24.2024 14:00 UTC+8  
**结束时间**: 9.24.2024 16:00 UTC+8

**维护时间最长将持续**: 2h(期间择机停运，最长持续不超过)  
**地点**: LAX, LAX2, HKG, BER

**API例行维护**

_9.24.2024 14:32 UTC+8_  
_by @kernelcrashdump_  

-----------------

**[维护通知]**  
**影响范围**: NextTrace API 全球所有区域服务会暂时中断

**开始时间**: 8.9.2024 19:00 UTC+8  
**结束时间**: 8.9.2024 21:00 UTC+8

**维护时间最长将持续**: 2h(期间择机停运，最长持续不超过)  
**地点**: LAX, LAX2, SJC, HKG, BER

**API例行维护**

_8.9.2024 16:30 UTC+8_  
_by @kernelcrashdump_  

-----------------

**[维护通知]**  
**影响范围**: NextTrace API 亚洲区域服务可能出现中断

**开始时间**: 6.25.2024 11:00 UTC+8  
**结束时间**: 6.25.2024 23:30 UTC+8

**维护时间最长将持续**: 2h(期间择机停运，最长持续不超过)  
**地点**: LAX, HKG

**API紧急维护**

_6.25.2024 10:20 UTC+8_  
_by @kernelcrashdump_  

-----------------

**[维护通知]**  
**影响范围**: NextTrace API所有服务将暂时中断

**开始时间**: 6.1.2024 19:20 UTC+8  
**结束时间**: 6.1.2024 21:20 UTC+8

**维护时间最长将持续**: 2h  
**地点**: LAX, LAX2, SJC, HKG, BER

**API例行维护**

_6.1.2024 19:08 UTC+8_  
_by @kernelcrashdump_  

-----------------

**[维护通知]**  
**影响范围**: NextTrace API所有服务将暂时中断

**开始时间**: 1.19.2023 23:00 UTC+8  
**结束时间**: 1.20.2023 01:00 UTC+8

**维护时间最长将持续**: 2h  
**地点**: LAX, LAX2, SJC, HKG, BER

**API例行维护**

_1.2.2023 21:54 UTC+8_  
_by @kernelcrashdump_  

-----------------

**[情况通报]**  
已知的问题: 观察到今天凌晨(01:39 UTC+8)开始API到大陆部分运营商服务出现中断,我们已将API切换至备份节点,暂时可能出现服务降级.  
故障原因初步排查为文件系统损坏,正在着手修复.  
  
_12.23.2023 22:57 UTC+8_  
_by @kernelcrashdump_  

-----------------

**[公告]**  
关于NextTrace的一些变更  
  
社区的大家好，  
  
因不可抗力，我必须退出NextTrace API的维护，包括但不限于 GEOIP 数据库维护、API 后端开发与运维等。  
在接下来的过渡时期，本项目将由新owner @kernelcrashdump 负责，我将把这些任务及其相关资源、文档移交给TA，  
在明年春天晚些时候将会有新的组织接手整个API的维护工作(将在时机成熟时官宣)。  
NextTrace 的客户端开发我将继续参与，NextTrace 没有跑路，我相信在变更后 NextTrace 项目也能继续稳定地为社区提供服务。  
  
由衷感谢社区和本项目赞助商( DMIT, Misaka, SnapStack )一直以来的支持  
  
_12.23.2023 22:57 UTC+8_  
_by @tsosunchia_  

-----------------

**[情况通报]**  
目前部分地区连接API，发生故障属于正常现象，请耐心等待维护完成。（API主节点在DMIT.LAX）  
>计划维护  
>地点：洛杉矶  
>时间：2023 年 12 月 18 日至 12 月 22 日 太平洋标准时  
>持续：  
>- 每个虚拟化主机少于 30 分钟；   
>- 单个虚拟机最多 0.5 小时。(由于启动顺序的原因）。  
>  
>内容：   
>部署 DMIT 完全第 3 层网络增强功能。  
>  
>https://t.me/DMIT_INC_CN/715  

_12.22.2023 10:51 UTC+8_  
_by @tsosunchia_

-----------------

**[维护通知]**  
**影响范围**: NextTrace API所有服务将暂时中断

**开始时间**: 12.15.2023 23:00 UTC+8  
**结束时间**: 12.16.2023 01:00 UTC+8

**维护时间最长将持续**: 2h  
**地点**: LAX, LAX2, SJC, HKG, BER

**API例行维护**

_12.10.2023 20:26 UTC+8_  
_by @tsosunchia_  

-----------------

**[通知]**  
最近在issue区有很多反馈，出现如下报错的问题  
`websocket: bad handshake`  
对于这种问题，不要急于发issue。大多数情况下，这是由用户的本地环境所引起的。  
特别需要注意的是，如果用户只为自己的DNS设置了代理，而没有为API设置代理，这可能会导致问题。  
我们的项目API使用了GeoDNS，如果用户代理了DNS，可能会接收到Cloudflare的IP地址。  
由于众所周知的原因，Cloudflare在中国大陆的访问并不顺畅。  
因此，当您遇到此类问题时，建议要么将DNS和API同时设置代理，要么就让DNS和API直连。

_12.07.2023 13:16 UTC+8_  
_by @tsosunchia_

-----------------

**[通知]**  
由于近期**API进行了一些变更**，对于自建反代的用户，请参考这条消息：  
https://t.me/nanaselog/205  
(PS: 普通用户请忽略此条内容)

_12.07.2023 09:56 UTC+8_  
_by @tsosunchia_

-----------------

