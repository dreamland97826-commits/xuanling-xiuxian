# 玄靈修仙風雲錄｜GitHub Pages 部署版

## 部署步驟
1. 登入 GitHub。
2. 建立新的 Repository，例如：xuanling-xiuxian
3. 建議 Visibility 選 Public。
4. 將本資料夾內所有檔案上傳到 Repository 根目錄：
   - index.html
   - manifest.webmanifest
   - .nojekyll
5. Repository → Settings → Pages
6. Build and deployment：
   - Source：Deploy from a branch
   - Branch：main
   - Folder：/(root)
7. Save。
8. 等待 GitHub Pages 發布完成。

完成後網址通常是：
https://你的GitHub帳號.github.io/xuanling-xiuxian/

## 後續更新
只要用新版 index.html 覆蓋同一 Repository 的 index.html，
分享網址不需要改。

## 手機建議
- iPhone：Safari
- Android：Chrome

## 存檔
遊戲使用 localStorage。
請盡量固定使用同一網址、同一瀏覽器。
若更換 Repository 名稱或網址路徑，瀏覽器會視為不同網站，原存檔不會自動沿用。
