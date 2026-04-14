# 北大法研社 財務概覽

互動式財務收支圓餅圖，部署於 GitHub Pages，可嵌入 Notion。

## 🚀 部署步驟

### 1. 建立 GitHub Repo
```bash
git init pku-law-finance
cd pku-law-finance
```

### 2. 放入檔案
將 `index.html` 放入根目錄。

### 3. 推送到 GitHub
```bash
git add .
git commit -m "feat: add finance overview charts"
git branch -M main
git remote add origin https://github.com/<你的帳號>/pku-law-finance.git
git push -u origin main
```

### 4. 啟用 GitHub Pages
1. 進入 repo → **Settings** → **Pages**
2. Source 選 **Deploy from a branch**
3. Branch 選 `main`，資料夾選 `/ (root)`
4. 點 Save，等待幾分鐘部署完成
5. 你的網址：`https://<你的帳號>.github.io/pku-law-finance/`

### 5. 嵌入 Notion
1. 在 Notion 頁面輸入 `/embed`
2. 貼上 GitHub Pages 網址
3. 完成！圓餅圖將即時渲染在 Notion 中

## 📊 圖表內容

**收入結構**
| 項目 | 比例 |
|------|------|
| AI、Notion 授權費 | 60% |
| 法學研究、出版 | 10% |
| 其他收入 | 30% |

**支出結構**
| 項目 | 比例 |
|------|------|
| AI API 維護費與獎學金 | 25% |
| 法學活動 | 75% |

## 🛠 技術
- 純 HTML/CSS/JS，無框架依賴
- SVG 動態圓餅圖，支援 hover 互動
- 深色主題，適配 Notion embed

---
*由 Claude AI 自動生成*
