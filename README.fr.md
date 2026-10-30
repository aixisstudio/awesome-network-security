# Awesome Network Security

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

Une sélection d'outils de sécurité réseau — pare-feux, sniffers, IDS, honeypots

Pare-feu et filtrage du trafic

Description de l'outil
|---|---|
[Snitch](https://github.com/aixisstudio/Snitch)= Pare-feu de l'application Open-source — voir et bloquer chaque connexion sortante, par processus, règles Sigma, 8 langues=
[OpenSnitch](https://github.com/evilsocket/opensnitch)= Pare-feu d'application Linux inspiré par Little Snitch=
[Portmaster](https://github.com/safing/portmaster)= Pare-feu d'application avec protection de la vie privée DNS
[LuLu](https://github.com/objective-see/LuLu) Le pare-feu or standard pour macOS
Pare-feu léger basé sur le PAM pour Windows
(https://netfilter.org/projects/nftables/) Le cadre moderne de filtrage des paquets Linux
[pfSense](https://github.com/pfsense/pfsense)= Distribution FreeBSD pare-feu/routeur=
[CrowdSec](https://github.com/crowdsecurity/crowdsec)=PIP en collaboration — bloque les IP hostiles en utilisant l'information communautaire=
[fail2ban](https://github.com/fail2ban/fail2ban)

Capture et analyse des paquets

Description de l'outil
|---|---|
(https://gitlab.com/wireshark/wireshark) L'analyseur de protocole de référence
[tcpdump](https://github.com/the-tcpdump-group/tcpdump)
[Sniffnet](https://github.com/GyulyVGC/sniffnet)=Le moniteur de trafic moderne basé sur la rouille avec une belle UI
[Arkime](https://github.com/arkime/arkime)= capture complète des paquets + indexage pour les grands réseaux=
[mitmproxy](https://github.com/mitmproxy/mitmproxy)= Proxy d'interception HTTPS interactif
[bettercap](https://github.com/bettercap/bettercap)
[EtherApe](https://etherape.sourceforge.io/)= Navigateur de trafic réseau graphique
[ngrep](https://github.com/jpr5/ngrep)= grep pour la couche réseau=

IDS / IPS & Détection

Description de l'outil
|---|---|
[Suricata] (https://github.com/OISF/suricata)
[Zeek](https://github.com/zeek/zeek)= Surveillance de sécurité réseau avec analyse de protocole profonde=
[Snort] (https://www.snort.org/) L'IPS d'origine open-source
[Wazuh](https://github.com/wazuh/wazuh)= XDR + SIEM pour les paramètres et le nuage=
[OSSEC](https://github.com/ossec/ossec-hids)
[Maltrail] (https://github.com/stamparm/Maltrail)
[RITA](https://github.com/activecm/rita)=Détection du sabotage et du C2 à partir de logs Zeek=

Numérisation et reconnaissance

Description de l'outil
|---|---|
[Nmap](https://github.com/nmap/nmap) Le scanner de port
[Masscan] (https://github.com/robertdavidgraham/masscan)
[Zmap](https://github.com/zmap/zmap)
[RustScan] (https://github.com/RustScan/RustScan)
[Nuclei](https://github.com/projectdiscovery/nuclei)

Les pots de miel et la perception

Description de l'outil
|---|---|
[Cowrie] (https://github.com/cowrie/cowrie)
[T-Pot](https://github.com/telekom-security/tpotce)= Plateforme multi-pots tout-en-un=
[Dionaea] (https://github.com/DinoTools/dionaea)
[OpenCanary](https://github.com/thinkst/opencanary)

## DNS & Privacy

Description de l'outil
|---|---|
[Pi-hole] (https://github.com/pi-hole/pi-hole)
[AdGuard Home](https://github.com/AdguardTeam/AdGuardHome)= Serveur de confidentialité DNS
[dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy)= Proxy DNS chiffré (DoH/DoT/DNSCrypt)=
[non lié](https://github.com/NLnetLabs/unbound)

Surveillance et tableaux de bord

Description de l'outil
|---|---|
[ntopng] (https://github.com/ntop/ntopng)
[Netdata](https://github.com/netdata/netdata)= Système en temps réel & métriques réseau==
[Kismet] (https://www.kismetwireless.net/)
[vnStat](https://github.com/vergoh/vnstat)= Comptabilité du trafic léger=

> **Legend**: . = activement maintenu · . = choix de l'éditeur · Tous les outils libres et open-source sauf indication contraire.

## Ajouter à l'analyse d'ingénierie et de trafic inverse

Description de l'outil
|---|---|
[PacketTotal](https://packettotal.com/)= Analyse de pcap Cloud — téléchargement, analyse du protocole
[A-Packets](https://apackets.com/)
[RéseauMiner](https://www.netresec.com/?page=NetworkMiner)
[BruteShark] (https://github.com/odedshimon/BruteShark)
[PCredz] (https://github.com/lgandx/PCredz)

Configuration du trafic et QoS
Description de l'outil
|---|---|
[NetLimiter](https://www.netlimiter.com/)= Contrôle de bande passante par application (Windows)=
`tc` + `tc-cake`
[Shaper Wonder](https://github.com/magnific0/wondershaper)
[Trickle](https://github.com/mariusae/trickle)

Réseau SD-WAN & Virtual
Description de l'outil
|---|---|
[Tailscale](https://github.com/tailscale/tailscale)=                                                                                                                                                                                                                                                  
[ZeroTier](https://github.com/zerotier/ZeroTierOne)= Ethernet virtuel pour la planète=
[Netbird](https://github.com/netbirdio/netbird)= Gestion des services de garde-fils de source ouverte=
[Innernet] (https://github.com/tonarino/innernet)

Détection de l'évacuation et des fuites
Description de l'outil
|---|---|
[Jetons canadiens](https://github.com/thinkst/canarytokens)=Les fils de voyage gratuits pour les données exfil=
[GREYNOISE] (https://www.greynoise.io/) Est-ce que c'est IP vous scanner ou l'Internet entier?
[IPQualityScore] (https://www.ipqualityscore.com/)

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
