

# 服务器代理服务

如果你觉得本项目对你有用,而且你也恰巧有这方面的需求,你也可以选择通过我的购买链接赞助我  
- [搬瓦工GIA服务器](https://bandwagonhost.com/aff.php?aff=41846)  - - - 仅推荐购买GIA套餐 - - -   

如果你希望购买一些现成的代理服务,可选择下述代理服务
- [搬瓦工官方机场](https://justmysocks.net/members/aff.php?aff=16884)  

## Frp服务端一键配置脚本，脚本默認获取Frp最新版本  
*Frp 是一个高性能的反向代理应用，可以帮助您轻松地进行内网穿透，对外网提供服务，支持 tcp, http, https 等协议类型，并且 web 服务支持根据域名进行路由转发。*

* Detail(详情)：fatedier[<img alt="github" src="https://img.shields.io/badge/github/fatedier/frp-8da0cb?style=for-the-badge&labelColor=555555&logo=github" height="16">](https://github.com/fatedier/frp)
* Script author（脚本原作者）：clangcn [<img alt="github" src="https://img.shields.io/badge/github/clangcn/onekey_install_shell-8da0cb?style=for-the-badge&labelColor=555555&logo=github" height="16">](https://github.com/clangcn/onekey-install-shell)

## Frps-Onekey-Install-Shell For CentOS/Debian/Ubuntu/Fedora (32bit/64bit)

### Install（安装）

#### Gitee
```Bash
wget https://gitee.com/mvscode/frps-onekey/raw/master/install-frps.sh -O ./install-frps.sh
chmod 700 ./install-frps.sh
./install-frps.sh install
```
#### Github
```Bash
wget https://raw.githubusercontent.com/mvscode/frps-onekey/master/install-frps.sh -O ./install-frps.sh
chmod 700 ./install-frps.sh
./install-frps.sh install
```


### Uninstall（卸载）
```Bash
./install-frps.sh uninstall
```
### Update（更新）
```Bash
./install-frps.sh update
```
### Server management（服务管理器）
```Bash
Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```
 
## Script ChangeLog
---------------------------------------

### [1.0.7] - 2024-07-24

#### Added
* Add progress bar for download frps tar file 
[Issue 101](https://github.com/mvscode/frps-onekey/issues/101)

#### Fixed
* fix typo

### [1.0.6] - 2024-06-25

#### Added
* Add new server os to support, RHEL,Rocky,AlmaLinux OS.

* Add new server os on frps.init file

#### Fixed
* fix check server os version script bug

### [1.0.5] - 2024-06-19

#### Added
* Add quic of transport protocol support,server port default same as https port.

* Add user-defined functions for the kcp bind port,server port default same as bind port.

#### Fixed
* Fix the script under frps server start faild still install complete bug.

### [1.0.4] - 2024-06-18

#### Updated
* Add trace option at log level, default is info

* Update shell update function, ask the user if they want to update

#### New
* frps support transport heartbeatTimeout = 90, default is enable

### [1.0.3] - 2024-06-16

#### Amendment
* Amend function name to frps

#### Changed
* Change curl command to get server ip from wget command [Issue 117](https://github.com/mvscode/frps-onekey/issues/117)

### [1.0.2] - 2024-06-13

#### Update
* Update frp server config format to follow up the latest version.
  ```
  bind_addr --> bindAddr
  bind_port --> bindPort
  kcp_bind_port --> kcpBindPort
  etc..
  ```

### [1.0.1] - 2024-06-07

#### Changed
* frps program config file change to frps.toml from frps.int







 

 
  
