# 思維獵犬模式 (Thinking Hound Mode) 🐕

> **「獵犬不只是兇猛，更在於牠的聽覺與紀律。」**

這是一套為 Google Anthropic / Claude Code環境量身打造的自定義 Agent 指令系統。它改進自 Burke Holland 的 "Beast Mode"，旨在將強大的 AI 代理轉化為一隻「受控、精準且具備防禦性思考」的開發獵犬。

![Thinking Hound Mode](https://img.shields.io/badge/Status-Beta-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🌟 核心特點

1.  **強制煞車點 (Braking Checkpoint)**：
    拒絕「盲目衝刺」。在進入實作階段前，獵犬必須停下來展示四個層次的規劃：**規格 (Specify)**、**釐清 (Clarify)**、**計畫 (Plan)** 與 **任務 (Tasks)**。只有在您授權後，實作才會啟動。

2.  **紅藍軍對抗協定 (Red-Blue Team)**：
    內建偵錯與韌性思考。在產出任何程式碼前，獵犬會啟動紅軍模式，扮演惡意環境挑戰自己的解法，直到程式碼具備足夠的防禦力（Try-Catch, Fallback, Validation）才准許輸出。

3.  **意圖偵測閘 (Intent Gate)**：
    具備「人情世故」的判斷力。
    - 使用 `[sudo]` 或 `[快]` 標籤：進入 **Hound Execution Mode**，極速修復小問題。
    - 複雜架構變動：自動進入 **Hound Planner Mode**，確保安全第一。

4.  **量子認知工作流**：
    超越傳統指令，使用多維度分析（元認知、 археology、多視角分析）來解決現代化且複雜的程式庫問題。

---

## 🚀 安裝指南

要把您的 AI 助手變成一隻敏銳的思維獵犬，只需以下幾步：

### 方法一：直接載入（推薦）

將本專案中的 `thinking-hound-mode.agent.md` 檔案上傳到您專案的 `.github/agents/` 目錄下：

1. 在您的專案根目錄建立目錄：
   ```bash
   mkdir -p .github/agents
   ```
2. 將 `thinking-hound-mode.agent.md` 放入該資料夾。
3. 重新啟動您的 AI 助手環境。

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
> _By Aster Wei & The Antigravity Team_
