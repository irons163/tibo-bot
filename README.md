# Tibo Bot 風格頭像

`tibo-bot` 是獨立的 Codex skill。它把一張照片或角色圖轉成 1:1 的 2D 頭肩插畫，套用 Tibo 的歪頭姿勢、近正面胸肩和暖色背景。可選原本衣服或 Tibo 黑衣，腮紅也可開關。

## 安裝

到 [GitHub Releases](https://github.com/irons163/tibo-bot/releases/latest) 下載 `tibo-bot-v0.1.0.zip`，解壓後把 `tibo-bot` 資料夾放進 `~/.codex/skills/`。如果設定了 `CODEX_HOME`，放到該目錄下的 `skills/`。若 Codex 還沒顯示 skill，重新啟動後開一個對話。

## 使用

在可使用圖片編輯功能的 Codex 對話附上一張單人照片或角色圖，再輸入這句話。

```text
請用 $tibo-bot 把這張照片做成 2D 頭像，保留原本衣服，關閉腮紅。
```

預設穿 Tibo 的素黑上衣，並加淡粉腮紅。生成結果依工作階段的圖片工具而異。

## 參考素材

隨附的姿勢照片取自 [Tibo 公開的頭像](https://pbs.twimg.com/profile_images/2093807917833281537/2yBgpwVV.jpg)。Bot 畫風參考和提示詞沿用 [我的T寶的 Tibo Bot 頁面](https://mytibo.zero2codex.dev/bot)。
