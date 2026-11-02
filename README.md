# 保單訊息小幫手

給理財顧問用：把旅遊保「投保成功」畫面的文字貼上，自動抽出保單號碼、承保日期、目的地區域、總額，按範本生成 WhatsApp 訊息（含 emoji），一鍵複製或直接開 WhatsApp。

- 純前端單一檔案 `index.html`，資料不上傳；範本及顧問電話存在瀏覽器 localStorage。
- 範本欄位：{保單號碼} {承保日期} {目的地區域} {聯絡電話} {總額} {受保人}
- 抽取規則為通用推測（未有真實保誠畫面樣本），抽不到的欄位會以橙色標示，需手動補上。
- 公開網站：https://lphky.github.io/policy-message/ （GitHub `lphky/policy-message`，main 根目錄 Pages）
- Zo 密碼保護版：https://lphky.zo.space/policy-message （zo.space 路由，讀取本資料夾 index.html）
