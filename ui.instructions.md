---
applyTo: "**/*.{tsx,ts,jsx,js,css,html,md}"
---
# UI/UX 指令集 (Design Constitution)

此文件為獵犬模式的視覺與互動核心指南，旨在產出具備生產等級、高美感且符合未來趨勢的介面。

## 🎯 核心原則
- **拒絕平庸**: 嚴禁產出預設的、未經調整的框架樣式。
- **深度延伸**: 視 UI 元件（如 shadcn/ui）為基礎，而非終點。必須根據專案調性進行「深層客製化」(Deep Customization)。
- **時間覺醒**: 主動偵測當前年份。若在 2026 年執行，應具備對「生成式 UI」、「自適應動態佈局」與「玻璃擬態 V3」等當代風格的感知。

## 🛠️ 開發流程 (2026+ 標準)
1. **抓取最新基準 (Fetch)**:
   - 始終使用 `fetch` 工具查閱官方文件（如 [shadcn/ui docs](https://ui.shadcn.com/docs/components)）。
   - **理由**: 您過去的訓練資料無法跟上 2026 年組件庫的高頻迭代。
2. **組件實作 (Implementation)**:
   - 使用 CLI 安裝元件：`pnpm dlx shadcn@latest add <component>`。
   - 優先從本地 `@/components/ui/` 載入，並在組件內進行風格注入 (Style Injection)。
3. **動態互動 (UX)**:
   - 每個元件必須定義完整的「狀態機」(States): Default, Hover, Active, Disabled, Loading, Error。
   - 加入微互動 (Micro-animations)，提升介面的「生動感」(Aliveness)。

## ♿ 無障礙與性能 (A11y & Performance)
- **Aria 合規**: 每個互動元素必須有無障礙標籤。
- **Focus 管理**: 全域鍵盤導航必須流暢。
- **性能預算**: 避免在主執行緒進行過重的視覺運算，優化圖片與粒子效果。

---
> **獵犬訓令**: 「介面不只是像素的堆疊，它是人類與量子資料糾纏的橋樑。」
