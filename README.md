# 名古屋旅遊 2026 行程網頁

手機好讀的行程網頁。內容都寫在 `content.md`，改它就會更新網頁。

## 第一次上線（約 5 分鐘）

1. 在 GitHub 建立一個新的 repository（例如 `nagoya-2026`）。
2. 把 `index.html`、`content.md`、`README.md` 三個檔案上傳到 repository 根目錄（Add file → Upload files → Commit changes）。
3. 到 Settings → Pages，在 Build and deployment 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 等 1～2 分鐘，頁面上方會出現網址，格式是 `https://你的帳號.github.io/nagoya-2026/`，把它傳給同行者即可。

## 之後要修改行程

1. 在 GitHub 打開 `content.md`，按右上角的鉛筆圖示。
2. 修改內容，按 **Commit changes** 存檔。
3. 約 1～2 分鐘後重新整理網頁就會看到新內容。

想在網頁頁尾放一顆「到 GitHub 修改行程」按鈕：把 `content.md` 第二行改成
`edit: https://github.com/你的帳號/nagoya-2026/edit/main/content.md`

## content.md 寫法

- 單一個 `#` 開頭的行是分頁：
  - `# 2026-10-14 標題` → 每日行程，依日期自動排序並編 Day 幾
  - `# 分頁名稱｜頁面標題` → 其他分頁
- 分頁裡請用 `##` 以下的標題，其餘和 HackMD 相同：`:::info`、`:::warning`、`:::danger`、`:::success`、`:::spoiler 標題`（都用 `:::` 結尾）、`- [ ] 待辦`、`` `編號` ``（點一下可複製）、`[地圖](網址)`。

## 注意

- GitHub Pages 的網址任何人都能開啟，請不要放密碼等敏感資料。
- 直接在電腦上雙擊 `index.html` 會看不到內容，要透過 GitHub Pages 網址開啟。
- 網頁上勾選的待辦只會記在各自的手機上；要讓大家都看到，請改 `content.md` 裡的 `[ ]` / `[x]`。

