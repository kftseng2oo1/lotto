# 大樂透開獎機 PWA

7×7=49 全程不重複大樂透開獎系統

## 功能
- 🎱 49 顆共用球池，7 組全程不重複
- 🔊 物理音效模擬 + TTS 語音播報
- 💾 localStorage 自動儲存
- 📊 報告 + Excel 匯出（4 個 Sheet）
- ✨ 彩色動畫 + 特別號紫色閃爍
- 📱 PWA 可安裝至手機桌面（離線可用）

## 部署到 GitHub Pages

```bash
git init
git add .
git commit -m "初始化大樂透 PWA"
git branch -M main
git remote add origin https://github.com/你的帳號/lotto.git
git push -u origin main
```

然後到 GitHub → Settings → Pages → Source 選 `main` 分支即可。

## 檔案說明
- `index.html` — 主程式（含 PWA manifest、Service Worker、icon 全部內嵌）
- `icon.svg` — 原始 SVG 圖示
- `icon-192.png` / `icon-512.png` — PWA 圖示
- `apple-touch-icon.png` — iOS 桌面圖示

## 安裝 PWA
- **iOS**：Safari 開啟 → 分享 → 加入主畫面
- **Android**：Chrome 開啟 → 選單 → 安裝應用程式
