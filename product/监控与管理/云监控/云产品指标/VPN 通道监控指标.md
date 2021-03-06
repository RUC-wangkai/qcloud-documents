腾讯云云监控为 VPN 通道提供以下监控指标：

| 指标中文名 | 指标含义         | 单位   | 维度    |
| ----- | ------------ | ---- | ----- |
| 网络出带宽 | VPN 通道平均每秒出流量  | Mbps |VPN 通道|
| 网络入带宽 | VPN 通道平均每秒入流量  | Mbps |VPN 通道|
| 出包量   | VPN 通道平均每秒出包量  | 个/s  |VPN 通道|
| 入包量   | VPN 通道平均每秒入包量  | 个/s  |VPN 通道|
| 丢包率   | VPN 探测一分钟的丢包比例 | %    |VPN 通道|
| 时延    | VPN 探测一分钟的平均时延 | ms   |VPN 通道|
| 通道不通  | VPN 通道实时连通状态   | 0/1  |VPN 通道|

有关更多如何使用 VPN 通道的监控指标内容，可以查看云监控 API 中的 [读取 VPN 通道监控指标接口](https://cloud.tencent.com/document/api/248/10989)。
