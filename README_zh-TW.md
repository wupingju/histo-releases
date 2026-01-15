# Histo

一個完全由 Claude Code 與 Opus 4.5 打造的原生 macOS 應用程式，用於瀏覽、搜尋、分析你的 Claude Code 對話歷史。

> 在一條時間軸上看見散落在不同專案中的關鍵決策，瞬間喚醒你的思考脈絡。

[![macOS 14+](https://img.shields.io/badge/macOS-14%2B-blue)](https://github.com/wupingju/histo-releases/releases)
[![Latest Release](https://img.shields.io/github/v/release/wupingju/histo-releases)](https://github.com/wupingju/histo-releases/releases/latest)

[English](./README.md) | 繁體中文

---

## 為什麼需要 Histo？

使用 Claude Code 開發時，那些幫助你釐清意圖、探索想法、做出決策的對話，散落在不同專案和時間點。Histo 把它們整合在一起，讓你可以：

- **找到關鍵時刻** — 快速定位那些想法與決策被鍛造的對話
- **從模式中學習** — 回顧成功的對話模式以便重複使用；記取失敗經驗以免重蹈覆轍
- **延續你的脈絡** — 從中斷處繼續，不必重新解釋一切

---

## 功能特色

### 跨專案時間軸

一次瀏覽所有專案，或聚焦在特定專案。

- 按時間順序排列所有 session
- 依對話回合數篩選，快速找到重要對話
- 一鍵跳轉至完整對話內容

### 智慧對話呈現

以最易讀的方式呈現對話。

- **Turn 分組** — 同一角色的連續訊息自動合併，更易閱讀
- **Sub-Session 分割** — 較長對話依 git commit 自動切割，快速跳轉到關鍵段落
- **工具呼叫折疊** — 優先呈現對話內容，需要時再展開工具細節
- **豐富內容支援** — 程式碼、Diff、圖片、Markdown、Shell 輸出

### 全域搜尋

找到任何對話中的任何內容，支援多國語言。

- 跨所有對話的全文搜尋
- 多語系混合搜尋支援
- 雙欄預覽，點擊直接跳轉到對應段落

### Resume & Fork

從中斷處繼續，或只帶走需要的脈絡重新開始。

- **Resume** — 回到原始 session 繼續對話
- **Fork** — 擷取關鍵討論內容到新的 Claude Code session

### 跨裝置同步

一台 Mac 上的對話，幾秒後就能在另一台看到。

- 透過 iCloud 即時同步
- 按需下載（先同步 metadata，點擊時才下載完整內容）
- 僅傳輸有新增或變更的部分

### 本地優先 & 隱私至上

你的資料只存在於你的裝置和 iCloud，絕不經過第三方伺服器。

- 無需註冊帳號
- 無任何追蹤或分析機制
- 離線也能正常使用

### 安全 & 不干擾原始資料

Histo 絕不修改你的 `.claude` 原始檔案。

- 唯讀存取你的 `.claude` 資料夾
- 所有快取存放於獨立的 SQLite 資料庫
- 自動備份原始資料

---

## 安裝方式

### 下載

從 [Releases](https://github.com/wupingju/histo-releases/releases/latest) 下載最新的 `.dmg` 檔案。

### 系統需求

- macOS 14.0 (Sonoma) 或更新版本
- Apple Silicon 或 Intel Mac

### 首次啟動

1. 打開 `.dmg`，將 Histo 拖曳至「應用程式」資料夾
2. 啟動 Histo
3. 授權讀取 Claude Code 資料目錄
4. 你的對話將自動完成索引

---

## 方案與定價

### Basic（免費）

- iCloud 同步
- 不限 session 數量
- 讀取最近 30 天的對話紀錄
- 搜尋最近 30 天的對話紀錄

### Pro

- **無時間限制** — 完整存取所有對話歷史
- AI 分析功能（即將推出）

### Pro 定價

| 階段 | 價格 | 說明 |
|------|------|------|
| Alpha（目前） | **免費** | 所有 Pro 功能皆已解鎖 |
| Early Bird | $29 USD | 一次性買斷，含一年免費更新 |
| 1.0 正式版 | $39 USD | 一次性買斷，含一年免費更新 |

*Histo 目前處於 alpha 階段，所有 Pro 功能在此期間皆為免費。*

---

## 開發藍圖

### 計劃中

- [ ] 本地 LLM 支援對話分析
- [ ] 進階搜尋篩選器
- [ ] 完整鍵盤快捷鍵支援
- [ ] 匯出選取訊息為 PDF
- [ ] 多國語系支援 (i18n)

### 評估中

- [ ] 行動裝置 App（唯讀）
- [ ] 使用統計與洞察
- [ ] 雲端 AI 模型整合（僅支援 BYOK）

---

## 資料與隱私

Histo 以隱私為核心設計原則：

| 項目 | Histo 的做法 |
|------|-------------|
| **資料儲存** | 本地 SQLite 資料庫 + 你的 iCloud |
| **原始檔案** | 唯讀，絕不修改 |
| **需要帳號** | 否 |
| **分析/追蹤** | 無 |
| **第三方伺服器** | 無 |

你的對話資料絕不會離開你的裝置和 iCloud 帳號。

---

## 支援

- **Email**: [support@histo.cc](mailto:support@histo.cc)
- **Website**: [building]
