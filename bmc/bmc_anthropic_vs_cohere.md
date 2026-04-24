# Business Model Canvas 對照表
### Anthropic vs. Cohere · Digital Economy Final Project

> **使用說明**
> - 每個區塊分成兩欄：左欄 Anthropic、右欄 Cohere，最下方是「關鍵差異觀察」——這格是寫報告時直接抓出來當論述用的。
> - 已填入的數據都附來源簡註；`[待補]` 是你們要分頭去挖的部分。
> - 核對重點：每格至少要有 **一個具體數字或命名實體**，不要只有形容詞（這是 Osterwalder 原書對好 BMC 的判準）。
> - 建議先各自填完自己負責的公司，再合併討論「關鍵差異觀察」欄。

---

## 1️⃣ Value Propositions（價值主張）

| Anthropic | Cohere |
|---|---|
| **前沿智能 + 安全保證的組合包**：Claude 系列是 2026 Q1 在編碼（SWE-bench）與 agentic 任務上仍領先 5–10% 的閉源模型 | **部署控制權 + 資料主權**：Model Vault 支援 VPC 與 on-premises，客戶的資料永遠不離開自家環境 |
| **Constitutional AI** 作為可驗證的安全品牌：模型遵循公開的成文規範，幻覺率低於 OpenAI 同級 | **右置模型（Right-sizing）**：Command 系列在小任務上可省 94% 輸入 token 成本，不追求大而全 |
| **唯一同時在三大雲端提供的前沿模型**：AWS Bedrock、Azure Foundry、Google Vertex AI | **雲端中立 + 多雲部署**：Oracle、Google Cloud、Azure、AWS 都可部署，不綁死任一家 |
| **Claude Code / Cowork** 將模型能力封裝成工作流工具，而非 raw API | **RAG 深耕**：Rerank 4 支援 32K 上下文 + 自我學習，專攻企業搜尋與知識管理痛點 |
| **多語言**：Aya 開源權重模型支援 101 種語言，非英語市場差異化 |

**關鍵差異觀察**：Anthropic 賣「最強的大腦 + 我保證它不亂來」；Cohere 賣「剛好夠用的大腦 + 但它絕對在你的控制下」。一個走能力溢價，一個走控制溢價。

---

## 2️⃣ Customer Segments（目標客群）

| Anthropic | Cohere |
|---|---|
| **企業：300,000+ 家**（2025 Q3 數據，Anthropic 官方） | **企業：金融、政府、醫療、法律**等高度監管產業為主（IntuitionLabs 2026） |
| **高端企業：1,000+ 家年支出 $1M+**（Series G 時 500 家，兩個月翻倍） | [待補：Cohere 百萬美元級客戶數量是否有披露？需查 Sacra / BetaKit] |
| **Fortune 10 覆蓋 8 家、Fortune 100 覆蓋 70%** | [待補：Cohere 的 Fortune 級客戶數量——目前只知道 Oracle NetSuite 全面嵌入] |
| **開發者**：Claude Code 企業訂閱在 2026 Q1 翻四倍 | **開發者**：較小眾，但 North Platform 支援 100 個子 agent 協作 |
| **一般消費者**：Claude.ai 在 2026 年 2 月有 2.88 億次月造訪（Semrush） | **幾乎不做 C 端**——這本身是戰略選擇 |
| **政府/國安**：Palantir 合作，Claude Gov 特化版本 | [待補：Cohere 是否有明確政府合約？加拿大政府是否有] |

**與 OpenAI 的企業客戶重疊率 79%**——這是我們寫「非零和市場」論點的關鍵數字。

**關鍵差異觀察**：Anthropic 同時抓 B2B + B2C + 政府三條線；Cohere 只鎖定一條 B2B 高合規垂直線。策略上 Cohere 是「焦土戰」，Anthropic 是「全面戰」。

---

## 3️⃣ Channels（通路）

| Anthropic | Cohere |
|---|---|
| **三大雲端 Marketplace**：AWS Bedrock、Azure Foundry、Google Vertex AI | **Oracle Cloud Infrastructure**：深度整合，NetSuite ERP 內嵌 |
| **Claude.ai 官網直營**：Free / Pro / Max / Team / Enterprise 五層 | **Cohere API 官網直營**：chat / embed / rerank / classify |
| **Claude Code CLI**：獨立的命令列工具 | **North Platform**：企業 AI 工作空間 |
| **Enterprise 直銷團隊**：Cognizant 等大單走這條 | **Oracle 銷售通路**：借 Oracle 的企業業務網絡 |
| **第三方應用整合**：Claude in Chrome、Excel、PowerPoint、Slack | **多雲 Marketplace**：Google / Azure / AWS（但整合深度明顯低於 Oracle） |

**關鍵差異觀察**：Anthropic 的通路是「廣撒網」——每一個大型企業 IT 環境都能觸及；Cohere 的通路是「借 Oracle 的腿」——靠單一大 ISV 夥伴把自己帶進企業後門。

---

## 4️⃣ Customer Relationships（顧客關係）

| Anthropic | Cohere |
|---|---|
| **自助式 API**：開發者文件、SDK、免費額度 | **自助式 API**：文件、SDK |
| **企業帳戶經理**：Fortune 級客戶專屬支援 | **企業帳戶經理**+**Oracle 共同銷售** |
| **開發者社群**：Claude Code 的「Glean CEO 稱之為 religion」口碑擴散 | [待補：Cohere 開發者社群規模] |
| **安全與對齊研究公開**：Constitutional AI 更新、Economic Index 報告——透過「學術型透明度」建立信任 | **企業個別訂製**：Model Vault 等私有部署需 professional services |
| **Anthropic Economic Index** 提供產業報告作為客戶教育工具 | **Aya 開源社群**：支援 101 語言的權重模型釋出，建立非英語市場關係 |

**關鍵差異觀察**：Anthropic 用「我比你更懂 AI 怎麼影響你的產業」建立顧問式關係；Cohere 用「我願意按你的規格客製部署」建立整合商式關係。

---

## 5️⃣ Revenue Streams（收入流）

| 項目 | Anthropic | Cohere |
|---|---|---|
| **年化營收 (ARR)** | **$30 B**（2026 年 4 月，TechCrunch） | **$240 M**（2025 年底，BetaKit） |
| **營收年增率** | 10× 連續三年 | [待補：Cohere 年增率——2024 到 2025 估計跳躍] |
| **主要收入類型** | Per-token API（per usage） | 混合：軟體授權 + usage-based |
| **企業佔比** | 80% | [待補：估計 >90%，需查證] |
| **消費者訂閱營收** | Pro $20 / Max $100–$200 / Team $25–$100 / Enterprise custom | 極少 |
| **單一產品爆款** | Claude Code ARR $2.5 B（2026 Q1） | North Platform [待補：貢獻百分比] |
| **毛利率** | [待補：估計偏低，因雲端分成] | **70%**（官方披露） |
| **雲端分成支出** | 預計 2027 年達峰值 $6.4 B，~50% | 顯著較低（Oracle 提供低成本 GPU） |

**關鍵差異觀察**：Anthropic 是「規模驅動 + 低毛利分成模式」；Cohere 是「軟體型企業的 70% 毛利」。這直接決定兩家 J 曲線的形狀——Anthropic 是深谷急升，Cohere 是淺谷緩升。

---

## 6️⃣ Key Resources（關鍵資源）

| Anthropic | Cohere |
|---|---|
| **Claude 模型 IP**：Opus 4.7 / Sonnet 4.6 / Haiku 4.5 / Mythos Preview | **Command 系列 + Rerank + Embed 模型 IP** |
| **Constitutional AI 方法論**：可公開文件化的安全訓練流程 | **RAG 技術堆疊**：Rerank 4（32K context + self-learning） |
| **人才**：Amodei 兄妹 + ex-OpenAI 核心（Kaplan、Olah、Brown、Schulman 等） | **Aidan Gomez**（Transformer 論文共同作者）+ Toronto 核心團隊 |
| **計算資源**：5 GW Trainium + 1M TPU + 1 GW Nvidia + $30B Azure 承諾 | [待補：Cohere 具體 GPU 容量——需查 Oracle 合作細節] |
| **PBC 架構 + Long-Term Benefit Trust**：治理層獨立於投資人 | **加拿大總部 + 多雲中立性**（商業設計上的資源） |
| **品牌資產**：「連五角大廈都能說不」的可信度 | **資料主權專業**：對 EU AI Act、各國監管的早期準備 |

**關鍵差異觀察**：Anthropic 最關鍵的資源是「前沿研究人才 + 巨量計算」，兩者都極度燒錢；Cohere 最關鍵的資源是「深厚的 RAG 工程能力 + Oracle 盟友」，兩者都是相對廉價的差異化。

---

## 7️⃣ Key Activities（關鍵活動）

| Anthropic | Cohere |
|---|---|
| **前沿模型 R&D**：每 3–6 個月一次重大版本 | **模型優化 R&D**：重點在效率而非參數規模 |
| **安全與對齊研究**：Responsible Scaling Policy、ASL 分級、interpretability | **企業整合開發**：Model Vault、VPC 部署、客製化 |
| **Claude Code / Cowork 產品迭代**：1 月一個月發布 30+ 功能 | **North Platform 開發**：agentic workflow 平台 |
| **多雲合作管理**：同時與三家競爭雲端協商 | **Oracle 深度整合**：NetSuite 內嵌、OCI 訓練 |
| **經濟研究**：Economic Index 報告作為行銷工具 | **Aya 開源治理**：101 語言模型的社群維護 |
| **政策與監管對話**：Dario 親自參與國會聽證 | **合規認證取得**：各國資料保護法規 |

**關鍵差異觀察**：Anthropic 的活動集中在「推動前沿」和「管理雲端夥伴張力」；Cohere 的活動集中在「把模型塞進企業既有系統」。

---

## 8️⃣ Key Partners（關鍵夥伴）

### Anthropic

| 夥伴 | 類型 | 金額/規模 |
|---|---|---|
| **AWS** | 投資 + 算力 + 分發 | $33B 投資 / $100B+ 10 年採購 / 5 GW Trainium |
| **Google + Broadcom** | 投資 + 算力 + 分發 | ~$3B 投資 / 1M TPU + 3.5 GW（2027）|
| **Microsoft + Azure** | 投資 + 算力 + 分發 | $5B 投資 / $30B Azure 採購 |
| **Nvidia** | 投資 + 硬體合作 | $10B 投資 / 1 GW Grace Blackwell + Vera Rubin |
| **Palantir** | 國防整合商 | 美國情報社群部署通路 |
| **Cognizant** | 系統整合商 | 350,000 員工部署 |
| **主要投資人** | 資本 | GIC、Coatue、ICONIQ、Lightspeed、Sequoia、Founders Fund 等 |

### Cohere

| 夥伴 | 類型 | 金額/規模 |
|---|---|---|
| **Oracle** | 投資 + 算力 + 分發 + ERP 整合 | [待補：投資金額] / OCI 訓練 / NetSuite 內嵌 |
| **Nvidia** | 投資者 | [待補：具體金額] |
| **Google Cloud** | 分發通路 | 較淺 |
| **Azure** | 分發通路 | 較淺 |
| **AWS** | 分發通路 | 較淺 |
| **主要投資人** | 資本 | [待補：Cohere 投資人清單，需從 Crunchbase 挖] |

**關鍵差異觀察**：Anthropic 的夥伴網絡是「多中心、高強度、利益衝突」——每家雲端既是夥伴又是競爭者；Cohere 的夥伴網絡是「單中心、深度綁定、模組化」——靠 Oracle 一家就能打進大部分企業。這正是我們 SNA 裡 Betweenness Centrality vs. Clustering Coefficient 的具體對照。

---

## 9️⃣ Cost Structure（成本結構）

| 成本項 | Anthropic | Cohere |
|---|---|---|
| **訓練與推理** | **$19 B/年（2026 預計，約等於營收）** | 顯著較低 [待補：具體數字] |
| **雲端分成** | 預計 2027 年峰值 **$6.4 B/年** | 極低（Oracle 低成本 GPU） |
| **人才** | [待補：員工數——2024 年中 ~950 人，之後減緩] | [待補：員工數] |
| **資本結構類型** | **重資產實驗室**（Heavy-asset Lab） | **輕資產 SaaS**（Asset-light） |
| **毛利率** | [待補：估計偏低] | **70%**（官方披露） |
| **累計募資** | **>$64 B** | **~$1 B** |
| **Break-even 預期** | 2027–2028 年自由現金流轉正 | 已接近獲利 |
| **單位經濟** | Capital Efficiency Ratio **~0.22** | **~0.24**（幾乎相同！） |

**關鍵差異觀察**：兩家每一塊募資產生的 ARR 幾乎一樣，但估值差 54 倍——這就是我們整個專題最核心的資本效率悖論。差異不在效率，在市場對「前沿能力 option value」的定價。

---

## 🎯 總整理：四框架銜接提示

寫報告時，這張 BMC 的每一區塊對應到哪個分析框架：

- **Value Propositions + Customer Segments** → Hotelling 模型的定位證據
- **Channels + Key Partners** → 社會網絡分析的節點與邊、平台包覆分析
- **Revenue Streams + Cost Structure** → J 曲線與資本效率悖論
- **Key Resources + Key Activities** → 信號理論（什麼是 costly signal？Constitutional AI 的研究投入就是）

---

## 📝 待補事項清單（分工建議）

**YTLi 負責**
- Anthropic 毛利率（估算 + 來源）
- Anthropic 員工數（2026 最新）
- Anthropic 2024–2025 收入結構 breakdown（API vs Code vs subscription）

**元貞負責**
- Cohere 百萬美元級客戶數
- Cohere 年增率（2024 → 2025）
- Cohere 企業佔比確認
- Cohere 總累計融資金額 + 投資人清單（Crunchbase）
- Cohere 員工數 + 計算容量
- Oracle 對 Cohere 的具體投資金額
- North Platform 貢獻營收百分比

**共同確認**
- Capital Efficiency Ratio 的計算公式是否一致（分母用累計募資還是近一輪估值？）
- 雲端分成估計值的來源可靠度（Markman Capital 部落格的 50% 是估算值，需找原始揭露）
