# flomo-proxy-server
a http proxy server of flomo

因 flomo 服务器设置以及浏览器安全设置原因，目前只能通过 http-proxy 的方法来获取 flomo 中的数据。

## 使用说明

本地需安装Node，可参考[此链接](https://www.runoob.com/nodejs/nodejs-install-setup.html)来安装。

1. 下载所有代码
2. 运行 npm start
    
运行成功之后访问 `localhost:3228/api` 会统一代理到 `https://flomoapp.com/api` 。
