# Discord 插件

此插件負責連接 Discord 並處理訊息及指令，採用 Discord.js 實作。

根目錄提供 `config.js` 儲存 Bot Token、應用程式 ID 等設定，可被各模組引用。

## 功能
- 登入與登出
- 全域監聽訊息並回覆 @ 提及
- Slash 指令 `ping`
- 外部 send(data) 可依據 `func` 呼叫插件內部功能，例如發送訊息
  (詳細參數請見 `send.md`)
