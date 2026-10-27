# Awesome Network Security

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

ネットワークセキュリティツール厳選リスト — ファイアウォール、スニファ、IDS、ハニーポット

_詳細なコンテンツ（リスト・リンク・説明）は保守のため英語です。以下のセクションがガイドになります。_

## 🛡️ Firewalls & Traffic Filtering

| Tool | Description |
|---|---|
| [Snitch](https://github.com/aixisstudio/Snitch) | Open-source app firewall — see & block every outbound connection, per-process, Sigma rules, 8 languages |
| [OpenSnitch](https://github.com/evilsocket/opensnitch) | Linux application firewall inspired by Little Snitch |
| [Portmaster](https://github.com/safing/portmaster) | Application firewall with DNS-level privacy protections |
| [LuLu](https://github.com/objective-see/LuLu) | The gold-standard outbound firewall for macOS |
| [simplewall](https://github.com/henrypp/simplewall) | Lightweight WFP-based firewall for Windows |
| [nftables](https://netfilter.org/projects/nftables/) | The modern Linux packet-filtering framework |
| [pfSense](https://github.com/pfsense/pfsense) | FreeBSD firewall/router distribution |
| [CrowdSec](https://github.com/crowdsecurity/crowdsec) | Collaborative IPS — blocks hostile IPs using community intel |
| [fail2ban](https://github.com/fail2ban/fail2ban) | Classic log-based brute-force protector |

## 📡 Packet Capture & Analysis

| Tool | Description |
|---|---|
| [Wireshark](https://gitlab.com/wireshark/wireshark) | The reference protocol analyzer |
| [tcpdump](https://github.com/the-tcpdump-group/tcpdump) | CLI packet capture — everywhere, always |
| [Sniffnet](https://github.com/GyulyVGC/sniffnet) | Modern Rust-based traffic monitor with beautiful UI |
| [Arkime](https://github.com/arkime/arkime) | Full packet capture + indexing for large networks |
| [mitmproxy](https://github.com/mitmproxy/mitmproxy) | Interactive HTTPS interception proxy |
| [bettercap](https://github.com/bettercap/bettercap) | Swiss-army knife for network attacks & monitoring |
| [EtherApe](https://etherape.sourceforge.io/) | Graphical network traffic browser |
| [ngrep](https://github.com/jpr5/ngrep) | grep for the network layer |

## 🚨 IDS / IPS & Detection

| Tool | Description |
|---|---|
| [Suricata](https://github.com/OISF/suricata) | High-performance IDS/IPS/NSM engine |
| [Zeek](https://github.com/zeek/zeek) | Network security monitor with deep protocol analysis |
| [Snort](https://www.snort.org/) | The original open-source IPS |
| [Wazuh](https://github.com/wazuh/wazuh) | XDR + SIEM for endpoints and cloud |
| [OSSEC](https://github.com/ossec/ossec-hids) | Host-based intrusion detection |
| [Maltrail](https://github.com/stamparm/Maltrail) | Malicious-traffic detection from public blacklists |
| [RITA](https://github.com/activecm/rita) | Beaconing & C2 detection from Zeek logs |

## 🔍 Scanning & Recon

| Tool | Description |
|---|---|
| [Nmap](https://github.com/nmap/nmap) | The port scanner |
| [Masscan](https://github.com/robertdavidgraham/masscan) | Internet-scale port scanning |
| [Zmap](https://github.com/zmap/zmap) | Single-packet whole-Internet scanner |
| [RustScan](https://github.com/RustScan/RustScan) | Blazing-fast modern scanner |
| [Nuclei](https://github.com/projectdiscovery/nuclei) | Template-based vulnerability scanner |

## 🍯 Honeypots & Deception

| Tool | Description |
|---|---|
| [Cowrie](https://github.com/cowrie/cowrie) | SSH/Telnet honeypot |
| [T-Pot](https://github.com/telekom-security/tpotce) | All-in-one multi-honeypot platform |
| [Dionaea](https://github.com/DinoTools/dionaea) | Malware-catching honeypot |
| [OpenCanary](https://github.com/thinkst/opencanary) | Lightweight daemon honeypot |

## 🌐 DNS & Privacy

| Tool | Description |
|---|---|
| [Pi-hole](https://github.com/pi-hole/pi-hole) | Network-wide ad & tracker blocking |
| [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) | DNS-level privacy server |
| [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) | Encrypted DNS proxy (DoH/DoT/DNSCrypt) |
| [unbound](https://github.com/NLnetLabs/unbound) | Validating recursive resolver |

## 📊 Monitoring & Dashboards

| Tool | Description |
|---|---|
| [ntopng](https://github.com/ntop/ntopng) | Web-based traffic visibility |
| [Netdata](https://github.com/netdata/netdata) | Real-time system & network metrics |
| [Kismet](https://www.kismetwireless.net/) | Wireless network detector & sniffer |
| [vnStat](https://github.com/vergoh/vnstat) | Lightweight traffic accounting |

> **Legend**: 🔥 = actively maintained · ⭐ = editor's pick · All tools free & open-source unless noted.

---
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
