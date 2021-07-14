# Postman-
Postman 的基本操作與整合到Jenkins測試<br /><br />

Postman是個可以測試網站API的免費軟體<br />
一開始需到https://www.postman.com/downloads/ 下載此軟體<br />

### Method 請求方法 | 小助理替你服務的類型，常見有四個  <br />
*GET，取得 (GET) 資料<br />
*POST，新增 (Create) 資料<br />
*PUT，更新 (Update) 資料<br />
*DELETE，刪除 (Delete) 資料<br /><br />
### URL 請求網址 | 小助理要到哪裡執行你交辦的任務 <br /><br />

我們會在請求三個地方，附加特定資訊，提供請求的細部設定，分別是 URL 網址、Header、Body <br />

*URL 網址，通常關於取得資料的篩選，都會放在這裡，可以加上兩種參數，Query Params 搜尋參數，Path Variables 路徑變數，搭配使用，做資料的篩選整理，特別注意不可以把密碼等敏感資訊放在網址<br />
*Header 部分，通常關於 API 請求的標示，都會存放在這裡，例如需要身份驗證的請求，會把驗證身份的token 以 Key-Value 存在 Header (ex. Authorization: token)<br />
*Body 部分，通常 API 需要提交給 Server 的資料，都會放在這裡（ex.註冊表單 name: 小明, password:1234）<br />
