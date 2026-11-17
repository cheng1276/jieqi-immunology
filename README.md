# 節氣的免疫學

現在是什麼節氣？打開網頁就知道。每個節氣都附上三候的古籍原文與現代解釋，以及一集免疫學短片。

- GitHub Pages：<https://cheng1276.github.io/jieqi-immunology/>
- Cloudflare Pages：<https://jieqi-immunology.pages.dev/>

## 網頁內容

- **節氣時刻**：網頁依太陽視黃經即時計算，並與中央氣象署 [2026 年](https://www.cwa.gov.tw/Data/astronomy/2026cal.pdf)、[2027 年](https://www.cwa.gov.tw/Data/astronomy/2027cal.pdf)年曆逐一核對。節氣開始的那一天整天都算這個節氣，之後每五天一候。
- **七十二候**：「古」引自元・吳澄《月令七十二候集解》，「今」用現代的氣象學與生物學解釋古人看到的現象。
- **影片**：Reels 系列「節氣裡的免疫學」，從立冬（第 1 集）到霜降（第 24 集），每個節氣一集，節氣當天在網頁上開放播放。醫學內容依據各集所列的文獻。

影片與網頁都是衛教資訊，不能取代看診。

## 檔案

| 路徑 | 內容 |
| --- | --- |
| `index.html` | 網頁本體，資料、樣式與程式都在這個檔案裡 |
| `v/01.mp4` – `v/24.mp4` | 影片，01 是立冬，24 是霜降 |
| `p/01.jpg` – `p/24.jpg` | 影片封面 |
| `f/` | 字型子集與授權條款 |
| `og.jpg` | 分享連結時的預覽圖 |
| `_headers` | Cloudflare Pages 的快取設定 |

網站沒有建置步驟：推送到 `main` 後，GitHub Pages 與 Cloudflare Pages 都會直接發佈這個資料夾。

Cloudflare Pages 不支援影片的分段讀取（iPhone 的 Safari 播放時需要），所以 Cloudflare 上的網頁會先從 GitHub Pages 讀取影片；讀不到時，改為整支下載 Cloudflare 上的檔案再播放。

## 字型

- 明體：Noto Serif TC，SIL Open Font License 1.1，見 `f/OFL-NotoSerifTC.txt`。
- 圓體：jf open 粉圓 2.1，SIL Open Font License 1.1（漢字部分源自 Kosugi Maru，Apache License 2.0），見 `f/LICENSE-jf-openhuninn.txt`。依 OFL 對保留字型名稱的規定，網頁使用的子集字型改名為「Jieqi Round」。

## 版權

影片、封面與文字的版權屬原作者所有。字型依各自的授權條款使用。
