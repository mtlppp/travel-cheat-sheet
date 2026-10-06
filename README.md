# 旅行貓紙 Travel Cheat Sheet v1.0

手機優先的旅行短句工具，提供中文／英文介面，收錄日語及泰語購物、點餐、付款、問路及求助常用句。

- 網站：https://mtlppp.github.io/travel-cheat-sheet/
- 純 HTML／CSS／JavaScript，無需建置，直接以 GitHub Pages 發布。

## 檔案

| 檔案 | 用途 |
| --- | --- |
| `index.html` | 主程式 |
| `privacy.html` | 私隱政策（AdSense 必需） |
| `robots.txt`、`sitemap.xml` | 搜尋引擎索引 |
| `ads.txt` | AdSense 授權賣家檔案（填入發布商 ID 後啟用；必須放在網域根目錄） |
| `favicon.svg` | 網站圖示 |

## 啟用 Google AdSense

1. AdSense 批准網站後，打開 `index.html`，找到 `window.ADS_CONFIG`，填入 `client: 'ca-pub-…'` 及廣告單元 `slot: '…'`。
2. 編輯 `ads.txt`，換上自己的 `pub-` ID 並移除 `#`。
3. 提交後 GitHub Pages 會自動更新。

## 版本

- v1.0（2026-10-07）：正式上線；日語及泰語句庫、中英介面、價錢數字板、SEO 及廣告位。
