# Business Model Canvas
## Anthropic vs. Cohere · Digital Economy Final Project

> **使用說明**
> - 本文件包含三部分：(A) Anthropic 單張九宮格 BMC、(B) Cohere 單張九宮格 BMC、(C) 跨欄差異討論。
> - 九宮格按 Osterwalder & Pigneur 標準佈局：左側合作夥伴/活動/資源 → 中央價值主張 → 右側顧客關係/客群/通路 → 底部成本/收入。
> - Anthropic 欄位已完整填入並核對來源；Cohere 欄位保留 `[待補]` 由元貞負責。
> - 每格至少包含一個具體數字或命名實體——這是 Osterwalder 原書對好 BMC 的判準。
> - 數據截至 2026 年 4 月 25 日。

---

## (A) Anthropic 商業模式畫布

**Designed for:** Anthropic, PBC　　**Date:** 2026/04　　**Version:** v1.1

---

### 區塊 1：關鍵合作夥伴（Key Partners）

**雲端與計算夥伴（投資 + 算力 + 分發三重關係）**

| 夥伴 | 投資金額 | 計算與分發承諾 |
|---|---|---|
| Amazon / AWS | 累計 $33B（2023 起 $8B + 2026-04-20 加碼 $25B，其中 $5B 立即投入、$20B 綁定商業里程碑） | Anthropic 承諾未來 10 年於 AWS 採購超過 $100B；最多 5 GW Trainium2/3/4 容量；Project Rainier 約 50 萬片 Trainium2；AWS 為主要訓練夥伴（2024 年起） |
| Google + Broadcom | Google 累計約 $3B | 2025-10 簽定最高 1M 片 TPU、2026 年 1 GW 以上；2026-04 擴大至 3.5 GW，2027 上線 |
| Microsoft + Azure | $5B（2025-11） | Anthropic 承諾採購 $30B Azure 算力；Claude 整合進 Azure Foundry |
| Nvidia | $10B（2025-11） | 1 GW Grace Blackwell + Vera Rubin 系統 |

**通路與整合夥伴**
- Snowflake：multi-year $200M 合約（2025-12-04）；Claude 透過 Snowflake Cortex AI 提供給其 12,600 全球客戶；Snowflake Intelligence 由 Claude Sonnet 4.5 驅動
- Palantir：透過 Maven Smart System 將 Claude 整合進美國國防工作流；Anthropic 過去佔 Palantir 美國政府業務約 60%（2026-02 受 Pentagon 事件衝擊）
- Cognizant：2025-11-04 宣布部署，將 Claude 推送至 35 萬名員工；Anthropic 三大企業客戶之一（WSJ）

**主要投資人（Series G 共同領投與重要參與者）**
- 領投：GIC（新加坡主權基金）、Coatue Management
- 共同領投：D. E. Shaw Ventures、Dragoneer、Founders Fund、ICONIQ Capital、MGX（阿聯主權基金）
- 重要參與：Accel、Fidelity、Lightspeed、Sequoia Capital（罕見同時投資 Anthropic 與 OpenAI）、Jane Street、Qatar Investment Authority、BlackRock 與 Blackstone 關聯基金、Bessemer、Baillie Gifford、JPMorganChase、Morgan Stanley、Temasek、TPG
- 早期天使：Jaan Tallinn、Dustin Moskovitz、Eric Schmidt
- 共 90 位投資人（81 機構 + 9 天使，Tracxn 數據）

---

### 區塊 2：關鍵活動（Key Activities）

- **前沿模型研發**：每 3–6 個月一次重大版本（Opus 4.6 於 2026-02-07 發表 → Opus 4.7 於 2026-04-16 發表，間隔僅 2 個月）
- **安全與對齊研究**：Constitutional AI 方法、Responsible Scaling Policy（ASL-1 至 ASL-4 風險分級）、可解釋性研究、Transparency Hub
- **產品迭代**：Claude Code（2025-02 內測、2025-05 公開）、Cowork（2026-01）、Claude Design（2026-04）；2026 年 1 月單月發布 30+ 功能
- **多雲合作管理**：同時與 AWS、Google、Microsoft 三家相互競爭的雲端協商，並維持 Claude 為「唯一同時於三大主流雲端可用的前沿模型」的定位
- **政策與監管對話**：Dario Amodei 親自參與美國國會聽證；2026-03 成立 Anthropic Institute（智庫）
- **產業研究發表**：Anthropic Economic Index、模型卡（Model Cards）、推理成本與生產力報告
- **企業安全事件處理**：2025-11 揭露中國國家級駭客利用 Claude 對 30 個全球組織進行自動化網路攻擊事件
- **拒絕作為信任訊號**：2026-02 拒絕 DoD 修改合約以解除「禁止大規模監控與全自動武器」的限制；同時段擴大 Snowflake 合作以鞏固民間市場

---

### 區塊 3：關鍵資源（Key Resources）

**模型與技術 IP**
- Claude 模型家族：Opus 4.7（旗艦）/ Opus 4.6 / Sonnet 4.6 / Haiku 4.5 / Mythos Preview
- Constitutional AI 方法論
- Model Context Protocol（MCP）：開源 agent 連接標準，2026-03 累計安裝突破 9,700 萬次

**人力資本**
- 員工數：4,954 人（Tracxn 2026-03-31，官方 LinkedIn 與註冊資料）；不同來源報告數字介於 3,000–5,000 之間
- 創辦核心：Dario Amodei（CEO）、Daniela Amodei（President），加上 5 位共同創辦人 Jared Kaplan（Chief Science Officer）、Jack Clark、Sam McCandlish、Benjamin Mann、Tom Brown，以及 Christopher Olah 等共七位前 OpenAI 核心成員（2021 年共同出走）
- 2024 年再從 OpenAI 挖角 Jan Leike、John Schulman、Durk Kingma
- 2026-04 任命前 Microsoft 高管 Eric Boyd 為 Head of Infrastructure
- Glassdoor 評分 4.4（同業比較：OpenAI 4.5、DeepMind 4.2、Cohere 2.9）；薪酬與福利評分 4.8/5.0；工程師總薪資範圍 $300K–$490K

**算力資產**
- 當前可用容量：約 1.5–2 GW（SaaStr 估計）
- 已承諾擴展總量：最多 5 GW AWS Trainium + 1M 片 Google TPU（其中 3.5 GW 於 2027 上線）+ 1 GW Nvidia Grace Blackwell + Vera Rubin + $30B Azure 採購；Anthropic 已運行超過 100 萬片 Trainium2

**治理結構**
- 公益公司（Public Benefit Corporation, PBC）
- Long-Term Benefit Trust（持有 Class T 股，可選舉部分董事，獨立於投資人的治理層）

**品牌資產**
- 「拒絕 Pentagon 修改合約」事件（2026-02）轉化為民間企業的可信度背書
- 2026-02 Super Bowl LX 兩支廣告（"A Time and a Place" 系列，Mother 廣告公司操刀），強化「ad-free」品牌定位

**近期收購**
- Vercept、Shenzhen XP（2025）
- Bun（2025-12，提升 Claude Code 速度與穩定性）
- Coefficient Bio（2026-04，切入製藥研發）
- 共 3 起公開收購（Tracxn 數據）

---

### 區塊 4：價值主張（Value Propositions）

**1. 前沿性能 + 安全保證的組合**
- Claude Opus 4.7（2026-04-16 發表）在 SWE-bench Verified 達 87.6%，較 GPT-5.4 的約 82% 領先 5–6 個百分點
- SWE-bench Pro 從 Opus 4.6 的 53.4% 升至 4.7 的 64.3%；CursorBench 從 58% 升至 70%
- 在編碼工具市場（Claude Code）佔有 54% 市占（TradingKey 數據）

**2. 可驗證的安全品牌**
- Constitutional AI：成文行為規範直接內嵌訓練流程
- Responsible Scaling Policy：自評 ASL-1 至 ASL-4 風險分級制度
- 幻覺率低於同級閉源模型（基於企業客戶選擇調查）

**3. 三大雲端共通模型**
- Claude 是唯一同時於 AWS Bedrock、Azure Foundry、Google Vertex AI 提供的前沿模型
- 提供企業反包覆（counter-envelopment）保險：避免單一雲端鎖定

**4. 工作流封裝產品**
- Claude Code：CLI agentic coding 工具，2025-11 達 ARR $1B（史上最快達此里程碑的企業軟體），2026-02 達 ARR $2.5B
- Cowork：4 名工程師於 10 天內打造，多數程式碼由 Claude Code 自己寫
- Claude Design：視覺內容協作（2026-04 推出）

**5. 垂直特化版本**
- Claude Gov：美國國安專用版本（2025-06 發表）
- Claude for Healthcare：HIPAA-ready，內建 CMS Coverage Database、ICD-10 codes、PubMed 整合
- iOS / Android 應用整合 Apple Health 與 Android Health Connect（Pro/Max 用戶 beta）

---

### 區塊 5：顧客關係（Customer Relationships）

- **自助式 API**：開發者文件、SDK、提供 $5 試用額度（無永久免費 API tier）
- **企業帳戶經理**：Fortune 級客戶專屬支援；Cognizant、Snowflake 等大單走此通路
- **開發者社群口碑**：Claude Code 在 X / Reddit 形成顯著擴散（Glean CEO 形容為「religion」級採用）
- **學術型透明度**：Constitutional AI 公開更新、Responsible Scaling Policy、Transparency Hub（2026-02 上線）
- **顧問式內容行銷**：Anthropic Economic Index 提供產業使用報告；Anthropic Institute 進行政策對話
- **拒絕作為信任訊號**：Pentagon 對峙事件——將「拒絕修改合約以解除大規模監控與自動化武器限制」公開化作為對民間企業的信任承諾
- **Anthropic Marketplace**（2026-02 推出）：企業客戶可將既有 API 預算用於購買第三方 Claude-powered 軟體，Anthropic 不收取交易抽成；Snowflake、Harvey、Replit 為首批夥伴

---

### 區塊 6：目標客群（Customer Segments）

**企業客戶（佔營收約 80%）**
- 30 萬以上家企業客戶（Sacra 2025-Q4 數據）
- 1,000 家以上年支出超過 $1M（2026-04，60 天內從 500 家翻倍）
- 年支出超過 $100K 客戶數於過去一年成長 7 倍
- Fortune 10 企業中 8 家、Fortune 100 中達 70% 採用 Claude
- 與 OpenAI 企業客戶重疊率 79%（Ramp 數據）；1/5 使用 Ramp 的企業付費使用 Anthropic（一年前為 1/25）
- 81% 受訪 Fortune 2000 高管同時使用 Claude、ChatGPT 與 Gemini（a16z 100 位 VP/C-level 調查）
- 已具名大型企業：Cognizant、Lyft、Pfizer、Netflix、Spotify、KPMG、L'Oréal、Salesforce 等

**開發者**
- Claude Code 企業訂閱於 2026 Q1 翻 4 倍
- Anthropic 公開表示早期工程資源 100% 投入 API 而非 C 端

**一般消費者**
- Claude.ai 月造訪數於 2026-02 達 2.88 億次（Semrush）
- 2025 年 Pro/Max 訂閱營收 $1.2B（Business of Apps）
- ChatGPT 同期週活約 9 億——Anthropic C 端規模顯著小於 OpenAI

**政府與國防**
- Palantir 合作 + Claude Gov 特化版本
- 2026-02 拒絕 DoD 監控合約 → 02-27 Trump 行政命令停用 Anthropic 模型 → 法院臨時裁定政府逾權（2026-04 持續訴訟中）

---

### 區塊 7：通路（Channels）

- **三大雲端 Marketplace**：AWS Bedrock（Anthropic 自稱「100,000+ 組織透過 AWS 使用 Claude」）、Microsoft Azure Foundry、Google Vertex AI
- **Claude.ai 官網直營**：Free / Pro / Max / Team / Enterprise 五層
- **Claude Code CLI**（命令列工具）+ **Cowork 桌面應用**（macOS / Windows，2026-04 正式上市）+ **Claude Design**
- **第三方應用整合**：Claude in Chrome、Excel、PowerPoint
- **行動端**：iOS / Android Apps（含 Apple Health + Android Health Connect 整合）
- **Snowflake Cortex AI**：嵌入企業資料分析環境，每月處理數萬億 Claude tokens
- **Anthropic Marketplace**（2026-02 推出）：企業客戶可在 Anthropic 既有預算內購買第三方 Claude-powered 軟體
- **品牌行銷通路**：2026-02 Super Bowl LX 兩支廣告

---

### 區塊 8：收入流（Revenue Streams）

**規模指標**
- 年化營收（ARR）：**$30B**（2026-04，Sacra / TechCrunch / SaaStr 多重交叉驗證）
- 軌跡：$87M（2024-01）→ $1B（2024-12）→ $9B（2025-12）→ $14B（2026-02）→ $19B（2026-03）→ $30B（2026-04）
- 連續三年 10× 年增率，企業軟體史上最快
- Anthropic 已超過 OpenAI（$25B ARR）成為營收最高的 AI 公司

**收入結構**
- 企業營收佔比：約 80%（Sacra 2025-Q4）；Anthropic 自身在 2025 年估算企業 API 佔 86%、消費 Claude 訂閱佔約 14%（Tiger Brokers / The Information 引用）
- Claude Code 單獨 ARR：$2.5B（2026-02），佔 Claude Code 營收的 50% 以上來自企業客戶
- 消費訂閱：2025 年 $1.2B（Pro / Max 方案，Business of Apps）

**收費模式**
- Per-token usage-based pricing（按量計費）
- 訂閱階梯：Pro $20/月（年繳折抵後 $17）/ Max 5× $100/月 / Max 20× $200/月 / Team Standard $30 月繳或 $25 年繳/座 / Team Premium $125 月繳或 $100 年繳/座 / Enterprise 訂製
- Claude.ai 一般用戶仍維持「ad-free」承諾（與 OpenAI 引入廣告形成對比）

**API 定價（per million tokens，2026-04 官方）**

| 模型 | Input | Output |
|---|---|---|
| Claude Opus 4.7 / 4.6 | $5.00 | $25.00 |
| Claude Sonnet 4.6 | $3.00 | $15.00 |
| Claude Haiku 4.5 | $1.00 | $5.00 |
| Claude Opus 4.1（legacy） | $15.00 | $75.00 |

優化機制：Batch API 五折、Prompt Caching cache hit 九折（cached input 0.10× 標準價）；Opus 4.7 支援 1M context 標準費率（無長上下文加價）；Fast Mode（Opus 4.6 research preview）為 6× 標準價

**效率指標**
- 每員工年化營收：約 $6M（Google 同期約 $1M、Salesforce 約 $0.4M）——史上同階段最高
- 推理成本 YoY 下降 90%（SaaStr 2026-04）

---

### 區塊 9：成本結構（Cost Structure）

**運算成本（最大支出項）**
- 2025 年訓練成本：約 $4.1B（Tiger Brokers / The Information 引用）
- 2025 年推理成本：約 $2.7B（不含免費用戶）
- 2026 年訓練 + 推理預計支出：$19B（其中訓練 $12B、推理 $7B）——約等於該年營收
- 2025 年推理成本超出內部預期 23%，導致毛利從 50% 目標下調至 40%
- 雲端分成：預計 2027 年達峰值 $6.4B（約佔當年營收 50%，Markman Capital Insight 估算）

**長期算力承諾總額**
- AWS：未來 10 年 $100B+ 採購承諾（2026-04 確認）
- 訓練支出：未來 3 年 $100B
- Microsoft Azure：$30B 採購承諾
- 雲端基礎建設總計（至 2029）：$80B

**人力成本**
- 員工數：4,954（2026-03，Tracxn）
- 工程師總薪酬範圍：$300K–$490K
- 員工成本估算：以 4,954 員工 × 平均 $400K 估算約 $2B/年（次要成本項目，遠低於運算成本）

**資本結構**
- 重資產實驗室（Heavy-asset Lab）模式
- 累計募資：**$67.3B**（Tracxn 2026-04，跨 17 輪：2 早期 + 13 後期 + 1 其他 + 1 債務）

**毛利率軌跡**
- 2024：-94%（Adeayo Medium、Tiger Brokers）
- 2025（不含免費用戶）：40%（The Information，2026-01-22 內部投資人材料）
- 2025（含免費用戶）：38%
- 2027 目標：原預期 70%
- 2028 目標：77%
- 對照 OpenAI 2025 預估毛利：46%

**現金燒率**
- 2024 燒掉 $5.6B 現金；2025 約 $2.8–3B
- 內部預測：2027 停止燒現金、2028 自由現金流轉正
- 預計 2025 EBITDA 損失：約 $5.2B

---

## (B) Cohere 商業模式畫布

**Designed for:** Cohere　　**Date:** 2026/04　　**Version:** v1.0（待元貞補齊）

---

### 區塊 1：關鍵合作夥伴
- **Oracle**：投資 + 算力 + 分發 + ERP 整合（NetSuite 內嵌）— [待補：投資金額]
- **Nvidia**：投資者 — [待補：具體金額]
- **Fujitsu**：日本金融與公共部門合作開發專屬日文 LLM
- **Google Cloud / Azure / AWS**：分發通路（深度較淺）
- **主要投資人** [待補：完整名單需從 Crunchbase 挖]

### 區塊 2：關鍵活動
- 模型優化 R&D（重點在效率，非參數規模）
- 企業整合開發：Model Vault、VPC 部署、客製化
- North Platform 開發（agentic workflow，支援最多 100 個子 agent 協作）
- Oracle 深度整合：NetSuite 內嵌、OCI 訓練
- Aya 開源治理（101 語言模型社群維護）
- 各國資料保護法規之合規認證取得

### 區塊 3：關鍵資源
- 模型 IP：Command 系列、Rerank 4（32K context + self-learning）、Embed、Aya（開源權重 101 語言）
- RAG 技術堆疊
- 創辦人 Aidan Gomez（Transformer 論文 *Attention Is All You Need* 共同作者）+ Toronto 核心團隊
- [待補：員工數、計算容量]
- 多雲中立性 + 加拿大總部（合規與商業設計上的資源）
- Glassdoor 評分 2.9（vs Anthropic 4.4，反差顯著）

### 區塊 4：價值主張
1. **部署控制權 + 資料主權**：Model Vault 支援 VPC / on-premises
2. **右置模型（Right-sizing）**：小任務省 94% 輸入 token 成本
3. **雲端中立**：跨雲部署，避免供應商鎖定
4. **RAG 深耕**：Rerank 4 專攻企業搜尋與知識管理
5. **多語言**：Aya 開源權重支援 101 語言

### 區塊 5：顧客關係
- 自助式 API（chat / embed / rerank / classify）
- 企業帳戶經理 + Oracle 共同銷售
- [待補：開發者社群規模]
- 企業客製整合（Model Vault、professional services）
- Aya 開源社群

### 區塊 6：目標客群
- 高度監管產業：金融、政府、醫療、法律
- 大型跨國企業：McKinsey & Company、Thomson Reuters、Cisco、Dell（IntuitionLabs 引用）
- 日本金融與公共部門（透過 Fujitsu）
- [待補：百萬美元級客戶數量]
- 幾乎不做 C 端

### 區塊 7：通路
- Oracle Cloud Infrastructure（深度整合）
- NetSuite ERP 內嵌
- 官網 API 直營
- North Platform
- 多雲 Marketplace（深度較淺）

### 區塊 8：收入流
- ARR：**$240M**（2025 年底，BetaKit）
- 主要：軟體授權 + usage-based 混合
- 毛利率：**70%**（官方披露）
- [待補：企業佔比、年增率、North Platform 貢獻百分比]

### 區塊 9：成本結構
- 輕資產 SaaS（Asset-light）
- 累計募資：約 $1B
- [待補：員工數、訓練推理成本]
- Oracle 提供低成本 GPU → 雲端分成顯著低於 Anthropic
- 已接近獲利

---

## (C) 跨欄差異討論

### 區塊 1 差異：價值主張
**Anthropic 賣「最強的大腦 + 我保證它不亂來」；Cohere 賣「剛好夠用的大腦 + 但它絕對在你的控制下」。**
一個走能力溢價（垂直差異化），一個走控制溢價（水平差異化）。兩者並非互斥，而是分別吸引不同需求面向的客戶。

### 區塊 2 差異：目標客群
**Anthropic 同時抓 B2B + B2C + 政府三條線；Cohere 只鎖定一條 B2B 高合規垂直線。**
策略上 Cohere 是「焦土戰」，Anthropic 是「全面戰」。Ramp 數據顯示 79% OpenAI 用戶同時付費使用 Anthropic——客戶採用是 "and" 不是 "or"，市場非贏者全拿。

### 區塊 3 差異：通路
**Anthropic 通路是「廣撒網」**——三大雲端 + 直營 + 第三方整合 + Marketplace；
**Cohere 通路是「借 Oracle 的腿」**——靠單一大 ISV 把自己帶進企業後門。

### 區塊 4 差異：顧客關係
**Anthropic 用「我比你更懂 AI 怎麼影響你的產業」建立顧問式關係**（甚至設智庫做政策對話）；
**Cohere 用「我願意按你的規格客製部署」建立整合商式關係**。

### 區塊 5 差異：收入流
**Anthropic 是「規模驅動 + 低毛利分成」**：40% 毛利但 ARR $30B；
**Cohere 是「軟體型企業的 70% 毛利」**：高毛利但 ARR $240M。
Anthropic 賭規模效應 + 推理成本下降；Cohere 賭不需規模就能存活。

### 區塊 6 差異：關鍵資源
**Anthropic 在 4,954 員工規模就達 $30B ARR——歷史上最高人均產出（約 $6M/員工）**；Cohere 走較典型 SaaS 員工結構。LLM 公司的「智能產出對員工人頭比」已發生結構性轉移。

### 區塊 7 差異：關鍵活動
**Anthropic 活動集中在三方向**：推動前沿、管理雲端夥伴張力、定義產業話語權；
**Cohere 活動集中在單方向**：把模型塞進企業既有系統。

### 區塊 8 差異：關鍵夥伴
**Anthropic 夥伴網絡：多中心、高強度、利益衝突**——每家雲端既是夥伴又是競爭者；
**Cohere 夥伴網絡：單中心、深度綁定、模組化**——靠 Oracle 一家打進企業。

### 區塊 9 差異：成本結構
**Anthropic 是「先燒到 -94% 毛利，再用規模拉回 40%，最終目標 77%」**；
**Cohere 是「一開始就守住 70%」**。
兩家賭注不同——Anthropic 賭推理成本下降 + 規模效應；Cohere 賭不需規模就能獲利。

---

## 重要提醒：Gross vs Net Revenue 認列議題

Sacra 與 OpenAI 雙雙指出，Anthropic 採用 **gross revenue 認列**——把雲端轉售（AWS、Google、Microsoft）的終端客戶總支出計入營收，再把分成記為費用。這讓 top line 比 net-reporting 同業多算約 $8B。OpenAI 主張 Anthropic 真實營收應為 $22B 而非 $30B（2026-04-14）。

報告若引用 ARR 數字，建議在 robustness check 段落並陳兩個版本：
- Gross 認列：ARR $30B，毛利 40%
- Net 認列：ARR $22B（扣除約 $8B 雲端轉售），毛利估約 55%

SEC 在 IPO 申請過程中可能要求 Anthropic 改變此認列方式，這是重要的學術誠信議題。

---

## BMC 與報告章節對應

寫期末報告時，這兩張 BMC 的每一區塊對應到正文哪一章節：

- **價值主張** → 第二章 理論框架（垂直 vs 水平差異化的具體展現）
- **目標客群 + 顧客關係** → 第三章 市場證據（客戶區隔）
- **收入流 + 成本結構** → 第四章 訂價策略與訂價權
- **關鍵夥伴 + 通路** → 第六章 場景分析（資料監管情境的因應）
- **關鍵資源 + 關鍵活動** → 第六章 場景分析（算力成本、開源衝擊情境的因應）

---

## 待補事項清單

**YTLi 已完成（Anthropic）**
- 毛利率：40%（2025 實際），目標 77%（2028）
- 員工數：4,954（Tracxn 2026-03）
- 收入結構：企業 80%、API 86%（內部估計）、Code ARR $2.5B、消費訂閱 $1.2B
- 累計募資：$67.3B（Tracxn 跨 17 輪）
- 每員工營收：約 $6M
- 訓練成本 $4.1B + 推理成本 $2.7B（2025 實際）
- 完整投資人清單與輪次
- Pentagon 事件時間軸

**元貞負責（Cohere）**
- 百萬美元級客戶數
- 年增率（2024 → 2025）
- 企業佔比確認
- 累計融資金額 + 投資人清單（Crunchbase）
- 員工數 + 計算容量
- Oracle 對 Cohere 的具體投資金額
- North Platform 貢獻營收百分比

**共同確認**
- Gross vs Net Revenue 認列要不要在報告中並陳
- Cohere 的 ARR $240M 是否同樣有 gross / net 計算差異

---

## 主要資料來源（核對用）

- Sacra: sacra.com/c/anthropic（2026-04，營收與企業客戶數據）
- Tracxn: tracxn.com/d/companies/anthropic（員工數、累計募資、投資人清單）
- The Information（2026-01-22，毛利率下調報告）
- TechCrunch（2025-12-04 Snowflake、2026-02-12 Series G、2026-04-20 Amazon）
- CNBC（2026-04-20 Amazon $25B 加碼）
- Anthropic 官方新聞稿（Series G、Snowflake、Amazon）
- Wikipedia: Anthropic（時間軸、Pentagon 事件）
- Menlo Ventures（2025 企業 AI 採用報告）
- Ramp（企業客戶重疊率數據）
- SaaStr（每員工營收、推理成本下降）
- Tiger Brokers / Investing.com（2026-01 毛利率與成本細節）
- Computerworld / WSJ（Cognizant 35 萬員工部署）
