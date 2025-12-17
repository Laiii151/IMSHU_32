# IMSHU_32

這個專案包含了一系列用於學校管理系統的自動化藍圖（Blueprint）檔案，涵蓋了從課表管理、出缺勤追蹤到 AI 助理等多個功能模組。

## 📋 目錄

- [專案簡介](#專案簡介)
- [Blueprint 檔案說明](#blueprint-檔案說明)
- [功能模組](#功能模組)
- [使用方式](#使用方式)
- [系統需求](#系統需求)

## 專案簡介

本專案使用 Make.com來串接各項服務。

## Blueprint 檔案說明

本倉庫包含以下 Blueprint 檔案：

### 1. **AI Agent.blueprint.json**
AI 智能助理模組，用於處理自動化查詢和智能回應。

**主要功能：**
- 智能對話處理
- 自動化任務執行
- 資訊檢索與回應

### 2. **attendance.blueprint.json**
出缺勤管理系統，用於記錄和追蹤學生出席狀況。

**主要功能：**
- 尋找該學生出缺勤狀況

### 3. **DayOf_QA.blueprint.json**
請假QA。

**主要功能：**
- 將QA存至pinecone

### 4. **Gradess.blueprint.json**
成績管理系統，用於處理學生成績資料。

**主要功能：**
- 尋找該生成績資料

### 5. **Query_question.blueprint.json**
問題查詢系統，用於搜尋和回答特定問題。

**主要功能：**
- 問題搜尋功能

### 6. **Question-rag.blueprint.json**
基於 RAG（Retrieval-Augmented Generation）的問答。

**主要功能：**
將處室的公告存至pinecone

### 7. **ranking.blueprint.json**
排名系統

**主要功能：**
查找該生排名

### 8. **Scraper.blueprint.json**
網頁爬蟲模組，用於抓取網路資料。

**主要功能：**
- 自動資料擷取
- 資料解析與清理

### 9. **timetable.blueprint.json**
課表管理系統

**主要功能：**
- 課表查詢

## 使用方式

### 匯入 Blueprint

1. 登入您的自動化平台（如 Make.com）
2. 選擇「匯入 Blueprint」功能
3. 上傳對應的 `.blueprint.json` 檔案
4. 根據提示配置必要的連接和參數
5. 測試並啟動自動化流程

### 設定步驟

```
1. 下載所需的 Blueprint 檔案
2. 準備相關 API 金鑰和授權
3. 匯入 Blueprint 到平台
4. 配置資料來源和目標
5. 測試運行
6. 正式啟用
```

## 系統需求

- **自動化平台**：Make.com 或相容的 iPaaS 平台
- **資料庫**：根據各模組需求配置
- **API 授權**：
  - 相關教務系統 API
  - AI 服務 API（用於 AI Agent）
  - 雲端儲存服務（如需要）

## 注意事項

⚠️ **使用前請注意：**
- 確保擁有所有必要的 API 授權
- 測試環境中先驗證 Blueprint 功能
- 注意資料隱私和安全規範
- 定期備份重要資料
- 監控自動化流程的執行狀態

## 技術支援

如有問題或建議，請透過以下方式聯繫：
- 開啟 GitHub Issue
- 提交 Pull Request

## 授權

本專案採用的授權方式請參考專案根目錄的 LICENSE 檔案。

---

**最後更新：** 2024

**維護者：** Laiii151
