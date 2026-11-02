# 321猶大書講義

## gp1103（2026-11-03）畫線面板補齊互動聖經標準
- 「寫下你的領受」畫線面板新增：「🔊 朗讀這句」（真人語音，失敗自動改用裝置語音）、「📋 複製」（經文＋出處＋我的領受）、「↗ 分享」（手機走系統分享，電腦自動複製）、「關閉」；「儲存」改稱「儲存領受」、「做一張圖」改稱「🖼 做成美圖」。↑前一句／－／＋／整節／整段 與 8 色原本就有，沒動。
- 做法：頁面尾端新增 `<script id="GXP">` 掛件（不改既有函式，用 MutationObserver 補按鈕）；原本的畫線範圍程式只多輸出一行 `window.mkRefOf`，讓複製／分享帶得出「書卷 章:節-節」。
- 上傳：index.html、sc.html、en.html（有的書卷沒有 sc.html）、sw.js、README.md 一起覆蓋。

國度321空中團契｜321聖經講義

猶大書全書一章 25 節：逐節原文解經、講章逐字稿、教學講章、321 生命應用、爭議地圖。

離線可用（PWA）。iPhone 加到主畫面之前，**請先把舊的主畫面捷徑刪掉再重新加一次**——iOS 會按網址快取圖示。

經文：新標點和合本（cmn-cu89t）｜原文：SBLGNT（SBL Greek New Testament）｜English: World English Bible (WEB)

## 三種語言 · Three languages
- `index.html` 繁體中文　`sc.html` 简体中文　`en.html` English（World English Bible）
- 頁首「EN」／「中」一鍵切換；「我的」頁也有語言卡。App 會記住上一次選的語言。
- Tap “EN” / “中” in the header to switch; the app remembers your last choice.
