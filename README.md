# RedisDesktopManager-Windows

[![AppVeyor branch](https://img.shields.io/appveyor/ci/jfcherng/RedisDesktopManager-Windows/master?style=flat-square&logo=appveyor)](https://ci.appveyor.com/project/jfcherng/RedisDesktopManager-Windows)
[![GitHub All Releases](https://img.shields.io/github/downloads/jfcherng/RedisDesktopManager-Windows/total?style=flat-square&logo=github)](https://github.com/jfcherng/RedisDesktopManager-Windows/releases)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/jfcherng/RedisDesktopManager-Windows?style=flat-square&logo=github)](https://github.com/jfcherng/RedisDesktopManager-Windows/tags)
[![Project license](https://img.shields.io/github/license/jfcherng/RedisDesktopManager-Windows?style=flat-square&logo=github)](https://github.com/jfcherng/RedisDesktopManager-Windows/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/jfcherng/RedisDesktopManager-Windows?style=flat-square&logo=github)](https://github.com/jfcherng/RedisDesktopManager-Windows/stargazers)
[![Donate to this project using Paypal](https://img.shields.io/badge/paypal-donate-blue.svg?style=flat-square&logo=paypal)](https://www.paypal.me/jfcherng/5usd)

RedisDesktopManager 以下（官方）簡稱 RDM 。

---

如果在條件允許的情況下，您可以用以下的方式支持原作者：

- [購買付費版的 RDM 訂閱](https://redisdesktop.com/pricing)
- [在 Microsoft Store 上一次性付費購買 RDM](https://www.microsoft.com/store/apps/9NDK76ZVZ3TM)
- 為 [RDM][rdm@github] 貢獻程式碼或翻譯

## Fork 修改說明

感謝由 [@lework][lework@github] 所編寫的 [appveyor.yml][lework_appveyor.yml]。
本倉庫在其基礎上進行以下改動：

- 允許使用 SSH Tunneling 功能
- 移除打開軟體時的更新檢查
- Embedded Python 使用 3.8.x 版本
- 將 Visual C++ Redistributable 打包進安裝檔（而非從網路上下載）

## 安裝使用

**RDM 僅支援 x64 平台。**

1. 前往本倉庫的 [Releases](https://github.com/jfcherng/RedisDesktopManager-Windows/releases) 頁面
1. 下載 `rdm-XXX.zip`
1. 解壓縮後安裝 `rdm-XXX.exe`

## 參考文件

- [官方編譯說明文件](http://docs.redisdesktop.com/en/latest/install/)
- [源码编译 Redis Desktop Manager](https://kany.me/2019/10/10/compile-redis-desktop-manager/)
- [@lework][lework@github] 所編寫的 [appveyor.yml][lework_appveyor.yml]

[lework_appveyor.yml]: https://github.com/lework/RedisDesktopManager-Windows/blob/master/appveyor.yml
[lework@github]: https://github.com/lework
[rdm@github]: https://github.com/uglide/RedisDesktopManager
