<p align="center">
<img src="https://hits.xykt.de/net.svg?action=view&count_bg=%2379C83D&title_bg=%23555555&title=Runs&edge_flat=false&ts=${new Date().getTime()}"/> 
<img src="https://hits.xykt.de/net_github.svg?action=hit&count_bg=%233DC8C0&title_bg=%23555555&title=Visits&edge_flat=false&ts=${new Date().getTime()}"/> 
<a href="/LICENSE"><img src="https://img.shields.io/badge/License-AGPL%20v3-blue.svg" alt="license" /></a>  
</p>

## Network Quality Check Script  -  [网络质量体检脚本 (CN)](https://github.com/xykt/NetQuality)

**Supported OS/Platform: Ubuntu | Debian | Linux Mint | Fedora | Red Hat Enterprise Linux (RHEL) | CentOS | Arch Linux | Manjaro | Alpine Linux | AlmaLinux | Rocky Linux | macOS | Anolis OS | Alibaba Cloud Linux | SUSE Linux | openSUSE | Void Linux**

- Bilingual support: English & Chinese
- Supports IPv4/IPv6 dual-stack queries
- Well-formatted output for clear and concise display, optimized for screenshots
- Seven key modules: BGP information, local policy, access information, three-network TCP large packet latency, three-network return routing, domestic speed test, and international interconnection
- Base data sourced from *BGP.TOOLS* and *BGP.HE.NET* databases
- Intuitive display of upstream and access information
- Return latency tests for China Mainland’s 31 provinces/cities/autonomous regions via China Telecom, China Unicom, and China Mobile
- Speed test for China Mainland’s three major ISPs (including the Greater Bay Area) based on *SPEEDTEST.NET*
- Global speed and latency tests across five continents
- Flexible test modes: latency mode, low data mode, selective section skipping
- JSON output for big data analysis

##### Screenshots

| IPv4 Test Result | IPv6 Test Result | Latency Mode Test Result |
| ---------------- | ---------------- | ------------------------ |
|![IPv4](https://github.com/xykt/NetQuality/raw/refs/heads/main/res/v4_en.png)|![IPv6](https://github.com/xykt/NetQuality/raw/refs/heads/main/res/v6_en.png)|![Ping](https://github.com/xykt/NetQuality/raw/refs/heads/main/res/ping_en.png)|

## Usage

![Help](https://github.com/xykt/NetQuality/raw/refs/heads/main/res/help.png)

##### Default dual-stack detection:

```bash
bash <(curl -Ls Net.Check.Place)
```

##### IPv4-only test:

```bash
bash <(curl -Ls Net.Check.Place) -4
```

##### IPv6-only test:

```bash
bash <(curl -Ls Net.Check.Place) -6
```

##### Latency mode:

```bash
bash <(curl -Ls Net.Check.Place) -P
```

##### Low data mode:

```bash
bash <(curl -Ls Net.Check.Place) -L
```

##### Skip specific sections:

```bash
bash <(curl -Ls Net.Check.Place) -S 1234567
```

##### Bilingual support:

```bash
bash <(curl -Ls Net.Check.Place) -l cn|en
```

##### JSON output ([Example Output](https://github.com/xykt/NetQuality/blob/main/res/output.json)):

```bash
bash <(curl -Ls Net.Check.Place) -j
```

##### Skip checking OS and dependencies:

```bash
bash <(curl -Ls Net.Check.Place) -n
```

##### Auto-install dependencies:

```bash
bash <(curl -Ls Net.Check.Place) -y
```

##### Display full IP addresses in the report:

```bash
bash <(curl -Ls Net.Check.Place) -f
```

## Script Updates

2025/03/13 22:40 Add -n for no checking OS & dependencies

2025/03/12 17:00 Script Released

## Contributions

**Server Sponsor:**

| Sponsor | Logo | Link | 
| - | - | - | 
| V.PS | ![vps_logo](https://raw.githubusercontent.com/xykt/NetQuality/main/res/sponsor/logo_vps.png) | [https://v.ps](https://v.ps)| 
| BAGE | ![bage_logo](https://raw.githubusercontent.com/xykt/NetQuality/main/res/sponsor/logo_bage.png) | [https://bagevm.com](https://bagevm.com)|
| LisaHost | ![lisa_logo](https://raw.githubusercontent.com/xykt/NetQuality/main/res/sponsor/logo_lisa.png) | [https://lisahost.com](https://lisahost.com)|
| DreamCloud | ![dreamcloud_logo](https://raw.githubusercontent.com/xykt/NetQuality/main/res/sponsor/logo_dreamcloud.png) | [https://as211392.com/](https://as211392.com/)|

**Only accepting merchants with long-term stable operations and good reputation*

**Acknowledgments:**

- Special thanks to [GlobalSign@Nodeseek](https://www.nodeseek.com/space/5813#/general) for providing a stable and reliable three-network test address, laying a solid foundation for one of the script's most important features.

- Thanks to [Sherlock@Nodeseek](https://www.nodeseek.com/space/13352#/general) for valuable suggestions on functionality and aesthetics.

- Thanks to [Jiushen@Nodeseek](https://www.nodeseek.com/space/9#/general) for technical support and valuable feedback.

- Thanks to Si for important recommendations on script functionality and formatting.

- Thanks to Kakan for providing valuable reference suggestions.


**Stars History:**

![Stargazers over time](https://starchart.cc/xykt/NetQuality.svg?background=%23FFFFFF&axis=%23333333&line=%2377ff77)

**History of daily runs:**

![History of daily runs](https://hits.seeyoufarm.com/api/count/graph/dailyhits.svg?url=https://net.check.place&date=20241109)
