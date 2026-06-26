# TOEFL 練習工具庫 — PWA（跨裝置同步版）

## 檔案結構
```
toefl-hub/
├── index.html        ← 主頁面
├── manifest.json     ← PWA 設定
├── sw.js             ← Service Worker
├── icon-192.png      ← App 圖示
├── icon-512.png      ← App 圖示
├── pages.json        ← 頁面清單（新增頁面時編輯這裡）
└── pages/            ← 練習 HTML 都放這裡
    └── 20260625-20260626.html
```

## 部署到 GitHub Pages

1. 到你的 `toefl-hub` repo（或新建一個）
2. 把所有檔案上傳（包含 `pages/` 資料夾）
3. Settings → Pages → Branch: `main` → Save
4. 網址：`https://你的帳號.github.io/toefl-hub/`

## 新增練習頁面（跨裝置同步）

1. 把新的 HTML 檔上傳到 repo 的 `pages/` 資料夾
2. 編輯 `pages.json`，加上一筆，例如：

```json
[
  {"name": "20260625-20260626", "file": "20260625-20260626.html"},
  {"name": "20260627-20260628", "file": "20260627-20260628.html"}
]
```

3. Commit changes
4. 等約 1 分鐘，電腦和手機都能看到新頁面！

## 手機安裝
- Android Chrome：點選單 → 安裝應用程式
- iPhone Safari：分享 → 加入主畫面
