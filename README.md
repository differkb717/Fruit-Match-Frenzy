# 消消樂遊戲

這是一個使用 HTML、CSS 和 JavaScript 製作的簡易「消消樂」方塊消除遊戲，支援桌機與行動裝置操作。

## 🎮 遊戲玩法說明

- 遊戲目標：  
  在 180 秒內，透過交換相鄰的水果方塊，湊成 **三個或以上相同水果** 的橫向或縱向排列，來進行消除並累積得分。

- 操作方式：
  - **桌機**：用滑鼠拖曳任一方塊到相鄰位置。
  - **手機／平板**：以手指滑動方式，向上下左右拖曳方塊。

- 消除說明：
  - 每成功消除 3 個方塊，分數會 +1。
  - 消除後方塊會下落並自動補滿，若再次形成消除會繼續連鎖得分。
  - 消除後的空位會自動補新水果。

- 時間限制：
  - 遊戲從 180 秒倒數開始。
  - 時間歸零後，遊戲結束並顯示提示訊息。

## 🧩 技術簡介

- 使用 **HTML5 + CSS3** 建立基礎頁面與樣式。
- 以 **Vanilla JavaScript** 製作互動邏輯與計分、計時功能。
- 支援 **拖曳事件**（Drag and Drop）與 **觸控事件**（Touch Events）確保跨裝置操作體驗。
- 使用 emoji 水果作為遊戲圖案，增添趣味性。

## 📦 運行方式

1. 下載專案後，打開 `index.html` 即可直接在瀏覽器中遊玩。
2. 無需伺服器支援，純前端靜態頁面。

## 🔤 字型支援

- 預設字型為 `"Microsoft JhengHei"`，確保中文字在大多數裝置上顯示良好。

## 📱 跨平台支援

- ✅ 桌機（滑鼠拖曳）
- ✅ 行動裝置（觸控滑動）


