# 存摺買賣點

匯入集保 e存摺（e手掌握）匯出的「證券存摺登摺資料」PDF，在 K 線圖上標出自己的買進、賣出點位。

- PDF 在瀏覽器內用密碼解開並解析，不會上傳到任何伺服器；交易紀錄存在瀏覽器 localStorage
- 股價來自 [FinMind](https://finmindtrade.com/) 開放資料（未還原權息），抓不到時可手動匯入 CSV
- 存摺不含成交價，價格預設為當日收盤價，可在明細表手動改成實際成交價

單一 `index.html`，不需建置。使用 [pdf.js](https://mozilla.github.io/pdf.js/) 與 [Lightweight Charts](https://www.tradingview.com/lightweight-charts/)。
