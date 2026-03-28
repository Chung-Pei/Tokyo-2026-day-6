# 東京一日遊行程手冊

一份支援 PWA（可加入主畫面）的行動版旅遊行程手冊。

## 📁 檔案說明

```
tokyo-trip/
├── index.html      ← 主頁面
├── manifest.json   ← PWA 設定
├── sw.js           ← Service Worker（離線快取）
├── icons/          ← App 圖示（請自行加入，見下方說明）
└── README.md
```

## 🚀 GitHub Pages 部署步驟

1. 在 GitHub 建立新的 Repository（如 `tokyo-trip`）
2. 將此資料夾所有檔案上傳至 Repository 根目錄
3. 前往 **Settings → Pages**
4. Source 選擇 **Deploy from a branch**
5. Branch 選擇 `main`，資料夾選 `/ (root)`
6. 儲存後等待約 1–3 分鐘
7. 網址格式：`https://<你的帳號>.github.io/<repo名>/`

## 🍎 Apple PWA 加入主畫面

1. 以 Safari 開啟部署後的網址
2. 點選底部分享按鈕（方塊加箭頭圖示）
3. 選擇「加入主畫面」
4. 即可像 App 一樣使用，支援全螢幕與離線瀏覽

## 🖼 圖示說明

`icons/` 資料夾需放入以下圖示（PNG 格式，建議使用 🌸 或鐵塔圖示）：
- `icon-32.png`   ← 瀏覽器 favicon
- `icon-152.png`  ← Apple Touch Icon
- `icon-180.png`  ← Apple Touch Icon (主要)
- `icon-192.png`  ← PWA manifest
- `icon-512.png`  ← PWA manifest

可使用 [favicon.io](https://favicon.io) 或 [realfavicongenerator.net](https://realfavicongenerator.net) 免費生成。

## ✅ 功能特色

- ✅ 完整 Apple PWA meta 標籤
- ✅ Web App Manifest
- ✅ Service Worker 離線快取
- ✅ Safe area inset（iPhone 瀏海/動態島適配）
- ✅ 捲動式單頁設計（行程 / 交通 / 費用 / 提醒）
- ✅ 響應式設計，手機最佳化
- ✅ 動態捲動顯示效果
