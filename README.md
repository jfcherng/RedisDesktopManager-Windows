# RedisDesktopManager-Windows

[![AppVeyor branch](https://img.shields.io/appveyor/ci/jfcherng/RedisDesktopManager-Windows/master?style=flat-square&logo=appveyor)](https://ci.appveyor.com/project/jfcherng/RedisDesktopManager-Windows)
[![GitHub All Releases](https://img.shields.io/github/downloads/jfcherng/RedisDesktopManager-Windows/total?style=flat-square&logo=github)](https://github.com/jfcherng/RedisDesktopManager-Windows/releases)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/jfcherng/RedisDesktopManager-Windows?style=flat-square&logo=github)](https://github.com/jfcherng/RedisDesktopManager-Windows/tags)
[![Project license](https://img.shields.io/github/license/jfcherng/RedisDesktopManager-Windows?style=flat-square&logo=github)](https://github.com/jfcherng/RedisDesktopManager-Windows/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/jfcherng/RedisDesktopManager-Windows?style=flat-square&logo=github)](https://github.com/jfcherng/RedisDesktopManager-Windows/stargazers)
[![Donate to this project using Paypal](https://img.shields.io/badge/paypal-donate-blue.svg?style=flat-square&logo=paypal)](https://www.paypal.me/jfcherng/5usd)

如果在條件允許的情況下，衷心地希望購買[訂閱](https://redisdesktop.com/pricing)支持作者，
在這裡也非常感謝作者開源 [RedisDesktopManager](https://github.com/uglide/RedisDesktopManager) 。

## Fork 修改說明

感謝由 [@lework](https://github.com/lework) 所編寫測試的初始版本 `appveyor.yml` 。

- 編譯時自動使用指定版本的 Embedded Python
- 修復格式化工具 (formatter) 無法使用的問題
- 允許使用 SSH Tunneling 功能

## 安裝使用

RedisDesktopManager 僅支援 x64 平台。

在本倉庫的 [Releases](https://github.com/jfcherng/RedisDesktopManager-Windows/releases)
頁面下載 `redis-desktop-manager-XXX.zip` ，解壓縮後安裝 `redis-desktop-manager-XXX.exe` 即可。

## FAQ

- 啟動出現 `0xc000007b` 錯誤，或找不到 DLL

  下載安裝 [vc_redist.x64.exe](https://aka.ms/vs/16/release/vc_redist.x64.exe) 點擊修復選項。

## 參考文件

- [官方編譯說明文件](http://docs.redisdesktop.com/en/latest/install/)
- [源码编译 Redis Desktop Manager](https://kany.me/2019/10/10/compile-redis-desktop-manager/)
- [@lework](https://github.com/lework) 所編寫的 [appveyor.yml](https://github.com/lework/RedisDesktopManager-Windows/blob/master/appveyor.yml)
