# 夜音

Apple Silicon Mac 的原生注音輸入法，使用標準／大千鍵位，提供中英混輸與繁簡輸出。

## 下載與安裝

最低需求：Apple Silicon、macOS 26.0。

1. 前往[最新版本](https://github.com/yetiz-org/yayin/releases/latest)，下載 `YAYin-X.Y.Z.pkg`。
2. 開啟安裝包，依畫面完成安裝並提供管理員授權。
3. 第一次安裝時，依安裝程序提示啟用「夜音」，再從選單列切換輸入法。

目前 App 採用 ad-hoc 簽章；安裝包未簽署、未公證，沒有 Apple 認證的發佈者身分。macOS 可能顯示 Gatekeeper 警告或阻擋安裝。請先確認下載來源；相關提示與處理方式見 [Apple 官方說明](https://support.apple.com/zh-tw/102445)。

手動安裝只需下載 `.pkg`；同版的 `manifest.json` 與 `manifest.json.sig` 供更新驗證使用。

## 更新

下載新版安裝包並直接安裝。已啟用的輸入法由安裝程序重新啟動，不用先刪除再加入。更新完成後回到原本的 App 即可繼續輸入。

## 資料授權

注音組音、拼音與繁簡轉換採夜音自有實作；McBopomofo 與 OpenCC 僅作為詞庫／字典資料來源。離線英文整詞表採 SCOWL／English Speller Database 2026.02.25 的 US、GB、CA large 純文字資料，見[完整 Copyright](https://raw.githubusercontent.com/en-wl/wordlist-diff/rel-2026.02.25/Copyright)。各項第三方資料仍依各自授權散布，完整授權聲明隨 App 提供。
