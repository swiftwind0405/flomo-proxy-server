# flomo-proxy-server
a http proxy server of flomo.

因 flomo 服务器设置以及浏览器安全设置原因，目前只能通过 http-proxy 的方法来获取 flomo 中的数据（期望flomo可以尽早开放接口）。

## 🔨 使用说明

建议下载打包好的[Releases](https://github.com/swiftwind0405/flomo-proxy-server/releases)直接运行。
MacOS 用户运行`flomo-proxy-server-macos` Windows用户运行`flomo-proxy-server-win.exe`。

## 📌 重要提示

每次运行[logseq-flomo-plugin](https://github.com/SeyeeL/logseq-flomo-plugin)插件需要同步 flomo 的时候，请确保此服务器处于运行状态。

本工具不记录任何用户信息，所有请求只做 proxy 转发给 flomo 服务器。
