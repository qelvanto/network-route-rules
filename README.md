# Network route rules

Credential-free routing rules shared by Shadowrocket and Mihomo.

`rules/proxy.list` contains only match expressions. The consumer assigns the
action: `PROXY` in Shadowrocket and `ROUTE` in Mihomo.

Stable raw URL:

```text
https://raw.githubusercontent.com/qelvanto/network-route-rules/main/rules/proxy.list
```

The list intentionally contains no VPN endpoints, subscription URLs, account
identifiers, or credentials.
