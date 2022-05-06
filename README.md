# flomo-proxy-server
a http proxy server of flomo.

因 flomo 服务器设置以及浏览器安全设置原因，目前只能通过 http-proxy 的方法来获取 flomo 中的数据（期望flomo可以尽早开放接口）。

每次运行[logseq-flomo-plugin](https://github.com/SeyeeL/logseq-flomo-plugin)插件需要同步的时候，请确保此服务器处于运行状态。

## 使用说明

本地需安装 Node，可参考[此链接](https://www.runoob.com/nodejs/nodejs-install-setup.html)来安装。若安装依赖出现错误，可参考[此文章](https://segmentfault.com/a/1190000023314583)更换 npm 源后重试。

1. 安装依赖
在当前目录下，命令行运行：
```bash
npm install
   ```
   
2. 启动服务器
在当前路径下，命令行运行：
```bash
npm install
```
    
运行成功之后会命令行会显示 `Starting Proxy at localhost:3228`，此时访问 `localhost:3228/api` 将统一代理到 `https://flomoapp.com/api` 。
