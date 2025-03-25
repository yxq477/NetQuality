<p align="center">
<img src="https://hits.xykt.de/net.svg?action=view&count_bg=%2379C83D&title_bg=%23555555&title=Runs&edge_flat=false&ts=${new Date().getTime()}"/> 
<img src="https://hits.xykt.de/net_github.svg?action=hit&count_bg=%233DC8C0&title_bg=%23555555&title=Visits&edge_flat=false&ts=${new Date().getTime()}"/> 
<a href="/LICENSE"><img src="https://img.shields.io/badge/License-AGPL%20v3-blue.svg" alt="license" /></a>  
</p>

## 网络质量体检脚本  -  [Network Quality Check Script (EN)](https://github.com/xykt/NetQuality/blob/main/README_EN.md)

**支持OS/Platform：Ubuntu | Debian | Linux Mint | Fedora | Red Hat Enterprise Linux (RHEL) | CentOS | Arch Linux | Manjaro | Alpine Linux | AlmaLinux | Rocky Linux | macOS | Anolis OS | Alibaba Cloud Linux | SUSE Linux | openSUSE | Void Linux**

- 中英文双语言支持
- 支持IPv4/IPv6双栈查询
- 精美排版，直观显示，多终端单屏优化展示，便于截图分享
- BGP信息、本地策略、接入信息、三网TCP大包延迟、三网回程路由、国内测速、国际互连七大模块
- 基础数据源自*BGP.TOOLS*及*BGP.HE.NET*数据库
- 上游及接入信息直观展示
- 中国大陆地区31个省/市/自治区电信/联通/移动三网回程延迟
- 基于*SPEEDTEST.NET*的中国大陆（含大湾区）三网网速测试
- 全球五大洲网速及延迟测试
- 延迟模式、低数据模式、跳过任意章节，多种测试方式弹性选择
- Json输出便于大数据分析

##### 屏幕截图
|IPv4测试结果|IPv6测试结果|延迟模式测试结果|
|---|---|---|
|![IPv4](https://github.com/xykt/NetQuality/raw/refs/heads/main/res/v4_cn.png)|![IPv6](https://github.com/xykt/NetQuality/raw/refs/heads/main/res/v6_cn.png)|![Ping](https://github.com/xykt/NetQuality/raw/refs/heads/main/res/ping_cn.png)|


## 使用方法

![Help](https://github.com/xykt/NetQuality/raw/refs/heads/main/res/help.png)

##### 默认双栈检测：
````bash
bash <(curl -Ls Net.Check.Place)
````

##### 只检测IPv4结果：
````bash
bash <(curl -Ls Net.Check.Place) -4
````

##### 只检测IPv6结果：
````bash
bash <(curl -Ls Net.Check.Place) -6
````

##### 延迟模式：
````bash
bash <(curl -Ls Net.Check.Place) -P
````

##### 低数据模式：
````bash
bash <(curl -Ls Net.Check.Place) -L
````

##### 跳过任意章节：
````bash
bash <(curl -Ls Net.Check.Place) -S 1234567
````

##### 中英文双语支持：
````bash
bash <(curl -Ls Net.Check.Place) -l cn|en
````

##### Json输出（[输出示例](https://github.com/xykt/NetQuality/blob/main/res/output.json)）：
````bash
bash <(curl -Ls Net.Check.Place) -j
````

##### 跳过检测系统及安装依赖：
````bash
bash <(curl -Ls Net.Check.Place) -n
````

##### 自动安装依赖：
````bash
bash <(curl -Ls Net.Check.Place) -y
````

##### 报告展示完整IP地址：
````bash
bash <(curl -Ls Net.Check.Place) -f
````


## 脚本更新

2025/03/13 22:40 增加-n参数，跳过OS检测及安装依赖

2025/03/12 17:00 脚本发布

## 脚本贡献

**Server Sponsor:**

| 赞助商| 商标 | 网址 | 
| - | - | - | 
| V.PS | ![vps_logo](https://raw.githubusercontent.com/xykt/NetQuality/main/res/sponsor/logo_vps.png) | [https://v.ps](https://v.ps)| 
| BAGE | ![bage_logo](https://raw.githubusercontent.com/xykt/NetQuality/main/res/sponsor/logo_bage.png) | [https://bagevm.com](https://bagevm.com)|
| 丽萨主机 | ![lisa_logo](https://raw.githubusercontent.com/xykt/NetQuality/main/res/sponsor/logo_lisa.png) | [https://lisahost.com](https://lisahost.com)|
| DreamCloud | ![dreamcloud_logo](https://raw.githubusercontent.com/xykt/NetQuality/main/res/sponsor/logo_dreamcloud.png) | [https://as211392.com/](https://as211392.com/)|

**仅接受长期稳定运营，信誉良好的商家*

**Acknowledgments:**

- 感谢[GlobalSign@Nodeseek](https://www.nodeseek.com/space/5813#/general)提供稳定可靠的三网测试地址，你的付出为脚本最重要的功能之一奠定了坚实基础

- 感谢[福尔摩斯@Nodeseek](https://www.nodeseek.com/space/13352#/general)，你在功能及美工方面为脚本提供了诸多宝贵建议

- 感谢[酒神@Nodeseek](https://www.nodeseek.com/space/9#/general)，你为脚本提供了技术支持及宝贵建议

- 感谢Si，你为脚本的功能及排版提供了重要建议参考

- 感谢Kakan，你为脚本提供了宝贵的参考意见


**Stars History:**

![Stargazers over time](https://starchart.cc/xykt/NetQuality.svg?background=%23FFFFFF&axis=%23333333&line=%2377ff77)

