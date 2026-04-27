# 老人的八卦裝卦系統

這是一個基於純前端技術（HTML/CSS/JavaScript）開發的文王卦（六爻）排盤與卦理運算系統。系統將傳統繁瑣的裝卦過程與進階卦理邏輯自動化，提供精準、直觀且符合邏輯的數位化輔助。

## 核心功能

 自動曆法轉換與神煞：內建陰陽曆轉換，即時計算年月日時柱（八字），並自動判定貴人、桃花、驛馬、羊刃、旬空、月破、日沖、日絕、日墓等關鍵神煞。
 多維度起卦模式：
   三數字起卦：輸入上下卦與動爻數字快速成卦。
   太極丸起卦：直接定義六至初爻的 6（陰變陽）、7（陽靜）、8（陰靜）、9（陽變陰）數值。
   隨機起卦：支援系統亂數生成三數字或太極丸組合。
 
 進階卦理運算引擎：
   生剋量化計分：將日月建對各爻的生、剋、沖、合影響轉化為具體的數值分數（支援無條件進位，負分自動標示紅字與括號）。
   動態應期推演：系統自動向未來推演 12 天，精準計算並標記空亡爻的「出旬（出空）」與「填實」天數。
   特殊卦理偵測：全盤掃描活躍池（動爻與化爻），自動判定並標示「貪生忘剋」、「仇忌同動」、「貪合忘生」、「貪合忘剋」等進階動態變化。
 專業排版與一鍵截圖：內建隱藏式截圖引擎。點擊相機按鈕後，系統會在背景生成傳統專業、去蕪存菁的純文字排盤版面（包含精確對齊的八字與自訂色彩標示），並自動寫入系統剪貼簿或觸發下載。
 前端防護機制：具備基礎的防護腳本，阻擋右鍵選單、文字反白複製及常見的開發者工具快捷鍵。

## 執行與使用方式

本系統為單一網頁應用程式（SPA），無需安裝任何後端伺服器或資料庫。

1. 雲端使用：直接訪問已部署的 GitHub Pages 連結 👉 https://eledgetw.github.io/bagua-system/
2. 本地執行：下載專案中的 `index.html` 檔案，使用任何現代瀏覽器（Chrome, Safari, Edge）開啟即可使用。

🔒 隱私說明
本系統為純前端運作，所有命盤數據僅儲存在使用者的瀏覽器本地空間 (localStorage)。開發者不會，也無法存取您的任何個人資料或八字紀錄。


## 贊助這個專案
✨ 喜歡這個專案嗎？ ✨
如果這個工具為你節省了時間 ⏱️，或者對你的研究有所啟發 💡
🧋 點擊圖示請我喝杯珍奶吧 🧋

[![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me)
←←(點擊珍奶圖示贊助作者)
這能讓程式碼持續穩定運行，也讓更多靈感不斷湧現！✨


## 📬 聯絡作者 (Contact)

如果您在使用上有任何建議、發現 Bug，或是對邏輯判定有疑問，歡迎透過以下方式與我聯繫：

- **Email**: [eledgetw@gmail.com](mailto:eledgetw@gmail.com)
- **GitHub Issues**: 您也可以直接在本專案的 [Issues](https://github.com/eledgetw/bagua-system/issues) 頁面提出回饋。

---
**用心排盤，理性論命。**
