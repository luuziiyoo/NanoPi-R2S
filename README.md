# 使用 Github Actions 在线编译 NanoPi-R2S 固件

已更新到 19.07.1

R2S 购买链接: [https://s.click.taobao.com/rFvYQpv](https://s.click.taobao.com/rFvYQpv)

## 说明
* IP: 192.168.2.1
* 密码: password

## 特色
* 集成 [frainzy1477/luci-app-clash](https://github.com/frainzy1477/luci-app-clash) 及其 clash bin
* 集成 Lean Lede 常用包
* 集成最新实时监控 Netdata v1.20.0

## 用法
Fork, 把 Actions yml 里面的 `runs-on: self-hosted` 改成 `runs-on: ubuntu-latest`（因为我是自己的服务器上编译，更快），编辑文件 Version 触发编译动作。

## 注意
产品发布初期，官方代码每天都在变，遇到无法编译时，请过来查看 Actions yml 最新更改。

## 参考
* [使用Github的Actions功能在线编译NanoPi-R1S固件（包含H5和H3）](https://totoro.site/index.php/archives/70/)
* [skytotwo/NanoPi-R1S-Build-By-Actions](https://github.com/skytotwo/NanoPi-R1S-Build-By-Actions)
* [klever1988/nanopi-openwrt](https://github.com/klever1988/nanopi-openwrt)
