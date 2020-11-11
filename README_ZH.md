# ZoneNet 客户端

全球局域网络. 对任何地点, 任何设备, 建立点对点和端到端加密的局域网

这是 ZoneNet Client, 更多信息 https://zonenet.io

> Windows, 需要先安装 [tap-windows](http://swupdate.openvpn.net/community/releases/tap-windows-9.21.2.exe), Copyright OpenVPN Technologies, Inc.

## 图形客户端

下载 [releases](https://github.com/zonenetio/zonenetclient/releases): [macOS](https://github.com/txthinking/brook/releases/download/v20201111/ZoneNet.dmg), [Windows](https://github.com/txthinking/brook/releases/download/v20201111/ZoneNet.exe), [Android](https://zonenet.io/download), [iOS](https://zonenet.io/download)

## 命令行客户端

### 通过[nami](https://github.com/txthinking/nami)安装

```
$ nami install github.com/zonenetio/zonenetclient
```

或直接下载二进制文件[releases](https://github.com/zonenetio/zonenetclient/releases)

### 使用

```
# 用root或sudo或管理员权限运行
$ zonenetclient --zoneuuid ZONE_UUID --name yourdevicename
```

> 更多参数: $ zonenetclient --help
