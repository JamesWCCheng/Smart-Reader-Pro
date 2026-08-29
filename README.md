# 🎓 SAT Smart Reader Pro v2.5 (AI-Powered English Tutor)

**SAT Smart Reader Pro** 是一個全端式英語學習 Web App，旨在成為您最強大的 **AI 虛擬家教**。

v2.5 版本帶來了 **「模型推薦升級」**、**「首頁 UI 精簡」**、**「Top 5 熱門話題推薦」** 與 **「LINE 3 則專屬訊息分享系統」**。現在您可以一鍵挑選最新時事熱門話題，並在完成挑戰後將成績單、文章全文、文法詳解與單字卡分 3 則訊息無縫發送給 LINE 好友！

本專案採用 **單一 HTML 架構 (Single File Application)**，無需安裝任何環境、無需後端資料庫，下載後直接用瀏覽器開啟即可開始學習！

---

## ✨ v2.5 重大更新 (New in v2.5)

### 🤖 1. 模型選取最佳化 (Model Optimization)
* **🏆 首選推薦 Gemini 2.5 Flash**：生成速度極快（約 3-5 秒）、繁體中文文法與單字解析最精確、考題結構完整，最適合日常 SAT 練習。
* **🧠 支援 Gemini 2.5 Pro / 2.0 Flash**：滿足深度思考或極速生成等不同需求。
* **🔍 自動模型探索與診斷**：一鍵測試 API Key 並自動探索最新可用模型，動態設置最佳推薦。

### 🎨 2. 首頁 UI 升級 (Clean UI Polish)
* **🚫 移除骰子 (Dice) 限制**：簡化流程，直接提供 **文章篇幅選擇器**（簡短 Short ~250字 / 標準 Medium ~500字 / 長篇 Long ~800字）。
* **📚 年級難度從 Grade 8 起跳**：移除 Grade 7，專注提供 Grade 8（Pre-SAT）至 Grade 12（進階挑戰）的高強度 SAT 閱讀訓練。
* **⚡ 一鍵直接生成**：填入金鑰與主題即可直接點擊生成，操作更加直覺順暢。

### 🔥 3. 今日即時熱門話題 Top 5 (Live Web RSS Fetching)
* **🌐 網路即時連線抓取**：打開網頁自動連線抓取 **ESPN NBA、BBC Science、BBC World、CNN Tech、Phys.org Earth** 的最新英文頭條。
* **🟢 LIVE 即時狀態指示**：卡片上即時顯示新聞來源標籤（如 `ESPN NBA • 即時`、`BBC Science • 即時`）與即時摘要。
* **點擊即選**：首頁直覺式卡片，點擊任一熱門新聞即可直接選取該最新時事生成專屬考卷。
* **🔄 即時換一批**：點擊一鍵換一批，動態輪播該新聞頻道的下一則最新時事頭條。
* **🛡️ 智慧備援機制**：若遇網路延遲或斷線自動切換至高頻精選庫，確保 100% 穩定不卡頓。

### 💬 4. LINE 3 則專屬訊息分享 (LINE 3-Message Sender)
* **分 3 則訊息格式化發送**：
  * **📊 第 1 則【測驗成績與閱讀文章】**：包含總得分、Rank 稱號、難度等級、文章標題、3 大核心重點 (Takeaways) 與全文。
  * **🔍 第 2 則【文法核心解析】**：包含精選英文焦點句型與繁體中文深度詳解。
  * **🗂️ 第 3 則【核心單字記憶卡】**：包含 6 個核心單字之詞性、繁中翻譯、英文定義與實戰例句。
* **多元傳送方式**：
  * 🟢 **LINE App 一鍵轉傳**：各則訊息獨立綠色按鈕，直接喚起 LINE App 發送給特定好友。
  * 🤖 **LINE Messaging API 直傳模式**：設定 Channel Token 與 Target User ID，一鍵自動推送 3 則訊息。
  * 📋 **快速複製與預覽**：支援各則獨立複製與一鍵複製全部 3 則訊息。

---

## 🚀 核心特色 (Core Features)

### 🤖 智慧課程生成
* **即時新聞導入**：內建 RSS 串接功能，可即時抓取 CNN、BBC、ESPN、National Geographic 或 The Economist 的最新頭條作為學習素材。
* **自訂主題模式**：想讀什麼就讀什麼！輸入任何關鍵字，AI 立即為您撰寫專屬文章。
* **雙語深度解析**：文章與題目為全英文，所有單字定義、文法解析與詳解皆提供 **繁體中文 (台灣)** 對照。
* **🧠 AI 智能總結**：考完試後，AI 會自動評估文章難度 (Lexile/CEFR) 並歸納 3 大核心重點 (Takeaways)。

### 🎮 遊戲化互動學習 (Gamification)
* **🏔️ 登山者進度條 (Mountain Tracker)**：獨創的置頂進度條，答對前進、答錯後退，視覺化攻頂之路！
* **🔥 連擊系統 (Combo)**：連續答對題目可累積 Combo 加成，配合火焰特效與音效，激發成就感。
* **🎵 動態音效回饋**：內建 Web Audio API 合成音效，答對時悅耳、答錯時警示，並伴隨畫面震動與彩帶特效。

### 📚 專業學習工具箱
* **📖 權威字典整合**：單字卡內建 **Cambridge Dictionary** 直連按鈕，一鍵查詢權威例句與發音。
* **🗣️ 多國口音朗讀**：內建懸浮播放器，支援切換 **🇺🇸 美式 / 🇬🇧 英式 / 🇦🇺 澳式** 口音。
* **📋 點擊即查 (Click-to-Copy)**：閱讀時點擊任意單字，系統會自動朗讀並將單字複製到剪貼簿。

---

## 🚀 快速開始 (Getting Started)

### 方式一：建立新課程
1. **開啟網頁**：直接雙擊 `index.html` 用瀏覽器開啟（推薦 Chrome / Edge）。
2. **輸入金鑰**：在設定面板貼上您的 **Google Gemini API Key**。
3. **選擇主題**：點擊首頁「今日熱門推薦」或選擇新聞頻道 / 自訂主題。
4. **開始生成**：選擇篇幅長度，按下「開始生成課程」。

### 方式二：接受朋友挑戰
1. 取得朋友傳來的 **.json 挑戰檔**。
2. 在首頁點擊 **"選擇檔案 (.json)"**。
3. 系統將自動載入課程，直接開始挑戰！

---

## 🔑 如何取得 Google Gemini API Key (免費)

本程式使用 Google 的 AI 模型，您需要一組免費的 API Key：

1. 前往 [Google AI Studio](https://aistudio.google.com/)。
2. 登入您的 Google 帳號。
3. 點擊左上角的 **"Get API key"** -> **"Create API key"**。
4. 複製 `AIza` 開頭的字串，貼入本程式即可。

> **隱私聲明**：您的 API Key 僅儲存在您電腦瀏覽器的 `localStorage` 中，直接與 Google 伺服器溝通，**絕不** 會傳送給任何第三方伺服器，請安心使用。

---

## 🛠️ 技術堆疊 (Tech Stack)

* **Frontend**: Pure HTML5, JavaScript (ES6+).
* **Styling**: Tailwind CSS (CDN) - RWD & Modern Design.
* **AI Engine**: Google Gemini API (`gemini-2.5-flash` / `gemini-2.5-pro` / `gemini-2.0-flash`).
* **Integration**: LINE URL Scheme & LINE Messaging API.
* **External Libraries**:
  * `FontAwesome`: UI Icons.
  * `Canvas Confetti`: Visual effects.
  * `HTML2Canvas`: 學習成果截圖。
  * `RSS2JSON`: 即時新聞來源串接。

---

## 🔗 關於專案 (About)

* **Project:** SAT Smart Reader Pro
* **Version:** 2.5.0 (Model Upgrade, Hot Topics & LINE Share Edition)
* **Author:** James Cheng
* **GitHub Repository:** [https://github.com/JamesWCCheng/Smart-Reader-Pro](https://github.com/JamesWCCheng/Smart-Reader-Pro)