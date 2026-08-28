# Eryndex 智序科技｜Tactile Grid Field Manual

這是 Eryndex 智序科技的**全新獨立網站版本**，與原本的 `eryndex-corporate-site` 分開維護。原網站、原網址與原 Git 歷史保持不變；本專案只沿用公司名稱與四項產品名稱，視覺、版面、品牌資產、標題、互動、動效與製作說明全部重新設計。

## New visual direction

Tactile Grid Field Manual 將企業 AI 系統想像成可被校準的工作台，使用礦物象牙白、深墨綠、訊號綠與銅紅，搭配工業編輯排版、紙張與機械材質、校準網格與現場手冊標籤。它刻意避開原版本的深色 Signal Atelier 與 Luminous Operations Journal 語彙，方便主管進行真正的方向比較。

## Product system

| Product | Focus |
|---|---|
| Qadryn | AI workflow automation |
| Vessyra | Data security and access control |
| Mireqon | Operational intelligence |
| Terviq | On-premise AI edge computing |

產品內容、三語文案與核心功能維持既有版本，讓比較重點集中在新品牌與介面設計。

## Experience architecture

首頁、About、Products、Solutions、Resources、Contact 與製作說明均保留單頁 modal 架構、固定關閉控制、背景點擊關閉與 Escape 鍵路徑，但所有視覺表達已改為 Tactile Grid：紙面工作台、校準網格、現場標籤、方形節點、深色系統區塊與銅紅操作標記。

## Stack and quality scope

React 19、TypeScript、Vite、Tailwind CSS 4、Wouter、Lucide React、CSS／SVG motion，以及 GitHub Actions + GitHub Pages。網站支援繁體中文、簡體中文與 English，並保留可見 focus、語意 HTML、表單提示、圖片替代文字、reduced-motion 與不依賴單一顏色的資訊表達。這是實作範圍紀錄，不宣稱已完成正式 WCAG 一致性稽核。

## Version separation

原網站 repository：<https://github.com/k129453497-byte/eryndex-corporate-site>

本新版本 repository：<https://github.com/k129453497-byte/eryndex-tactile-systems>

本新版本 GitHub Pages：<https://k129453497-byte.github.io/eryndex-tactile-systems/>

兩個版本使用不同的 GitHub Pages URL；新版本的任何調整不會覆蓋原版本。

## Local development

```bash
pnpm install
pnpm dev
```

Production build：

```bash
pnpm check
pnpm build
```

GitHub Pages workflow 會在 `main` 更新時自動建置並發布。聯絡表單為前端互動示範，未連接 CRM 或後端資料庫；網站中的聯絡資訊、文章與成果描述均為示範內容，不捏造真實客戶、評價或未證實數據。
