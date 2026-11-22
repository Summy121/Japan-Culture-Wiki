# Nihongo Buddy｜日本文化探索 LLM Wiki

**內容：** 5 大文化分類、8 個來源摘要、10 篇 Wiki 條目、8 頁互動式 HTML 簡報。

## 開啟方式
- 開啟 `index.html`：文化 Wiki（搜尋、分類、詞彙、相關文章、小測驗）。
- 開啟 `slides/presentation.html`：8 頁教學簡報（按鈕／左右方向鍵切換、內含 5 題測驗）。
- `sources.csv`：8 篇官方資料與 ingest 狀態；`raw/`：來源摘要。
- `wiki/`：10 篇雙語 Markdown；`AGENTS.md`：生成與驗收規則。
- `logs/workflow.md`：Graph／Loop 與實際查證記錄。
- `logs/validation.json`：程式驗收結果。

## 資料準確性與限制
來源文字以整理重述為主，非全文轉載。條目中的初級日語句子為教學示例；跨地區、場合的文化差異不可一概而論。
目前已完成本機資料整理與靜態網站；**尚未在外部 Agentic LLM Wiki 環境實際進行自主 ingest**，請勿將本機處理紀錄當成外部工具操作證據。

## GitHub Pages
新 Repository 的根目錄應包含 `index.html`、`slides/`、`data/`。部署時可選 `main` 和 `/(root)`。
