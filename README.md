# 行動學習沙龍 Landing Page

單一檔案 `index.html`，無外部依賴（字型走 Google Fonts CDN），可直接部署到任何靜態空間（GitHub Pages / Netlify / Vercel / 自有主機）。

## 狀態

- 已發佈：https://rt007969.github.io/action-learning-salon/ （GitHub Pages, repo: RT007969/action-learning-salon）
- 報名按鈕連到 Google Form：https://docs.google.com/forms/d/e/1FAIpQLScklLyNI6wkuiPjBQDgOF2MjF5ezN6taEW6dNuJ8U2pxY4ZrA/viewform
- [x] 教練資訊（8 位，照片在 `images/`，源檔在 `~/Desktop/AL Pic`）
- [x] 時間（9/12 六 13:30 報到，14:00–17:30）
- [x] 地點（No.500 活動 課程 攝影空間，臺北市信義區忠孝東路四段500號10樓之一）
- [x] 費用（500 TWD 場地費）
- [ ] 教練簡介目前統一寫「行動學習教練」，之後可個別補充
- [ ] 繳費方式目前寫「報名後告知」，有金流連結後可加進表單或頁面

更新流程：改本地檔案 → `git commit` → `git push`，Pages 會自動重新部署（約 1 分鐘）。

## 結構

Hero → 鉤子（稀缺經驗）→ 沙龍由來 → 行動學習介紹（L=P×Q×R + 三規則）→ 適合帶來的問題 → 三大收穫 → AI 時代價值 → 當天流程 → 適合對象 → 教練團隊 → 報名資訊（CTA）→ FAQ

參考風格：wendellyu.com/empire26 的銷售頁脈絡，視覺改走沙龍的暖紙墨色調。
