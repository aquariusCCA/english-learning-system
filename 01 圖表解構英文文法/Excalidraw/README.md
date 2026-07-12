# Excalidraw 繪圖工作流

放「手繪風漂亮圖表」的**原始檔**（`.excalidraw`）；把匯出的 **SVG** 嵌到筆記裡。

## 步驟
1. 開 [excalidraw.com](https://excalidraw.com)，或在 VS Code 裝 **Excalidraw** 擴充（`pomdtr.excalidraw-editor`）。
2. 依該章書中的圖表**重繪**（忠實重製，不用標 💬）。
3. **存原始檔**到這個資料夾，命名 `章-主題.excalidraw`，例：`01-五大句型.excalidraw`。
4. **匯出圖檔**：`Export image → SVG`，存到**該章的 `images/`**，例：`01 五大句型/images/五大句型.svg`。
5. **嵌入筆記**的 📊 區塊（標準語法，各工具都顯示）：
   ```markdown
   ![五大句型結構圖](images/五大句型.svg)
   ```
6. 到 [[圖表索引]] 補一列。

## 為什麼用 SVG
SVG 在 **VS Code 預覽 / GitHub / Obsidian 全都直接顯示**，是文字格式、放大不糊、版本控制友善。PNG 也可，但會糊且為二進位。

## Mermaid vs Excalidraw 怎麼選
| | Mermaid（寫在筆記裡） | Excalidraw（這裡） |
| --- | --- | --- |
| 適合 | 結構化流程／樹狀圖 | 漂亮、自由排版、手繪風大圖 |
| 形式 | 純文字、可 diff | 圖檔（`.excalidraw` 原始 + `.svg` 嵌入） |
| 渲染 | GitHub 原生／VS Code 需擴充 | 靠匯出的 SVG，到處都顯示 |
