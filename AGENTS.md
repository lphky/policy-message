# policy-message
- 單檔純前端；保留 main 根目錄 GitHub Pages、無後端、無追蹤。
- 預設範本依使用者 2026-10-31 提供文字，只把「注意事頂」改為「注意事項」；改動範本時更新 DEFAULT_TPL（localStorage key 保持 pm.template.v1，用戶自訂範本會覆蓋預設）。
- 抽取規則已按 2026-11-02 真實保誠「旅遊樂」成功投保頁（Ctrl+A 複製）調整：總額取「保費及徵費總額」，受保人可多行。範本 key 已升為 pm.template.v2；名字 pm.name.v1、電話 pm.contact.v1。
- Zo 版（2026-11-02 使用者要求）：zo.space API 路由 `/policy-message`（https://lphky.zo.space/policy-message ），每次請求讀本資料夾 `index.html`，密碼閘門（cookie 30 日）。密碼及簽名密鑰存 `.zo-secret.json`（已 gitignore，勿提交／輸出）；改密碼只需改該檔。Free 方案託管服務已滿，故不用 user service。GitHub Pages 版仍公開、未改動。
