# flomo-proxy-server
a http proxy server of flomo

因 flomo 服务器设置以及浏览器安全设置原因，目前只能通过 http-proxy 的方法来获取 flomo 中的数据。

## 使用说明

本地需安装Node，可参考[此链接](https://www.runoob.com/nodejs/nodejs-install-setup.html)来安装。安装依赖出现错误，可参考[此文章](https://segmentfault.com/a/1190000023314583)更换 npm 源后重试。

1. 下载所有代码
2. 安装依赖包，在当前路径下，命令行运行 `npm install`
3. 运行，在当前路径下，命令行运行 `npm start`
    
运行成功之后访问 `localhost:3228/api` 会统一代理到 `https://flomoapp.com/api` 。
