# Awesome Network Security

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

ネットワークセキュリティツール厳選リスト — ファイアウォール、スニファ、IDS、ハニーポット

## 🛡️ファイアウォールとトラフィックフィルタリング

| ツール | 説明 |
|---|---|
| [Snitch](https://github.com/aixisstudio/Snitch) | オープンソースアプリファイアウォール — あらゆるアウトバウンド接続、パープロセス、シグマルール、8言語の参照とブロック |
| 【OpenSnitch】(https://github.com/evilsocket/opensnitch) | リトル・スニッチに触発するLinuxアプリケーションファイアウォール |
| 【ポートマスター】(https://github.com/safing/portmaster) | DNSレベルのプライバシー保護を備えたアプリケーションファイアウォール |
| 【ルルー】(https://github.com/objective-see/LuLu) | macOS のゴールドスタンダードのアウトバウンドファイアウォール |
| [simplewall](https://github.com/henrypp/simplewall) | Windows用軽量WFPベースのファイアウォール |
| [nftables](https://netfilter.org/projects/nftables/) | 現代のLinuxパケットフィルタフレームワーク |
| 【pfSense】(https://github.com/pfsense/pfsense) | FreeBSD ファイアウォール/ルーター配布 |
| [クラウドSec](https://github.com/crowdsecurity/crowdsec) | コミュニティ・インテルによる敵対IPブロック |
| 【fail2ban】(https://github.com/fail2ban/fail2ban) | クラシックログベースブルトフォースプロテクター |

## パケットキャプチャと分析

| ツール | 説明 |
|---|---|
| 【Wireshark】(https://gitlab.com/wireshark/wireshark) | リファレンスプロトコルアナライザ |
| 【tcpdump】(https://github.com/the-tcpdump-group/tcpdump) | クリップキャプチャー — どこでも |
| 【Sniffnet】(https://github.com/GyulyVGC/sniffnet) | 美しいUIでモダンなRustベースのトラフィックモニター |
| [Arkime](https://github.com/arkime/arkime) | 大型ネットワーク向けフルパケットキャプチャ+インデックス作成 |
| [mitmproxy](https://github.com/mitmproxy/mitmproxy) | インタラクティブHTTPSの介入プロキシ |
| 【ベターキャップ】(https://github.com/bettercap/bettercap) | ネットワーク攻撃・監視用スイス式ナイフ |
| 【イーサリアペ】(https://etherape.sourceforge.io/) | グラフィックネットワークのトラフィックブラウザ |
| [ngrep](https://github.com/jpr5/ngrep) | ネットワーク層別 |

## 使い捨て IDS/IPS/検出

| ツール | 説明 |
|---|---|
| 【成田】(https://github.com/OISF/suricata) | 高性能 IDS/IPS/NSM エンジン |
| 【Zeek】(https://github.com/zeek/zeek) | ディーププロトコル解析によるネットワークセキュリティモニター |
| 【予告】(https://www.snort.org/) | オリジナルオープンソース IPS |
| 【Wazuh】(https://github.com/wazuh/wazuh) | XDR + SIEM エンドポイント・クラウド向け |
| 【OSSEC】(https://github.com/ossec/ossec-hids) | ホスト型侵入検知 |
| 【Maltrail】(https://github.com/stamparm/Maltrail) | パブリックブラックリストによる悪質な異物検出 |
| 【RITA】(https://github.com/activecm/rita) | ビーコン&チークログによるC2検出 |

## スキャン&リコン

| ツール | 説明 |
|---|---|
| 【Nmap】(https://github.com/nmap/nmap) | ポートスキャナ |
| 【Masscan】(https://github.com/robertdavidgraham/masscan) | インターネット規模のポートスキャン |
| 【Zmap】(https://github.com/zmap/zmap) | シングルパケット全インターネットスキャナ |
| 【RustScan】(https://github.com/RustScan/RustScan) | ブロースファストモダンスキャナ |
| [Nuclei](https://github.com/projectdiscovery/nuclei) | テンプレートベースの脆弱性スキャナー |

## ハネスポットと認知

| ツール | 説明 |
|---|---|
| 【Cowrie】(https://github.com/cowrie/cowrie) | SSH/Telnet はちみつ |
| 【T-Pot】(https://github.com/telekom-security/tpotce) | オールインワンマルチホニーポットプラットフォーム |
| 【ジオナア】(https://github.com/DinoTools/dionaea) | マルウェア対策 | マルウェア対策 |
| 【オープンカナリー】(https://github.com/thinkst/opencanary) | 軽量デーモンハニーポット |

## インポート DNS & プライバシー

| ツール | 説明 |
|---|---|
| 【Pi-hole】(https://github.com/pi-hole/pi-hole) | 全国の広告・追跡者ブロック |
| 【ガードホーム】(https://github.com/AdguardTeam/AdGuardHome) | DNSレベルのプライバシーサーバ |
| [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) | 暗号化されたDNSプロキシ(DoH/DoT/DNSCrypt) |
| [unbound](https://github.com/NLnetLabs/unbound) | 再帰的解決剤の検証 |

## 監視&ダッシュボード

| ツール | 説明 |
|---|---|
| 【ntopng】(https://github.com/ntop/ntopng) | Webによるトラフィックの可視性 |
| [Netdata](https://github.com/netdata/netdata) | リアルタイムシステム・ネットワークメトリック |
| 【Kismet】(https://www.kismetwireless.net/) | 無線ネットワークディテクタ・スニッファ |
|【vnStat】(https://github.com/vergoh/vnstat) | 軽量化|軽量化|

>**Legend**: ◀ = 積極的に維持される · ◀ = エディタのピック · 通知されない限り、すべてのツールは無料&オープンソース。

## リバースエンジニアリング&トラフィック分析エキストラ

| ツール | 説明 |
|---|---|
| [PacketTotal](https://packettotal.com/) | クラウド pcap 解析 — アップロード、プロトコルの破壊 |
| [A-Packets](https://apackets.com/) | オンラインのpcapビジュラ |
| 【ネットワークマイナー】(https://www.netresec.com/?page=NetworkMiner) | フォレンジック抽出用パッシブスニッファ |
| 【BruteShark】(https://github.com/odedshimon/BruteShark) | ネットワークフォレンジックツールキット |
| [PCredz](https://github.com/lgandx/PCredz) | pcaps のクレデンシャル抽出 |

## 観光&QoS
| ツール | 説明 |
|---|---|
| 【NetLimiter】(https://www.netlimiter.com/) | アプリごとの帯域幅制御(Windows) |
| `tc` + `tc-cake` | Linux トラフィック制御 | フローの形状 |
| [Wondershaper](https://github.com/magnific0/wondershaper) | シンプルな帯域幅制限スクリプト |
| [Trickle](https://github.com/mariusae/trickle) | 加工速度制限 |

##SD-WANと仮想ネットワーク
| ツール | 説明 |
|---|---|
| 【Tailscale】(https://github.com/tailscale/tailscale) | WireGuard メッシュ VPN — ゼロ設定 |
|【ゼロティア】(https://github.com/zerotier/ZeroTierOne) | 地球の仮想イーサネット |
| 【Netbird】(https://github.com/netbirdio/netbird) | オープンソースのWireGuard管理 |
| 【インネルネット】(https://github.com/tonarino/innernet) | 錆ワイヤーガードのオーケストレーション |

## ️️ エグレス&リーク検出
| ツール | 説明 |
|---|---|
| 【カナリアトークン】(https://github.com/thinkst/canarytokens) | データエクスフィルのフリートリップワイヤー |
| 【GREYNOISE】(https://www.greynoise.io/) | IP はインターネット全体でスキャンする? |
| 【IPQualityScore】(https://www.ipqualityscore.com/) | 知財評価チェック |

---
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
