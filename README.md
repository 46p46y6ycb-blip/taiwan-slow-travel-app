# Taiwan Slow Travel App

這個專案是一個可安裝的行動版旅遊 App，內容是你提供的「台灣慢旅行 2026–2027」行程計畫。

## 使用方式

1. 直接在瀏覽器開啟 `index.html`
2. 在手機上使用 Chrome / Edge / Safari 開啟
3. 點選「安裝到主畫面」即可像 App 一樣使用
4. 除了瀏覽器中也可離線使用（已加入 service worker）

## 本地快取預覽

若你要在本機做預覽，可在專案目錄執行：

```bash
python3 -m http.server 8000
```

然後打開：

```text
http://localhost:8000
```

## 功能

- 每日行程瀏覽
- 交通、住宿、預算區塊
- 可勾選的行李清單
- 自動保存到 localStorage
- 支援 PWA 安裝
- 手機介面適配

## 專案結構

- `index.html`：主頁面
- `manifest.webmanifest`：PWA 安裝設定
- `sw.js`：離線快取
- `icon.svg`：應用圖示
