# 保單訊息小幫手

給理財顧問用：把旅遊保「投保成功」畫面的文字貼上，自動抽出保單號碼、承保日期、目的地區域、總額，按範本生成 WhatsApp 訊息（含 emoji），一鍵複製或直接開 WhatsApp。

- 純前端單一檔案 `index.html`，資料不上傳；範本及顧問電話存在瀏覽器 localStorage。
- 範本欄位：{保單號碼} {承保日期} {目的地區域} {聯絡電話} {總額} {受保人}
- 抽取規則為通用推測（未有真實保誠畫面樣本），抽不到的欄位會以橙色標示，需手動補上。
- 公開網站：https://porscheyeung.github.io/policy-message/ （GitHub `porscheyeung/policy-message`，main 根目錄 Pages；lphky/policy-message 的 Pages 已下架）
- Zo 密碼保護版：https://lphky.zo.space/policy-message （zo.space 路由，讀取本資料夾 index.html）

- 2026-11-03 依使用者指示將副本自我介紹功能更新至原站：左方預填介紹，可修改並本機儲存；範本使用 {自我介紹}，舊範本相同段落自動轉換，保留其他自訂內容。
