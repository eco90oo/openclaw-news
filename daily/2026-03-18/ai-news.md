# 🔥 2026年3月18日 AI 新聞摘要

---

## 1️⃣ Google 推出 Sashiko：AI 程式碼審查機器人守護 Linux 核心

**話題是什麼？**
Google 工程師開發了名為「Sashiko」的 AI 代理程式碼審查系統，專門用於審查 Linux 核心的程式碼提交。Sashiko 會自動監看 Linux Kernel Mailing List (LKML) 上的所有提交，從高階架構驗證到低階資源管理、並發分析等進行全面審查。

**為什麼受關注？**
- **53.6% 偵測率**：在測試中，Sashiko 能成功識別過去 1000 個帶有「Fixes:」標籤的提交中的 53.6% 錯誤
- **100% 人類漏掉**：這些被發現的錯誤，當初全部都通過了人類代碼審查
- **開源且獲 Google 資助**：Google 提供了所有運算資源和 LLM tokens，項目將遷移至 Linux Foundation

**對創業/學習的啟發：**
- AI 輔助程式碼審查已進入實用階段，可考慮開發針對特定領域（金融、醫療）的 AI 審查工具
- 學習提示工程（prompt engineering）用於程式碼分析是極具價值的技能

**真實_URL：** https://sashiko.dev/

---

## 2️⃣ Snowflake Cortex AI 嚴重漏洞：沙盒逃逸可執行惡意程式碼

**話題是什麼？**
安全研究機構 PromptArmor 發現 Snowflake Cortex Code CLI 存在嚴重漏洞。攻擊者可透過「間接提示注入」（indirect prompt injection），讓 AI 在使用者不知情的情況下，下載並執行惡意腳本，利用受害者的憑證在 Snowflake 中進行資料竊取或刪除資料庫等惡意操作。

**為什麼受關注？**
- **沙盒形同虛設**：即使開啟了沙盒模式，攻擊者仍可繞過安全限制
- **已修復但值得警惕**：Snowflake 已於 2026年2月28日發布修復（v1.0.25）
- **這類漏洞會越來越多**：隨著 AI 代理（agents）普及，提示注入攻擊將成為重大資安威脅

**對創業/學習的啟發：**
- 開發 AI 產品時，必須將「不受信任的輸入」視為潛在攻擊向量
- 資安公司有大量商機：AI 代理的紅隊測試、滲透測試需求暴增
- 學習 AI 安全性（prompt injection、sandbox escape）是最具前瞻性的資安領域

**真實_URL：** https://www.promptarmor.com/resources/snowflake-ai-escapes-sandbox-and-executes-malware

---

## 3️⃣ Stripe 發布 Machine Payments Protocol：AI 代理的支付基礎設施

**話題是什麼？**
Stripe 宣布推出「機器支付協議」（Machine Payments Protocol, MPP），這是一個開放標準，讓 AI 代理可以像人類一樣自動進行支付。MPP 由 Stripe 與 Tempo 共同開發，支援穩定幣（stablecoin）支付、信用卡分期付款，以及透過「共享支付代幣」（Shared Payment Tokens）實現企業對企業的交易。

**為什麼受關注？**
- **AI 經濟的基礎設施**：解決了 AI 代理無法獨立完成支付的痛點
- **已有實際應用案例**：Browserbase、PostalForm、Prospect Butcher Co. 等已整合 MPP
- **微交易可能普及**：AI 代理可以「按次付費」使用 API、影印、寄信等服務

**對創業/學習的啟發：**
- **Agentic Commerce（代理商務）**是下一個風口：開發者可以開始構建「AI 為 AI 服務」的商業模式
- 理解區塊鏈/穩定幣支付的開發者是稀缺人才
- 可思考：如果 AI 可以自行付款，哪些傳統業務會被顛覆？（例如：AI 自動訂咖啡、自动續訂 SaaS）

**真實_URL：** https://stripe.com/blog/machine-payments-protocol

---

*資料來源：Hacker News、Phoronix、PromptArmor、Stripe Blog*
*本摘要於 2026-03-18 生成*