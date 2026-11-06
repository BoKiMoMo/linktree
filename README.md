# linktree

石楷賢 Chris Shih（技術產品經理）的個人連結頁與作品集入口，概念類似 Linktree：一頁整理個人簡介、作品集 PDF 與各平台連結。

## 內容

| 檔案 | 說明 |
|---|---|
| `index.html` | 整個網站（單一頁面） |
| `avatar.png` | 大頭照 |
| `Logo_background_1.png`、`Logo_background_2.png` | 背景浮水印圖騰 |
| `Portfolio_Chris_Shih_TPM.pdf` | 作品集 PDF |

## 技術

- 純靜態 HTML，沒有建置流程
- Tailwind CSS（CDN）、Font Awesome、Google Fonts（Noto Sans TC／Noto Serif TC／Cinzel Decorative）
- Vanilla Tilt 3D 傾斜效果、Canvas 粒子背景
- 已設定 SEO 與 Open Graph 標籤，分享連結時會顯示標題與描述

## 本機預覽

直接用瀏覽器開啟 `index.html` 即可。如果想用本機伺服器：

```bash
python -m http.server 8000
```

然後開啟 <http://localhost:8000>。

## 部署

因為是純靜態檔案，可以直接用 GitHub Pages 等靜態網站服務發布 `main` 分支的根目錄。

## 待辦

- `og:image` 目前還是 placeholder 圖片，可以換成正式的分享預覽圖。
