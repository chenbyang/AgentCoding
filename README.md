# AgentCoding - 個人 GitHub 專案展示網頁

這是一個為 **[chenbyang](https://github.com/chenbyang)** 量身打造的 GitHub 個人專案與儲存庫展示網頁。本專案透過動態串接 GitHub API，即時呈現所有的公開專案，並提供流暢且極具現代美感的互動介面。

👉 **[立即線上預覽成果 🌐](https://chenbyang.github.io/AgentCoding/)**

---

## ✨ 設計與互動亮點

- **🌌 動態 Canvas 粒子背景**：利用 HTML5 Canvas 繪製隨機漂浮的星空粒子，粒子間會根據距離自動產生微弱連線，且會對滑鼠游標產生排斥與推移效果，增添互動沉浸感。
- **🔮 玻璃擬態風格 (Glassmorphism)**：採用現代 UI 最流行的半透明毛玻璃面板設計，結合暗黑漸層底色與柔和光暈，呈現極致質感的視覺美學。
- **📐 3D 卡片懸浮傾斜 (3D Card Tilt)**：當滑鼠游標移至專案卡片時，卡片會自動跟隨游標進行 3D 空間旋轉，並在游標碰觸處產生邊框漸層發光（Glow Effect）。
- **⚡ 即時 API 串接與過濾**：
  - **即時搜尋**：輸入關鍵字立即過濾專案名稱或描述。
  - **多維度排序**：支援「最近更新」、「最多 Stars」、「最多 Forks」與「名稱 A-Z」排序。
  - **語言自動過濾**：動態解析所有儲存庫的程式語言，生成彩色語言標籤供一鍵篩選。
  - **Fork 隱藏開關**：提供切換開關，預設隱藏 fork 的專案以突顯個人原創作品。
- **🛡️ 5 分鐘快取優化 (LocalStorage Cache)**：網頁會將 API 請求快取 5 分鐘，避免頻繁重新整理網頁時因觸發 GitHub 的 API Rate Limit 而導致頁面空白。

---

## 🛠️ 技術堆疊

- **結構 (HTML)**：HTML5 語意標籤
- **樣式 (CSS)**：Vanilla CSS, CSS 變數系統, Backdrop Filter, Keyframes 動畫
- **邏輯 (JS)**：原生 JavaScript (ES6+), Canvas API, Fetch API, LocalStorage Cache

---

## 📂 檔案目錄結構

- `index.html`：整合了所有 HTML 結構、CSS 樣式與 JavaScript 互動邏輯的單檔案，方便透過 GitHub Pages 進行極速部署。
- `README.md`：專案說明文件（本檔案）。
