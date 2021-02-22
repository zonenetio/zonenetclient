# ZoneNet Client

[中文](README_ZH.md)

Global Area Networking. Peer-to-Peer & End-to-End Encryption for every device, anywhere

This is ZoneNet Client, more https://zonenet.io

> Windows, need to install [tap-windows](http://swupdate.openvpn.net/community/releases/tap-windows-9.21.2.exe) first, Copyright OpenVPN Technologies, Inc.

## GUI Client

Download from [releases](https://github.com/zonenetio/zonenetclient/releases): [macOS](https://github.com/zonenetio/zonenetclient/releases/download/v20210214/ZoneNet.dmg), [Windows](https://github.com/zonenetio/zonenetclient/releases/download/v20210214/ZoneNet.msi), [Android](https://github.com/zonenetio/zonenetclient/releases/download/v20210214/ZoneNet.apk), [iOS](https://zonenet.io/download)

## CLI Client

### Install CLI Client via [nami](https://github.com/txthinking/nami)

```
$ nami install github.com/zonenetio/zonenetclient
```

or download binary from [releases](https://github.com/zonenetio/zonenetclient/releases)

### Usage

```
# Run command with root or sudo 
$ zonenetclient --zoneuuid ZONE_UUID --name yourdevicename
```

> more parameters: $ zonenetclient --help
