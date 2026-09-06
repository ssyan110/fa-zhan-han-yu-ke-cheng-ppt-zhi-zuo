# KỸ NĂNG NÓI 4 - L1 HTML_PPT 製作稿

## 一、基本資料

| 項目 | 內容 |
|---|---|
| 課程 | Kỹ năng Nói 4 |
| 課次 | L1 |
| 課名 | 在家靠父母，出门靠朋友 |
| 課本頁碼 | p.1-p.12 |
| 上課時間 | 45 分鐘 x 3 堂 |
| 班級人數 | 40 人 |
| 分組 | 兩人一組，共 20 組 |
| 投影片形式 | HTML 課堂投影片 |
| 製作系統 | `ai-teaching-material-system-main` |
| 設計風格 | Original Course |
| 來源稿 | `KỸ NĂNG NÓI 4-L1課堂PPT教師審核稿.md` |
| 製作稿狀態 | 已完成 |
| HTML 實作狀態 | 已完成 |

## 二、製作規則

- 本稿是 HTML 製作前的最後內容稿，不再改課堂架構，只整理每頁的 HTML 製作需求。
- `ai-teaching-material-system-main` 只參考 HTML PPT 格式、視覺風格與工具欄；不得參考或套用其中的課程架構、學生程度、教學流程與活動設計。
- 投影片上的說明、任務指令、活動規則使用越南語。
- 中文題目、生詞、例句、句型使用簡體中文。
- 教師備註可以使用繁體中文，只放在製作稿或 presenter notes，不放進學生畫面。
- 每頁檔名用 `slide-XX.html`，XX 為兩位數頁碼。
- 頁面尺寸依系統規範使用 960 x 540。
- 圖片不是必須，但可用圖片、icon 或簡潔視覺元素優化版面；封面頁、下課頁可優先使用，P26 需要「充電線插進手機」圖片。
- P26 答案使用點擊出現動畫。
- 功能句、語法練習與團體任務頁要清楚標示課本頁數或課堂任務要求。
- 每頁左下角灰色來源文字只顯示對應課本頁碼，格式為 `Sách giáo khoa P{{page}}` 或 `Sách giáo khoa P{{start}}~P{{end}}`；不得顯示 `課文一／二／三` 等內部分類。
- 正式製作 HTML 前，必須先確認教師審核稿的「超綱生詞交叉檢查」已完成並通過；若未完成，本稿只能作為 HTML 製作準備稿。
- 若不得已保留超綱詞，投影片畫面必須做三層標記：上方拼音、中間漢字、下方 `（越南語）` 翻譯。
- 生詞閃卡背面只放兩行越南語資訊：越南語詞性在上、越南語翻譯在下；不顯示 `Loại từ`、`Nghĩa` 等欄位標籤。詞性使用青綠色 `#5AACAC`，翻譯使用深藍色 `#1A3A5A`，兩行水平、垂直置中，上下間距約 `6px`。

## 三、頁型對照

| 頁型 | 用途 | HTML 重點 |
|---|---|---|
| Cover | 封面 | 課名、課程、Lesson 編號，版面簡潔。 |
| Prompt | 暖身、預習回收 | 大問題置中，提示句型與提示詞分區。 |
| Vocab | 生詞講解 | 生詞大字、拼音、詞性、越文、問句或 AB 對話。 |
| Compare | 辨析或補充 | 左右欄或上下分區，清楚比較。 |
| Practice | 練習 | 題目、填空、答案區或教師點擊提示。 |
| Grammar | 語法講解 | 句型、越南語使用情境、課本例句、補充例句。 |
| Function | 功能句 | 功能名稱、常用句、情境或文化補充。 |
| Culture | 文化／歷史快問 | 越南語標題、置中問題、左右兩個人物／群體選項與文字圖像。 |
| Task | 團體任務 | 任務步驟、角色、要求、時間與 Formative 規則。 |

## 四、L1 HTML 投影片製作表

| 堂次 | 頁碼 | 檔名 | 頁型 | 畫面主標 | 投影片畫面文字 | 互動／動畫／素材 | 教師備註 |
|---|---:|---|---|---|---|---|---|
| 第 1 堂 | 1 | slide-01.html | Cover | KN4 L1 | `在家靠父母，出门靠朋友`；`KN4 - Bài 1` | 可用簡潔圖片或 icon 優化版面 | 2 分鐘帶過課名與情境。 |
| 第 1 堂 | 2 | slide-02.html | Prompt | Khởi động | `一位外国朋友来到越南生活，你可以怎么帮助他？`；Mẫu câu：`我可以帮他......`、`我可以带他......`、`我可以告诉他......`、`怎么 + V`；Từ gợi ý：`银行卡、电话卡、房子、新朋友、叫车、超市` | 上方小 Banner 使用越南語 `Khởi động`；問題區不放白底框；問句縮小並儘量一行；`Mẫu câu` 與 `Từ gợi ý` 標籤樣式一致；橫式支架；提示詞上方放拼音、下方放越南語。 | 暖身只做一題，讓學生短答。 |
| 第 1 堂 | 3 | slide-03.html | Prompt | Ôn phần chuẩn bị | `办银行卡需要带哪些证件？`；答案：`办银行卡需要带护照、学生证或者其他有效证件。` | 課文資訊顯示 `课文：P1-2《我想办张银行卡》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示生詞與句型。 |
| 第 1 堂 | 4 | slide-04.html | Prompt | Ôn phần chuẩn bị | `星期六，大卫可以怎么和王楠联系？`；Mẫu câu：`……或者……`；答案：`星期六，大卫可以给王楠打电话或者发短信。` | 課文資訊顯示 `课文：P1-2《我想办张银行卡》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示生詞。 |
| 第 1 堂 | 5 | slide-05.html | Prompt | Ôn phần chuẩn bị | `大卫为什么想办银行卡？`；Mẫu câu：`因为……所以……、……是因为……`；答案：`答案1：大卫想办银行卡，是因为买东西太不方便了。`；`答案2：因为买东西太不方便了，所以大卫想办银行卡。` | 課文資訊顯示 `课文：P1-2《我想办张银行卡》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示生詞。 |
| 第 1 堂 | 6 | slide-06.html | Prompt | Ôn phần chuẩn bị | `王楠什么时候有空儿？`；Mẫu câu：`……都……`；答案：`王楠星期六上午和下午都有空儿。` | 課文資訊顯示 `课文：P1-2《我想办张银行卡》`；題目做成閃卡，點擊翻面顯示答案。 | 不放提示生詞。 |
| 第 1 堂 | 7 | slide-07.html | Vocab | Từ vựng | `办卡 bàn kǎ`；Loại từ：`cụm động từ`；Nghĩa：`làm thẻ`；Mẫu câu：`你办过什么会员卡？` | 無 | 讓學生說自己辦過的卡。 |
| 第 1 堂 | 8 | slide-08.html | Compare | Phân biệt | `办 vs 做`；`办: Dùng khi làm thủ tục, giấy tờ hoặc việc chính thức.`；`做: Dùng khi thực hiện hành động, công việc, món ăn hoặc bài tập.`；Ví dụ：`办证件、办手续、办签证`；`做作业、做饭、做练习` | 無 | 說明什麼情況用辦，什麼情況用做；越南語說明開頭大寫；白框內不放重複小標，左右對照置中；`手续` 做超綱上下標記。 |
| 第 1 堂 | 9 | slide-09.html | Practice | Luyện tập | `Chọn “办” hoặc “做” để điền vào chỗ trống.`；`1. 我明天要去银行__信用卡。`；`2. 我今天晚上要__作业，不能出去玩。`；`3. 你会__牛肉河粉吗？`；`4. 外国学生在中国可以__银行卡吗？`；Đáp án：`办、做、做、办` | 題目由上至下排列；答案點擊後以紅字帶入空格。 | `信用卡` 為銀行卡相關補充詞。 |
| 第 1 堂 | 10 | slide-10.html | Vocab | Từ vựng | `专业 zhuān yè`；Loại từ：`danh từ`；Nghĩa：`chuyên ngành`；Mẫu câu：`你的大学专业是什么？` | 無 | 名詞義。 |
| 第 1 堂 | 11 | slide-11.html | Vocab | Từ vựng | `专业 zhuān yè`；Loại từ：`tính từ`；Nghĩa：`chuyên nghiệp`；Mẫu câu：`你觉得哪个职业需要很专业？` | 無 | 形容詞義。 |
| 第 1 堂 | 12 | slide-12.html | Vocab | Từ vựng | `填 tián`；Loại từ：`động từ`；Nghĩa：`điền`；Mẫu câu：`在申请表上，填你的姓名和生日。` | `申请表` 為超綱生詞，畫面上方標 `shēnqǐng biǎo`，下方標 `（mẫu đơn đăng ký）`，不做黃底紅字生詞標色。 | 讓學生注意填資料的情境。 |
| 第 1 堂 | 13 | slide-13.html | Vocab | Từ vựng | `可靠 kě kào`；Loại từ：`tính từ`；Nghĩa：`đáng tin cậy`；Mẫu câu：`你觉得班上哪一位同学最可靠？` | 無 | 避免變成評價攻擊，提醒說理由要正向。 |
| 第 1 堂 | 14 | slide-14.html | Compare | Bổ sung | `可＋V. = Adj.`；`可＋爱 = 可爱`；`可＋恨 = 可恨`；`可＋信任 = 可信`；`可 ＋ 怕 = ＿＿＿。`；`可＋V. = ?`；Đáp án：`可怕` | 左側例子由上到下、置左，第四題答案點擊後以紅字帶入底線；右側保留提問，`?` 用紅色。 | 補充構詞，不展開太久。 |
| 第 1 堂 | 15 | slide-15.html | Grammar | Ngữ pháp / Mẫu câu | `……，要不……`；Cách dùng：`Dùng để nói hậu quả nếu không làm việc phía trước.`；Ví dụ 1：`我得在公司附近租间房子，要不上下班太不方便了。`；Ví dụ 2：`我们早点儿出门吧，要不可能会迟到。` | 無 | 第一例句固定課本「读一读、试一试」（1）。 |
| 第 1 堂 | 16 | slide-16.html | Practice | Luyện tập | `Hoàn thành câu với “要不”.`；`把剩下的饭菜打包吧，____。`；`我想买本电子词典，____。`；Đáp án：`要不太浪费了、要不学习的时候不方便` | 題目由上至下排列；答案點擊後以紅字帶入空格。 | 使用課本 p.2 未放入回家作業題。 |
| 第 1 堂 | 17 | slide-17.html | Grammar | Ngữ pháp / Mẫu câu | `……或者……`；Cách dùng：`Dùng để đưa ra lựa chọn trong câu nói.`；Ví dụ 1：`外国学生办银行卡，需要带着护照、学生证或者其他有效证件。`；Ví dụ 2：`你可以打电话或者发短信联系我。` | 點擊後紅圈標出 Ví dụ 1 的 `、`，並顯示越南語說明：`Dấu “、” dùng để liệt kê các mục ngắn; “或者” đặt trước lựa chọn cuối.` | 刪除補充說明，聚焦課本句型；標點提示放在 VD1 卡片內，不另開 `Bổ sung` 卡。 |
| 第 1 堂 | 18 | slide-18.html | Practice | Luyện tập | `Hoàn thành hội thoại với “或者”.`；`（1）A: 我要怎么跟你联系？ B: ____都可以。`；`（2）A: 周末我们要去哪里约会？ B: ____，你说去哪儿，咱们就去哪儿。`；Đáp án：`打电话或者发短信、去饭馆或者去超市都可以` | `联系` 為超綱生詞，畫面上方標 `liánxì`，下方標 `（liên lạc）`；題目由上至下排列；答案點擊後以紅字帶入空格。 | 使用課本 p.2 未放入回家作業題，改為 AB 對話填空。 |
| 第 2 堂 | 19 | slide-19.html | Prompt | Ôn phần chuẩn bị | `大卫想去超市买什么？`；答案：`大卫想去超市买变压器、插头、插座，还想买一条长点儿的网线。` | 課文資訊顯示 `课文：P3-4《附近有超市吗》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示。 |
| 第 2 堂 | 20 | slide-20.html | Prompt | Ôn phần chuẩn bị | `大卫为什么要买网线？`；Mẫu câu：`因为……而且……所以……、……是因为……`；答案：`答案1：大卫要买网线，是因为他房间里的网线太短了，而且有时会掉线。`；`答案2：因为大卫房间里的网线太短了，而且有时候会掉线，所以他要买新网线。` | 課文資訊顯示 `课文：P3-4《附近有超市吗》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示生詞。 |
| 第 2 堂 | 21 | slide-21.html | Prompt | Ôn phần chuẩn bị | `王楠为什么不想去超市了？`；答案：`王楠不想去超市，因为他有点儿累。` | 課文資訊顯示 `课文：P3-4《附近有超市吗》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示。 |
| 第 2 堂 | 22 | slide-22.html | Prompt | Ôn phần chuẩn bị | `说说王楠刚到美国时的情况。`；答案：`王楠刚到美国时，生活不太方便，常常需要大卫帮忙。` | 課文資訊顯示 `课文：P3-4《附近有超市吗》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示。 |
| 第 2 堂 | 23 | slide-23.html | Prompt | Ôn phần chuẩn bị | `说说你房间里常用电器的名称。`；Mẫu câu：`在……里，我常用的电器有……`；答案：`在我的房间里，我常用的电器有电脑、手机和充电器。` | 課文資訊顯示 `课文：P3-4《附近有超市吗》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示生詞。 |
| 第 2 堂 | 24 | slide-24.html | Vocab | Từ vựng | `变压器 biàn yā qì`；Loại từ：`danh từ`；Nghĩa：`máy biến áp`；Ví dụ：`去中国旅游，需要带变压器吗？`；`越南的电压是多少伏特呢？中国呢？` | `电压` 為超綱生詞，畫面上方標 `diànyā`，下方標 `（điện áp）`；`伏特` 為超綱生詞，畫面上方標 `fútè`，下方標 `（vôn）`；兩詞不做黃底紅字生詞標色。 | 補充 `电压、伏特／伏`。 |
| 第 2 堂 | 25 | slide-25.html | Vocab | Từ vựng | `插头 chā tóu`；`插座 chā zuò`；`插 chā`；Loại từ：`danh từ / danh từ / động từ`；Nghĩa：`phích cắm / ổ cắm / cắm`；Ví dụ：`把电脑的插头插进插座里。` | 無 | 三詞合併一頁。 |
| 第 2 堂 | 26 | slide-26.html | Practice | Nhìn tranh nói câu | Yêu cầu：`Đặt câu theo tấm hình`；Từ gợi ý：`插、充电线`；Mẫu câu：`把...`；Đáp án：`把充电线插进手机里。` | 需要圖片：手機充電線插進手機。答案點擊出現。 | 圖片清楚即可，不需複雜設計；提示生詞與提示句型放在指令下方。 |
| 第 2 堂 | 27 | slide-27.html | Vocab | Từ vựng | `网线 wǎng xiàn`；Loại từ：`danh từ`；Nghĩa：`dây mạng`；Mẫu câu：`这条网线不够长，我需要买一条新的网线。` | 無 | 讓學生注意量詞 `条`。 |
| 第 2 堂 | 28 | slide-28.html | Vocab | Từ vựng | `掉线 diào xiàn`；Loại từ：`động từ`；Nghĩa：`mất kết nối`；Mẫu câu：`上网课的时候，你常常掉线吗？` | 無 | 可追問什麼時候掉線。 |
| 第 2 堂 | 29 | slide-29.html | Vocab | Từ vựng | `稳定 wěn dìng`；Loại từ：`tính từ`；Nghĩa：`ổn định`；Mẫu câu：`学校的网络稳定吗？` | 無 | 改為學校網路。 |
| 第 2 堂 | 30 | slide-30.html | Grammar | Ngữ pháp / Mẫu câu | `在……下`；Cách dùng：`Dùng để nói một việc xảy ra trong điều kiện, hoàn cảnh hoặc nhờ sự giúp đỡ nào đó.`；Ví dụ 1：`在就业这么困难的情况下，你能找到这么好的工作，祝贺你！`；Ví dụ 2：`在老师的帮助下，我的发音进步了。` | 無 | 第一例句固定課本（1）。 |
| 第 2 堂 | 31 | slide-31.html | Practice | Luyện tập | `Hoàn thành hội thoại với “在……下”.`；`（1）A: 听说他病得很厉害，但又不想去医院，后来呢？ B: 后来在我的劝说下，____。`；`（2）A: 现在没有老师，也没有朋友可以帮我们。怎么办？ B: ____，我们只能依靠自己的努力。`；Đáp án：`他决定去医院看看、在这种情况下` | 題目由上至下排列；答案點擊後以紅字帶入空格。 | 改為 AB 對話填空；P31 `劝说`、`依靠` 需做超綱上下標記。 |
| 第 2 堂 | 32 | slide-32.html | Grammar | Ngữ pháp / Mẫu câu | `A是A，可是……`；Cách dùng：`Dùng để thừa nhận một phần trước, sau đó chuyển ý bằng “可是”.`；Hội thoại：`A: 他做错了，不应该批评他吗？`；`B: 应该是应该，可是不能把所有责任都推给他一个人。` | 無 | AB 對話只放一組，符合模板規則；P32 `批评`、`责任`、`推` 需做超綱上下標記。 |
| 第 2 堂 | 33 | slide-33.html | Practice | Luyện tập | `Hoàn thành hội thoại với “A是A，可是……”.`；`（1）A: 这件衣服要3000块，太贵了吧？ B: ____，可是穿上显得特别帅，有精神。`；`（2）A: 周末我们去看电影吧，你想去吗？ B: ____，可是我没有时间啊。`；Đáp án：`贵是贵、想去是想去` | 題目由上至下排列；答案點擊後以紅字帶入空格。 | 教師要求改為 AB 對話填空；保留課本題核心句。 |
| 第 2 堂 | 34 | slide-34.html | Prompt | Ôn phần chuẩn bị | `除了课文中说到的中国菜，你还知道哪些中国菜？`；Mẫu câu：`除了……以外，我还知道……`；答案：`除了课文中说到的中国菜以外，我还知道饺子、包子、烤鸭。` | 課文資訊顯示 `课文：P5-7《我不吃香菜》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示生詞。 |
| 第 2 堂 | 35 | slide-35.html | Prompt | Ôn phần chuẩn bị | `大卫和王楠先后做了什么？`；Mẫu câu：`先……，然后／接着……`；答案：`大卫和王楠先去银行办了一张银行卡，然后去超市买了一些东西，接着去饭馆吃饭。` | 課文資訊顯示 `课文：P5-7《我不吃香菜》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示生詞。 |
| 第 2 堂 | 36 | slide-36.html | Prompt | Ôn phần chuẩn bị | `大卫有什么忌口？`；答案：`大卫不吃香菜。` | 課文資訊顯示 `课文：P5-7《我不吃香菜》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示。 |
| 第 2 堂 | 37 | slide-37.html | Prompt | Ôn phần chuẩn bị | `谁买单？为什么？`；Mẫu câu：`本来……，后来……。`；`因为……`；答案：`本来是大卫请客，后来王楠买单，因为王楠说要给大卫接风。` | 課文資訊顯示 `课文：P5-7《我不吃香菜》`；題目做成閃卡，點擊翻面顯示完整句答案。 | 不放提示生詞。 |
| 第 2 堂 | 38 | slide-38.html | Vocab | Từ vựng | `点菜 diǎn cài`；Loại từ：`động từ`；Nghĩa：`gọi món`；Mẫu câu：`去中国餐厅吃饭时，你一定会点什么菜？` | 無 | 動詞說明。 |
| 第 2 堂 | 39 | slide-39.html | Vocab | Từ vựng | `忌口 jì kǒu`；`香菜 xiāng cài`；Loại từ：`động từ / danh từ`；Nghĩa：`kiêng ăn / rau mùi`；Hội thoại：`A: 您有什么忌口的吗？`；`B: 我不吃香菜。` | 無 | 合併一頁。 |
| 第 3 堂 | 40 | slide-40.html | Vocab | Từ vựng | `破费 pò fèi`；Loại từ：`động từ`；Nghĩa：`tốn tiền`；Hội thoại：`A: 今天我请客吧！`；`B: 谢谢，让您破费了。` | 無 | 客氣用語。 |
| 第 3 堂 | 41 | slide-41.html | Vocab | Từ vựng | `接风 jiē fēng`；Loại từ：`động từ`；Nghĩa：`đón tiếp bằng bữa ăn`；Mẫu câu：`你会怎么帮朋友接风？` | 無 | 可讓學生說餐廳、活動。 |
| 第 3 堂 | 42 | slide-42.html | Vocab | Từ vựng | `打包 dǎ bāo`；Loại từ：`động từ`；Nghĩa：`gói mang về`；Mẫu câu：`您要在这里吃还是打包？` | 無 | 餐廳情境。 |
| 第 3 堂 | 43 | slide-43.html | Grammar | Ngữ pháp / Mẫu câu | `千万`；Cách dùng：`Dùng để nhấn mạnh lời nhắc, lời dặn hoặc điều không nên làm.`；Ví dụ 1：`最近股票市场非常不稳定，你要买股票的话，千万要小心。`；Ví dụ 2：`明天你出门去机场前，千万要记得带护照。` | 無 | 第一例句固定課本（1），另加肯定例句。 |
| 第 3 堂 | 44 | slide-44.html | Practice | Luyện tập | `Hoàn thành câu theo sách giáo khoa.`；`（3）____千万不要告诉任何人。`；`（4）____，千万不要大意。`；Đáp án：`昨天我跟同事吵架的事，、比赛还没结束` | 題目由上至下排列；答案點擊後以紅字帶入空格。 | 第一題答案自帶逗號，畫面避免重複標點；課本 p.7 題（3）（4）。 |
| 第 3 堂 | 45 | slide-45.html | Grammar | Ngữ pháp / Mẫu câu | `再说`；Cách dùng：`Dùng để bổ sung thêm một lý do.`；Ví dụ 1：`他不是有意的，再说，他也承认了自己的错误，我们不要再批评他了。`；Ví dụ 2：`今天太晚了，再说外面下雨，我们明天再去吧。` | 無 | 第一例句固定課本（1）；P45 `承认` 需做超綱上下標記。 |
| 第 3 堂 | 46 | slide-46.html | Practice | Luyện tập | `Hoàn thành hội thoại với “再说”.`；`（1）A: 我们现在去找她吧。 B: 时间太晚了，____，还是明天再去找她吧。`；`（2）A: 我有两张京剧票，一起去看吧！ B: ____，再说，大卫一直想去看京剧，你约他去看吧！`；Đáp án：`再说她可能已经睡了、这部京剧我已经看过了` | 題目由上至下排列；答案點擊後以紅字帶入空格。 | 教師要求改為 AB 對話填空；保留課本題核心句。 |
| 第 3 堂 | 47 | slide-47.html | Grammar | Ngữ pháp / Mẫu câu | `哪能……呢`；Cách dùng：`Dùng trong câu hỏi tu từ, thường để phủ định, phản bác hoặc nói khách sáo.`；Ví dụ 1：`他哪能这么说话呢？明明是他自己做错了，还对别人说三道四。`；Ví dụ 2：`你帮了我这么多忙，我哪能不谢谢你呢？` | 無 | 第一例句固定課本（1）；P47 `明明`、`说三道四` 需做超綱上下標記。 |
| 第 3 堂 | 48 | slide-48.html | Practice | Luyện tập | `Hoàn thành hội thoại với “哪能……呢”.`；`（1）A: 这些饭菜吃不完，我们扔了吧？ B: 这都是粮食，____？真可惜！`；`（2）A: 我工作不开心，明天就想辞职。 B: 你哪能说辞职就辞职呢？____`；Đáp án：`哪能扔了呢、应该先想清楚辞职后要做什么吧？` | 題目由上至下排列；答案點擊後以紅字帶入空格。 | 教師要求改為 AB 對話填空；P48 A 句 `辞职` 需做超綱上下標記；第二題答案自帶問號，畫面不另加句號。 |
| 第 3 堂 | 49 | slide-49.html | Function | Câu chức năng | Chức năng：`介绍（人／事）`；Ví dụ：`我给你介绍一下。`；`我帮你介绍一下。`；`让我给你介绍一下。`；`我来给大家介绍一下。`；`我自我介绍一下。` | 無 | 功能句介紹頁；例句取自課本 p.9；新增例句中 `自我介绍` 四字用紅色。 |
| 第 3 堂 | 50 | slide-50.html | Function | Luyện tập câu chức năng | `Hoàn thành hội thoại.`；Tình huống（1）：`大卫和王楠去参加一个朋友的生日晚会。王楠要让大卫和她的几个朋友明珠、王兰、玛丽、山田互相认识。`；`（1）王楠：____，这是大卫，美国人，……`；`大卫：大家好！很高兴认识你们。`；`王楠：大卫，____，这是明珠，这是王兰，……`；Tình huống（2）：`大卫不知道地铁的情况，王楠告诉他。`；`（2）王楠：____。北京的地铁一共有10条，……`；Đáp án：`我来给大家介绍一下、我给你介绍一下、我给你介绍一下北京的地铁情况` | 題目由上至下排列；情境說明放在對應題目前；答案點擊後以紅字帶入空格。 | 課本 p.9 功能項目練習；介紹順序文化由老師口頭補充。 |
| 第 3 堂 | 51 | slide-51.html | Culture | Văn hoá / lịch sử | Câu hỏi：`Nên giới thiệu ai trước?`；A：`职员`；B：`领导` | 問題水平置中；下方左右兩區塊，各放一個人文字＋對應文字圖像。 | 介紹順序文化學習；讓學生先猜答案。 |
| 第 3 堂 | 52 | slide-52.html | Culture | Văn hoá / lịch sử | Câu hỏi：`Nên giới thiệu ai trước?`；A：`50岁`；B：`20岁` | 問題水平置中；下方左右兩區塊，各放一個人文字＋對應文字圖像。 | 介紹順序文化學習；讓學生先猜答案。 |
| 第 3 堂 | 53 | slide-53.html | Culture | Văn hoá / lịch sử | Câu hỏi：`Nên giới thiệu ai trước?`；A：`客户`；B：`同事` | 問題水平置中；下方左右兩區塊，各放一個人文字＋對應文字圖像。 | 介紹順序文化學習；讓學生先猜答案。 |
| 第 3 堂 | 54 | slide-54.html | Culture | Văn hoá / lịch sử | Câu hỏi：`Nên giới thiệu ai trước?`；A：`个人`；B：`团体` | 問題水平置中；下方左右兩區塊，各放一個人文字＋對應文字圖像。 | 介紹順序文化學習；讓學生先猜答案。 |
| 第 3 堂 | 55 | slide-55.html | Function | Câu chức năng | Chức năng：`感谢`；Câu thường dùng：`真是太谢谢你了。`；`非常感谢。`；`实在太感谢了。`；`真不知道怎么感谢您才好。` | 無 | 學句型。 |
| 第 3 堂 | 56 | slide-56.html | Function | Luyện tập câu chức năng | `Hoàn thành hội thoại.`；Tình huống：`王楠帮大卫买了一本词典，大卫表示感谢。`；`大卫：____。`；`王楠：不客气。`；Đáp án：`真是太谢谢你了` | 題目由上至下排列；情境說明放在題目前；答案點擊後以紅字帶入空格。 | 課本 p.9 功能項目練習。 |
| 第 3 堂 | 57 | slide-57.html | Function | Câu chức năng | Chức năng：`问路`；Câu thường dùng：`附近有超市吗？`；`哪儿有银行？`；`家乐福超市怎么走？`；`去健身房坐什么车（健身房怎么去？）`；`学校离这儿多远？` | 無 | 每個例句加入實際地點；`附近有`、`吗？` 用紅色標記。 |
| 第 3 堂 | 58 | slide-58.html | Function | Luyện tập câu chức năng | `Hoàn thành hội thoại.`；Tình huống（1）：`大卫想去银行，但不知道在哪儿，他要找一个人问问。`；`（1）大卫：你好，____？`；Tình huống（2）：`大卫想去家乐福超市，但不知道怎么去，他要找一个人问问。`；`（2）大卫：你好，请问____？`；Tình huống（3）：`大卫想去健身房，不知道远不远，他问王楠。`；`（3）大卫：王楠，____？`；`王楠：不远，走路10分钟就到。`；Đáp án：`附近有银行吗、去家乐福超市怎么走、健身房离这儿多远` | 題目由上至下排列；情境說明放在對應題目前；答案點擊後以紅字帶入空格。 | 課本 p.10 功能項目練習。 |
| 第 3 堂 | 59 | slide-59.html | Task | Nhiệm vụ nhóm | `Làm việc theo cặp.`；`Hoàn thành đoạn hội thoại ở Sách giáo khoa P11, mục II. Hoạt động nhóm.`；`Quét QR Code và ghi âm trên Formative ngay trong giờ học.`；`Nhóm lên trình bày cũng phải ghi âm.`；`5 nhóm lên thực hành trước lớp.` | 右側留白放 QR Code | 刪除原任務說明頁；將標題 `Nhiệm vụ nhóm` 移到任務執行頁上方；只放完整越南語說明；包含準備、Formative 錄音、5 組上台演練與共通回饋。 |
| 第 3 堂 | 60 | slide-60.html | Closing | 下课 | 左卡：`BÀI TẬP VỀ NHÀ`；`KN4 - L1`；`Hoàn thành bài tập về nhà và nộp đúng hạn.`；右卡：`CHUẨN BỊ BÀI TIẾP THEO`；`KN4 - L2`；`Hoàn thành Formative chuẩn bị trước buổi học.` | 上方小 Banner 只放勾勾 icon；中央大標題 `下课`；左右兩張白色卡片；左卡嵌入回家作業 QR Code（https://frm.tv/join/5VMN2C），右卡嵌入下一課課前預習 QR Code（https://frm.tv/join/VZADA5）。 | 1 分鐘收尾；兩個 QR Code 圖大小一致、置中，外層保留淡色虛線框。 |

## 五、素材清單

| 頁碼 | 素材 | 需求 |
|---:|---|---|
| 1 | 封面圖片 | 替換目前 HTML/CSS 畫出的封面視覺；外國朋友在越南生活，朋友協助處理生活大小事；16:9 或可裁成右側主圖，避免文字、標籤與招牌。 |
| 7 | icon／小圖 | 會員卡、銀行卡或辦卡櫃台，輔助 `办卡`。 |
| 8 | icon／小圖 | `办`：證件、窗口、文件；`做`：作業、做飯或練習，輔助辨析。 |
| 10 | icon／小圖 | 大學科系、書本或校園，輔助名詞義 `专业`。 |
| 11 | icon／小圖 | 專業人士、工作證或證書，輔助形容詞義 `专业`。 |
| 12 | icon／小圖 | 表格加筆、申請表，輔助 `填`。 |
| 13 | icon／小圖 | 握手、盾牌或打勾，輔助 `可靠`。 |
| 24 | icon／小圖 | 旅行變壓器、插座轉接器、電壓符號，輔助 `变压器`。 |
| 25 | icon／小圖 | 插頭插進插座，輔助 `插头／插座／插`。 |
| 26 | 圖片 | 替換 `charging-phone.svg`；手機充電線插進手機的清楚圖片。可用簡單生成圖，不需要裝飾性背景。 |
| 27 | icon／小圖 | 網路線太短或一條網線，輔助 `网线`。 |
| 28 | icon／小圖 | Wi-Fi 或線路中斷，輔助 `掉线`。 |
| 29 | icon／小圖 | 穩定 Wi-Fi、訊號滿格或學校網路，輔助 `稳定`。 |
| 38 | icon／小圖 | 餐廳菜單、服務員點餐，輔助 `点菜`。 |
| 39 | icon／小圖 | 香菜與飲食限制符號，輔助 `忌口／香菜`。 |
| 40 | icon／小圖 | 請客、付款或帳單，輔助 `破费`，避免畫成單純買東西。 |
| 41 | icon／小圖 | 朋友聚餐、歡迎朋友吃飯，輔助 `接风`。 |
| 42 | icon／小圖 | 外帶盒、打包袋，輔助 `打包`。 |
| 51 | 文化小圖 | 職員 vs 領導，圖中不放文字。 |
| 52 | 文化小圖 | 年長者 vs 年輕人，圖中不放數字。 |
| 53 | 文化小圖 | 客戶 vs 同事，圖中不放文字。 |
| 54 | 文化小圖 | 個人 vs 團體，圖中不放文字。 |
| 60 | QR Code | 左側回家作業：https://frm.tv/join/5VMN2C；右側下一課課前預習：https://frm.tv/join/VZADA5；轉成 QR Code 圖後嵌入下課頁，保持畫面簡潔。 |

## 六、ChatGPT 圖片生成 Prompt

規則：每個 prompt 最多 16 張圖；圖片內文字、字母、數字、標籤或字幕依教師指定與圖片需求表為準，未指定時不主動加入可讀文字。生成後需裁切、按頁碼命名，再嵌入 PPT 對應位置。

### 共同風格規格

```text
Create educational textbook-style illustrations for a Chinese pinyin vocabulary HTML slide deck. Keep a consistent style across all images: soft textbook line-art, thin grey-blue outlines, muted pastel fills, white or very pale grey background, gentle flat shading, subtle low-contrast shadows, clean uncluttered composition, natural human proportions when people appear. Do not add readable text, letters, numerals, Chinese characters, labels, captions, or watermarks unless they are explicitly specified in the image request table. Use simple classroom-friendly objects and scenes. Leave enough clean negative space so each image can be cropped into a 960 x 540 HTML slide.
```

### P1 封面單張

```text
Create one 16:9 educational textbook-style cover illustration for a Chinese speaking class slide deck. Scene: a foreign student newly living in Vietnam receives help from a local friend with everyday life, such as getting a phone card, finding a place to live, using a ride-hailing app, shopping at a supermarket, and asking about a bank card. Warm friendly city-life mood, Vietnam-inspired but not touristy, clean modern classroom textbook style. Soft line-art, thin grey-blue outlines, muted pastel fills, white or very pale grey background, gentle flat shading, subtle low-contrast shadows, clean uncluttered composition. Leave safe empty space on the left for slide title. Do not add readable text, letters, numerals, Chinese characters, labels, captions, or watermarks unless they are explicitly specified in the image request table.
```

### 單字／icon 批次 A（4 x 4）

```text
Create one square 4 by 4 contact sheet image for a Chinese pinyin vocabulary slide deck. This prompt contains exactly 16 images, the maximum allowed per prompt. Each cell is a separate square textbook-style illustration, consistent style across all cells. Soft educational textbook line-art, thin grey-blue outlines, muted pastel fills, white or very pale grey background, gentle flat shading, subtle low-contrast shadows, clean uncluttered composition. Natural human proportions when people appear. Do not add readable text, letters, numerals, Chinese characters, labels, captions, or watermarks unless they are explicitly specified in the image request table.

Use exactly this row-major order, one subject per cell:

1. a bank card and membership card on a clean desk, suggesting applying for a card
2. a service counter with documents and an official stamp, suggesting handling official paperwork
3. a student doing homework at a desk with a simple bowl of food nearby, suggesting doing tasks
4. a university student choosing a major, with books and a campus building in the background
5. a professional worker with a badge and neat tools, suggesting professional skill
6. a hand filling in an application form with a pen
7. two classmates shaking hands with a small shield-like trust symbol nearby
8. a travel power transformer and plug adapter on a suitcase
9. a computer plug being inserted into a wall socket
10. a phone charging cable being inserted into a smartphone
11. a short ethernet cable beside a laptop
12. an online class on a laptop with the Wi-Fi connection breaking
13. a school building with stable full Wi-Fi signal shown only as simple icon shapes, no text
14. a person ordering food from a menu in a Chinese restaurant
15. cilantro beside a small food restriction symbol, no words
16. one person politely thanking another person who is paying a restaurant bill

Important: keep every cell visually separate with narrow white gutters, but do not add any written labels or numbers.
```

### 單字／文化批次 B（2 x 5，共 10 張）

```text
Create one rectangular 2 by 5 contact sheet image for a Chinese pinyin vocabulary and culture slide deck. This prompt contains exactly 10 images, under the maximum of 16 images per prompt. Each cell is a separate square textbook-style illustration, consistent style across all cells. Soft educational textbook line-art, thin grey-blue outlines, muted pastel fills, white or very pale grey background, gentle flat shading, subtle low-contrast shadows, clean uncluttered composition. Natural human proportions when people appear. Do not add readable text, letters, numerals, Chinese characters, labels, captions, or watermarks unless they are explicitly specified in the image request table.

Use exactly this row-major order, one subject per cell:

1. friends welcoming a newly arrived friend with a meal at a restaurant
2. a takeout food box and paper bag on a restaurant counter
3. an office employee in a neat workplace, friendly and approachable, no name badge text
4. a leader or manager in a neat workplace, calm and authoritative, no name badge text
5. an older adult standing calmly, respectful and dignified, no numbers
6. a young adult standing calmly, energetic but not childish, no numbers
7. a customer in a polite business setting, being welcomed respectfully, no signs or text
8. a coworker in a friendly office setting, approachable and equal-status, no signs or text
9. one individual standing alone in a simple neutral setting
10. a small group of people standing together in a simple neutral setting

Important: keep every cell visually separate with narrow white gutters, but do not add any written labels or numbers.
```

## 七、正式 HTML 製作前置檢查

| 檢查項目 | 狀態 | 處理方式 |
|---|---|---|
| 教師審核稿已完成超綱生詞交叉檢查 | [x] | 已完成，結果回填教師審核稿。 |
| 若有超綱詞，已先改用已學詞 | [x] | P27、P50 已先降超綱風險。 |
| 無法替換的超綱詞已做上下標記 | [x] | P12 `申请表`、P24 `电压／伏特` 已保留並做上方拼音、下方越南語標記。 |
| 課本原文中的超綱詞已註明「課本原文保留」 | [x] | 課本題目與讀一讀例句保留。 |
| 超綱檢查結果已回填教師審核稿 | [x] | 完成後可進 HTML 實作。 |

## 八、HTML 製作檢查

| 檢查項目 | 狀態 |
|---|---|
| 頁碼 1-61 齊全 | [x] |
| 檔名 `slide-01.html` 至 `slide-60.html` 正確 | [x] |
| 說明文字為越南語 | [x] |
| 中文內容為簡體中文 | [x] |
| P1、P7、P8、P10、P11、P12、P13、P24-P29、P38-P42、P51-P54 可用圖片／icon 優化版面；P26 有圖片與點擊答案 | [x] |
| P1 左文右圖已固定分區，課名已縮小並在逗號後換行；標題已在 PPT 左邊界到右圖左框的可用區域內置中，且不顯示 `45 phút x 3 buổi` | [x] |
| P2 暖身題目為中文簡體，上方小 Banner 使用越南語 `Khởi động`，未使用中文「暖身活動」，問題區不放白底框，提示句型與提示詞在問句下方橫式排列 | [x] |
| P2 問句已縮小並儘量一行呈現，`Mẫu câu` 與 `Từ gợi ý` 標籤樣式一致 | [x] |
| P2 提示詞已做上方拼音、下方 `（越南語）` | [x] |
| 預習回收頁上方小 Banner 顯示 `Ôn phần chuẩn bị`，問句卡內未重複該標題 | [x] |
| 預習回收頁問句上方已顯示課文頁碼範圍與《課文名稱》，格式為 `课文：P{{page_range}}《{{text_title}}》` | [x] |
| 預習回收頁課文資訊與問題卡依 PPT 上下左右安全邊界整體置中，問題儘量一行呈現 | [x] |
| 預習回收頁問題卡為閃卡，正面為問題，背面只放完整句參考答案，可翻牌 | [x] |
| 預習回收頁閃卡背面未顯示 `答案` 標籤；答案句子置中在白色閃卡框中 | [x] |
| Từ vựng 頁白色生詞框已做成閃卡；正面為拼音＋漢字，背面為越南語詞性＋越南語翻譯，詞性未使用中文 | [x] |
| Từ vựng 頁例句／對話中的本頁生詞已用黃底紅字突出 | [x] |
| Compare／Bổ sung 頁白框內未重複 `Phân biệt / Bổ sung`，未使用 `cách dùng` 標籤；P8 對比詞置中標色，左右例子皆有 `VÍ DỤ` | [x] |
| P49-P58 功能句與文化快問已按順序呈現；功能句仍採介紹頁＋練習頁兩頁結構 | [x] |
| 語法第一例句均使用「读一读、试一试」（1） | [ ] |
| 單句語法講解放兩個單句例句，AB 對話只放一組 | [ ] |
| 正式 HTML 製作前置檢查已全部完成 | [x] |
| 保留的超綱詞已做上方拼音、下方 `（越南語）` 標記 | [x] |
| 團體任務明確寫課堂 Formative 錄音 | [x] |
| 上台組也要錄音 | [x] |
| HTML presenter 可開啟 | [x] |
| 下方工具列已 icon 化，並有單頁 `下載PDF` 功能 | [x] |
| `下載PDF` 已測試可匯出當頁內容、手寫筆記、文字註記與 reveal 狀態 | [x] |
| 投影片 CSS/JS 已加版本參數，避免瀏覽器載入舊版樣式 | [x] |
| 每頁左下角來源文字已改為 `Sách giáo khoa P{{page}}` 或 `Sách giáo khoa P{{start}}~P{{end}}`，未顯示 `課文一／二／三` | [x] |

## 九、HTML 輸出與 QA

| 項目 | 結果 |
|---|---|
| HTML 輸出路徑 | `ai-teaching-material-system-main/output/kn4/lesson-01/` |
| Presenter | `ai-teaching-material-system-main/output/kn4/lesson-01/slides/index.html` |
| 生成方式 | `node scripts/create-kn4-l1-deck.mjs` |
| QA | Playwright 使用本機 Chrome 檢查；P1 左文右圖固定分區，右圖左框 524px，左側可用區中心 262px，標題中心 x=262px、y=270px，符合水平與垂直置中；標題與右圖保留 57px 安全距離，已刪 `Kỹ năng Nói 4 - Bài 1` 與時間；投影片 CSS/JS 已帶版本參數避免舊版快取；P2 上方小 Banner 使用越南語 `Khởi động`，未使用中文「暖身活動」，問題區無白底框，問句 27pt 並一行呈現，`Mẫu câu` 與 `Từ gợi ý` 標籤字體、字級、字重一致，提示句型用 `......`，6 個提示詞皆有拼音與越南語，無元素超出版面；13 張預習回收頁均已顯示 `课文：P1-2《我想办张银行卡》`、`课文：P3-4《附近有超市吗》`、`课文：P5-7《我不吃香菜》`，課文資訊與問題卡在安全範圍置中，問題一行呈現且未溢出，閃卡翻面只顯示置中的完整句參考答案，未顯示 `答案` 標籤，答案與提示區未超界；P9 reveal 正常；下方工具列 icon 顯示正常；單頁 PDF 下載已實測成功，含手寫註記。 |
| QA | 15 張 Từ vựng 頁（P7、P10、P11、P12、P13、P24、P25、P27、P28、P29、P38、P39、P40、P41、P42）均已檢查：白色生詞框可翻牌，正面為拼音＋漢字，背面只顯示越南語詞性與越南語翻譯兩行，不顯示欄位標籤；詞性為青綠色、翻譯為深藍色，兩行已置中且未溢出卡片。 |
| QA | 15 張 Từ vựng 頁均已檢查：右側互動句標籤改為 `Mẫu câu`，輸出頁未殘留 `Câu hỏi`；句子字級已放大為 25pt，一行或兩行呈現且未超過 PPT 右側安全邊界。 |
| QA | P8 已檢查：白框內未顯示 `Phân biệt / Bổ sung` 或 `cách dùng`；越南語說明開頭已大寫；`办`、`做` 放在解釋上方置中並用不同標色；左右例子區皆有 `VÍ DỤ`；例子已改為 `办证件、办手续、办签证`；所有元素未超出 PPT 安全邊界。P14 同型頁已確認白框主標題置中且未重複小標。 |
| QA | 15 張 Từ vựng 頁均已檢查：右側例句／對話中出現的本頁生詞已用黃底紅字突出；P25 已同時突出 `插头`、`插`、`插座`，P39 已突出 `忌口`、`香菜`；P7 `办卡` 因例句非連續詞，已突出 `办`、`卡`；P38 `点菜` 已突出 `点`、`菜`。 |
| QA 截圖 | `ai-teaching-material-system-main/output/kn4/lesson-01/exports/qa/screenshots/` |
