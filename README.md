# 🎵 音樂班術科排課系統 - Niaosong Music Schedule Lite

[![GitHub Pages Status](https://github.com/YourUserName/music-schedule-lite/actions/workflows/github-pages/github-pages.yml/badge.svg)](https://github.com/YourUserName/music-schedule-lite/actions/workflows/github-pages/github-pages.yml)
[![Version](https://img.shields.io/badge/Version-v2.2.0-blue.svg)](https://github.com/YourUserName/music-schedule-lite/blob/main/index.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 🌟 專案簡介 (Project Introduction)

本專案是一個專為音樂班設計的術科排課系統，主要功能是提供一個視覺化、互動式的拖曳介面，協助管理者快速安排學生和教師的個別課、團體課和練琴時間，並能即時偵測時間/地點/學生/老師的排課衝突。

該系統是一個純前端 (Pure Frontend) 解決方案，所有資料皆儲存在瀏覽器的 `localStorage` 中，無需伺服器或後端資料庫。

## ✨ 主要功能 (Key Features)

* **拖曳式排課：** 直觀地將課程卡片拖曳到課表上的空位，即時移動課程。
* **衝突偵測：** 即時檢查同一時間內，教室、學生、或老師是否發生衝突。
* **數據備份/還原：** 支援將整個系統數據匯出為 `.json` 備份檔，或從備份檔還原。
* **學生/師資資料庫：** 獨立管理師生資料，支援 CSV 批次匯入與匯出。
* **智慧查詢：** 支援學生、老師、科目、教室的週課表及列表清單查詢。
* **篩選器：** 根據樓層、星期、課程類型（個別/團體/練琴/其他）篩選顯示。
* **響應式設計：** 支援行動裝置及電腦瀏覽器（視覺設計已針對 v2.2.0 優化）。
* **多樣主題：** 支援淺色模式與深色模式切換。

## 🌐 實際使用 (Usage)

您可以直接透過 GitHub Pages 連結存取和使用本系統：

👉 **[前往 Niaosong Music Schedule Lite (v2.2.0)](https://YourUserName.github.io/music-schedule-lite/)**

## 🛠️ 開發與技術 (Technology Stack)

本專案僅使用一個 HTML 檔案實現所有功能：

* **HTML5 / JavaScript：** 核心邏輯和數據管理。
* **Tailwind CSS：** 用於快速且響應式的介面樣式。
* **Font Awesome：** 圖標集。
* **數據持久化：** 瀏覽器 `localStorage`。

## 許可 (License)

本專案以 MIT 許可證發布。

---
