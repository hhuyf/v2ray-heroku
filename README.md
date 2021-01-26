# V2Ray vless Heroku

## 概述

用于在 Heroku 上部署 V2Ray Websocket vless。

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Fhhuyf%2Fv2ray-heroku)

## ENV 设定

### UUID

`UUID` > `一个 UUID，供用户连接时验证身份使用`。
### PATH
PATH WS路径
### DEST
DEST 回落地址

## 注意

WebSocket 路径为 `PATH`

V2Ray 将在部署时自动安装最新版本。

**出于安全考量，除非使用 CDN，否则请不要使用自定义域名，而使用 Heroku 分配的二级域名，以实现 V2Ray Websocket + TLS。**
