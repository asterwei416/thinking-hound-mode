# 思維獵犬模式 (Thinking Hound Mode) 🐕

> **「獵犬不只是兇猛，更在於牠的聽覺與紀律。」**

這是一套為 Google Anthropic / Claude Code環境量身打造的自定義 Agent 指令系統。它改進自 Burke Holland 的 "Beast Mode"，旨在將強大的 AI 代理轉化為一隻「受控、精準且具備防禦性思考」的開發獵犬。

![Thinking Hound Mode](https://img.shields.io/badge/Status-Beta-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🌟 核心特點 (Core Features)

這是一套具備自我疊加能力的 Agent 架構，目前包含以下核心能力：

1.  **🧬 動態與時俱進演化 (Dynamic Perpetual Evolution)**：
    獵犬不再死守過時的文檔。它具備「時間感知」能力，會主動測量當前年份與技術代差，若發現知識過時，會自動啟動「代差質擬模式」並透過網路搜尋抓取當下最前瞻的技術實踐。

2.  **🎨 UI/UX 設計憲法整合**：
    內建專屬的 `ui.instructions.md` 指引。將 UI 套件（如 shadcn/ui）視為 Open Code，進行深度的客製化與延伸。

3.  **🛑 強制煞車點 (Braking Checkpoint)**：
    在進入實作階段前，獵犬必須停下來展示四個層次的規劃：**規格 (Specify)**、**釐清 (Clarify)**、**計畫 (Plan)** 與 **任務 (Tasks)**。

4.  **🛡️ 紅藍軍對抗協定 (Red-Blue Team)**：
    在產出任何程式碼前，獵犬會啟動紅軍模式，扮演惡意環境挑戰自己的解法，直到程式碼具備足夠的防禦力才准許輸出。

5.  **⚡ 意圖偵測閘 (Intent Gate)**：
    根據標籤（如 `[sudo]` 或 `[快]`）自動切換執行或規劃模式。

6.  **🔍 量子認知工作流**：
    使用多維度分析（元認知、考古、多視角分析）來解決現代化且複雜的程式庫問題。

---

## 📜 演化日誌 (Evolutionary Log)

本專案遵循「基因疊加」原則，每一次重大更新都是對前代的繼承與變遷：

### 🧬 V2.0 - 與時俱進的量子演化 (2026.03)
- **變異點**: 導入「時間感知 (Time-Awareness)」引擎。
- **疊加**: 解決了 AI 知識庫（2025 年）與現實開發環境（2026+ 年）脫節的問題。
- **強化**: 加入 `ui.instructions.md` 作為全域設計憲法。

### 🐕 V1.1 - 紀律獵犬的誕生 (2026.02)
- **繼承**: Burke Holland 的 "Beast Mode" 自主性。
- **變異**: 引入「強制煞車點」機制，解決了自主性過高導致的盲目修補問題。
- **強化**: 加入「紅藍軍對抗」防禦性思考。

### 👹 V1.0 - 狂野野獸原型 (起源)
- **基礎**: 高自主、不間斷任務執行的 Beast Mode 原始架構。

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
