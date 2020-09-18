# VLESS Heroku

## 概述

用于在 Heroku 上部署 vless。vless 性能更加优秀，占用资源更少。

## 镜像

经测试本镜像不会因为大量占用资源而被封号。

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2FGeekNAUer%2Fvlessheroku)

## ENV 设定

### UUID

`UUID` > `一个 UUID，供用户连接时验证身份使用`。

## 注意

WebSocket 路径为 `/app`。

`alterId` 为 `0`。
