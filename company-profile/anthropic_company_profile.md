# Anthropic 公司檔案
### Digital Economy Final Project — Reference Document
*Last updated: April 2026 · 資料截止：2026 年 4 月 23 日*

---

## 一、創辦故事

Anthropic 於 2021 年 1 月由 Dario Amodei（現任 CEO，Princeton 生物物理博士、前 Baidu、Google Brain、OpenAI 研究副總裁）與其妹 Daniela Amodei（現任總裁，前 OpenAI 安全與政策副總裁）共同創立於舊金山。兩人與另外約七位 OpenAI 核心研究員同時離開，包括：

- **Jared Kaplan**（首席科學家）— scaling laws 奠基者之一
- **Sam McCandlish**（首席架構師）
- **Tom Brown** — GPT-3 第一作者
- **Christopher Olah**（可解釋性研究負責人）— 知名的神經網路可視化研究者
- **Benjamin Mann**（Anthropic Labs 負責人）
- **Jack Clark**（政策負責人）

Dario 於 2020 年 12 月離開 OpenAI。根據他本人向 Lex Fridman 及其他媒體的說法，出走的核心原因是他和 OpenAI 高層對「如何將安全研究內建於能力擴展流程」有根本性分歧——他們主張安全必須從訓練的第一天就成為模型核心，而非事後打補丁。2016 年 Dario 曾與 Google 同事合著〈Concrete Problems in AI Safety〉，奠定了這一觀點的學術基礎。

**公司治理結構的三個特色：**

1. **公益公司（Public Benefit Corporation, PBC）**：董事會被法律授權在獲利之外，也可將「確保變革性 AI 造福人類」的使命納入考量。這給予 Anthropic 比純商業公司更大的策略彈性。
2. **Long-Term Benefit Trust（長期利益信託）**：持有 Class T 股份，可選舉部分董事會成員，形成獨立於投資人的治理層。截至 2025 年 10 月，信託成員包括 Neil Buddy Shah、Kanika Bahl、Zach Robinson、Richard Fontaine。
3. **Responsible Scaling Policy (RSP)**：Anthropic 公開的 AI Safety Level (ASL) 分級制度，Opus 4 已被分類為 ASL-3 級（具顯著潛在風險）。

**2023 年 11 月的關鍵插曲**：OpenAI 董事會在 Sam Altman 短暫被解職期間，曾接觸 Dario，提議由他接任 Sam 的職位並合併兩家公司。Dario 拒絕了兩項提議，此事被視為 Anthropic 獨立路線的關鍵轉折點。

> **來源**：Contrary Research · research.contrary.com/company/anthropic; Wikipedia: Anthropic; Wikipedia: Dario Amodei; datastudios.org; Inc. Magazine (Nov 2024)

---

## 二、產品線（截至 2026 年 4 月）

### 2.1 Claude 模型家族（當前主力）

| 模型 | 模型 ID | 上市時間 | 定位 |
|---|---|---|---|
| **Claude Opus 4.7** | `claude-opus-4-7` | 2026 年 4 月 | 旗艦模型，最強編碼與長時程 agent 任務能力 |
| **Claude Opus 4.6** | `claude-opus-4-6` | 2026 年 2 月 | 前一代旗艦，仍維持供應 |
| **Claude Sonnet 4.6** | `claude-sonnet-4-6` | 2026 年 2 月 | 主力工作模型，性價比最佳 |
| **Claude Haiku 4.5** | `claude-haiku-4-5-20251001` | 2025 年 10 月 | 最快、最便宜，適合高吞吐量任務 |

### 2.2 面向開發者與企業的產品線

- **Claude API**：傳統 per-token 計費介面，是企業整合的主要管道
- **Claude Code**（2025 年 2 月內測、5 月公開發表）：命令列 agentic coding 工具，已成為 Anthropic 最快速成長的產品線；2026 年 2 月年化收入達 $2.5 B，2026 Q1 商業訂閱數較 2026 年初翻了四倍
- **Claude Cowork**（2026 年 1 月推出，4 月在 macOS/Windows 桌面正式上市）：將 Claude Code 的 agent 能力擴展到非工程知識工作，包含法律、銷售、財務等 11 個開源插件
- **Claude Design**（2026 年 4 月）：與 Opus 4.7 同時推出的視覺內容協作產品，可產出設計稿、原型、簡報
- **Claude in Chrome / Claude in Excel / Claude in PowerPoint**：第三方應用整合
- **Claude Gov**（2025 年 6 月）：面向美國國安機構的特化版本

### 2.3 面向一般使用者的 Claude.ai 訂閱

| 方案 | 月費（美元） | 主要特徵 |
|---|---|---|
| Free | $0 | 基本使用，有訊息上限 |
| Pro | $20（月繳）/ ~$17（年繳） | 5 小時滾動視窗、Projects、Research mode |
| Max 5× | $100 | Pro 的 5 倍用量，含 Claude Code |
| Max 20× | $200 | Pro 的 20 倍用量 |
| Team Standard | $30 月繳 / $25 年繳 | 最少 5 人，團隊協作功能 |
| Team Premium | $100/座/月（年繳） | 含 Claude Code，SSO、SCIM、中央計費 |
| Enterprise | 訂製（約 $60/座、最少 70 席、年約） | 資料駐留、合規性、專屬支援 |

> **來源**：Anthropic 官方定價頁、Finout、MetaCTO、checkthat.ai、juma.ai、findskill.ai

---

## 三、定價（API 端，2026 年 4 月）

**標準費率**（美元／百萬 token，輸入／輸出）：

| 模型 | 輸入 | 輸出 | 備註 |
|---|---|---|---|
| Opus 4.7 | $5.00 | $25.00 | 1 M context 標準費率 |
| Opus 4.6 | $5.00 | $25.00 | 1 M context 標準費率 |
| Sonnet 4.6 | $3.00 | $15.00 | 1 M context 標準費率 |
| Haiku 4.5 | $1.00 | $5.00 | 200 K context |
| Opus 4.1（legacy） | $15.00 | $75.00 | 比 4.6 貴 3 倍 |

**關鍵成本優化機制：**

- **Batch API**：所有模型五折
- **Prompt Caching**：快取命中的輸入 token 費率降至 10%（九折）
- **Fast Mode**（Opus 4.6 研究預覽）：$30/$150，六倍標準費率，換取極低延遲
- **長上下文附加費用於 2026 年 3 月 13 日取消**：現在 900 K token 請求與 9 K token 同費率

**與競品對照（2026 年 4 月）**：Sonnet 4.6 的 $3/$15 高於 GPT-5.2 的 $1.75/$14 及 Gemini 3.1 Pro 的 $2/$12；Opus 級保持 Claude 層級的 $5/$25 定價，是本研究中「安全溢價」論點的重要數據。

> **來源**：finout.io、metacto.com、evolink.ai、silicondata.com；Anthropic 官方文件（已於 2026-04-12 校對）

---

## 四、客戶

**規模數據（2026 年 4 月）：**

- 全球**超過 300,000** 家企業客戶
- **1,000+ 家**企業年度支出超過 $1M（2026 年 2 月時為 500 家，兩個月內翻倍）
- 年度支出超過 $100K 的客戶數在 2025 年內成長 7 倍
- **Fortune 10 中有 8 家**是 Claude 客戶；Fortune 100 採用率達 70%
- Claude Code 企業訂閱佔其總營收一半以上
- 企業佔 Anthropic 總營收約 80%
- 與 OpenAI 的企業客戶重疊率約 79%（企業實際上是雙平台策略，不是二選一）

**已公開的代表性企業客戶：**

- **Cognizant**（2025 年 11 月 4 日宣布）：IT 服務巨頭，規劃將 Claude 部署到 350,000 名員工與所有客戶端平台，是 Anthropic 前三大企業客戶之一
- **Palantir + AWS**：2024 年 11 月起合作，提供 Claude 給美國情報與國防機構
- **美國國安機構**（透過 Claude Gov，2025 年 6 月起）

**企業收入來源結構（menlovc.com / Menlo Ventures 2025 報告）：**企業級 LLM API 市場 2024 年底到 2025 年中成長至 $8.4B；Anthropic 以約 32% 市佔率超越 OpenAI（25%）成為企業市場領導者；Cohere 屬於長尾供應商群。Menlo 報告後更新的 2026 年數據指出 Anthropic 企業市佔進一步升至 40%。

**營收軌跡：**

| 時間點 | 年化營收 (ARR) |
|---|---|
| 2024 年 12 月 | $1 B |
| 2025 年中 | $3 B |
| 2025 年底 | $9 B–$10 B |
| 2026 年 2 月 | $14 B |
| 2026 年 3 月 | $19 B |
| 2026 年 4 月 | $30 B |

連續三年以 10x 年增長率擴張，是企業軟體史上前所未有的速度。

> **來源**：Anthropic Series G 官方公告（2026-02-12）、Menlo Ventures 2025 Report、techcrunch.com、getpanto.ai、aibusinessweekly.net、webpronews.com

---

## 五、合作夥伴清單

Anthropic 的核心策略是「成為唯一在三大雲端（AWS、Azure、Google Cloud）同時提供的前沿模型」。這使其同時獲得分發通路與談判槓桿，但也必須支付龐大的利潤分成。

### 5.1 雲端與計算合作夥伴

| 夥伴 | 投資金額 | 計算承諾 | 關鍵細節 |
|---|---|---|---|
| **Amazon / AWS** | 總計 $33 B（2023 年初始 $4 B + $4 B 續投、2026 年 4 月再投 $25 B） | Anthropic 承諾未來 10 年支出 $100 B+ 於 AWS | 最多 5 GW 的 Trainium2–4 容量；Claude 全平台整合進 AWS；AWS 是 Anthropic 自 2024 年起的「主要訓練夥伴」 |
| **Google Cloud / Broadcom** | Google 累計投資約 $3 B | 2025 年 10 月簽定最高 1 M 片 TPU、1 GW 以上；2026 年 4 月再擴大至 3.5 GW，2027 年上線 | 使用 TPU 和 Ironwood 第七代加速器；與 Broadcom 合作客製晶片 |
| **Microsoft / Azure** | 最多 $5 B（2025 年 11 月宣布） | Anthropic 承諾採購 $30 B 的 Azure 算力 | Claude 整合進 Azure Foundry；Satya Nadella 稱雙方「越來越是彼此的客戶」 |
| **Nvidia** | 最多 $10 B（2025 年 11 月宣布） | Anthropic 購買 1 GW 的 Grace Blackwell + Vera Rubin 系統 | 雙方首次深度合作，共同優化模型與硬體架構 |

**一項關鍵策略意涵**：2025 年 10 月的 AWS 大規模服務中斷期間，Claude 因多雲架構維持正常運作，這成為 Anthropic 對外銷售「韌性」的實證案例。

### 5.2 國防與政府夥伴

- **Palantir**：2024 年 11 月起與 AWS 三方合作，提供 Claude 給美國情報社群
- **美國國防部**：2026 年 3 月發生「五角大廈對峙」事件——當 DoD 要求修改合約以移除對大規模監控的限制時，Anthropic 堅持其「紅線」立場，結果被國防部長指定為「供應鏈風險」。短期內傷害政府業務，長期反而鞏固民間企業心中的「負責任 AI」形象。

### 5.3 其他關鍵股東投資人

- **Google**（非 Google Cloud 商業合約）：戰略投資者，累積投入約 $3 B
- **ICONIQ Capital**：Series F 領投
- **Lightspeed Venture Partners**：Series F 共同領投
- **Fidelity Management & Research**：Series F 共同領投
- **GIC**（新加坡主權基金）：Series F 與 Series G 領投
- **Coatue Management**：Series F 與 Series G 領投
- **Sequoia Capital**：罕見地同時投資 Anthropic 與 OpenAI
- **其他 Series G 共同領投**：D. E. Shaw Ventures、Dragoneer、Founders Fund、MGX（阿聯主權科技基金）
- **其他參與**：BlackRock、Blackstone 關聯基金、Qatar Investment Authority、Salesforce Ventures
- **早期天使**：Jaan Tallinn（Skype 共同創辦人）、Dustin Moskovitz（Facebook 共同創辦人）、Eric Schmidt（前 Google 執行長）

> **來源**：Anthropic 官方新聞稿、CNBC、TechCrunch、GeekWire、Crunchbase、Tracxn、Futurum Group

---

## 六、融資輪次與金額

Anthropic 自 2021 年創立以來累計融資超過 $64 B（截至 2026 年 2 月 Series G 結束），為史上第二高估值的生成式 AI 新創（僅次於 OpenAI）。

| 輪次 | 時間 | 金額 | 投後估值 | 領投者 |
|---|---|---|---|---|
| **Series A** | 2021 年 5 月 | $124 M | — | Jaan Tallinn、James McClave |
| **Series B** | 2022 年 4 月 | $580 M | ~$4 B | Alameda Research（SBF）等 |
| **Spark Capital Round** | 2023 年 5 月 | $450 M | ~$4.1 B | Spark Capital |
| **Google 策略投資** | 2023 年 10 月 | $2 B | — | Google |
| **Amazon 首輪** | 2023 年 9 月–2024 年 3 月 | $4 B + $4 B = $8 B | — | Amazon |
| **Series C/D/E**（多輪延伸） | 2024 年 | 多輪合計約 $10 B+ | ~$18 B（2024 年底） | Menlo Ventures、Lightspeed、General Catalyst、其他 |
| **Series E 擴增** | 2025 年 3 月 | $3.5 B | $61.5 B | Lightspeed（領投） |
| **Series F** | 2025 年 9 月 2 日 | $13 B | $183 B | ICONIQ（領投），Fidelity、Lightspeed 共同領投 |
| **Microsoft + Nvidia 策略投資** | 2025 年 11 月 | $5 B + $10 B = $15 B | — | Microsoft、Nvidia |
| **Series G** | 2026 年 2 月 12 日 | **$30 B** | **$380 B** | GIC、Coatue（領投）；D. E. Shaw、Dragoneer、Founders Fund、ICONIQ、MGX（共同領投） |
| **Amazon 擴大投資** | 2026 年 4 月 20 日 | 再 $25 B（$5 B 現金 + $20 B 綁定商業里程碑） | — | Amazon |

**IPO 進展**：Anthropic 已聘請 Wilson Sonsini 法律事務所協助上市準備，目標 2026 年 10 月在 Nasdaq 上市，主承銷商為 Goldman Sachs 與 JPMorgan Chase，預計融資規模超過 $60 B、估值介於 $400 B–$500 B。不過 CCO Sasha de Marigny 在 2025 年 12 月一場公開活動中表示「目前沒有立即的上市計劃」。

**資本效率悖論的數據**：Anthropic 2026 年預計訓練與推理支出為 $19 B，約等於其年度營收；支付給雲端夥伴的分成預計在 2027 年達到峰值 $6.4 B。Series G 後的 Capital Efficiency Ratio（每 $1 募資產生多少 ARR）約為 0.22，與 Cohere 的 0.24 接近——這是你們專題核心的「J 曲線對照」數據點。

> **來源**：Crunchbase、Tracxn、Sacra、CNBC、Axios、Anthropic 官方新聞稿、GeekWire（2026-04-20）

---

## 七、關鍵新聞事件時間軸

### 2020–2022：創立與早期擴張
- **2020 年 12 月**：Dario Amodei 離開 OpenAI
- **2021 年 1 月**：Anthropic 於舊金山成立，註冊為公益公司
- **2021 年 5 月**：Series A $124 M
- **2022 年 4 月**：Series B $580 M（Alameda Research 領投）— 此後 FTX 崩盤成為公司治理的敏感議題
- **2022 年夏**：內部完成 Claude 第一版訓練，但選擇不立即發布

### 2023：產品初步商業化
- **2023 年 3 月**：Claude 1 公開發表
- **2023 年 5 月**：Spark Capital 主導 $450 M 融資
- **2023 年 7 月**：Claude 2 公開，成為首個向一般大眾開放的 Anthropic 模型
- **2023 年 9 月**：Amazon 首輪 $4 B 投資
- **2023 年 10 月**：Google $2 B 投資；Anthropic 成為 AWS「主要雲端夥伴」
- **2023 年 11 月**：Claude 2.1 推出 200 K token 上下文；OpenAI 董事會接觸 Dario 接任 Sam Altman 職位，Dario 拒絕

### 2024：Claude 3 家族與國防入場
- **2024 年 3 月 4 日**：Claude 3 家族發表（Haiku / Sonnet / Opus 三層定價結構）
- **2024 年 3 月**：Amazon 第二輪 $4 B，總投資達 $8 B
- **2024 年 6 月 20 日**：Claude 3.5 Sonnet 與 Artifacts 功能推出
- **2024 年 8 月**：OpenAI 共同創辦人 John Schulman 離職加入 Anthropic
- **2024 年 10 月 22 日**：Claude 3.5 Sonnet v2 與 3.5 Haiku 同步推出
- **2024 年 11 月**：與 Palantir + AWS 合作，向美國情報與國防機構提供 Claude
- **2024 年底**：年化營收達 $1 B

### 2025：規模化與企業市場領導地位
- **2025 年 2 月**：Claude Code 內測啟動
- **2025 年 3 月**：Series E 擴增 $3.5 B，估值達 $61.5 B
- **2025 年 5 月 22 日**：Claude 4 家族發表（Opus 4 + Sonnet 4）；Opus 4 被分類為 ASL-3
- **2025 年 5 月**：Claude Code 正式對外發表
- **2025 年 6 月**：推出 Claude Gov，供美國國安機構使用
- **2025 年 7 月**：Menlo Ventures 報告顯示 Anthropic 以 32% 市佔率超越 OpenAI 成為企業 LLM API 領導者
- **2025 年 8 月**：Claude Opus 4.1 發表
- **2025 年 9 月 2 日**：Series F $13 B，估值 $183 B
- **2025 年 10 月 23 日**：Google TPU 大單——最多 1 M 片 TPU，超過 1 GW 容量
- **2025 年 11 月**：Claude Code 年化營收達 $1 B（為史上最快達到此里程碑的企業軟體）
- **2025 年 11 月 4 日**：與 Cognizant 合作，部署到 350,000 名員工
- **2025 年 11 月**：Microsoft ($5 B) + Nvidia ($10 B) 雙重策略投資；宣布 $50 B 投入美國本土計算基礎設施；Claude 成為唯一在 AWS、Azure、Google Cloud 同時可用的前沿模型
- **2025 年末**：年化營收 $9 B–$10 B

### 2026：Series G 與無前例的規模爆發
- **2026 年 1 月**：Cowork 內測；Team Premium 定價從 $150/座降至 $100/座
- **2026 年 1 月**：月均推出 30+ 新產品與功能
- **2026 年 2 月 7 日**：Claude Opus 4.6 發表
- **2026 年 2 月 12 日**：**Series G $30 B，估值 $380 B**（史上第二大私募融資，僅次於 OpenAI $40 B）
- **2026 年 2 月 18 日**：Claude Sonnet 4.6 發表
- **2026 年 2 月**：年化營收達 $14 B；Claude Code ARR 達 $2.5 B
- **2026 年 3 月**：年化營收攀升至 $19 B；聘請 Wilson Sonsini 準備 IPO
- **2026 年 3 月**：**「五角大廈對峙」事件**——DoD 將 Anthropic 標示為「供應鏈風險」
- **2026 年 3 月 13 日**：取消長上下文請求的附加費用
- **2026 年 4 月 7 日**：Google + Broadcom 合作擴大至 3.5 GW，2027 年上線；年化營收達 $30 B，百萬美元級客戶突破 1,000 家
- **2026 年 4 月**：Claude Opus 4.7 發表；Claude Design 上線；Mythos Preview 推出（威力過強，僅透過 Project Glasswing 提供給關鍵基礎設施夥伴，$25/$125/MTok）
- **2026 年 4 月 20 日**：Amazon 再投資 $25 B，總投資額達 $33 B；Anthropic 承諾 10 年內在 AWS 上花費 $100 B+
- **目標：2026 年 10 月 Nasdaq 上市**

---

## 八、給專題撰寫的幾個重點提示

1. **與 Cohere 對照的關鍵數據**：Anthropic $64 B 募資 vs. Cohere ~$1 B、估值比 54:1、ARR 比 125:1，但資本效率比 0.22 vs. 0.24 幾乎相同——這是 J 曲線分析最有力的切入點。

2. **Hotelling 模型定位**：Anthropic 明顯站在「效能–合規軸」的高效能高合規端，Claude Gov 與 Palantir 合作是合規端的極致延伸；Meta LLaMA 4 壓縮效能端但無法觸及合規端，這正是 Anthropic 的護城河邏輯。

3. **平台包覆（Platform Envelopment）張力的核心素材**：AWS/Google/Microsoft 三者的自有模型（Nova、Gemini、OpenAI via Azure）都與 Claude 競爭，但他們同時是 Claude 的分發通路與最大投資人——這是你們專題最有張力的分析切片。

4. **DoD 事件**：是信號理論的絕佳案例——Anthropic 以短期政府業務損失換取民間企業的信任溢價，可對接 Spence 的 job market signaling 框架。

5. **資料時效提醒**：2026 年 4 月 20 日的 Amazon 擴大投資是最新事件，建議在報告正式繳交前再做一次搜尋確認有無新變動。
