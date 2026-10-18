# FeelVerse 感受宇宙

> 你的感受是真實的。

一個把 FeelVerse 品牌的七顆感受守護星轉化為互動體驗的單頁 Web App。訪客可以探索七星、閱讀故事、依感受選星、製作含稱呼的星語卡、收藏與下載。

## 公開作品

- [開啟 FeelVerse 感受宇宙](https://sakurastarran.github.io/sakura_starran/)
- [GitHub 儲存庫](https://github.com/sakurastarran/sakura_starran)
- 發布日期：2026-10-18；來源：`main` 分支、`/ (root)`。

## 直接使用

下載 `index.html` 後，以支援現代 HTML / CSS / JavaScript 的瀏覽器開啟。網站沒有外部圖片、字型、CDN 或 API，不需要安裝套件。收藏存在目前瀏覽器的 localStorage，可能因清除網站資料或私人瀏覽而消失；亦可下載 SVG 星語卡留存。

## 互動功能

1. 七顆星球的名稱、感受與英文名搜尋，以及角色狀態篩選。
2. 可開關的星球故事視窗，並可從故事直接選取星球。
3. 依七種需要選星；切換送給自己或朋友，輸入選填稱呼。
4. 等機率隨機選一顆星球，將結果同步到星語卡。
5. 收藏至多 12 張不同內容的卡，重新開啟、移除與重新載入。
6. 下載 1080×1440 SVG 星語卡，或複製星語文字。
7. 剪貼簿被禁止時顯示手動複製視窗；儲存被禁止時仍可暫存與下載。

## GitHub Pages 發布

1. 本作品已使用公開 repository `sakurastarran/sakura_starran`。
2. 將 `index.html` 放在 `main` 分支的根目錄。其他 Markdown 文件為作業說明，不是網站運作的依賴。
3. 開啟 repository 的 **Settings → Pages**。
4. **Source** 選 **Deploy from a branch**；**Branch** 選 `main`；資料夾選 `/ (root)`，再按 **Save**。
5. 等 Pages 顯示實際發布網址後，開啟該網址並測試，再把網址填入課程繳交欄。

本機檔案、GitHub 儲存庫網址與 GitHub Pages 網站網址不同；課程「網站連結」要使用發布完成的 Pages 網址。

## 品牌與實作

- 內容依據 FeelVerse 品牌核心文件 v1.3。四顆正式角色的故事為網頁摘要；其餘三顆只呈現已確立的定位。
- 星球、星環與圖示以 CSS 與內嵌 SVG 製作，屬網站意象，並非正式角色卡牌。
- 以 AI 協助規格、程式實作與修改；實際測試與修正記錄見 `TESTING.md`、`CHANGELOG.md`。
- 未設置會員、付款、交易、庫存或真人陪伴預約。

## 文件

- `index.html`：唯一需要的網站檔案，CSS / JS 全部內嵌。
- `SPEC.md`：實作前建立的規格與 F01–F09 驗收要求。
- `TESTING.md`：已完成與尚未完成的驗證。
- `CHANGELOG.md`：實際 AI 協作與修正過程。
- `SUBMISSION.txt`：另附於繳交資料的文字稿；不影響網站執行。

技術參考：[GitHub Pages 官方文件](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)、[MDN dialog](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/dialog)、[MDN localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)。
