# Python Google Sheets Integrator

🚀 **一個簡單、高效的 Python 工具，用於自動化讀寫 Google Sheets 資料。**

這個專案旨在解決手動輸入資料的痛點，透過 Google Sheets API，讓 Python 腳本能夠輕鬆地將數據寫入試算表，或從中讀取資料進行分析。適用於資料備份、自動化報表、爬蟲資料儲存等場景。

---

## ✨ 核心功能

- **快速讀取**：一鍵將 Google Sheets 的指定工作表（Worksheet）轉為 Python 字典或 Pandas DataFrame。
- **高效寫入**：支援單格寫入、整列/整行更新，以及批量（Batch）寫入以節省 API 配額。
- **自動驗證**：內建 OAuth2.0 與 Service Account 憑證設定流程。

---

## 🛠️ 開發工具與套件

- **語言**: Python Python 3.11.7
- **核心套件**: 
  - `gspread` (或 `google-api-python-client`)
  - `oauth2client` / `google-auth`
  - `pandas` 

---
