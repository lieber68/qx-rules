# 简介

本项目生成适用于 [**QuantumultX**](https://apps.apple.com/us/app/quantumult-x/id1443988620) 的规则集。使用 GitHub Actions 北京时间每天早上 6:30 自动构建，保证规则最新。

## 说明

本项目的规则集主要来源于项目 [@Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) 和 [@v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)；[`Apple`](https://github.com/lieber68/qx-rules/blob/release/apple.txt) 和 [`Google`](https://github.com/lieber68/qx-rules/blob/release/google.txt) 列表里的部分域名来源于项目 [@felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)；中国大陆 IPv4 地址数据使用 [@17mon/china_ip_list](https://github.com/17mon/china_ip_list)。

## 规则文件地址及使用方式

### ⚠️ 注意：

- **本项目基于[**Loyalsoldier/surge-rules**](https://github.com/Loyalsoldier/surge-rules)修改！！！！** 

### 在线地址（URL）

> 如果无法访问域名 `raw.githubusercontent.com`，可以使用第二个地址（`cdn.jsdelivr.net`），但是内容更新会有 12 小时的延迟。

#### 规则文件链接:

- **直连域名列表 direct.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/direct.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/direct.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/direct.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/direct.txt)
- **代理域名列表 proxy.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/proxy.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/proxy.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/proxy.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/proxy.txt)
- **广告域名列表 reject.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/reject.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/reject.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/reject.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/reject.txt)
- **私有网络专用域名列表 private.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/private.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/private.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/private.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/private.txt)
- **Apple 域名列表 apple.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/apple.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/apple.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/apple.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/apple.txt)
- **iCloud 域名列表 icloud.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/icloud.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/icloud.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/icloud.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/icloud.txt)
- **Google 域名列表 google.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/google.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/google.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/google.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/google.txt)
- **GFWList 域名列表 gfw.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/gfw.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/gfw.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/gfw.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/gfw.txt)
- **Greatfire 域名列表 greatfire.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/greatfire.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/greatfire.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/greatfire.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/greatfire.txt)
- **非中国大陆使用的顶级域名列表 tld-not-cn.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/tld-not-cn.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/tld-not-cn.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/tld-not-cn.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/tld-not-cn.txt)
- **Telegram 使用的 IP 地址列表 telegramcidr.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/telegramcidr.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/telegramcidr.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/telegramcidr.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/telegramcidr.txt)
- **中国大陆 IPv4 地址列表 cncidr.txt**：
  - [https://raw.githubusercontent.com/lieber68/qx-rules/release/cncidr.txt](https://raw.githubusercontent.com/lieber68/qx-rules/release/cncidr.txt)
  - [https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/cncidr.txt](https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/cncidr.txt)

### 使用方式

#### 白名单模式（推荐）

⚠️ 注意：

- 白名单模式，意为「**没有命中规则的网络流量，统统使用代理**」，适用于服务器线路网络质量稳定、快速，不缺服务器流量的用户。
- 如你希望 Apple、iCloud 和 Google 列表中的域名使用代理，则把 policy 由 `DIRECT` 改为 `PROXY`，以此类推，举一反三。

**远程规则：**

```
[filter_remote]
https://gitee.com/lieber68/selfUseRules/raw/master/lieber/X/direct.list, tag=Lieber, update-interval=43200, force-policy=direct, enabled=true
https://gitee.com/lieber68/selfUseRules/raw/master/lieber/X/proxy.list, tag=Lieber, update-interval=43200, force-policy=𝐏𝐫𝐨𝐱𝐲, enabled=true
https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/ruleset/private.txt, tag=private, update-interval=43200, force-policy=direct, enabled=true
https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/ruleset/reject.txt, tag=reject, force-policy=reject, update-interval=43200, enabled=true
https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/ruleset/icloud.txt, tag=icloud, update-interval=43200, force-policy=direct, enabled=true
https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/ruleset/apple.txt, tag=apple, update-interval=43200, force-policy=direct, enabled=true
https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/ruleset/google.txt, tag=google, update-interval=43200, force-policy=direct, enabled=true
https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/ruleset/proxy.txt, tag=proxy, update-interval=43200, force-policy=𝐏𝐫𝐨𝐱𝐲, enabled=true
https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/ruleset/direct.txt, tag=direct, update-interval=43200, force-policy=direct, enabled=true
https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/ruleset/telegramcidr.txt, tag=telegramcidr, update-interval=43200, force-policy=direct, enabled=true
https://cdn.jsdelivr.net/gh/lieber68/qx-rules@release/ruleset/cncidr.txt, tag=cncidr, update-interval=43200, force-policy=direct, enabled=true

[filter_local]
ip-cidr, 10.0.0.0/8, direct
ip-cidr, 127.0.0.0/8, direct
ip-cidr, 172.16.0.0/12, direct
ip-cidr, 192.168.0.0/16, direct
ip-cidr, 224.0.0.0/24, direct
geoip, cn, direct
final, 𝐅𝐢𝐧𝐚𝐥
```

## 致谢

- [@Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)
- [@Loyalsoldier/cn-blocked-domain](https://github.com/Loyalsoldier/cn-blocked-domain)
- [@v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)
- [@felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)
- [@17mon/china_ip_list](https://github.com/17mon/china_ip_list)
