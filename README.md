# Prompt Atlas

包含 108 張卡、25 個分類的靜態 Prompt 指令庫，提供搜尋、分類篩選、完整指令查看及複製功能。

## 檔案

- `index.html`：網站入口，內嵌樣式、JavaScript 及指令資料。
- `prompts.json`：與 HTML 內 `prompt-data` 同步的資料。
- `index.md`：完整 Markdown 版指令庫。
- `.nojekyll`：以靜態檔案方式發佈 GitHub Pages。

## 本機查看

直接以瀏覽器開啟 `index.html`。

## 更新

修改指令時，同步更新 `index.html` 的 `prompt-data`、`prompts.json` 及 `index.md`。

## GitHub Pages

在 repository 的 Settings → Pages 選擇 Deploy from a branch，使用 `main` 分支的 `/ (root)`。

## 來源

各卡保留原有來源欄位。
