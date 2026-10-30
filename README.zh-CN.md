# Awesome Network Security

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | **中文** | [日本語](README.ja.md) | [Русский](README.ru.md)

网络安全工具精选 — 防火墙、嗅探器、IDS、蜜罐

##### 防火墙和交通过滤

* 工具 * * 描述 * *
|---|---|
QQ [Snitch] (https://github.com/aixisstudio/Snitch) QQ 开源应用防火墙 — 见 & 屏蔽每条出入口连接, 每个进程, 西格玛规则, 8种语言 QQ
QQ[OpenSnitch](https://github.com/evilsocket/opensnitch) Linux应用防火墙,灵感来自小Snitch QQ
QQ [Portmaster] (https://github.com/safing/portmaster) QQ 应用防火墙 带有 DNS级隐私保护 QQ
[卢鲁] (https://github.com/objective-see/LuLu) |. MacOS 的黄金标准出境防火墙QQ
(https://github.com/henrypp/simplewall) QQ 轻量级 WFP为 Windows 设计的防火墙
[表 (https://netfilter.org/projects/nftables/)                                          现代 Linux 包过滤框架 QQ
[pfSense](https://github.com/pfsense/pfsense)#################################################################################################################################################################################################################################################
[人群Sec](https://github.com/crowdsecurity/crowdsec) 协作IPS — 使用社区英特尔来阻挡敌对IPs QQ.
[失败2ban](https://github.com/fail2ban/fail2ban) 经典的基于日志的野蛮力量保护者 |

# # # # # 包装抓取与分析

* 工具 * * 描述 * *
|---|---|
[Wireshark] (https://gitlab.com/wireshark/wireshark) | | 参考协议分析器 QQ
[tcpdump](https://github.com/the-tcpdump-group/tcpdump) ================================================================================================================================================================================================================================================
[Sniffnet](https://github.com/GyulyVGC/sniffnet)##################################################################################################################################################################################################################################################
[Arkime](https://github.com/arkime/arkime) QQ 完整包捕获+大网络索引QQ
[mitmproxy](https://github.com/mitmproxy/mitmproxy) \ \ \ 交互式 HTTPS 截取代理 \ \
[bettercap](https://github.com/bettercap/bettercap) 用于网络攻击和监控的瑞士兵器刀 |
[乙醚](https://etherape.sourceforge.io/) QQ 图形网络流量浏览器QQ
[ngrep](https://github.com/jpr5/ngrep) 网络层的grep |

□ QQ IDS / IPS 和检测

* 工具 * * 描述 * *
|---|---|
高性能的IDS/IPS/NSM引擎 QQ
[Zeek](https://github.com/zeek/zeek) 网络安全监视器 深协议分析 |
[吸 (https://www.snort.org/) | 原始开源 IPS QQ
[Wazuh](https://github.com/wazuh/wazuh) + XDR + SIEM 用于端点和云 + .
[OSSEC](https://github.com/ossec/ossec-hids) |基于主机的入侵探测 |
[Maltrail](https://github.com/stamparm/Maltrail) 从公共黑名单中发现的恶意交通...
[RITA](https://github.com/activecm/rita) 从Zeek日志中检测到灯塔和C2

□ 扫描和调试

* 工具 * * 描述 * *
|---|---|
[Nmap] (https://github.com/nmap/nmap) |. 端口扫描仪 {}
[Masscan] (https://github.com/robertdavidgraham/masscan) 互联网规模的端口扫描 |
[Zmap](https://github.com/zmap/zmap) 单包全互联网扫描仪
[RustScan] (https://github.com/RustScan/RustScan)#################################################################################################################################################################################################################################################
[Nuclei](https://github.com/projectdiscovery/nuclei) QQ基于模板的脆弱性扫描仪 QQ

# # # 蜜壶和欺骗

* 工具 * * 描述 * *
|---|---|
[牛](https://github.com/cowrie/cowrie) SSH/Telnet蜂蜜罐
[T-Pot](https://github.com/telekom-security/tpotce) | | | | | | - | | | | | | | | | | |
[Dionaea](https://github.com/DinoTools/dionaea) 马利沃捕蜜罐
轻量级守护神蜜罐

□ & DNS 隐私

* 工具 * * 描述 * *
|---|---|
[Pi-hole](https://github.com/pi-hole/pi-hole) 腾讯网全网广告和追踪器屏蔽 腾讯网.
[AdGuard Home] (https://github.com/AdguardTeam/AdGuardHome) DNS级隐私服务器 腾讯网.
[dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) 加密DNS代理(DoH/DoT/DNSCrypt) |.
[无约束](https://github.com/NLnetLabs/unbound) 校验递归解解解解解解解解解解解解

□ QQ 监视和显示板

* 工具 * * 描述 * *
|---|---|
[ntopng] (https://github.com/ntop/ntopng) 腾讯网交通知名度 腾讯网.
[Netdata](https://github.com/netdata/netdata) | 实时系统和网络度量衡 |
[吻] (https://www.kismetwireless.net/) | 无线网络探测器和嗅觉 |
[vnStat](https://github.com/vergoh/vnstat) 轻量级交通核算 |

> ** Legend**: = 积极维护 = = 编辑器选择 = 除非注明,否则所有工具都免费开放源代码.

□ 反向工程和交通分析额外

* 工具 * * 描述 * *
|---|---|
[PacketTotal](https://packettotal.com/)                                 
[A-Packets] (https://apackets.com/) | Online pcap可视化器 |
[网工] (https://www.netresec.com/?page=NetworkMiner) 被动嗅探器用于法证提取
[BruteShark] (https://github.com/odedshimon/BruteShark) 网络法证工具包 |
[PCredz] (https://github.com/lgandx/PCredz) 校对:Soup

###### 交通塑造 & QoS
* 工具 * * 描述 * *
|---|---|
[NetLimiter](https://www.netlimiter.com/) 每一个应用程序的带宽控制(Windows) |
• `tc` + `tc-cake` + Linux 交通管制—— 塑造任何流量
[Wondershaper](https://github.com/magnific0/wondershaper) 简单带宽限制脚本 {}
[Trickle] (https://github.com/mariusae/trickle) – 过程率限制 – 过程率限制 –

□ □ SD-WAN和虚拟网络
* 工具 * * 描述 * *
|---|---|
[标 (https://github.com/tailscale/tailscale) |线卫视网易VPN 零配置 |线卫视.
[ZeroTier](https://github.com/zerotier/ZeroTierOne) 虚拟以太网 行星 |
[Netbird](https://github.com/netbirdio/netbird) 开放源代码线导管理 腾讯网.
[内网] (https://github.com/tonarino/innernet)####################################################################################################################################################################################################################################################

□□□□□□□□
* 工具 * * 描述 * *
|---|---|
[卡纳里·托肯斯] (https://github.com/thinkst/canarytokens) 数据输出的免费绊线 |
[GREYNOISE] (https://www.greynoise.io/) | 是IP扫描你还是整个互联网?
[IP质量评分] (https://www.ipqualityscore.com/) QQIP声誉检查 QQ.

---
## 贡献

欢迎提交 Pull Request，我们会审查并合并。由 [aixisstudio](https://github.com/aixisstudio) 维护，他也是开源应用防火墙 [Snitch](https://github.com/aixisstudio/Snitch) 的作者。

## 许可证: MIT
