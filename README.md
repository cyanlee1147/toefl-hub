# TOEFL 練習工具庫 — PWA 部署指南

## 檔案說明
- `index.html` — 主頁面（所有功能都在這一個檔案裡）
- `manifest.json` — PWA 設定檔（名稱、圖示、主題色）
- `sw.js` — Service Worker（離線快取）
- `icon-192.png` / `icon-512.png` — App 圖示

## 部署到 GitHub Pages

### 1. 建立 Repository
1. 登入 GitHub → 點右上角 `+` → `New repository`
2. 名稱填 `toefl-hub`（或任意名稱）
3. 設為 **Public**
4. 點 `Create repository`

### 2. 上傳檔案
1. 在新建的 repo 頁面點 `uploading an existing file`
2. 把這五個檔案全部拖進去上傳
3. 點 `Commit changes`

### 3. 啟用 GitHub Pages
1. 進入 repo → `Settings` → 左邊選 `Pages`
2. Source 選 `Deploy from a branch`
3. Branch 選 `main`，資料夾選 `/ (root)`
4. 點 `Save`
5. 等約 1 分鐘，頁面會顯示你的網址：
   `https://你的帳號.github.io/toefl-hub/`

### 4. 手機安裝
1. 手機瀏覽器開啟上面的網址
2. **Android Chrome**：會自動跳出「新增至主畫面」提示，或點右上 ⋮ 選單 → 安裝應用程式
3. **iPhone Safari**：點分享按鈕 → 加入主畫面

安裝後桌面會出現 App 圖示，點開就像原生 App 一樣全螢幕使用！

## 使用方式
- 點 `＋` 新增練習頁面
- 輸入名稱（例如 `20260625-20260626`）
- 選擇 HTML 檔案或貼上原始碼
- 點「開啟」就能全螢幕使用該練習工具
- 所有資料儲存在手機瀏覽器的 localStorage，不會消失
