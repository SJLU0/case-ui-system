# Case UI System

## Vue CSR 資料流程

```text
第一次開啟網站
────────────────────────────────

瀏覽器
  │
  │ 請求網站
  ▼
index.html
  │
  │ 載入 /src/main.js
  ▼
main.js
  │
  │ createApp(App)
  ▼
App.vue 掛載完成
  │
  │ fetch("/api/users")
  ▼
後端 API
  │
  │ 查詢
  ▼
SQL
  │
  │ 回傳資料
  ▼
後端 API
  │
  │ 回傳 JSON
  ▼
App.vue 中的 JavaScript
  │
  │ 儲存進 reactive state
  ▼
Vue Template
  │
  │ 自動 render
  ▼
瀏覽器 DOM
```
