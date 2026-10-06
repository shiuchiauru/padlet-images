# padlet-images

巧茹老師的 Padlet 圖片託管庫。

Padlet 的 API 只接受**公開網址**的附件，不支援直接上傳本機檔案，所以這個 repo 專門存放要貼到 Padlet 上的圖片，透過 `raw.githubusercontent.com` 提供公開連結。

## 目錄結構

一個資料夾對應一面 Padlet 板子：

```
gemini-canvas/            Gemini Canvas 教學實戰牆｜從做教材到上線
gemini-canvas-english/    Gemini Canvas 英語教學實戰牆
ai-agent/                 AI Agent 國語與數學教學應用共備牆
gemini-canvas-subjects/   Gemini Canvas 各科課堂教學應用指南（5+2區段）
```

## 取用網址

```
https://raw.githubusercontent.com/shiuchiauru/padlet-images/main/<資料夾>/<檔名>.png
```

## ai-agent

給國小教師的 AI Agent 國語與數學教學應用共備牆引導圖，繁體中文手繪風格，七個區段各一張，放置於各區最上方。

| 檔名 | 對應區段 | 旁白 |
|---|---|---|
| `00-agent-levels.png` | 🎯 區段 0：課前互動與 5 大等級 | AI Agent 五大等級，測測你的教學超能力！ |
| `01-opencode-setup.png` | 🛠️ 區段 1：OpenCode 安裝攻略 | 三步安裝，開啟你的 AI 智慧助教！ |
| `02-chinese-low.png` | 📖 區段 2：國語科・低年級 | 注音識字變好玩，出題遊戲一鍵搞定！ |
| `03-chinese-mid.png` | 📚 區段 3：國語科・中年級 | 閱讀理解搭鷹架，成語寫作創意爆發！ |
| `04-math-low.png` | 🔢 區段 4：數學科・低年級 | 夜市算錢玩遊戲，生活數感輕鬆養成！ |
| `05-math-mid.png` | 📐 區段 5：數學科・中年級 | 多步驟解題不卡關，幾何錯題大變身！ |
| `06-agent-galaxy.png` | 🚀 區段 6：工具大觀園 | 探索主流 Agent 工具，打造智慧未來教室！ |

對應板子：https://padlet.com/friends69096/ai-agent-g0bjnf6v27657auh

## gemini-canvas

給國小班級導師的 Gemini Canvas 研習用引導圖（聚焦國語與數學），1536×1024，五個區段各一張，各區最上方一張。

| 檔名 | 對應區段 | 旁白 |
|---|---|---|
| `01-canvas-intro.png` | ① Canvas 入門 | 從對話到作品，Canvas 是你的第二個螢幕 |
| `02-make-materials.png` | ② 用 Canvas 做教材 | 一句話，生出三種難度的學習單 |
| `03-interactive-web.png` | ③ 用 Canvas 做互動網頁 | 不用寫程式，做出會回饋、能計分的教材 |
| `04-google-apps-script.png` | ④ 串接 Google Apps Script | 學生答完，成績自動進試算表 |
| `05-netlify-publish.png` | ⑤ 發布到 Netlify | 一個網址，全班都能用 |

## gemini-canvas-subjects

給國小教師的 Gemini Canvas 各科課堂教學應用指南（5+2 區段：國語、數學、英語、自然、社會 + 入門投票與備用區），八個區段各一張引導圖，放置於各區最上方。

| 檔名 | 對應區段 | 旁白 |
|---|---|---|
| `01-canvas-intro.jpg` | 💡 區段一：Google Canvas 是什麼？（入門介紹與課前投票） | 從對話到作品，Canvas 是老師備課與設計互動教材的超級利器！ |
| `02-chinese-low.jpg` | 📖 區段二：國語科課堂應用（低年級：識字、造詞、語文遊戲） | 注音識字變好玩，出題遊戲一鍵搞定！ |
| `03-math-low.jpg` | 🔢 區段三：數學科課堂應用（低年級：數感、圖形空間、生活算術） | 把抽象數字變成具體操作，天平時鐘玩中學！ |
| `04-english-low.jpg` | 🔤 區段四：英語科課堂應用（低年級：Phonics自然發音、單字圖卡、趣味問答） | 沉浸式自然發音與圖卡互動，打造全方位聽說教室！ |
| `05-science-mid.jpg` | 🔬 區段五：自然科課堂應用（中年級：動植物觀察、科學探究、天氣紀錄） | 打造數位探究實驗室，動態觀測與科學變因摸得到！ |
| `06-social-mid.jpg` | 🗺️ 區段六：社會科課堂應用（中年級：家鄉地圖、社區探索、傳統節慶） | 走入家鄉探索生活，方位地圖與節慶巡禮大冒險！ |
| `07-backup-ideas.jpg` | 💡 區段七：備用區一・跨領域延伸與共備靈感（STEAM專題、跨學科教案發想） | 跨學科 STEAM 創意碰撞，線上共備點子庫！ |
| `08-backup-tools.jpg` | 🧰 區段八：備用區二・提示詞庫與常見問題 Q&A（實用 Prompt、發布指南、常見解答） | 備課工具大彙整，提問黃金公式與現場 Q&A！ |

對應板子：https://padlet.com/friends69096/gemini-canvas-s024960kbwsrd2c3ykt5
CDN Base：https://fantastic-hummingbird-a0943f.netlify.app/

## 注意

- **repo 必須維持 public**，改成 private 的話 Padlet 上的圖會全部變成破圖。
- 圖片檔名請勿更動，Padlet 卡片是用固定網址引用的。


