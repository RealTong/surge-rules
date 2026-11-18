# Surge Rules

从 Clash 规则集转换而来的 Surge `.list` 规则文件。

## 可用文件

| 文件 | 规则数 | 说明 |
|:---|:---|:---|
| `BankUS_Domain.list` | 58 | 美国银行，含通配域名（**推荐**） |
| `BankUS.list` | 45 | 美国银行，DOMAIN-* 形式 |
| `BankUS_No_Resolve.list` | 45 | 与 `BankUS.list` 相同，保留以对齐上游 |

## Surge 用法

```
[Rule]
RULE-SET,https://<project>.pages.dev/BankUS_Domain.list,US-Bank
```

上游源：https://github.com/Accademia/Additional_Rule_For_Clash/tree/main/Bank
