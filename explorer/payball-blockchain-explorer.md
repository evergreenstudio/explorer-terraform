---
description: PayBall是一款基于以太坊主链搭建的区块浏览器，旨在提高国内区块链上事务数据查询效率
---

# PayBall 区块浏览器

## PayBall业务主要面向区域为国内

站点主域名为 [https://mainnet.eth.api.lc](https://mainnet.eth.api.lc),目前仅提供主网业务查询:

```
$ mainnet
```

{% hint style="info" %}
 如果你需要链接到测试网络断点进行开发测试，请耐心等待我们下一版本开放的测试环境数据
{% endhint %}

关于Api 业务域名参见代码块地址内容:

{% code title="https://mainnet.eth.api.lc/api/gateway/" %}
```bash
# 如果你需要使用RPC端口请求，可以使用我们的另外一个业务域名
curl -X POST -H "Content-Type: application/json" -d '{"jsonrpc": "2.0","method":"eth_call","params":[],"id":1}' https://main.eth.api.lc
```
{% endcode %}



