# 旅遊小工具 (Travel Helper)

我的每日行程 PWA，專為手機和平板設計，方便查看行程、導航和旅遊資訊。

## 功能

- 每日行程卡片：景點、餐廳、交通
- 導航按鈕：點擊即可在地圖打開路線
- 天氣資訊：顯示每日地點即時天氣
- AI 標籤：自動分析行程文字，標出「必吃美食」、「重要預約號碼」等
- 分頁工具：
  - 航班資訊
  - 住宿資訊
  - 緊急聯絡電話
  - 記帳/預算表

## 檔案結構

travel-app/
├─ index.html # 首頁行程卡片
├─ style.css # 手機優先樣式
├─ script.js # 導航按鈕 + 範例天氣
├─ manifest.json # PWA 設定
└─ README.md # 專案說明

markdown
複製程式碼

## 部署方式

1. 將專案 push 到 GitHub
2. 使用 Vercel 或 Netlify 連結 GitHub 自動部署
3. 開啟部署網址，即可在手機或平板使用 PWA

## 注意事項

- 記帳功能可額外串接 Firebase 資料庫
- AI 標籤需搭配 ChatGPT 或其他 AI 助手使用
