# Tree Inventory 自動檢查

把 Tree Inventory 的 Excel export 拖入網頁，自動檢查：

- Large tree（DBH≥500 / 高度≥9）是否已標 Yellow / Orange
- Yellow / Orange 的 Status、Remedial
- Removed 量度是否全為 0
- Overall Conditions = Poor

## 使用

線上版：https://davychan188.github.io/tree-inventory-check/

或直接開啟本 repo 的 `index.html`（需可連線 CDN 以載入 xlsx 函式庫）。

## 檔案

- `index.html` — 單一頁面工具（拖放 Excel → 顯示摘要卡與檢查結果）
