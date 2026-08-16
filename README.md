# padlet-images

巧茹老師的 Padlet 圖片託管庫。

Padlet 的 API 只接受**公開網址**的附件，不支援直接上傳本機檔案，所以這個 repo 專門存放要貼到 Padlet 上的圖片，透過 `raw.githubusercontent.com` 提供公開連結。

## 目錄結構

一個資料夾對應一面 Padlet 板子：

```
gemini-canvas/    Gemini Canvas 教學實戰牆｜從做教材到上線
```

## 取用網址

```
https://raw.githubusercontent.com/shiuchiauru/padlet-images/main/<資料夾>/<檔名>.png
```

## gemini-canvas

給國小老師的 Gemini Canvas 研習用引導圖，1536×1024，五個區段各一張。

| 檔名 | 對應區段 | 旁白 |
|---|---|---|
| `01-canvas-intro.png` | ① Canvas 入門 | 從對話到作品，Canvas 是你的第二個螢幕 |
| `02-make-materials.png` | ② 用 Canvas 做教材 | 一句話，生出三種難度的學習單 |
| `03-interactive-web.png` | ③ 用 Canvas 做互動網頁 | 不用寫程式，做出會回饋、能計分的教材 |
| `04-google-apps-script.png` | ④ 串接 Google Apps Script | 學生答完，成績自動進試算表 |
| `05-netlify-publish.png` | ⑤ 發布到 Netlify | 一個網址，全班都能用 |

對應板子：https://padlet.com/friends69096/gemini-canvas-21oahuh3fnslo5ro

## 注意

- **repo 必須維持 public**，改成 private 的話 Padlet 上的圖會全部變成破圖。
- 圖片檔名請勿更動，Padlet 卡片是用固定網址引用的。
