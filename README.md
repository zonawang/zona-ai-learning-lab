# 🧪 Zona's AI Learning Lab 

歡迎來到我的 AI 探索與實作實驗室！這裡記錄了我與 AI 助理（Google Antigravity）攜手合作，從零開始打造、升級雲端應用程式的精彩歷程。

---

## 📅 專案進化歷程時間軸 (Chronological Project Timeline)

我們採用漸進式學習與開發，從最基礎的串接驗證，逐步演進至多模態大腦與高安全性雲端部署。以下是專案的演進軌跡：

```mermaid
gantt
    title 專案演進時間軸
    dateFormat  YYYY-MM-DD
    axisFormat  %b %d
    
    section 基礎奠定
    Echo Bot :active, p1, 2026-05-15, 5d
    
    section 智慧升級
    AI Bot :crit, p2, 2026-05-25, 5d
    
    section 記憶與代理
    Memory Bot :active, p3, 2026-06-02, 5d
    
    section 動態體驗
    Quick Reply :active, p4, 2026-06-08, 5d
    
    section 視覺極致
    Flex Message :active, p5, 2026-06-14, 5d
```

---

### 📍 🚀 第一站：LINE Echo Bot（基礎學舌鳥機器人）
> **起點：從零開始，快速驗證 LINE Messaging API 與雲端基礎串接。**

不懂程式、沒架過伺服器也能輕鬆起步！此專案記錄了如何在短短 20 分鐘內，透過與 AI 助理的完美協作，無痛部署一個穩健的 LINE 訊息回傳機器人。

*   **專案資源：**
    *   [![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/zonawang/line-echo-bot)
    *   [![Medium Article](https://img.shields.io/badge/Medium-Article-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@zonawang/%E4%B8%8D%E6%87%82%E7%A8%8B%E5%BC%8F%E4%B9%9F%E8%83%BD%E7%9C%8B%E6%87%82-%E6%88%91%E8%88%87-ai-%E5%8A%A9%E7%90%86%E6%94%9C%E6%89%8B-20-%E5%88%86%E9%90%98%E7%84%A1%E7%97%9B%E6%89%93%E9%80%A0%E9%9B%B2%E7%AB%AF-line-%E6%A9%9F%E5%99%A8%E4%BA%BA%E5%AF%A6%E9%8C%84-a8977432d84b)
*   **核心技術：**
    *   `LINE Messaging API` 核心對接
    *   `Google Apps Script (GAS)` 輕量級雲端託管
    *   `AI-Driven Development` 提示詞導向開發
*   **關鍵亮點：**
    *   **20 分鐘快速上線：** 透過對話式開發，免去繁瑣的本機開發環境設定。
    *   **零成本託管：** 善用 Google Apps Script (GAS) 部署為網頁應用程式（Web App），完全免費且高可用。
    *   **無痛除錯：** 示範如何直接將錯誤訊息丟給 AI 進行「對話式除錯（Conversational Debugging）」，打通開發瓶頸。

---

### 📍 🧠 第二站：LINE AI Bot（Gemini 2.5 多模態大腦與免密通關）
> **進階：賦予機器人視覺與智慧，並引進企業級的安全認證架構。**

從「學舌鳥」到「看圖說故事」！僅花費 15 分鐘，便將原本的 Echo Bot 進行脫胎換骨的升級，引入強大的 Gemini 2.5 多模態大型語言模型，並完美實踐雲端免密碼（Passwordless/Secretless）安全整合。

*   **專案資源：**
    *   [![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/zonawang/line-ai-bot)
    *   [![Medium Article](https://img.shields.io/badge/Medium-Article-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@zonawang/%E7%BA%8C%E9%9B%86-%E5%BE%9E%E5%AD%B8%E8%88%8C%E5%88%B0%E7%9C%8B%E5%9C%96%E8%AA%AA%E6%95%85%E4%BA%8B-%E6%88%91%E8%88%87-ai-%E5%8A%A9%E7%90%86-15-%E5%88%86%E9%90%98%E5%B0%87-line-bot-%E5%8D%87%E7%B4%9A-gemini-2-5-%E5%A4%9A%E6%A8%A1%E6%85%8B%E5%A4%A7%E8%85%A6%E8%88%87%E5%85%8D%E5%AF%86%E9%80%9A%E9%97%9C%E5%AF%A6%E9%8C%84-9fe9c64d1ea2)
*   **核心技術：**
    *   `Google Gemini 2.5 Flash / Pro` 多模態大型語言模型
    *   `LINE Message Event Handler` 圖像與音訊等多媒體處理
    *   `Secretless Authentication / Workload Identity` 雲端免密通關安全架構
*   **關鍵亮點：**
    *   **15 分鐘極速升級：** 示範如何快速導入強大的 AI 大腦，讓機器人不僅能聊天，還能「讀懂圖片並說故事」。
    *   **多模態處理能力：** 完整實作圖片、文字等多樣化格式輸入的解析，讓互動體驗大幅精進。
    *   **企業級免密通關：** 揚棄在程式碼中寫死（Hardcode）密鑰的危險做法，改採進階的免密安全機制（如 IAM / Workload Identity / Secret Manager 等方式），兼顧開發速度與資安規範。

---

### 📍 🔮 第三站：LINE Memory Bot（長效記憶占星水晶專家）
> **登峰：融合 Agent 框架、永久雲端記憶與多模態分析，打造有溫度的長效智慧助理。**

為了解決雲端 Serverless（如 Cloud Run）無狀態容器重啟導致對話記憶消失的問題，本專案引進了 Google 最新的 **ADK (Agent Development Kit)** 智慧代理框架，並首創自製的中繁體中文記憶體檢索匹配器，將使用者的每一次對話、星盤與水晶特徵永久刻在 **Cloud Firestore**。

*   **專案資源：**
    *   [![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/zonawang/line-memory-bot/tree/main)
    *   [![Medium Article](https://img.shields.io/badge/Medium-Article-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://reurl.cc/qpRD2y)
*   **核心技術：**
    *   `Google ADK (Agent Development Kit)` 與 `PreloadMemoryTool`
    *   `Google Cloud Firestore` 永久雲端資料庫（`ChineseFirestoreMemoryService`）
    *   `Vertex AI Gemini 2.5 Flash` 多模態影像解析
    *   `Node.js 22` 混血模組相容啟動旗標（`--experimental-require-module`）
*   **關鍵亮點：**
    *   **記憶預載（PreloadMemoryTool）**：只需一行程式碼，在每次對話啟動時自動預載使用者的歷史互動與生日星盤設定。
    *   **獨家中文分詞修補（Chinese Word Segmentation Regex Patch）**：徹底解決 ADK 內建 `InMemoryMemoryService` 僅支援英文分詞的 Bug，實作中繁體中文漢字與占星高頻詞彙的匹配器。
    *   **多模態影像鑑定**：傳送水晶礦石照片，機器人自動轉為 Base64 並透由 Vertex AI Gemini 2.5 Flash 鑑定其脈輪與五行共振特徵。
    *   **長效記憶整合**：在隔了幾天後對話，機器人仍能根據 Firestore 的持久記憶，記住您的生日、星座以及上次傳送的水晶照片特徵，給出高度客製化的諮詢回覆。
    *   **全免密雲端部署**：安全託管於 **Google Cloud Run**，利用 IAM / 應用程式預設憑證（ADC）安全存取 Google 資源，免除硬編碼 API 金鑰的安全漏洞。

---

### 📍 💬 第四站：LINE Quick Reply Bot（動態追問建議與極致對話體驗）
> **精進：根據上下文動態預測使用者下一步，提升互動體驗。**

讓對話更自然、更流暢！本專案的核心在於實現「動態追問機制」，捨棄傳統死板的靜態按鈕選單，由 Gemini 2.5 Flash 在生成對話回答的當下，即時預測最符合當前語境的 3 個第一人稱追問問題，並自動轉換成 LINE 鍵盤上方的 Quick Reply 建議按鈕。

*   **專案資源：**
    *   [![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/zonawang/line-quick-reply/tree/main)
    *   [![Medium Article](https://img.shields.io/badge/Medium-Article-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/p/c4dba34cad43)
*   **核心技術：**
    *   `Google ADK (Agent Development Kit)` 智慧代理與 PreloadMemoryTool
    *   `Gemini 2.5 Flash` 單回合多目標生成 (回答與追問建議預測)
    *   `LINE Messaging API` 快速回覆鍵盤機制 (`quickReply`)
    *   `Google Cloud Firestore` 永久對話記憶（`ChineseFirestoreMemoryService`）
*   **關鍵亮點：**
    *   **智慧動態追問 (Dynamic Suggestions)**：在對話過程中，由 AI 即時預測並生成 3 個第一人稱的追問選項，點擊即送出，完美契合語境並大幅提升使用者的互動率。
    *   **單回合零額外成本與延遲**：利用 Prompt 精妙設計，指示 Gemini 在回答最後以 `|||` 與 `|` 作為分隔格式，同時生成主回答與建議問題。後端僅需調用一次 API 即可解析完成，兼顧極速效能與控本效益。
    *   **20 字元字數限制過濾**：自動化對接 LINE 官方對 Quick Reply Label 的 20 字元上限。透過 Prompt 雙重約束及後端程式碼字符限制，防範因字數過長被系統截斷的難堪情形。
    *   **智慧 Fallback 機制**：當 LLM 的輸出格式未符預期或分隔符遺漏時，系統將自動套用預設高頻追問按鈕，確保使用者對話歷程在任何極端狀況下皆順暢無阻。

---

### 📍 ✨ 第五站：LINE Flex Message Bot（動態隨機推薦與極致視覺卡片）
> **突破：打造奢華、具互動性的高階 Flex Message，讓對話視覺感拉滿。**

視覺震撼！本專案旨在將互動視覺效果直接拉到極致，設計多款符合現代奢華感、文青風格的高階 Flex Message 卡片，並融入動態隨機洗牌演算機制，給予使用者最尊榮的視覺與互動體驗。

*   **專案資源：**
    *   [![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/zonawang/line-flex-message)
    *   [![Medium Article](https://img.shields.io/badge/Medium-Article-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://reurl.cc/qpeq73)
*   **核心技術：**
    *   `LINE Messaging API` 氣泡卡片與輪播展示大廳（`Flex Message Carousel`）
    *   `Fisher-Yates 隨機洗牌演算法`（確保每次觸發不重複隨機提取 3 款卡片）
    *   `Google ADK (Agent Development Kit)` 智慧大腦與 Firestore 記憶整併
    *   `Express` Webhook 精準關鍵字前綴分流（`#水晶` 精準觸發與普通對話分流）
*   **關鍵亮點：**
    *   **奢華視覺三大高階範本**：預建精緻細調的「極簡莫蘭迪數位名片 (Glassmorphism Digital Card)」、「星宇極致登機證 (Luxury Boarding Pass)」與「日系文青下午茶菜單 (Cafe Specialty Menu)」，排版與色彩搭配達到極致美感。
    *   **Fisher-Yates 隨機不重複推薦**：內建七款能量水晶資料庫。透過 Fisher-Yates 洗牌演算法，使用者每次輸入關鍵字時皆能動態獲得 3 款隨機且絕不重複的 Micro-Carousel 精美水晶圖卡。
    *   **雙重大腦合一與防干擾分流**：全面移植了前幾代專案的 ADK 智慧代理、Firestore 永久記憶與 Gemini 多模態影像解析大腦。同時巧妙設計 `#水晶` 前綴觸發 Flex Message，其餘普通關鍵字與照片上傳則無縫交給 AI 占星師大腦進行流暢對話，互不干擾。
    *   **本地端權限衝突繞過**：針對 npm install 快取目錄鎖定問題，提供優雅的 `--cache ./.npm-cache` 專案內隔離快取技術，免除不安全的 sudo 權限要求。

---

## 🛠️ 實驗室技術雷達 (Tech Stack Radar)

在本實驗室中，我們廣泛運用並實踐了以下技術棧：

| 領域 | 採用技術與服務 |
| :--- | :--- |
| **通訊渠道 (Messaging)** | LINE Messaging API, Rich Menu, Flex Message (Carousel), Quick Reply, Blob API |
| **人工智慧 (AI/LLM)** | Google ADK, PreloadMemoryTool, Gemini 2.5 Multimodal (Flash/Pro) |
| **雲端部署 (Deployment)** | Cloud Run, Google Apps Script, Vercel / Render |
| **資料記憶 (Database/Memory)**| Cloud Firestore, ChineseFirestoreMemoryService (中文分詞檢索) |
| **資訊安全 (Security)** | Application Default Credentials (ADC), IAM, Secretless Auth |
| **開發語言與環境** | Node.js 22 (--experimental-require-module), ESM/CJS |
| **輔助開發 (AI Copilot)** | Cursor, ChatGPT, Claude |

---

## 🤝 聯絡與社群

如果您對 AI 輔助開發、LINE Bot 實作或多模態應用有興趣，歡迎隨時透過以下渠道與我交流！

- **Medium 部落格：** [@zonawang](https://medium.com/@zonawang)
- **GitHub 主頁：** [zonawang](https://github.com/zonawang)
