# 搬家照片整理

新竹市搬家照片對照頁，以照片搭配搬運說明呈現。

功能：分類篩選、點照片放大、列印。共 24 張照片。

## 新家擺放

- 二樓：部分櫃子。
- 一樓：其餘搬入新家的物品。
- 哪些櫃子上二樓，由搬家公司現場詢問屋主。

## 檔案內容

- `index.html`：網頁首頁。
- `搬家照片整理.md`：Markdown 圖文對照，可直接在 GitHub 閱讀。
- `assets/photos/`：24 張照片，網頁透過相對路徑讀取。
- `.nojekyll`：GitHub Pages 靜態檔案設定。
- `.gitignore`：排除系統暫存檔與壓縮檔。

## 上傳 GitHub

1. 解壓縮 ZIP，開啟 `moving-photos` 資料夾。
2. 將資料夾內的檔案及 `assets` 資料夾上傳到 GitHub 儲存庫根目錄。
3. 確保 `index.html` 與 `assets` 位於同一層，不要只上傳 ZIP。

網頁無須安裝套件或執行建置。可在本機直接開啟 `index.html`。

## 使用 GitHub Pages 展示

1. 進入儲存庫的 **Settings → Pages**。
2. 在 **Build and deployment → Source** 選擇 **Deploy from a branch**。
3. 選擇已上傳檔案的分支，資料夾選擇 **/ (root)**，按 **Save**。
4. 部署完成後，使用 Pages 顯示的網站網址。

[GitHub Pages 官方設定說明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
