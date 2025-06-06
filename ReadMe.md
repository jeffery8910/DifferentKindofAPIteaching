# **🚀 互動式 API 學習之旅 \- Readme**

歡迎來到「互動式 API 學習之旅」！這是一個使用 HTML、Tailwind CSS 和純 JavaScript 打造的單頁面互動式教學網站，旨在幫助初學者以有趣和實用的方式理解 API 的核心概念和不同的設計典範。

## **✨ 專案特色**

* **現代化設計風格：** 採用 Neo 感毛玻璃風格 (Neo-brutalist Glassmorphism)，提供美觀且具現代感的視覺體驗。  
* **分頁式教學：** 內容組織在不同的分頁中，方便使用者逐步學習：  
  * 🤔 什麼是 API？  
  * 📚 API 典範概覽  
  * 🛠️ REST API 實戰  
  * ✨ GraphQL API 體驗  
  * 🔔 WebHooks 即時通  
  * 📞 RPC 概念  
* **卡片式排版：** 大部分教學內容採用卡片式佈局，使資訊呈現更清晰、更易於閱讀。  
* **互動小遊戲：** 針對 REST API、GraphQL 和 WebHooks 設計了簡單的互動小遊戲，讓使用者可以動手操作，加深理解。  
* **API 模擬器：** 為 REST、GraphQL、WebHooks 和 RPC (HTTP-based) 提供了模擬器，使用者可以嘗試定義請求參數，並觀察模擬的 API 請求和回應格式。  
* **即時回饋：** 在小遊戲中，系統會對使用者的答案提供即時的正確或錯誤提示。  
* **純前端實現：** 所有互動和模擬功能均在前端透過 JavaScript 實現，無需後端伺服器，方便本地運行和學習。

## **🛠️ 使用技術**

* **HTML5:** 網頁基本結構。  
* **Tailwind CSS:** 用於快速建構現代化 UI 的 CSS 框架。  
* **JavaScript (ES6+):** 實現所有互動邏輯、遊戲機制和 API 模擬功能。  
* **Google Fonts (Inter):** 提供美觀的字體。

## **🚀 如何使用**

1. **下載檔案：** 將專案的 HTML 檔案（例如 api\_interactive\_tutorial.html）儲存到您的電腦上。  
2. **開啟網頁：** 使用任何現代網頁瀏覽器（如 Chrome, Firefox, Edge, Safari）開啟這個 HTML 檔案。  
3. **開始學習：**  
   * 點擊頂部的分頁按鈕來切換不同的學習主題。  
   * 閱讀每個分頁的介紹文字。  
   * 參與「小遊戲」部分，嘗試回答問題或進行操作。  
   * 使用「模擬器」部分，輸入不同的參數，觀察產生的 API 請求和回應。

## **📄 分頁內容概覽**

1. **🤔 什麼是 API？**  
   * 以餐廳點餐的生動比喻解釋 API 的基本概念。  
   * 使用卡片式佈局呈現核心比喻和 API 的重要性（模組化、重複使用、整合、創新）。  
2. **📚 API 典範概覽**  
   * 介紹請求-回應 API (REST, GraphQL, RPC) 和事件驅動 API (WebHooks, WebSockets) 的主要分類。  
   * 每個典範以獨立的卡片形式呈現，包含簡要描述和前往對應實戰分頁的按鈕。  
3. **🛠️ REST API 實戰**  
   * **卡片一：小遊戲 \- 設計你的訂單 API**  
     * 引導使用者為常見的訂單操作（獲取列表、建立、獲取特定）選擇正確的 HTTP 方法和設計 URL 路徑。  
   * **卡片二：REST API 模擬器**  
     * 允許使用者定義資源名稱、HTTP 方法、路徑參數和請求內容，模擬產生 HTTP 請求和回應。  
4. **✨ GraphQL API 體驗**  
   * **卡片一：小遊戲 \- 構建你的電影查詢**  
     * 讓使用者勾選想查詢的電影欄位，動態產生 GraphQL 查詢語句和模擬回應。  
   * **卡片二：GraphQL 模擬器**  
     * 提供文字區域讓使用者手動輸入 GraphQL 查詢，並顯示模擬回應。  
5. **🔔 WebHooks 即時通**  
   * **卡片一：小遊戲 \- 設定您的 WebHook 監聽器**  
     * 讓使用者輸入模擬的 WebHook URL，模擬一個「訂單已發貨」事件的 POST 請求。  
   * **卡片二：WebHook 模擬器**  
     * 允許使用者定義事件類型、Payload 和目標 URL，模擬觸發 WebHook。  
6. **📞 RPC 概念**  
   * **卡片一：RPC 概念介紹**  
     * 解釋 RPC 的核心概念、特點以及一個簡單的 HTTP POST RPC 請求/回應範例。  
   * **卡片二：RPC 模擬器 (HTTP-based)**  
     * 允許使用者定義服務名稱、方法名稱和參數，模擬產生基於 HTTP POST 的 RPC 風格請求和回應。

希望這個互動式教學網站能幫助您更好地理解 API！
