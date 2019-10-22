# RedisDesktopManager-Windows

如果在條件允許的情況下，衷心地希望購買[訂閱](https://redisdesktop.com/pricing)支持作者，
在這裡也非常感謝作者開源 [RedisDesktopManager](https://github.com/uglide/RedisDesktopManager) 。


## Fork 說明

此倉庫為 [lework/RedisDesktopManager-Windows](https://github.com/lework/RedisDesktopManager-Windows)
的分支，只是修改為每次 commit 後會自動拉取最新版本的 RedisDesktopManager 編譯並發布。

感謝由 [@lework](https://github.com/lework) 所編寫的 `appveyor.yml` 。


## 安裝使用

RedisDesktopManager 只支援 x64 平台。

在本倉庫的 [Releases](https://github.com/jfcherng/RedisDesktopManager-Windows/releases)
頁面下載 `redis-desktop-manager-XXX.zip` ，解壓後安裝 `redis-desktop-manager-XXX.exe` 即可。


## FAQ

1. 啟動出現 `0xc000007b` 錯誤

   下載安裝 [vc_redist.x64.exe](https://aka.ms/vs/15/release/vc_redist.x64.exe) 點擊修復選項。
