# HTML Presentation

純 HTML/CSS/JS 簡報專案，無外部依賴，開啟 `index.html` 即可使用。

## 操作方式

| 動作 | 按鍵 |
|------|------|
| 下一頁 | `→` / `↓` / `Space` |
| 上一頁 | `←` / `↑` |
| 滑鼠 | 畫面底部 Prev / Next 按鈕 |

## 結構

```
HTML-presentation/
└── index.html   # 所有投影片、樣式、邏輯
```

## 新增投影片

在 `index.html` 的 `<div id="deck">` 內複製一個 `<section class="slide">` 區塊即可，JS 會自動計算頁數與進度條。

可用的 slide 樣式：
- `.slide-title` — 深藍色放射漸層（封面、結尾）
- `.slide-section` — 深綠色放射漸層（章節過場）
- 無額外 class — 預設黑色背景（內容頁）
