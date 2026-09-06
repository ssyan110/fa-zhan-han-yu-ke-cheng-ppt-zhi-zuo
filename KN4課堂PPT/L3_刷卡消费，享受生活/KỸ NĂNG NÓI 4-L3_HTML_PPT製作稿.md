# KỸ NĂNG NÓI 4 - L3 HTML_PPT 製作稿

## 一、基本資料

| 項目 | 內容 |
|---|---|
| 課程 | Kỹ năng Nói 4 |
| 課次 | L3 |
| 課名 | 刷卡消费，享受生活 |
| 課本頁碼 | P26～P36 |
| 上課時間 | 45 分鐘 × 3 堂，共 135 分鐘 |
| 班級人數 | 40 人 |
| 分組 | 兩人一組，共 20 組；每課 5 組上台 |
| 投影片形式 | HTML 課堂投影片 |
| 製作系統 | `ai-teaching-material-system-main` |
| 設計風格 | 沿用 KN4 已通過的 HTML PPT 格式、風格與工具欄 |
| 製作稿狀態 | 已更新本次指定題目；其餘一般語法自編補足題仍待教師確認 |
| HTML 實作狀態 | 已重建 66 張 L3 HTML PPT；已移除詞語練習一、二、三頁，並完成關鍵練習頁題目數量、內容與邊界檢查 |

頁碼備註：頁碼以實際投影片序號為準，`slide-21.html` 永遠是第 21 張。原本併入 P6 的 `密码` 不另占頁，因此實際第 7 張沿用下一個內容；不建立空白頁碼，也不以課本頁碼取代投影片頁碼。

## 二、製作規則

- `ai-teaching-material-system-main` 只參考 HTML PPT 格式、視覺風格與工具欄；課堂內容依 L3 教師審核稿。
- 投影片說明、操作指令與任務要求使用越南語；中文題目、生詞、例句、句型使用簡體中文。
- 沿用 KN4 的封面、上方 Banner、下方工具欄、閃卡、點擊答案、翻牌效果與下課頁版型。
- 預習回收一題一頁，問題卡背面只放完整中文答案，不顯示「答案」標籤。
- 生詞頁左側白色框為閃卡；正面為拼音＋漢字，背面只放兩行越南語資訊：越南語詞性在上、越南語翻譯在下；不顯示 `Loại từ`、`Nghĩa` 等欄位標籤。詞性使用青綠色 `#5AACAC`，翻譯使用深藍色 `#1A3A5A`，兩行水平、垂直置中，上下間距約 `6px`。
- 若生詞為離合動詞，左側閃卡正面漢字下方加紫色 `Động từ ly hợp`；若為成語，左側閃卡正面漢字下方加紫色 `Thành ngữ`。兩者固定放在漢字下方，不放到背面。
- 生詞頁右側標籤使用 `Mẫu câu`；本頁生詞在例句／對話中用黃底紅字突出。
- 練習頁不得直接渲染完整句子；所有填空題需拆成題幹、`answer-slot` 與隱藏答案，點擊後以紅字帶入。AB 對話的 A/B 分行並共用同一題區塊；拼音寫字題提供漢字作答空格；開放題提供學生自行完成的底線。
- 超綱生詞採 inline 標注：漢字上方拼音、漢字下方 `（越南語）`；拼音與越南語字級 `9.33px`，拼音到漢字 `-5px`，越南語到漢字 `-4px`。
- 例句主字級 `22pt`；一般同句換行 `line-height: 44px`；含超綱標注且可能換行時，外層 `line-height: 60px`，超綱詞內部 `line-height: 42px`；段落間距 `6px`。
- AB 對話視為同一個例句區塊，不拆成多個排版容器；A/B 換行使用同一句內部 `line-height` 控制。
- 成語與離合動詞的左卡類型標注，和右側例句中的生詞黃底紅字、超綱詞三層標注分開處理。
- 例句、題目與提示詞製作完成後，必須做超綱生詞交叉檢查與 DOM／截圖排版檢查。
- 圖片不是必須；先完成圖片位置與 Prompt 表，經教師確認並取得明確生圖同意後，才可操作 ChatGPT 生成圖片。生成後先下載、裁切並交教師檢查，確認後才可嵌入 PPT。

## 三、HTML 投影片製作表

| 堂次 | 頁碼 | 檔名 | 頁型 | 畫面主標 | 投影片畫面文字 | 互動／動畫／素材 |
|---|---:|---|---|---|---|---|
| 第 1 堂 | 1 | `slide-01.html` | Cover | `KN4 - Bài 3` | `刷卡消费，享受生活` | 封面右側主圖；標題與圖片不得重疊 |
| 第 1 堂 | 2 | `slide-02.html` | Prompt | `Khởi động` | `Nhìn tranh kể chuyện` | 4 張故事圖由左至右排列；可依序顯示 |
| 第 1 堂 | 3 | `slide-03.html` | Prompt | `Ôn phần chuẩn bị` | `大卫为什么想办信用卡？` | 問題閃卡翻牌，背面完整句答案 |
| 第 1 堂 | 4 | `slide-04.html` | Prompt | `Ôn phần chuẩn bị` | `大卫办信用卡需要提供哪些材料？` | 問題閃卡翻牌，背面完整句答案 |
| 第 1 堂 | 5 | `slide-05.html` | Vocab | `Từ vựng` | `透支 tòu zhī`；`你常常透支每个月的生活费吗？` | 生詞閃卡；`透支`用黃底紅字突出 |
| 第 1 堂 | 6 | `slide-06.html` | Vocab | `Từ vựng` | `输入 shū rù`、`密码 mì mǎ`；例句：`请输入您的账号和密码。`／`你会常常忘记你的密码吗？` | 兩詞同頁閃卡；`账号`超綱標注 |
| 第 1 堂 | 7 | `slide-07.html` | Vocab | `Từ vựng` | `原件`／`复印件`；`办信用卡时，要带身份证的原件和复印件。` | 實際第 7 張；檢查 `身份证` 是否超綱；依結果標注 |
| 第 1 堂 | 8 | `slide-08.html` | Vocab | `Từ vựng` | `财力 cái lì`；`办信用卡为什么要提供财力证明？` | 實際第 8 張；生詞閃卡；例句生詞突出 |
| 第 1 堂 | 9 | `slide-09.html` | Vocab | `Từ vựng` | `附 fù`；`这份电子邮件里附了一个PDF文件。` | 實際第 9 張；生詞閃卡；依交叉檢查處理 `文件` |
| 第 1 堂 | 10 | `slide-10.html` | Vocab | `Từ vựng` | `询问 xún wèn`；`工作上有问题的时候，你会询问谁？` | 實際第 10 張；生詞閃卡；例句生詞突出 |
| 第 1 堂 | 11 | `slide-11.html` | Grammar | `Ngữ pháp / Mẫu câu` | `此外`；課本例句（1）與補充單句 | 實際第 11 張；`Cách dùng`、`VD1`、`VD2` 垂直排列 |
| 第 1 堂 | 12 | `slide-12.html` | Practice | `Luyện tập` | 課堂 3 題：課本 P28「此外」第（1）題＋2 題自編補足；第（2）題保留作業 | 實際第 12 張；題目與答案已更新；仍待教師確認 |
| 第 1 堂 | 13 | `slide-13.html` | Grammar | `Ngữ pháp / Mẫu câu` | 課本 P43：`表填好后，在后面附上所有证明材料。（V.+上）`；第（1）題例句 | 實際第 13 張；語法內容黃底紅字突出；課本頁碼改為 P43 |
| 第 1 堂 | 14 | `slide-14.html` | Supplement | `Bổ sung` | V.+上 補充說明與四組例句 | 實際第 14 張；置於語法講解與練習之間 |
| 第 1 堂 | 15 | `slide-15.html` | Practice | `Luyện tập` | 課堂 3 題：課本 P43「V.+上」第（1）～（2）題＋1 題自編補足；第（3）題保留作業 | 實際第 15 張；自編題待教師確認後才製作 |
| 第 2 堂 | 16 | `slide-16.html` | Prompt | `Ôn phần chuẩn bị` | `王楠为什么这么早回来？` | 問題閃卡翻牌 |
| 第 2 堂 | 17 | `slide-17.html` | Prompt | `Ôn phần chuẩn bị` | `王楠的卡为什么越来越多了？` | 問題閃卡翻牌 |
| 第 2 堂 | 18 | `slide-18.html` | Vocab | `Từ vựng` | `赶 gǎn`；`为了赶十点的火车，他决定坐出租车去车站。`；`Cấu trúc: 赶 + V` | 生詞閃卡；例句生詞突出；檢查 `车站` |
| 第 2 堂 | 19 | `slide-19.html` | Vocab | `Từ vựng` | 紫色 `成语`；`鼓鼓囊囊 gǔ gǔ nāng nāng`；`在班上，谁的书包常常鼓鼓囊囊的？` | 成語標示在左卡正面漢字下方 |
| 第 2 堂 | 20 | `slide-20.html` | Vocab | `Từ vựng` | `收银员 shōu yín yuán`；`谁做过收银员？收银员的工作辛苦吗？` | 生詞閃卡 |
| 第 2 堂 | 21 | `slide-21.html` | Vocab | `Từ vựng` | `享受 xiǎng shòu`；`如果要享受海边风景，你会去哪里旅游？` | 生詞閃卡 |
| 第 2 堂 | 22 | `slide-22.html` | Vocab | `Từ vựng` | `健身`／`健身房`；`越南最有名的健身房叫什么名字？` | 兩詞同頁閃卡 |
| 第 2 堂 | 23 | `slide-23.html` | Vocab | `Từ vựng` | `实惠 shí huì`；`你觉得哪家超市的东西最实惠？` | 生詞閃卡 |
| 第 2 堂 | 24 | `slide-24.html` | Vocab | `Từ vựng` | `赠送 zèng sòng`；`买手机的时候，你希望商家赠送你什么礼物？`；補充 `赠品` | 補充生詞置於例句下方；檢查 `赠品` |
| 第 2 堂 | 25 | `slide-25.html` | Vocab | `Từ vựng` | `馅饼 xiàn bǐng`；`你遇过天上掉馅饼的事吗？` | `天上掉馅饼`整體加拼音與越南語 |
| 第 2 堂 | 26 | `slide-26.html` | Vocab | `Từ vựng` | `提醒 tí xǐng`；`如果有外国朋友来越南旅游，你会提醒他注意哪些事情？` | 生詞閃卡 |
| 第 2 堂 | 27 | `slide-27.html` | Grammar | `Ngữ pháp / Mẫu câu` | `好不容易`；課本例句（1）與補充單句 | 例句垂直排列 |
| 第 2 堂 | 28 | `slide-28.html` | Practice | `Luyện tập` | 課堂 3 題：課本 P30「好不容易」第（1）題＋2 題自編補足；第（2）題保留作業 | 題型統一為 G4；題目與答案已更新；仍待教師確認 |
| 第 2 堂 | 29 | `slide-29.html` | Grammar | `Ngữ pháp / Mẫu câu` | `不管……，都／也……`；課本例句（1）與補充單句 2 句（含 `也` 造句） | 例句垂直排列 |
| 第 2 堂 | 30 | `slide-30.html` | Practice | `Luyện tập` | 課堂 3 題：課本 P30 第（2）、（3）題＋1 題自編題；第（4）題保留作業 | G5 完成句子；第（1）題已於 P29 使用 |
| 第 2 堂 | 31 | `slide-31.html` | Prompt | `Ôn phần chuẩn bị` | `说说什么是“卡奴”。` | 問題閃卡翻牌 |
| 第 2 堂 | 32 | `slide-32.html` | Prompt | `Ôn phần chuẩn bị` | `举几个类似“……奴”的例子。` | 問題閃卡翻牌 |
| 第 2 堂 | 33 | `slide-33.html` | Prompt | `Ôn phần chuẩn bị` | `你手里都有哪些卡？` | 問題閃卡翻牌 |
| 第 2 堂 | 34 | `slide-34.html` | Prompt | `Ôn phần chuẩn bị` | `你用卡消费时遇到过麻烦吗？` | 問題閃卡翻牌 |
| 第 2 堂 | 35 | `slide-35.html` | Vocab | `Từ vựng` | `掏 tāo`；`你现在可以从裤子口袋里掏出什么东西？` | 生詞閃卡 |
| 第 2 堂 | 36 | `slide-36.html` | Vocab | `Từ vựng` | 紫色 `成语`；`应有尽有 yīng yǒu jìn yǒu`；`哪家超市卖的东西应有尽有？` | 成語標示在左卡正面漢字下方 |
| 第 2 堂 | 37 | `slide-37.html` | Vocab | `Từ vựng` | `烦恼 fán nǎo`；背面列 `danh từ、động từ、tính từ`；例句 1：`你最近有什么烦恼吗？`；例句 2：`他在烦恼应该先去工作还是先读大学。`；例句 3：`唉，生活费又透支了，真烦恼。` | 閃卡背面詞性與三類例句分區；例句前加 `1. `、`2. `、` `3. ` |
| 第 2 堂 | 38 | `slide-38.html` | Vocab | `Từ vựng` | `设置 shè zhì`；`设置密码时，你会用你的生日来当作密码吗？`；`当作 dāng zuò` 下方加 `（coi như）` | `当作` 已確認為超綱詞，明確顯示三層 inline 標注 |
| 第 3 堂 | 39 | `slide-39.html` | Vocab | `Từ vựng` | `作废 zuò fèi`；`因为他没有付钱，所以他的虾皮订单被作废了。` | `虾皮`超綱標注 |
| 第 3 堂 | 40 | `slide-40.html` | Vocab | `Từ vựng` | `忽悠 hū yōu`；`你有没有被别人忽悠过？` | 生詞閃卡 |
| 第 3 堂 | 41 | `slide-41.html` | Vocab Special | `Từ vựng` | 左側 `郁闷 yù mèn` 生詞閃卡；右側題目 `你曾经遇到过什么让你很郁闷的事情吗？`；題目下方圖片 | 左卡翻牌；右側題目上、圖片下；題目中的生詞黃底紅字突出 |
| 第 3 堂 | 42 | `slide-42.html` | Vocab Special | `Từ vựng` | 左側生詞閃卡 `插`；右側題目 `你会把插头插进哪里？`；題目下方放圖片 | 左側生詞閃卡；右側題目在上、圖片在下 |
| 第 3 堂 | 43 | `slide-43.html` | Vocab | `Từ vựng` | `吞 tūn`；`如果银行卡被取款机吞了，你会怎么办？` | 生詞閃卡 |
| 第 3 堂 | 44 | `slide-44.html` | Vocab | `Từ vựng` | `中圈套 zhòng quān tào`／`圈套 quān tào`；`你曾經中過別人的圈套嗎？` | `中`四聲；例句改為指定問句；下方放打獵圈套圖片 |
| 第 3 堂 | 45 | `slide-45.html` | Grammar | `Ngữ pháp / Mẫu câu` | `这个……那个……`；VD1 `可是这个密码那个密码，搞得头都大了。`；VD2 `我看看这个，又看看那个，不知道派谁去更合适。` | 語法內容黃底紅字；例句垂直排列；依課本 P32「读一读，试一试」抓取 |
| 第 3 堂 | 46 | `slide-46.html` | Practice | `Luyện tập` | G6「完成句子」三題：①課本 P32 第（2）題之教師指定改寫；②課本 P32 第（3）題；③自編題。答案依序為 `要商家给他打折`、`不知道买哪一件好`、`他总是这个理由那个理由` | 題目由上至下排列；三題均為填空互動；第一題註明教師指定改寫；第三題註明自編題 |
| 第 3 堂 | 47 | `slide-47.html` | Grammar | `Ngữ pháp / Mẫu câu` | `……来……去`；VD1 課文原句 `所以，密码设置来设置去，最后很多卡的密码就记不清了。`；VD2 課本 P32「读一读，试一试」第（1）句 `她的日记是这样写的：我的生活就像风筝似的，在天空中飞来飞去。` | `日记`、`风筝`、`似的` 為超綱詞，依規則加拼音與越南語三層 inline 標注；其餘語法內容黃底紅字；例句垂直排列 |
| 第 3 堂 | 48 | `slide-48.html` | Practice | `Luyện tập` | 課堂 3 題：課本 P32 第（2）題、 第（3）題＋1 題自編題（信用卡情境）；課本 P32 第（4）題保留作業 | 第（2）、（3）題的「翻来覆去」「想来想去」保留在題幹；答案分別為「怎么也睡不着」「还是决定办一张信用卡」，三題均可依序點擊揭示；自編題答案為「看来看去」；作業保留第（4）題 |
| 第 3 堂 | 49 | `slide-49.html` | Function | `Câu chức năng` | `表示排除`；`除了……（以外），还……`、`除了……（以外），都……` | 一頁一功能；只放課本句型；兩句不標示生詞／語法顏色 |
| 第 3 堂 | 50 | `slide-50.html` | Function Explanation | `Câu chức năng` | `除了 A（以外），还 B。`；越南語用途說明；A、B兩圓形圖像化理解；例句 `除了现金以外，我还可以用信用卡付款。` | Cách làm、兩圓形不重疊；A／B使用不同色彩；說明頁不使用 imagegen 生成含文字圖片 |
| 第 3 堂 | 52 | `slide-52.html` | Function Explanation | `Câu chức năng` | `除了 A（以外），những người/vật còn lại 都.....。`；Cách làm 說明；綠色外圓包覆紅色內圓；例句 `除了榴莲以外，其他的水果我都爱吃。`（`榴莲`未在 KN1～KN4 詞彙資料庫找到，按超綱詞標注） | 綠色外圓右上方放小字黑色「Những người/ vật còn lại」與原大小、原綠色「都」，兩者間保留一格空白；整組視覺置中並略向左；刪除外圓內文；紅色內圓縮小；紅色「除了...以外」移至圓形同層、恢復原位置並置於圖形前；不使用 imagegen 生成含文字圖片 |
| 第 3 堂 | 51 | `slide-51.html` | Function Examples | `Câu chức năng` | `除了……（以外），还……` 三句更多例句：① `除了银行卡以外，我还有信用卡。`；② `除了中文以外，我还会说英文。`；③ `一般的会员卡除了打折，商家还会根据消费积分赠送礼物。` | 「Ví dụ thêm」移至下方例句區塊第一行左側；例句由上至下；句型用黃底紅字 |
| 第 3 堂 | 52 | `slide-52.html` | Function Explanation | `Câu chức năng` | `除了 A（以外），những người/vật còn lại 都 B。`；Cách làm 說明；綠色外圓包覆紅色內圓；例句 `除了榴莲以外，其他的水果我都爱吃。`（`榴莲`未在 KN1～KN4 詞彙資料庫找到，按超綱詞標注） | 沿用 P51 已確認的圖像化排版與文字層級 |
| 第 3 堂 | 53 | `slide-53.html` | Function Examples | `Câu chức năng` | `除了……（以外），都……` 三句更多例句：① `除了玛丽，大家都去旅游了。`；② `除了星期日以外，我每天都上班。`；③ `除了苹果以外，其他的水果我都喜欢。` | 「Ví dụ thêm」移至下方例句區塊第一行左側；例句由上至下；句型用黃底紅字 |
| 第 3 堂 | 54 | `slide-54.html` | Function Practice | `Luyện tập câu chức năng` | 課本 P34 表示排除第（1）～（3）題，另含教師指定 F1-S1；完整保留課本功能項目練習 | 不套用一般語法 3-5 題或作業保留規則；F1-S1 為教師指定補充 |
| 第 3 堂 | 55 | `slide-55.html` | Function | `Câu chức năng` | `说明`；四組課本句型 | 句型由上至下 |
| 第 3 堂 | 56 | `slide-56.html` | Function Examples | `Câu chức năng` | 说明的完整例句 | `Chức năng`在上；例句由上至下；句型用黃底紅字 |
| 第 3 堂 | 57 | `slide-57.html` | Function Practice | `Luyện tập câu chức năng` | 課本 P35 说明第（1）～（2）題，完整保留課本功能項目練習 | 不套用一般語法 3-5 題或作業保留規則 |
| 第 3 堂 | 58 | `slide-58.html` | Function | `Câu chức năng` | `双重否定`；六組課本句型 | 句型由上至下 |
| 第 3 堂 | 59 | `slide-59.html` | Function Examples | `Câu chức năng` | 双重否定的完整例句 | `Chức năng`在上；例句由上至下 |
| 第 3 堂 | 60 | `slide-60.html` | Function Practice | `Luyện tập câu chức năng` | 課本 P35 双重否定第（1）～（3）題，完整保留課本功能項目練習 | 不套用一般語法 3-5 題或作業保留規則 |
| 第 3 堂 | 61 | `slide-61.html` | Function | `Câu chức năng` | `表示吃惊、奇怪`；四組課本句型 | 句型由上至下 |
| 第 3 堂 | 62 | `slide-62.html` | Function Examples | `Câu chức năng` | 表示吃惊、奇怪的完整例句 | `Chức năng`在上；例句由上至下 |
| 第 3 堂 | 63 | `slide-63.html` | Function Practice | `Luyện tập câu chức năng` | 課本 P35 表示吃惊、奇怪第（1）～（3）題，完整保留課本功能項目練習 | 不套用一般語法 3-5 題或作業保留規則 |
| 第 3 堂 | 63 | `slide-63.html` | Task | `Nhiệm vụ nhóm` | `Đặt vấn đề: Có nên sử dụng thẻ tín dụng không?`；正方／反方規則 | 兩人一組；一人正方、一人反方；頁面預留 QR Code |
| 第 3 堂 | 64 | `slide-64.html` | Task Guide | `Nhiệm vụ nhóm` | 正方、反方討論方向與提示生詞 | 分兩欄；課堂準備、Formative 錄音、5 組上台發表；上台組也錄音 |
| 第 3 堂 | 65 | `slide-65.html` | Closing | `Kết thúc` | 左卡回家作業；右卡下一課課前預習 | 雙 QR Code；保留下方工具欄 |

## 三之一、練習題目使用登記與回家作業保留

一般語法採「作業先保留、課堂後補足」；功能句則完整登記課本「功能項目練習」並全部安排到課堂。功能句回家作業另建同功能改寫題，使用獨立作業題目 ID，不直接挪用課堂功能題。自編題以 `S` 編號，需經教師確認後才能進入 HTML 製作。回家作業製作時必須讀取本表，排除課堂使用題、自編補足題與高度相似改寫。`Q` 編號以課本該練習區塊的題號為準，`PPT` 欄以實際投影片頁碼為準。

| 題目 ID | 課堂 PPT | 課堂使用 | 回家作業保留 | 題型／備註 |
|---|---:|---|---|---|
| `KN4-L3-G1-P28-Q1` | P12 | 使用 | 否 | `此外` 課本完成句 |
| `KN4-L3-G1-P28-S1` | P12 | 使用 | 否 | `此外` 自編補足，題目與答案已更新，待教師確認 |
| `KN4-L3-G1-P28-S2` | P12 | 使用 | 否 | `此外` 自編補足，題目與答案已更新，待教師確認 |
| `KN4-L3-G1-P28-Q2` | - | 不使用 | 是 | `此外` 課本完成句，保留作業 |
| `KN4-L3-G2-P43-Q1` | P15 | 使用 | 否 | `V.+上` 課本完成句 |
| `KN4-L3-G2-P43-Q2` | P15 | 使用 | 否 | `V.+上` 課本完成句 |
| `KN4-L3-G2-P43-S1` | P15 | 使用 | 否 | `V.+上` 自編補足，題目已更新，待教師確認 |
| `KN4-L3-G2-P43-Q3` | - | 不使用 | 是 | `V.+上` 課本完成句，保留作業 |
| `KN4-L3-G3-P30-Q1` | P28 | 使用 | 否 | `好不容易` 課本完成句 |
| `KN4-L3-G3-P30-S1` | P28 | 使用 | 否 | P28 採 G4 情境造句；`好不容易` 自編題，待教師確認 |
| `KN4-L3-G3-P30-S2` | P28 | 使用 | 否 | P28 採 G4 情境造句；題目與答案已更新，待教師確認 |
| `KN4-L3-G3-P30-Q2` | - | 不使用 | 是 | `好不容易` 課本完成句，保留作業 |
| `KN4-L3-G4-P30-Q2` | P30 | 使用 | 否 | `不管……，都／也……` 課本完成句 |
| `KN4-L3-G4-P30-Q3` | P30 | 使用 | 否 | `不管……，都／也……` 課本完成句 |
| `KN4-L3-G4-P30-S1` | P30 | 使用 | 否 | `不管……，都／也……` 自編完成句；題目與答案已確認 |
| `KN4-L3-G4-P30-Q4` | - | 不使用 | 是 | `不管……，都／也……` 課本完成句，保留作業 |
| `KN4-L3-G5-P32-Q1` | P46 | 使用 | 否 | `这个……那个……` 課本完成句 |
| `KN4-L3-G5-P32-S1` | P46 | 使用 | 否 | P46 採 G6 完成 AB 對話；自編題，待教師確認 |
| `KN4-L3-G5-P32-S2` | P46 | 使用 | 否 | P46 採 G6 完成 AB 對話；自編題，待教師確認 |
| `KN4-L3-G5-P32-Q2` | - | 不使用 | 是 | `这个……那个……` 課本完成句，保留作業 |
| `KN4-L3-G6-P32-Q2` | P48 | 使用 | 否 | `……来……去` 課本 P32 第（2）題：`他躺在床上翻来覆去，＿＿＿＿＿＿。`；答案 `怎么也睡不着` |
| `KN4-L3-G6-P32-Q3` | P48 | 使用 | 否 | `……来……去` 課本 P32 第（3）題：`大卫想来想去，＿＿＿＿＿＿。`；答案 `还是决定办一张信用卡` |
| `KN4-L3-G6-P32-S1` | P48 | 使用 | 否 | `……来……去` 自編題：信用卡情境；答案 `看来看去` |
| `KN4-L3-G6-P32-Q4` | - | 不使用 | 是 | `……来……去` 課本 P32 第（4）題，保留作業 |
| `KN4-L3-F1-P34-Q1~Q3` | P54 | 使用 | 否（作業另建改寫題） | 表示排除；課本完整情境與對話 |
| `KN4-L3-F1-P34-S1` | P54 | 使用 | 否（作業另建改寫題） | 教師指定功能句補充；完成 AB 對話；題目與答案已提供 |
| `KN4-L3-F2-P35-Q1~Q2` | P57 | 使用 | 否（作業另建改寫題） | 说明；課本完整情境與對話 |
| `KN4-L3-F3-P35-Q1~Q3` | P60 | 使用 | 否（作業另建改寫題） | 双重否定；課本完整情境與對話 |
| `KN4-L3-F4-P35-Q1~Q3` | P63 | 使用 | 否（作業另建改寫題） | 表示吃驚／奇怪；課本完整情境與對話 |

詞語練習一、二、三不列入本課 PPT 練習頁，也不列入課堂題目使用登記；除非教師另行明確指定，不得製作為 PPT 頁面。每一個語法點的回家作業仍需另外建立 1 題 AB 對話完成句子與 1 題語法應用造句，且不得重複本表已標示為 PPT 使用的題目。

## 四、生詞頁製作資料

| 頁碼 | 生詞 | 拼音 | 詞性背面 | 越南語翻譯／備註 |
|---:|---|---|---|---|
| P5 | 透支 | tòu zhī | động từ | thấu chi; tiêu vượt số dư |
| P6 | 輸入／密碼 | shū rù／mì mǎ | động từ／danh từ | nhập vào／mật khẩu；`账号`為超綱詞 |
| P7 | 原件／復印件 | yuán jiàn／fù yìn jiàn | danh từ | bản gốc／bản sao；檢查 `身份证`；實際第 7 張 |
| P8 | 財力 | cái lì | danh từ | năng lực tài chính；實際第 8 張 |
| P9 | 附 | fù | động từ | đính kèm；實際第 9 張 |
| P10 | 詢問 | xún wèn | động từ | hỏi, hỏi thêm；實際第 10 張 |
| P18 | 趕 | gǎn | động từ | kịp, tranh thủ làm；`Cấu trúc: 赶 + V` |
| P19 | 鼓鼓囊囊 | gǔ gǔ nāng nāng | tính từ | căng phồng；正面 `Thành ngữ` |
| P20 | 收銀員 | shōu yín yuán | danh từ | nhân viên thu ngân |
| P21 | 享受 | xiǎng shòu | động từ | hưởng, hưởng thụ |
| P22 | 健身／健身房 | jiàn shēn／jiàn shēn fáng | động từ／danh từ | tập thể dục／phòng gym |
| P23 | 實惠 | shí huì | tính từ | lợi ích thiết thực |
| P24 | 贈送／贈品 | zèng sòng／zèng pǐn | động詞／danh từ | tặng, biếu／quà tặng |
| P25 | 餡餅 | xiàn bǐng | danh từ | bánh có nhân；`天上掉馅饼`整體標注 |
| P26 | 提醒 | tí xǐng | động từ | nhắc nhở |
| P35 | 掏 | tāo | động từ | lấy ra, móc ra |
| P36 | 應有盡有 | yīng yǒu jìn yǒu | thành ngữ | cái gì cần có đều có；正面 `Thành ngữ` |
| P37 | 煩惱 | fán nǎo | danh詞／動詞／形容詞 | `danh từ／động từ／tính từ`；背面分區呈現三類例句 |
| P38 | 設置 | shè zhì | động từ | cài đặt；檢查 `当作` |
| P39 | 作廢 | zuò fèi | động từ | mất hiệu lực；`虾皮`為超綱詞 |
| P40 | 忽悠 | hū yōu | động詞 | lừa, gạt |
| P41 | 鬱悶 | yù mèn | tính từ | buồn bực, chán nản |
| P42 | 插 | chā | động từ | cắm, đút vào；特殊填空頁 |
| P43 | 吞 | tūn | động từ | nuốt; bị máy giữ lại |
| P44 | 中圈套／圈套 | zhòng quān tào／quān tào | động詞／danh từ | mắc bẫy／cái bẫy；`中`四聲；成語／圖片輔助 |

## 五、超綱生詞處理

| 詞語 | 頁碼 | 處理 |
|---|---:|---|
| 账号 | P6 | 漢字上方 `zhàng hào`，下方 `（tài khoản）` |
| 身份证 | P8 | 先依 KN1～KN4 資料庫確認；若判定超綱，套用三層 inline 標注 |
| 文件 | P9 | 交叉檢查後，若保留為超綱詞，補拼音與越南語 |
| 车站 | P18 | 交叉檢查後，若保留為超綱詞，補拼音與越南語 |
| 赠品 | P24 | 交叉檢查後，若保留為超綱詞，補拼音與越南語 |
| 当作 | P38 | `dāng zuò`；`（coi như）`；已確認為超綱詞，套用三層 inline 標注 |
| 榴莲 | P51 | `liú lián`；`（sầu riêng）`；詞彙資料庫未找到，按超綱候選處理 |
| 日记 | P47 | `rì jì`；`（nhật ký）`；超綱詞，套用三層 inline 標注 |
| 风筝 | P47 | `fēng zheng`；`（con diều）`；超綱詞，套用三層 inline 標注 |
| 似的 | P47 | `shì de`；`（giống như）`；超綱詞，套用三層 inline 標注 |
| 虾皮 | P39 | 漢字上方 `xiā pí`，下方 `（sàn thương mại Shopee）` |
| 生活费 | P5、P37 | 交叉檢查後，若保留為超綱詞，補拼音與越南語 |

## 六、語法與功能句製作資料

| 頁碼 | 類型 | 內容要求 |
|---:|---|---|
| P11～P15 | 語法／練習 | `此外`、`V.+上`；先保留回家作業題，再安排未保留課本題，不足 3 題時補自編題；補充頁置於 V.+上 講解與練習之間 |
| P27～P30 | 語法／練習 | `好不容易`、`不管……，都／也……`；先保留回家作業題，再安排未保留課本題，不足 3 題時補自編題；練習題型與挖空依課本 |
| P45～P48 | 語法／練習 | `这个……那个……`、`……来……去`；先保留回家作業題，再安排未保留課本題，不足 3 題時補自編題；例句頁垂直排列，練習一個語法一頁 |
| P49～P54 | 功能句 | `表示排除`：功能介紹、兩頁差異說明、兩頁更多例句、課本練習六頁 |
| P55～P57 | 功能句 | `说明`：功能介紹、例句、課本練習三頁 |
| P58～P60 | 功能句 | `双重否定`：功能介紹、例句、課本練習三頁 |
| P61～P63 | 功能句 | `表示吃惊、奇怪`：功能介紹、例句、課本練習三頁 |

功能句例句頁固定使用：句型結構在上、例句在下、例句由上到下排列；新增更多例句頁的 `Ví dụ thêm` 標籤放在下方例句區塊第一行左側；功能句型套用生詞／語法黃底紅字標記。功能句練習保留課本完整情境，不簡化題目。

## 七、P64～P65 辯論任務

| 項目 | 內容 |
|---|---|
| 題目 | `Có nên sử dụng thẻ tín dụng không?` |
| 分組 | 兩人一組；一人正方，一人反方 |
| P64 | 說明辯論題目、正反方立場、發言規則與 Formative 錄音方式；合併任務說明與要求 |
| P65 正方方向 | 方便、不用帶現金、網路購物、累積積分、緊急時可以使用、可以透支 |
| P65 反方方向 | 容易透支、忘記繳款、需要付利息、過度消費、可能被盜刷、增加生活負擔 |
| P65 提示生詞 | 正方：`方便、網路購物、積分、緊急、透支`；反方：`忘記繳款、利息、過度消費、盜刷、負擔`；所有提示詞依超綱檢查處理 |
| 課堂產出 | 每人至少提出 2 個理由，並回應對方至少 1 次；全班 Formative 錄音 |
| 發表 | 5 組上台；上台組也必須錄音；不回家補錄 |

## 八、圖片需求與 Prompt 前置表

圖片流程依 `05_KN4圖片生成與嵌入流程.md`。目前只列需求，不生成、不裁切、不嵌入。

| 頁碼 | 素材 | 用途 | 狀態 |
|---:|---|---|---|
| P1 | 刷卡消費／生活情境主圖 | 封面右側主圖 | 待教師確認 |
| P2 | 4 格故事圖：錢不夠結帳、信用卡結帳、信用卡網路購物、收到高額帳單 | 暖身看圖說故事 | 待教師確認；圖片不嵌文字，第四格 `¥ 50000`由 HTML 疊加 |
| P5～P6、P7～P10 | 錢包、信用卡、密碼、文件、財力證明等 icon | 生詞頁詞義輔助 | 待教師確認 |
| P18～P26 | 收銀員、健身房、贈品、餡餅等 icon | 生詞頁詞義輔助 | 待教師確認 |
| P35～P43 | 口袋、超市、設定密碼、銀行卡／取款機等 icon | 生詞頁詞義輔助 | 待教師確認 |
| P44 | 打獵圈套圖片 | 輔助理解 `圈套` | 待教師確認；不放文字 |
| P42 | 插頭插入插座圖片 | 特殊生詞頁情境 | 待教師確認；不放文字 |
| P64～P65 | Formative QR Code | 辯論錄音 | 待實際連結 |
| P66 | 回家作業／下一課預習 QR Code | 下課頁 | 待實際連結 |

### P2 生圖 Prompt 草案

```text
Create one rectangular 4 by 1 contact sheet image for a Chinese speaking class slide deck. Use exactly four separate square textbook-style illustrations in this left-to-right order:

1. During checkout, a customer opens a wallet and discovers that there is not enough money.
2. The customer takes out a credit card and pays with the credit card.
3. The customer feels that a credit card is convenient: one hand holds the credit card while the other hand operates a computer for online shopping; above the computer is a visual bubble containing only a shopping-cart icon.
4. The customer receives a credit-card bill with a very high amount; show a visual money or bill scene. Leave a clean empty area above the bill for HTML to overlay a currency symbol and 50000 later.

Use consistent soft educational textbook line-art, thin grey-blue outlines, muted pastel fills, pale background, gentle flat shading, subtle low-contrast shadows, clean uncluttered composition, and natural human proportions.
Keep every cell visually separate with narrow white gutters. Do not add readable text, letters, numerals, Chinese characters, Vietnamese words, labels, captions, logos, watermarks, or written speech bubbles. The currency symbol and 50000 will be added in HTML, not inside the generated image.
```

### P44 圈套圖片 Prompt 草案

```text
Create one square educational textbook-style illustration showing a traditional hunting snare trap in a forest clearing. The trap should be clearly recognizable as a non-violent hunting snare or loop trap, with no captured animal, no injury, and no frightening content. Use thin grey-blue line-art, muted pastel fills, pale background, gentle flat shading, and a clean uncluttered composition. Do not add any text, letters, numerals, labels, captions, logos, or watermarks.
```

### P42 插頭／插座圖片 Prompt 草案

```text
Create one square educational textbook-style illustration showing a plug being inserted into a wall socket. Use a close but safe view, with the plug and socket clearly visible and the action easy to understand. Use soft textbook line-art, thin grey-blue outlines, muted pastel fills, pale background, gentle flat shading, and a clean uncluttered composition. Do not add any text, letters, numerals, labels, captions, logos, or watermarks.
```

## 九、製作前檢查

| 檢查項目 | 狀態 | 備註 |
|---|---|---|
| 教師審核稿已確認 | [x] | 可進入製作稿階段。 |
| 本製作稿內容與審核稿一致 | [x] | 已依製作稿建立 HTML 初版；圖片仍待審核。 |
| P7 實際頁碼已同步 | [x] | `slide-07.html` 對應實際第 7 張；不建立空白頁碼。 |
| 超綱生詞交叉檢查 | [ ] | 建立 HTML 前逐頁確認。 |
| 離合動詞／成語左卡標注 | [ ] | 逐頁確認正面漢字下方的越南語類型標注。 |
| 例句、AB 對話與題目排版 | [ ] | DOM／截圖檢查基準線、行距與區塊間距。 |
| 圖片位置與 Prompt 表 | [ ] | 先交教師確認，不直接生圖。 |
| ChatGPT 生圖明確同意 | [ ] | 未取得同意前不得使用任何生圖工具。 |
| 圖片裁切素材教師審核 | [ ] | 裁切後先交付檢查，不直接嵌入。 |
| Formative／下課頁 QR Code | [ ] | 連結確認後才產生與嵌入。 |
| 是否可開始 HTML 實作 | [x] | 已開始建立 L3 HTML PPT；圖片與 QR Code 仍待後續確認。 |
