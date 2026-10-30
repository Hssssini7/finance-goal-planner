# 目標式財務規劃網站

純靜態網站（單一 index.html，不需要建置），使用 PV / FV / PMT 試算購屋、退休與自訂目標，並依結果給出建議。

線上版：https://你的帳號.github.io/你的儲存庫名稱/

## 檔案
- index.html：網站本體
- README.md：說明文件

## 部署到 GitHub Pages
1. 在 GitHub 建立新的儲存庫（Public），例如 finance-goal-planner
2. 進入儲存庫，按 Add file → Upload files，把 index.html 與 README.md 拖進去，按 Commit changes
3. 進入 Settings → Pages
4. Source 選 Deploy from a branch，Branch 選 main，資料夾選 / (root)，按 Save
5. 等 1 到 3 分鐘，頁面上方會出現網址

## 本機預覽
直接用瀏覽器開啟 index.html 即可。

## 注意
- 試算採月複利、期末投入，結果僅供教學參考，不構成投資建議
- 頁面使用 Google Fonts，載入失敗時會自動改用系統字型
