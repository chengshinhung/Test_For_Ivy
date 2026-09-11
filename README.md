# Test_For_Ivy

這是一個最小但完整的 GitHub Pages 靜態網站示範。

網站本體只有：

- `index.html`：HTML、CSS、JavaScript 全部放在同一個檔案裡
- 不需要 Node.js
- 不需要資料庫
- 不需要自己租主機

## 發佈成 GitHub Pages

1. 進入這個 repository 的 **Settings**
2. 點左側 **Pages**
3. 在 **Build and deployment** 的 Source 選 **Deploy from a branch**
4. Branch 選 `main`，資料夾選 `/(root)`
5. 按 **Save**

成功後，網站網址通常會是：

`https://chengshinhung.github.io/Test_For_Ivy/`

> 注意：目前 repository 是 Private。GitHub Pages 對 Private repository 的可用性會依 GitHub 帳號方案而異；若只是要免費分享給朋友，最直接的方式是把 repo 改成 Public 再開 Pages。

## 想修改網站？

直接修改 `index.html` 後 commit / push。GitHub Pages 會重新部署新版本。
