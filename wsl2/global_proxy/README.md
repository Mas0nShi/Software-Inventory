# Global Proxy

为wsl2 ubuntu 设置全局代理（其实是没钱捣鼓软路由）

- 不同WIFI下选择本机代理地址
- 快速开关代理（鸡肋功能）



使用方式

```shell
source .quick_proxy
# 持久化：写入~/.bashrc
```

- Qptest 探测当前网络环境
- Qpon 使用代理
- Qpoff 取消代理