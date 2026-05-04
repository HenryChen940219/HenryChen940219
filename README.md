<div align="center">

# 陳紀宇 Chi-Yu, Chen

**東吳大學 資料科學系 ｜ 行動開發 × 資安研究 × 資料科學 × 全端開發**

[![GitHub followers](https://img.shields.io/github/followers/HenryChen940219?style=flat&color=6366f1)](https://github.com/HenryChen940219)
[![Email](https://img.shields.io/badge/Email-cchen7393%40gmail.com-f97316?style=flat&logo=gmail&logoColor=white)](mailto:cchen7393@gmail.com)

</div>

---

## 關於我

目前就讀東吳大學資料科學系，涵蓋從行動應用（AR、遊戲開發）、LLM 資安研究、雲端全端開發，到量化金融與自然語言處理的多元實作經驗。熱衷於將生成式 AI、機器學習與雲端技術落地於真實場景，並持續探索 AI 安全的前沿議題。

執行**國科會大專生研究計畫**（NSTC 114-2813-C-031-057-E），研究成果已發表於 **TCSE 2025（台灣軟體工程研討會）**，並獲 AI-MetaACES 2026, APSCE TBICS Festival of Learning 2026 錄取。

---

## 專案

### AI × AR 教育科技

#### [ARAssistant — AI 虛擬學習助理與 AR 引導式概念圖學習系統](https://github.com/HenryChen940219/unity-ai-learning-system)

> 國科會大專生研究計畫 NSTC 114-2813-C-031-057-E ｜ 東吳大學資料科學系

結合**擴增實境（AR）** 與 **Gemini 生成式 AI**，開發應用於物聯網課程的行動學習平台。以運算思維四步驟為核心，透過 3D AI 虛擬助理引導學生完成概念構圖，並以 AR 技術將數位提示疊映於實體學習單，打造虛實整合的沉浸式學習體驗。

實驗驗證學習動機（p = 0.007）、運算思維傾向（p = 0.022）均顯著提升。

`Unity` `Vuforia` `Gemini API` `Firebase` `Google Cloud STT/TTS` `C#` `Android`

---

### 金融科技

#### [因子投資 × 機器學習 — 台灣股市多空組合策略](https://github.com/HenryChen940219/factor-investing-ml-taiwan)

> 金融科技創新與應用課程期末專案

以規模、帳面市值比、動能三大量化因子的 IC 時間序列為輸入，訓練 OLS、隨機森林、神經網路（NN1–NN5）、XGBoost、LSTM 等 9 種模型預測下一期 IC，並據此建構多空投資組合，比較各模型在台灣股市（900+ 檔，1999–2025）的選股績效。

[![Tableau Dashboard](https://img.shields.io/badge/Tableau-互動式儀表板-blue?logo=tableau)](https://public.tableau.com/views/ML_17778235978420/sheet3)

`Python` `scikit-learn` `XGBoost` `TensorFlow/Keras` `LSTM` `Pandas` `Tableau`

---

#### [金融科技與智能交易 — 台股高漲幅事件預測](https://github.com/HenryChen940219/tw-stock-prediction-text-mining)

> 金融科技與智能交易課程期末專案

利用文字探勘（TF-IDF）與資料重採樣（SMOTETomek）技術，結合 OCSVM、CNN、隨機森林三種模型，預測台灣個股（台積電、緯創、金像電、奇鋐）的高漲幅事件。採 Walk-Forward Validation 回測，以勝率與累積報酬率評估策略績效。

`Python` `scikit-learn` `TF-IDF` `SMOTETomek` `OCSVM` `CNN` `yfinance` `鉅亨網 API`

---

### 資安研究

#### [RAGPen — RAG 應用程式自動化安全評估框架](https://github.com/HenryChen940219/ragpen)

> RAGPen 之於 RAG 系統，猶如 Burp Suite 之於網頁應用程式

第一個將**完整 RAG Pipeline** 視為滲透目標的自動化紅隊框架，跨三種攻擊向量（PII 洩漏、憑證洩漏、間接 Prompt Injection）對整個系統進行探測，並自動生成 OWASP LLM Top 10 對齊的安全報告。附帶刻意設計有漏洞的 HR RAG 靶機系統（50 份文件）供即時示範。

`Python` `Gemini API` `FastAPI` `OWASP LLM Top 10` `LLM Security` `RAG`

---

### 雲端與全端開發

#### [AI 智慧工具平台 — Azure 多功能 AI 網頁應用](https://github.com/HenryChen940219/azure-project)

整合 **6 項 AI 功能**、串接 **9 項 Azure 服務**的多功能網頁應用，功能涵蓋：圖片語音翻譯、文字情緒分析、PDF 摘要、OCR 文字擷取、地址地圖定位、GPT 健康餐點推薦，並以 Docker 容器化部署至 Azure Container Instance。

`Python` `Flask` `Docker` `Azure OpenAI` `Azure Computer Vision` `Azure Speech` `Azure Maps` `Azure Blob Storage`

---

#### [健身工作坊 Fitness Workshop — 全端健身房網站](https://github.com/HenryChen940219/sqlite-project)

以 Node.js + SQLite 為後端、Vanilla HTML/CSS/JS 為前端的完整健身房網站。功能包含課程瀏覽、器材購買、購物車（含折扣碼）、會員系統（bcrypt 加密）、VIP 升級機制與問卷回饋系統。

`Node.js` `Express.js` `SQLite` `bcryptjs` `HTML/CSS/JS` `express-session`

---

### 資料科學

#### [PTT 情感分析系統 — 批踢踢論壇 NLP 分析](https://github.com/HenryChen940219/ptt-sentiment-analysis)

> 資料分析期末專題

爬取 PTT 六大版面文章，結合 OpenCC 繁簡轉換與 SnowNLP 情感分析，對文字進行正面／負面／中立三分類。提供互動式 Tkinter GUI、文字雲視覺化、跨版面批次比較，並支援 CSV / Excel / PDF 多格式匯出。

`Python` `SnowNLP` `OpenCC` `BeautifulSoup4` `Tkinter` `Matplotlib` `WordCloud` `ReportLab`

---

### AR 遊戲開發

#### [AR Tower Defense — 擴增實境塔防遊戲](https://github.com/HenryChen940219/Unity_SCU_ARFoundation_TD_20250423)

基於 **Unity AR Foundation** 的行動裝置 AR 塔防遊戲。玩家透過手機掃描真實平面，將遊戲場景投影至現實世界，操控砲塔抵禦持續湧入的敵人。支援 NavMesh 智慧尋路、血量系統與完整 Game Over 流程。

`Unity 6` `AR Foundation` `ARCore` `NavMesh` `URP` `C#` `Android`

---

#### [小宇\_接西瓜 — Unity 手機休閒遊戲](https://github.com/HenryChen940219/Unity_SCU_12173212_midterm)

> 東吳大學 2026 期中作品

以海洋為背景的直式休閒躲避遊戲，共三個關卡（第三關為無盡生存模式）。玩家接住西瓜累積分數，閃避炸彈避免血量歸零。含遊玩紀錄系統、跨關卡血量延續與完整 HUD。

`Unity 6` `URP` `C#` `TextMeshPro` `PlayerPrefs` `Android / iOS`

---

## 獎項、研究成果與證照

<table>
<tr>
<td width="50%">

### 研究成果 &nbsp;[![repo](https://img.shields.io/badge/repo-academic--awards-6366f1?style=flat)](https://github.com/HenryChen940219/academic-awards)

**[TCSE 2025 發表證明](https://github.com/HenryChen940219/academic-awards/blob/main/TCSE台灣軟體工程研討會_發表證明.png)**
第二十一屆台灣軟體工程研討會，發表 AR × AI 學習系統研究，高雄，台灣。

**[國科會大專生研究計畫結案證明](https://github.com/HenryChen940219/academic-awards/blob/main/國科會大專生研究計畫英文結案證明.png)**
NSTC 114-2813-C-031-057-E，結案報告通過審查。

**[AI-MetaACES 2026 接收函](https://github.com/HenryChen940219/academic-awards/blob/main/熊本研討會接收函.png)**
論文獲 AI-MetaACES 2026, APSCE TBICS Festival of Learning 2026 國際研討會接收。

</td>
<td width="50%">

### 競賽獎項 &nbsp;[![repo](https://img.shields.io/badge/repo-academic--awards-6366f1?style=flat)](https://github.com/HenryChen940219/academic-awards)

**[中研院統計所資科漫步競賽 — 優選](https://github.com/HenryChen940219/academic-awards/blob/main/中研院統計科學研究所資科漫步競賽_優選.png)**
中央研究院統計科學研究所主辦，資料科學實作競賽優選。

**[學生社會責任專題競賽](https://github.com/HenryChen940219/academic-awards/blob/main/學生社會責任專題競賽.png)**
大學社會責任（USR）專題競賽入選成果。

**[數位人文優秀青年學者](https://github.com/HenryChen940219/academic-awards/blob/main/數位人文優秀青年學者.png)**
獲選數位人文領域優秀青年學者表揚。

</td>
</tr>
<tr>
<td width="50%">

### 技術證照 &nbsp;[![repo](https://img.shields.io/badge/repo-certifications-6366f1?style=flat)](https://github.com/HenryChen940219/certifications)

**[NVIDIA 深度學習證書](https://github.com/HenryChen940219/certifications/blob/main/深度學習%20_%20NVIDIA證書.png)**
NVIDIA Deep Learning Institute（DLI）深度學習課程結業證書。

**[NVIDIA Jetson Nano 證書](https://github.com/HenryChen940219/certifications/blob/main/jetson%20nano%20_%20NVIDIA證書.png)**
NVIDIA DLI Jetson Nano 邊緣 AI 課程結業證書。

</td>
<td width="50%">

### 專業認證 &nbsp;[![repo](https://img.shields.io/badge/repo-certifications-6366f1?style=flat)](https://github.com/HenryChen940219/certifications)

**[Google Gemini Certified Educator](https://github.com/HenryChen940219/certifications/blob/main/Gemini%20Certified%20Eduacator.png)**
通過 Google Gemini 認證教育工作者測驗。

**[Google Analytics 認證](https://github.com/HenryChen940219/certifications/blob/main/Google%20Analytics%20(%E5%88%86%E6%9E%90)%20%E8%AA%8D%E8%AD%89%E8%AD%89%E6%9B%B8.png)**
通過 Google Analytics（GA4）官方認證考試。

</td>
</tr>
</table>

---

## 技術棧

| 領域 | 技術 |
|------|------|
| **語言** | Python · C# · JavaScript · SQL |
| **AI / ML** | Gemini API · Azure OpenAI · scikit-learn · TensorFlow · XGBoost · LSTM · SnowNLP |
| **AR / 遊戲** | Unity · Vuforia · AR Foundation · ARCore · NavMesh |
| **後端 / 雲端** | Flask · Node.js · Express · Docker · Azure · Firebase · Google Cloud |
| **資料庫** | SQLite · Firebase Realtime DB · Azure Blob Storage |
| **工具** | Git · Jupyter · Tableau · ReportLab |

---

<div align="center">

*東吳大學 資料科學系 ｜ HenryChen940219*

</div>
