# Daily Deck｜遊戲日常排程器

以 Python 製作的 Windows 桌面工具，協助依序執行各款遊戲已設定好的自動日常腳本。

## 下載

前往 [最新版本下載頁](https://github.com/R1w10/DailyDeck/releases/latest)，下載：

**DailyDeck-v版本號-windows-x64.zip**

解壓縮到固定資料夾，開啟「遊戲日常排程器.exe」即可，不需要另外安裝 Python。

請下載 DailyDeck 的 ZIP，不要下載 GitHub 自動產生的 Source code。

## 使用前準備

Daily Deck 需要搭配對應的遊戲工具，不能單獨完成遊戲日常。

請先自行安裝並設定好需要使用的工具，確認它能獨立執行日常：

- 鳴潮：[ok-ww](https://github.com/ok-oldking/ok-wuthering-waves)
- 明日方舟：終末地：[MaaEnd](https://github.com/MaaEnd/MaaEnd)
- 星塔旅人：[星塔助手 MaaStellaSora](https://github.com/MaaStellaSora/MaaStellaSora)，使用包含遊戲資源的完整版本。

星塔助手採用 [MFAAvalonia](https://github.com/MaaXYZ/MFAAvalonia) 圖形介面。MFAAvalonia 是通用介面，與底層的 [MaaFramework](https://github.com/MaaXYZ/MaaFramework) 是不同專案。

## 使用方式

1. 開啟 Daily Deck，接受 Windows 管理員權限提示。
2. 首次設定時，確認偵測到的工具位置，或自行選擇安裝資料夾。
3. 選擇已儲存的日常配置。
4. 建議先單獨測試每款遊戲，再使用完整佇列。
5. 用開關選擇遊戲，拖曳調整執行順序，按「開始排程」。

遊戲內的任務項目與選項，請在各工具內設定並儲存。

## 功能

- 依序啟動工具、監控完成並接續下一款遊戲
- 每日定時執行
- Discord Webhook 結果通知
- 可選擇日常結束後自動關機
- 週一執行鳴潮每日任務時，加做每週樂園檢查
- GitHub 新版本檢查與程式內更新

## 使用提醒

- 定時執行需要電腦開機、已登入並解鎖桌面。
- 部分工具會使用前景視窗、滑鼠與鍵盤，請預留執行時間。
- 自動關機預設停用，啟用後請先儲存其他文件。
- 請勿公開分享 Discord Webhook 或個人設定檔。
- v0.7.1 及更舊版本需要手動更換成 v0.8.0 一次，之後才支援程式內更新。

## 專案定位與致謝

Daily Deck 主要負責既有開源工具的啟動、排程、監控與串接，以及少量相容性適配。

各遊戲的登入、畫面辨識、戰鬥與日常任務邏輯，主要由原專案提供，並非由 Daily Deck 重新開發一套遊戲自動化腳本。

感謝 ok-ww、MaaEnd、MaaStellaSora、MFAAvalonia、MaaFramework 的作者、維護者與貢獻者。
