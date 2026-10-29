烘豆記錄 Web/PWA V5.4.25 TEST

來源：Android V5.4.24 已驗證核心。
第一階段：將現有 HTML/JavaScript 核心轉為可安裝的 Web/PWA 測試版。

目前保留：
- 基本資料與失重率
- 烘焙計時與每 30 秒記錄
- 豆溫 / 火力 / 風力 / RoR
- 關鍵點與階段分析
- 曲線與比較 / 參考曲線
- 歷史資料
- CSV 匯出
- JSON 備份 / 還原
- 曲線圖片儲存 / 分享（依瀏覽器支援）
- PWA manifest + Service Worker 離線殼層

注意：
1. 這是第一個 Web 測試版，資料目前仍存於瀏覽器 localStorage。
2. 正式公開測試前，下一階段會加強 IndexedDB / 儲存可靠性與 iPhone Safari 行為。
3. PWA 必須透過 HTTPS 網址（或 localhost）才能完整啟用 Service Worker / 安裝能力；直接點開本機 index.html 只能做有限測試。
