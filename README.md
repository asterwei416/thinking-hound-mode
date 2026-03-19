# 思維獵犬模式 (Thinking Hound Mode) 🐕

> **「獵犬不只是兇猛，更在於牠的聽覺與紀律。」**

這是一套為 Google Anthropic / Claude Code環境量身打造的自定義 Agent 指令系統。它改進自 Burke Holland 的 "Beast Mode"，旨在將強大的 AI 代理轉化為一隻「受控、精準且具備防禦性思考」的開發獵犬。

![Thinking Hound Mode](https://img.shields.io/badge/Status-Beta-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

---

5.  **與時俱進的動態演化 (Dynamic Perpetual Evolution)**：
    獵犬不再死守過時的文檔。它具備「時間感知」能力，會主動測量當前年份與技術代差，若發現知識過時，會自動啟動「代差質擬模式」並透過網路搜尋抓取當下最前瞻的技術實踐。

6.  **UI/UX 設計憲法整合**：
    內建專屬的 `ui.instructions.md` 指引。獵犬在此模式下會將 UI 套件（如 shadcn/ui）視為 Open Code，進行深度的客製化與延伸，確保產出的介面具備高品質的微互動與 A11y 合規性。

---

## 🚀 安裝指南

要把您的 AI 助手變成一隻敏銳的思維獵犬，只需以下幾步：

### 方法一：直接載入（推薦）

將本專案中的 `thinking-hound-mode.agent.md` 與 `ui.instructions.md` 檔案上傳到您專案的 `.github/agents/` (或 `.github/instructions/`) 目錄下：

1. 在您的專案根目錄建立目錄：
   ```bash
   mkdir -p .github/agents
   mkdir -p .github/instructions
   ```
2. 將 `thinking-hound-mode.agent.md` 放入 `.github/agents/`。
3. 將 `ui.instructions.md` 放入 `.github/instructions/` (或者跟 agent 放在一起並參考 Plan A 配置)。
4. 重新啟動您的 AI 助手環境。

### 方法二：作為全域技能 (Global Skills)

如果您使用的是 Antigravity 或自定義的環境，可以將此 .md 內容貼入您的 System Prompt 或對應的 Agent 設定檔中。

---

## 🛠️ 如何使用？

當您啟動環境後，您可以像平常一樣對話，但您可以透過標籤來提速：

- **想要精準規劃？** 直接描述您的需求，獵犬會自動進入規劃模式。
- **需要極速修復？**
  - `[sudo] 幫我把這個按鈕改成紅色`
  - `[快] 修復這個語法錯誤`

---

## 📜 授權協議

本專案採用 **MIT License** 授權。歡迎隨時魔改、分叉與分享。

---

> **開發紀錄**：
> 本專案誕生於 2026 年，象徵著從「混亂的野獸 (Beast)」向「有紀律的獵犬 (Hound)」的演化。
> **2026.03 升級**: 導入「動態演化引擎」與「UI 設計憲法」，確保獵犬永遠跑在技術最前沿。
> _By Aster Wei & The Antigravity Team_
