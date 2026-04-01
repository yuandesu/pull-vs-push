# Pull vs Push — 互動式講解

一個用繁體中文製作的互動式視覺化簡報，說明 **Pull** 與 **Push** 兩種資料傳遞模式的差異，並以 **REST API**（Pull）與 **Webhook**（Push）為具體範例。

## 線上預覽

[View on GitHub Pages](https://yuandesu.github.io/pull-vs-push/)

## 內容涵蓋

- Pull vs Push 的概念差異
- Pull 模式的兩種子類型：On-demand（按需呼叫）vs Polling（定期輪詢）
- Pull 實作範例：REST API 呼叫流程
- Push 實作範例：Webhook 事件推送流程
- 兩種模式的詳細比較表格（即時性、資源消耗、錯誤處理等）
- Datadog 實戰範例（REST API 查詢 monitor / Webhook 接收 alert）
- 互動式動畫，逐頁導覽

## 核心概念

| 模式 | 實作範例 | 發起方 | 特性 |
|------|----------|--------|------|
| Pull | REST API | 你主動呼叫 | On-demand 或定期 polling |
| Push | Webhook  | 對方主動 POST | 事件驅動，即時通知 |

> ⚠️ Push（Webhook）不是 API 的相反。Webhook 底層就是透過 HTTP 實現的。真正的差別是**誰主動發起 request**。

## 技術

純 HTML / CSS / JavaScript，無需任何框架或後端，開啟即可使用。

## 本地執行

直接用瀏覽器開啟 `index.html` 即可。

```bash
open index.html
```
