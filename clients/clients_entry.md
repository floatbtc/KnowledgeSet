# 常用的客户端

所谓**客户端**，其实就是本地用来进行加密的工具。当加密工具打开，每个用户就可以通过自己订阅的机场访问到墙外的网络。

常用的客户端有以下这些：
* Clash
* V2Ray
* ShadowSocks
* ...

客户端经常有不少的变种（因为各种各样原因不再支持）。不同的变种之间，功能是基本类似的。

## Clash
目前，比较主流的工具是Clash, 它包含多个变种。不过，它们都是基于Clash项目进行开发的。

Clash的项目代码

https://github.com/BackupTime/clash

### ClashN

![alt text](/pictures/clash_n.png)

ClashN 的特点：

* 简化的用户界面： ClashN 的界面设计更加简洁，注重易用性。它去除了复杂的配置项和高级功能，适合那些希望快速上手而不需要过多自定义设置的用户。

* 跨平台支持： ClashN 不仅可以在 Windows 上使用，也支持 macOS 等其他桌面操作系统。它的跨平台特性使得用户能够在不同设备上获得一致的使用体验。

* 多协议支持： 与 Clash for Windows 一样，ClashN 支持多个代理协议，包括 VMess、Shadowsocks、Socks5 等，适用于各种代理使用场景。

* 轻量化与高效： ClashN 的设计注重性能和效率，运行时资源占用较小，适合在较低性能的设备上运行。与 Clash for Windows 相比，它更加轻量，且启动和操作速度较快。

* 订阅管理与规则配置： ClashN 支持订阅管理，用户可以方便地导入代理订阅链接。它还支持自动更新订阅和规则，使得用户无需手动更新代理配置。它还提供了类似于 Clash for Windows 的规则配置功能，能够灵活地定义流量的路由策略。


Github地址：
https://github.com/2dust/clashN

### Clash for Windows
![alt text](/pictures/clash_4_windows.png)

Clash 最早由 Dreamacro 开发，主要是命令行工具。随着用户需求的增加，许多用户希望在桌面环境中使用更便捷的图形化管理工具，于是 Clash for Windows 开发了它的 GUI 版本。

### Clash Verge Rev

这个工具目前我主力在使用。界面比较漂亮（相对于V2Ray :smile: ）, 管理订阅也比较方便。
![alt text](/pictures/clash_verge_rev.png)