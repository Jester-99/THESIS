# THESIS (研海燈塔) - Tool for Holistic Editing and Scoring Information System

[![React](https://img.shields.io/badge/Frontend-React-blue.svg)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-green.svg)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen.svg)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**THESIS (研海燈塔)** 是一個專為學術論文撰寫量身打造的一體化平台。本專案結合了協作編輯、AI 輔助檢測、自動化 LaTeX 排版以及文獻推薦系統，旨在解決研究者在撰寫論文時面臨的格式繁瑣、文獻搜尋耗時以及 AI 依賴風險等痛點。

---

## 📖 專案背景與動機 (Background & Motivation)

撰寫論文是每位學生的關鍵考驗，但往往耗費大量精力在：
1. **文獻搜尋**：平均每篇論文需引用超過 40 篇文獻。
2. **格式排版**：超過 70% 的研究者認為遵循機構格式（標題、間距、引用格式）極其繁瑣。
3. **學術誠信**：在 AI 盛行的時代，如何確保文章的獨創性並避免過度依賴工具。

**THESIS (研海燈塔)** 透過整合政府開放資料與機器學習技術，提供一個流暢、直觀且高效的寫作環境。

---

## 🌟 核心功能 (Key Features)

### 1. 協作編輯平台 (Collaborative Editor)
*   基於 **Tiptap/ProseMirror** 的即時線上協作編輯器。
*   支援多人在線同時編輯，簡化團隊研究流程。

### 2. 研海燈塔 - 文獻推薦系統 (Literature Recommendation)
*   結合 **臺灣博碩士論文知識加值系統** 與 **NBINet (全國圖書書目資訊網)** 等開放資料。
*   利用機器學習技術，根據使用者輸入的內容或片段，自動推薦最相關的文獻、書籍及大學課程資訊。

### 3. AI 偵測與文章查核 (AI Detection & Analysis)
*   即時分析文章中疑似由 AI 生成的內容。
*   提供可信度百分比，並以紅字標註高風險句段，幫助維護學術獨創性。

### 4. 自動化 LaTeX 排版 (LaTeX Formatting Engine)
*   使用者只需專注於內容創作，系統自動套用 LaTeX 模板。
*   支援不同大學/機構的格式要求，快速產出符合規範的 PDF 文件。

### 5. 論文評分與改進建議 (Scoring & Feedback)
*   視覺化圖表呈現：AI 佔比、文章相似度、文獻引用情況。
*   提供具體的修改建議，優化論文質量。

### 6. AI 聊天機器人助手 (AI Chatbot)
*   提供操作指引與寫作建議，解決撰寫過程中的各類疑難雜症。

---

## 🚀 技術架構 (Technology Stack)

*   **前端 (Frontend)**: React.js, Tailwind CSS, Material UI, Vite
*   **後端 (Backend)**: Node.js, Express
*   **資料庫 (Database)**: MongoDB
*   **核心引擎**: Tiptap (編輯器), LaTeX (排版系統)
*   **開發方法**: Scrum 敏捷開發 (經歷 3 次 Sprint 迭代)

---

## 📂 專案成員 (Team Members)

*   **指導教授**: 張朝旭 博士
*   **團隊成員**: 黃柏瑜、陳盛茂、林士庭、羅珮綺、陳芊慈、李佳軒
*   **學術機構**: 國立聯合大學 資訊管理學系

---

## 📦 快速開始 (Getting Started)

1.  **安裝依賴**:
    ```bash
    npm install
    ```
2.  **啟動開發環境**:
    ```bash
    npm run dev
    ```
3.  **詳細文件**: 請參閱本倉庫中的 `Project_Documentation.docx`。

---

## 📜 免責聲明 (Disclaimer)

本系統所提供之文獻推薦與 AI 偵測結果僅供參考，使用者應自行對學術內容之準確性與原創性負責。

---
**開發商**: 研海燈塔開發團隊 (THESIS Team)  
**參考專案**: [oomao/Thesis](https://github.com/oomao/Thesis)
