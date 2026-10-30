# Awesome Network Security

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | **Русский**

Курируемый список инструментов сетевой безопасности — файрволы, снифферы, IDS, honeypots

##  ️ Фейерволы и фильтрация трафика

| Инструмент | Описание
|---|---|
| [Snitch] (https://github.com/aixisstudio/Snitch) | Брандмауэр приложений с открытым исходным кодом — см. и блокируйте каждое исходящее соединение, каждый процесс, правила Sigma, 8 языков |
[OpenSnitch] (https://github.com/evilsocket/opensnitch) | Брандмауэр приложений Linux, вдохновленный Little Snitch
| [Portmaster] (https://github.com/safing/portmaster) | Брандмауэр приложений с защитой конфиденциальности на уровне DNS |
[LuLu] (https://github.com/objective-see/LuLu) Золотой стандартный исходящий брандмауэр для macOS
| [simplewall] (https://github.com/henrypp/simplewall) | Легкий брандмауэр на основе WFP для Windows |
[nftables] (https://netfilter.org/projects/nftables/) Современная система фильтрации пакетов Linux
| [pfSense] (https://github.com/pfsense/pfsense) | FreeBSD firewall/router distribution |
[CrowdSec] (https://github.com/crowdsecurity/crowdsec) | Совместная IPS — блокирует враждебные IP-адреса с использованием общественной информации
| [fail2ban] (https://github.com/fail2ban/fail2ban) | Классический бревенчатый грубо-силовой защитник |

##   Захват и анализ пакетов

| Инструмент | Описание
|---|---|
[Wireshark] (https://gitlab.com/wireshark/wireshark) Анализатор справочного протокола.
| [tcpdump] (https://github.com/the-tcpdump-group/tcpdump) | Захват пакетов CLI — везде, всегда |
| [Sniffnet] (https://github.com/GyulyVGC/sniffnet) | Современный монитор трафика на основе ржавчины с красивым интерфейсом |
| [Arkime](https://github.com/arkime/arkime) | Полный захват пакетов + индексация для больших сетей |
[mitmproxy] (https://github.com/mitmproxy/mitmproxy) | Интерактивный HTTPS-прокси
https://github.com/bettercap/bettercap - швейцарский армейский нож для сетевых атак и мониторинга
[EtherApe] (https://etherape.sourceforge.io/) | Браузер графического сетевого трафика
| [ngrep](https://github.com/jpr5/ngrep) | grep для сетевого уровня |

##   IDS / IPS & Detection

| Инструмент | Описание
|---|---|
| [Suricata](https://github.com/OISF/suricata) | Высокопроизводительный двигатель IDS/IPS/NSM |
| [Zeek](https://github.com/zeek/zeek) | Монитор сетевой безопасности с глубоким анализом протокола |
[Snort] (https://www.snort.org/) Оригинальный open-source IPS
[Wazuh] (https://github.com/wazuh/wazuh) | XDR + SIEM для конечных точек и облака
[OSSEC] (https://github.com/ossec/ossec-hids) | Обнаружение вторжений на основе хоста
[Maltrail] (https://github.com/stamparm/Maltrail) | Обнаружение вредоносного трафика из публичных черных списков
[RITA](https://github.com/activecm/rita) | Обнаружение маяков и C2 из журналов Zeek |

###Сканирование и реконструкция

| Инструмент | Описание
|---|---|
[Nmap] (https://github.com/nmap/nmap) Портовый сканер.
[Masscan] (https://github.com/robertdavidgraham/masscan) | Сканирование портов в масштабе Интернета
| [Zmap](https://github.com/zmap/zmap) | Однопакетный сканер всего Интернета |
[RustScan] (https://github.com/RustScan/RustScan) | Блазящий современный сканер
[Nuclei] (https://github.com/projectdiscovery/nuclei) | Сканер уязвимостей на основе шаблонов

Оригинальное название: Honeypots & Deception

| Инструмент | Описание
|---|---|
[Cowrie] (https://github.com/cowrie/cowrie) | SSH/Telnet honeypot |
| [T-Pot] (https://github.com/telekom-security/tpotce) | Все в одном мультимедийная платформа |
[Dionaea] (https://github.com/DinoTools/dionaea) | Вредоносный котел
[OpenCanary] (https://github.com/thinkst/opencanary) | Легкий медоносный котел демона

##   DNS и конфиденциальность

| Инструмент | Описание
|---|---|
| [Pi-hole] (https://github.com/pi-hole/pi-hole) | Блокировка сетевой рекламы и трекера |
[AdGuard Home] (https://github.com/AdguardTeam/AdGuardHome) | Сервер конфиденциальности уровня DNS
[dnscrypt-proxy] (https://github.com/DNSCrypt/dnscrypt-proxy) | Зашифрованный DNS-прокси (DoH/DoT/DNSCrypt)
| [несвязанный] (https://github.com/NLnetLabs/unbound) | Валидирующий рекурсивный растворитель |

##   Мониторинг и панели инструментов

| Инструмент | Описание
|---|---|
| [ntopng] (https://github.com/ntop/ntopng) | Видимость веб-трафика |
| [Netdata] (https://github.com/netdata/netdata) | Системные и сетевые показатели в реальном времени |
| [Kismet] (https://www.kismetwireless.net/) | Детектор беспроводной сети
[vnStat] (https://github.com/vergoh/vnstat) | Легкий учет трафика

**Legend**: . = активно поддерживается · . = выбор редактора · Все инструменты бесплатны и с открытым исходным кодом, если не указано.

##   Обратная инженерия и анализ трафика

| Инструмент | Описание
|---|---|
| [PacketTotal] (https://packettotal.com/) | Облачный pcap анализ — загрузите, получите разбивку протокола |
| [A-Packets] (https://apackets.com/) | Визуализатор в режиме онлайн
[NetworkMiner] (https://www.netresec.com/?page=NetworkMiner) Пассивный сниффер для криминалистической экстракции
[BruteShark] (https://github.com/odedshimon/BruteShark) | Инструментарий сетевой криминалистики |
| [PCredz] (https://github.com/lgandx/PCredz) | Доверительное извлечение из колпачков |

## ping Формирование трафика и QoS
| Инструмент | Описание
|---|---|
[NetLimiter] (https://www.netlimiter.com/) | Управление пропускной способностью Per-app (Windows)
| `tc` + `tc-cake` | Управление трафиком Linux — форма любого потока
[Wondershaper] (https://github.com/magnific0/wondershaper) | Простой скрипт ограничения полосы пропускания
| [Trickle] (https://github.com/mariusae/trickle) | Ограничение скорости каждого процесса |

SD-WAN и виртуальные сети
| Инструмент | Описание
|---|---|
| [Tailscale] (https://github.com/tailscale/tailscale) | WireGuard mesh VPN — нулевая конфигурация |
[ZeroTier] (https://github.com/zerotier/ZeroTierOne) | Виртуальный Ethernet для планеты
[Netbird] (https://github.com/netbirdio/netbird) | Управление WireGuard с открытым исходным кодом
[Innernet] (https://github.com/tonarino/innernet) | оркестровка Rust WireGuard

##  ️ Обнаружение утечек
| Инструмент | Описание
|---|---|
| [Канарские токены] (https://github.com/thinkst/canarytokens) | Бесплатные прокладки для эксфила данных |
[GREYNOISE] (https://www.greynoise.io/) Это IP-сканирование вас или всего Интернета?
[IPQualityScore] (https://www.ipqualityscore.com/) Проверка репутации IP

---
## Участие

Pull request'ы приветствуются — открой PR, он будет проверен и принят. Ведёт [aixisstudio](https://github.com/aixisstudio), автор [Snitch](https://github.com/aixisstudio/Snitch) — open-source application firewall.

## Лицензия: MIT
