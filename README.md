# shadowrocket-config

个人使用的 Shadowrocket 分流配置。

## 使用方法

Shadowrocket → 配置 → 添加，填入：

```
https://raw.githubusercontent.com/batchor/shadowrocket-config/main/shadowrocket.conf
```

## 规则

| 文件 | 说明 | 策略 |
| --- | --- | --- |
| `anthropic.list` | Claude / Anthropic 相关域名 | PROXY |
| `github.list` | GitHub 相关域名 | PROXY |
| `wiki.banned.in.china.list` | 维基百科「中国大陆封锁网站列表」中的域名 | PROXY |

命中以上规则的流量走代理，其余全部直连。

## 贡献

欢迎提 PR 新增规则。
