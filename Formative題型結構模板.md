# Formative 題型結構模板

適用工具：Formative  
適用任務：課前預習、課中活動、回家作業  
用途：定義 Formative 作業的共通結構、文字格式、題型格式、音檔位置、配分與困難度。

## 一、作業基本內容

### 1. 作業標題

課前預習作業固定格式：

```text
Kỹ năng nói {{level_number}} - L{{lesson_number}}: Bài tập chuẩn bị trước buổi học.
```

回家作業固定格式：

```text
Kỹ năng nói {{level_number}} - L{{lesson_number}}: Bài tập về nhà.
```

### 2. 操作帳號與作業顯示設定

操作 Formative 前，必須先確認當下 Google Chrome 設定檔完整名稱為 `Shihsiang Yan`（帳號可對應 `shihsiangyan1001@gmail.com`）。若目前是其他設定檔或其他老師帳號，必須停止操作並回報。

建立或修改 Formative 作業時，必須進入 `Assign settings` 的 `Content display`，將以下選項關閉：

```text
Display each item as a separate page：OFF
```

此設定不需要等作業發布後才可調整；未發布／未指派前可以設定，已發布後也可從 `Responses` → `Guest students` 的 `Assignment options` → `Adjust settings` 修改。

目的：

- 讓同一個 Phần 的 Text 說明與右側題目卡能連續呈現。
- 避免學生每題被切到獨立頁面後，看不到所屬 Phần 的說明、生詞表或音檔提示。
- 課前預習與回家作業都適用。

### 3. 學生須知

放在 Formative 內建「學生須知 / 学生须知」頁面，不使用自創 Text 題卡。

固定內容：

```md
<strong>學生須知</strong>

1. <strong>Hãy sử dụng <span style="color:red">Google Chrome</span> để làm bài.</strong>
2. <strong>Hãy <span style="color:red">chú ý thời hạn nộp bài</span>. Sau khi hết hạn nộp, bài tập này sẽ tự động đóng; học sinh không làm bài sẽ nhận <span style="color:red">0 điểm</span> cho bài tập này.</strong>
3. <strong>Bắt buộc phải bấm nút <span style="color:red">Submit(Nộp bài)</span> thì bài tập mới được tính là đã nộp.</strong>
```

格式：

- 標題為 `學生須知`，用粗體。
- 全文用粗體。
- `Google Chrome`、`chú ý thời hạn nộp bài`、`0 điểm`、`Submit(Nộp bài)` 用紅色。

### 4. Submit 提醒

放在作業最後一個 Text。

固定內容：

```md
<strong>Nhớ bấm nút <span style="color:red">Submit(Nộp bài)</span> sau khi hoàn thành bài tập.</strong>
```

格式：

- 全句粗體。
- `Submit(Nộp bài)` 紅色。
- 字體大小應明顯大於一般題目文字。

## 二、Formative 區塊結構

### 1. Phần Text 與題目卡分工

Formative 建置時，必須把「區塊說明」與「題目內容」分開。

Phần Text 區塊負責：

- Phần 標題。
- 本 Phần 的學生作答方式。
- 本 Phần 的文字格式。
- 課文位置。
- 閱讀提醒。
- 生詞表。
- 非題目型提醒，例如第二次聽課文。

題目卡負責：

- Formative 題型。
- 題目文字。
- 選項。
- 正確答案或參考答案。
- Hint。每一個提示必須放入 Formative 題卡的提示欄，一個知識點一欄。
- 分數。
- 必答設定。
- 音檔。

不可把每一道題目的完整內容全部塞進 Phần Text。題目卡必須從 Phần Text 區塊右側／內部的 `+` 新增，成為同一張 Text 卡片右側欄位內的 Formative 題目卡。

Phần 的題型說明、`Hướng dẫn:` 與學生作答方式必須放在 Phần Text 主文本內，不可在同一 Phần 右側欄另創一張 Text 卡作為說明卡。右側欄只放該 Phần 題目卡；若誤建獨立說明 Text，必須先把說明併回 Phần Text 主文本，再刪除該獨立 Text 卡。

嚴禁用外層 `+` 或底部快速工具列建立 Phần 內題卡。外層 `+`／底部快速工具列只能用於：

- 新增課文標題 Text。
- 新增下一個 Phần Text。
- 新增全課最後的 Submit 提醒 Text。
- 新增明確規定需放在整份作業最外層的題目。

正確畫面應呈現同一卡片左側為 Phần 文本、右側為題目卡。若題卡出現在 Phần Text 下方、與 Phần 並列，而不是 Phần Text 右側欄位內，該結構即為錯誤。不可用拖曳／移動修復；必須先在正確 Phần Text 右側欄位重建新題卡，確認內容、分數、答案與音檔後，再刪除原本獨立題卡。

`Đọc thử` 需要語法點提示時，優先放在該 Phần 右側 Text；若平台操作會覆蓋 Phần Text，改把語法點寫進相關題幹，不可覆蓋 Phần Text 說明。

題卡文字通用規則：

- Formative 會自動產生題號；題幹不可再手動輸入 `1.`、`2.` 等編號。
- 題型作答說明一律用越南語；簡體中文只用於題目本身、對話、可用句式與學生需回答的中文內容。
- 需要學生寫完整句、完成句子或造句的題卡，使用 `Free Response（自由回应）`，不使用 `Short Answer（简短答案）`。
- 所有計分題卡都必須設定為「需要 / Required」。
- 所有 Multiple Choice 題卡都必須開啟「隨機順序 / 随机顺序 / Randomize answer order」。
- 所有 Free Response（自由回应）題卡都啟用「部分信用 / Partial credit」。
- 客觀完成句類 Free Response 要視情況加入正確答案；AB 對話完成句建議至少加入答案片段與填入後完整句兩種。主觀回答題與開放造句題不加正確答案，以免限制學生答案。
- 不在學生可見 Text 題卡中另外放 `Mẫu ngữ pháp`；語法提示以題幹中的越南語說明或 Hint 欄處理。

### 2. Phần Text 區塊通用格式

每個 Phần 先建立一個 Text 區塊。Phần 標題必須在 Text 內，使用一般文字，不使用 Heading 2，並設定為藍色粗體。

固定格式：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: {{section_title_vi}}</span></strong>

<strong>Hướng dẫn:</strong>
{{student_instructions_vi}}
```

規則：

- 每個 Phần 的標題用一般文字、粗體、藍色。
- 每個 Phần 標題下方都要有一行黑色粗體 `Hướng dẫn:`。
- 課文標題如 `课文一《我想办张银行卡》` 使用 Heading 2。
- 課文標題是獨立 Text 區塊，位於該課文第一個 Phần 之前；不可刪除。
- Phần Text 內不可再次重複課文標題。
- Phần Text 只放本區塊說明與必要的文本資料。
- Phần 的題型說明與 `Hướng dẫn:` 必須在 Phần Text 主文本內，不可另創右側 Text 說明卡。
- 不可把題目卡新增在 Phần 區塊下方的最外層位置。

### 3. 常用 Phần Text 格式

#### Phần：重要句聽讀

用途：讓學生知道本區題目是「聽重要句後錄音復述」。

Text 固定內容：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Ghi âm câu quan trọng.</span></strong>

<strong>Hướng dẫn:</strong>
1. Đọc và nghe câu quan trọng, chú ý phần <strong><span style="color:red">màu đỏ</span></strong> và <strong><span style="color:purple">màu tím</span></strong>, sau đó <strong>ghi âm lặp lại câu này</strong>.
2. Nếu chưa hiểu nghĩa của câu, bạn có thể bấm nút <strong>hint (gợi ý)</strong> để xem giải thích.
```

格式規則：

- Phần 標題一般文字、粗體、藍色。
- `Hướng dẫn:` 黑色粗體。
- `màu đỏ` 紅色粗體。
- `màu tím` 紫色粗體。
- `ghi âm lặp lại câu này` 粗體。
- `hint (gợi ý)` 粗體。
- 重要句本身不放在 Text，必須放在右側 Audio Response 題目卡。

#### Phần：第一次聽課文

用途：讓學生不打開課本，只聽一次後回答大意。

Text 固定內容：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Nghe đoạn hội thoại và trả lời ý chính.</span></strong>

<strong>Hướng dẫn:</strong>
Nghe đoạn hội thoại một lần rồi trả lời câu hỏi <strong>(Không mở sách, chỉ nghe thôi).</strong> Hãy ghi âm trả lời câu hỏi.
```

格式規則：

- Phần 標題一般文字、粗體、藍色。
- `Hướng dẫn:` 黑色粗體。
- 本區不放完整課文。
- 課文音檔不放在 Text，必須放在右側大意題題目卡最前面。
- 大意題題目前綴固定用 `Câu hỏi:`，不寫 `听课文Ｘ以后，请说说：`。

#### Phần：看課文後細節理解

用途：讓學生打開課本，閱讀指定課文位置後回答細節問題。

Text 固定內容：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Đọc đoạn hội thoại và trả lời câu hỏi.</span></strong>

<strong>Hướng dẫn:</strong>
<strong>P.{{page_range}}, 课文{{text_number}}《{{text_title}}》</strong>

Formative không hiển thị toàn bộ "bài học". <strong>Hãy mở sách giáo khoa</strong> để đọc.

| 汉字 | 拼音 | 词性 | 越南语 |
|---|---|---|---|
| <span style="color:red"><strong>{{word}}</strong></span> | {{pinyin}} | {{pos}} | {{vi}} |
```

格式規則：

- Phần 標題一般文字、粗體、藍色。
- `Hướng dẫn:` 黑色粗體。
- `P.{{page_range}}, 课文...` 用粗體。
- `Hướng dẫn` 內容的任務重點要加粗；KN4 回家作業依各題型固定規則加粗，不自行擴大重點。
- 表格標題 `汉字` 不用紅色。
- 表格內容的漢字欄位用紅色粗體。
- 詞性欄位一律用英文簡寫，例如：`V.`、`N.`、`Adj.`。
- 詞性若為 `非`，詞性欄位留空。
- Formative 中不呈現完整課文。
- 細節問題不放在 Text，必須放在右側題目卡。

#### Phần：Đọc hiểu 只錄音回答

用途：讓學生根據課本課文回答理解題；學生只錄音，不提交文字答案。適用於 KN2 回家作業的 `Đọc hiểu`。

Text 固定內容：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Đọc hiểu.</span></strong>

<strong>Hướng dẫn:</strong>
Hãy trả lời câu hỏi dựa vào bài khóa tương ứng trong sách.
Hãy <strong>ghi âm câu trả lời</strong> của mình.
Câu trả lời cần là <strong>câu hoàn chỉnh</strong> hoặc <strong>một đoạn ngắn</strong>.

VD:
Câu hỏi: 你今天吃什么？
Câu trả lời <span style="color:red"><strong>Sai</strong></span>: 米饭、面条。
Câu trả lời <span style="color:#1a73e8"><strong>đúng</strong></span>: 我今天吃了米饭、面条。
```

格式規則：

- Phần 標題一般文字、粗體、藍色。
- `Hướng dẫn:` 黑色粗體。
- `ghi âm câu trả lời`、`câu hoàn chỉnh`、`một đoạn ngắn` 粗體。
- `Sai` 紅色粗體；`đúng` 藍色粗體。
- VD 只示範回答方式，不代表學生需提交文字答案。
- 題目卡使用 Audio Response，必須放在右側題目卡；不建立 Long Answer / Free Response 寫答案題卡。

#### Phần：看問題，根據圖片錄音回答

用途：讓學生看中文問題與圖片，用中文錄音回答。適用於 KN2 回家作業的 `Nhìn câu hỏi và hình, ghi âm trả lời`。

Text 固定內容：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Nhìn câu hỏi và hình, ghi âm trả lời.</span></strong>

<strong>Hướng dẫn:</strong>
Hãy <strong>nhìn câu hỏi và hình ảnh</strong>, sau đó <strong>ghi âm câu trả lời</strong> của bạn <strong>bằng tiếng Trung</strong>.
```

格式規則：

- Phần 標題一般文字、粗體、藍色。
- `Hướng dẫn:` 黑色粗體。
- `nhìn câu hỏi và hình ảnh`、`ghi âm câu trả lời`、`bằng tiếng Trung` 粗體。
- 不寫 `Không cần viết câu trả lời.`。
- 題目卡使用 Audio Response，必須放在同一個 Phần Text 右側。

#### Phần：替換詞語錄音

用途：讓學生看句子與提示詞，替換後錄音說出新句子。適用於 KN2 回家作業的 `Thay từ và nói`。

Text 固定內容：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Thay từ và nói.</span></strong>

<strong>Hướng dẫn:</strong>
Hãy nhìn <strong>câu mẫu</strong> và <strong>từ gợi ý</strong>, sau đó <strong>thay từ</strong> và <strong>ghi âm câu mới</strong> bằng tiếng Trung.
```

格式規則：

- `câu mẫu`、`từ gợi ý`、`thay từ`、`ghi âm câu mới` 粗體。
- 不寫 `Không cần viết câu trả lời.`。
- 題目卡使用 Audio Response，必須放在同一個 Phần Text 右側。

#### Phần：功能句情境完成對話

用途：讓學生讀情境後完成中文對話，並錄音讀出完成後的句子或對話。適用於 KN2 回家作業的 `Luyện tập câu chức năng`。

Text 固定內容：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Luyện tập câu chức năng.</span></strong>

<strong>Hướng dẫn:</strong>
Hãy <strong>đọc tình huống</strong>, sau đó <strong>hoàn thành đối thoại</strong>. Sau khi viết câu trả lời, hãy <strong>ghi âm</strong> đọc đầy đủ câu bạn đã hoàn thành.
```

格式規則：

- Phần 標題一般文字、粗體、藍色。
- `Hướng dẫn:` 黑色粗體。
- `đọc tình huống`、`hoàn thành đối thoại` 與 `ghi âm` 粗體。
- 不寫 `bằng tiếng Việt`。
- 不寫 `hoàn thành câu tiếng Trung còn thiếu`。
- 題目卡使用 Free Response + Audio Response，必須放在同一個 Phần Text 右側。

#### Phần：完成對話，錄音整句

用途：讓學生完成課本 `练一练：完成对话` 題目，並錄音讀出自己完成後的 A 整句或 B 整句，不要求錄整段對話。

Text 固定內容：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Hoàn thành hội thoại.</span></strong>

<strong>Hướng dẫn:</strong>
Hãy <strong>hoàn thành hội thoại bằng tiếng Trung</strong>. Sau khi viết câu trả lời, hãy <strong>ghi âm đọc đầy đủ câu A hoặc câu B</strong> mà bạn đã hoàn thành.
```

格式規則：

- `hoàn thành hội thoại bằng tiếng Trung`、`ghi âm đọc đầy đủ câu A hoặc câu B` 粗體。
- Audio Response 題卡指令也寫「錄音讀完整 A 句或 B 句」，不可要求錄整段對話。
- 題目卡使用 Free Response + Audio Response，必須放在同一個 Phần Text 右側。

#### Phần：第二次聽課文

用途：提醒學生再聽一次並對照課本；本區不是題目，不計分。

Text 固定內容：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Nghe lại và đối chiếu với bài trong sách.</span></strong>

<strong>Hướng dẫn:</strong>
{{audio_file}}

Hãy nghe lại một lần nữa, đồng thời đối chiếu với đoạn trong sách. Hãy chú ý và cố gắng bắt chước giọng, ngữ điệu và các điểm ngắt nghỉ của nhân vật; đừng chỉ đọc qua một cách đơn giản.
```

格式規則：

- Phần 標題一般文字、粗體、藍色。
- `Hướng dẫn:` 黑色粗體。
- 音檔放在 Text 區塊內。
- 不建立題目卡。
- 不計分。

#### Phần：學習困難回報

用途：讓學生回報不懂的生詞、句子或內容。

若使用 Text 作為區塊說明：

```md
<strong><span style="color:#1a73e8">Phần {{number}}: Báo cáo nội dung chưa hiểu.</span></strong>

<strong>Hướng dẫn:</strong>
Nếu có chỗ chưa hiểu, bạn có thể viết vào câu hỏi bên dưới. Nếu đã hiểu hết, có thể để trống hoặc viết “沒有”.
```

格式規則：

- Phần 標題一般文字、粗體、藍色。
- `Hướng dẫn:` 黑色粗體。
- 實際回報題放在右側 Free Response（自由回应）或 Long Answer 題目卡。
- 該題非必答、0 分。

若學習困難回報作為整份作業最後一題，不另外建立 Phần Text，則題目卡必須放在最後一個 Phần 的下方，不放在最後一個 Phần 的右側。此題之後才放 Submit 提醒 Text。

### 4. Phần 內題目卡

題目卡放在 Phần 的右側，同屬該 Phần。

每題需確認：

- 題型正確。
- 分數正確。
- 必答/非必答正確。
- 題目文字與格式正確。
- 音檔位置正確。
- Hint 內容正確。

### 5. 課文位置與生詞表

用於「看課文後細節理解」。

Text 內固定包含：

```md
<strong>P.{{page_range}}, 课文{{text_number}}《{{text_title}}》</strong>

Formative không hiển thị toàn bộ "bài học". <strong>Hãy mở sách giáo khoa</strong> để đọc.

| 汉字 | 拼音 | 词性 | 越南语 |
|---|---|---|---|
| <span style="color:red"><strong>{{word}}</strong></span> | {{pinyin}} | {{pos}} | {{vi}} |
```

格式：

- `P.{{page_range}}, 课文...` 用粗體。
- 表格標題 `汉字` 不用紅色。
- 表格內容的漢字欄位用紅色粗體。
- 詞性欄位一律用英文簡寫，例如：`V.`、`N.`、`Adj.`。
- 詞性若為 `非`，詞性欄位留空。

## 三、標色規則

在重要句、越南語翻譯、Hint 與必要的生詞表中使用；Multiple Choice 的 A/B/C 答案選項不套用標色或粗體：

| 類別 | 顏色 | 使用位置 |
|---|---|---|
| 該課生詞 | 紅色 | 重要句、越南語翻譯、Hint、生詞表漢字 |
| 語法/功能句/句型 | 紫色 | 重要句、越南語翻譯、Hint |
| 超綱詞/不在資料庫詞 | 藍色 | 重要句、越南語翻譯、Hint、超綱註記 |

Multiple Choice 選項規則：A/B/C 答案選項一律使用純文字，不加 `<span>`、顏色、粗體或其他 HTML 標記。若選項文字包含生詞或語法點，也不在答案選項內標色。

Markdown/HTML 寫法：

```md
<span style="color:red">帮助</span>
<span style="color:purple">在……下</span>
<span style="color:#1a73e8">开户</span>
```

## 四、Hint 格式

Hint 用於幫學生理解題目中的重點，不放入答案。

生詞 Hint：

```text
帮助 / bāng zhù / giúp đỡ
```

語法 Hint：

```text
在……下 / zài...xià / dưới sự..., trong hoàn cảnh...
Dùng để nói một việc xảy ra hoặc hoàn thành dưới một điều kiện, hoàn cảnh, sự ảnh hưởng hoặc sự giúp đỡ nào đó.
```

超綱詞 Hint：

```text
开户 / kāi hù / mở tài khoản
```

規則：

- 生詞需有漢字、pinyin、越南語。
- 語法需有漢字結構、pinyin、越南語、越南語使用情境。
- 超綱詞需標藍，且不得成為答案。
- 每一個詞義、語法或功能句提示在 Formative 內都要建立為獨立提示欄，不可寫成題幹中的 `提示：...`。
- 一個 Formative hint 欄只能放一個知識點；若同一題有 2 個生詞和 1 個語法點，必須建立 3 個 hint 欄，不可合併成同一欄。
- 若 Formative Hint 無法保留顏色，至少要保留完整文字註記。

## 五、音檔位置規則

### 1. 重要句聽讀

音檔放在題目卡內容最前面，接著才是重要句文字。

題型：Audio Response  
必答：是  
自動批改：否

音檔檢查：

- 音檔內容必須和題目卡顯示的重要句完全一致。
- 若為了降低難度縮短原句，必須重新裁切或重新生成同一句音檔。
- 不可出現「題目卡是短句，但音檔仍播放原文長句」。
- 上傳前需用人工聽檢或語音辨識比對一次。

### 2. 第一次聽課文

課文音檔放在大意題題目卡最前面。

題型：

- KN1/KN2：Multiple Choice。
- KN3/KN4：Audio Response。

### 3. 第二次聽課文

音檔放在第二次聽課文的 Text 區塊內，不建立題目卡，不計分。

音檔上傳後，必須刪除學生可見正文中的 `[Âm thanh: 檔名]`、音檔檔名或其他音檔佔位文字；音檔元件本身保留，檔名只保留在上傳版 metadata 或音檔表中。

### 4. 音檔缺漏

若來源音檔缺漏，不得任意用相近音檔替代。需在教師審核稿與上傳版標記：

```text
音檔狀態：缺漏，暫不加入音檔。
```

## 六、可用 Formative 題型

| Formative 題型 | 適用任務 | 備註 |
|---|---|---|
| Multiple Choice | 單選、大意理解、細節理解 | 一般可用 |
| Multiple Selection | 多選 | 一般可用 |
| True/False | 判斷 | 一般可用 |
| Fill in the Blank | 固定答案填空 | 一般可用 |
| Inline Choice | 下拉選項填空 | 一般可用 |
| Short Answer | 1-3 個詞或很短答案 | 一般可用 |
| Long Answer | 句子、段落、開放回答 | 一般可用，人工批改 |
| Numeric | 數字或帶符號答案 | 一般可用 |
| Matching | 詞義、拼音、漢字配對 | 一般可用 |
| Resequence | 句子或事件排序 | 一般可用 |
| Categorize | 分類任務 | 一般可用 |
| Drag and Drop | 拖拽填空或分類 | 可能為付費題型 |
| Show Your Work | 手寫、寫字練習 | 一般可用 |
| Upload | 拍照上傳、手寫作文 | 一般可用 |
| Audio Response | 朗讀、口說、錄音回答 | 可能為付費題型 |

## 七、題型模板

### 1. Audio Response：重要句復述

```md
題型：Audio Response
分數：{{points}}
必答：是

{{audio}}
{{number}}. {{important_sentence_zh}}
{{translation_vi}}

Hint:
{{hint_items}}
```

困難度：低。學生只需聽、看、模仿、復述。

### 2. Audio Response：第一次聽大意

```md
題型：Audio Response
分數：{{points}}
必答：是

{{audio}}
{{number}}. Câu hỏi: {{main_idea_question_zh}}

學生將錄製音頻回复
參考答案：{{full_sentence_reference_answer}}
```

困難度：中。學生不看書，需要抓大意。

### 3. Audio Response：看課文後細節理解

```md
題型：Audio Response
分數：{{points}}
必答：是

{{number}}. {{detail_question_zh}}

學生將錄製音頻回复
參考答案：{{full_sentence_reference_answer}}
```

困難度：中高。學生需打開課本閱讀，整理資訊後用中文回答。

### 4. Multiple Choice

```md
題型：Multiple Choice
分數：{{points}}
必答：是
隨機順序：是

{{number}}. {{question_zh}}
A. {{option_a}}
B. {{option_b}}
C. {{option_c}}

正確答案：{{answer}}
```

困難度：低至中。適合 KN1/KN2 或客觀理解題。

Multiple Choice 檢查：

- 每一張 Multiple Choice 題卡都必須開啟「隨機順序 / 随机顺序 / Randomize answer order」。
- A/B/C 答案選項為純文字，未加入顏色、粗體、`<span>` 或其他 HTML 標記。
- 每題固定 3 個選項時，正確答案位置需在同一份作業中分散。
- 不得讓同一份作業的 Multiple Choice 正確答案全部集中在 A、B 或 C。
- 連續 3 題 Multiple Choice 不得使用同一個正確答案位置。

### 5. Free Response（自由回应） / Long Answer：學習困難回報

```md
題型：Free Response（自由回应）或 Long Answer
分數：0
必答：否

Bài học này bạn còn từ mới, câu hoặc nội dung nào chưa hiểu không? Nếu đã hiểu hết, bạn có thể để trống hoặc viết “沒有”.
```

困難度：不計入。此題目的是收集學生問題，不作為評量題。

## 八、配分與困難度

配分不可只平均分配，必須反映任務負荷。每一課 Formative 最終總分固定調整為 100 分，不因題數多少而改變。

題卡原始分數可保留在審核稿中，用來檢查任務重量與題型比例；上傳時若需要調整題卡分數，必須以「最終總分 100」為準。

| 任務 | 困難度 | 建議配分邏輯 |
|---|---|---|
| 重要句復述 | 低 | 單題低分，重視完成與模仿 |
| 第一次聽大意 | 中 | 高於單句復述 |
| 看課文後一般細節 | 中高 | 高於大意題或接近大意題 |
| 因果、態度、推論 | 高 | 可設為該課最高單題分 |
| 學習困難回報 | 不計分 | 0 分，非必答 |

最終總分 100 分示例：

- 重要句聽讀：每題 3-5 分。
- 第一次聽大意：每題 6-10 分。
- 細節理解：每題 6-9 分。
- 較難推論：每題 8-12 分。
- 學習困難回報：0 分。

## 九、上傳前檢查

- [ ] 操作 Formative 前已確認 Google Chrome 設定檔完整名稱為 `Shihsiang Yan`（帳號可對應 `shihsiangyan1001@gmail.com`），未使用其他 Google 設定檔或其他老師帳號。
- [ ] 作業標題正確。
- [ ] `Assign settings` → `Content display` 的 `Display each item as a separate page` 已設為關閉；不需先發布作業即可設定，若已發布也可從 `Responses` → `Guest students` → `Assignment options` → `Adjust settings` 修改。
- [ ] 學生須知已填入 Formative 內建「學生須知 / 学生须知」頁面，沒有自創學生須知 Text 題卡。
- [ ] 每個 Phần 是 Text 區塊。
- [ ] 每個 Phần 標題為一般文字、粗體、藍色，不是 Heading 2。
- [ ] 每個 Phần 標題下方有黑色粗體 `Hướng dẫn:`。
- [ ] Phần 題型說明與 `Hướng dẫn:` 位於 Phần Text 主文本內，未另建右側獨立 Text 說明卡。
- [ ] 題目卡從所屬 Phần Text 右側／內部 `+` 新增，位於同一張 Text 卡右側欄位內，不在外層下方。
- [ ] 題卡題幹沒有手動題號。
- [ ] 題型作答說明為越南語，未殘留中文說明句。
- [ ] 需要寫完整句、完成句子或造句的題卡使用 `Free Response（自由回应）`，未使用 `Short Answer（简短答案）`。
- [ ] 所有 Free Response（自由回应）題卡已啟用「部分信用 / Partial credit」。
- [ ] 客觀完成句類 Free Response 已視情況加入正確答案；AB 對話完成句至少有答案片段與完整句兩種。
- [ ] 所有計分題卡都已設定為「需要 / Required」。
- [ ] 所有 Multiple Choice 題卡都已開啟「隨機順序 / 随机顺序 / Randomize answer order」。
- [ ] Multiple Choice 的 A/B/C 答案選項為純文字，未加入顏色、粗體、`<span>` 或其他 HTML 標記。
- [ ] Hint 已放入 Formative 提示欄，一個知識點一欄，未把多個知識點合併在同一欄，也未在題幹正文寫 `提示：...`。
- [ ] 沒有學生可見的 `Mẫu ngữ pháp` Text 題卡。
- [ ] 課文標題為 Heading 2。
- [ ] 課文標題是獨立 Text，且未被誤刪；Phần Text 內未重複課文標題。
- [ ] 課文位置用粗體。
- [ ] 生詞表漢字欄位內容為紅色粗體，標題不紅。
- [ ] Phần 3 生詞表詞性欄位已統一為英文簡寫，例如：`V.`、`N.`、`Adj.`。
- [ ] Multiple Choice 正確答案位置已分散，未全部集中在同一選項。
- [ ] Multiple Choice 題卡已開啟隨機順序。
- [ ] Multiple Choice 答案選項未標色、未粗體、未加 HTML 標記。
- [ ] 詞性為 `非` 時欄位留空。
- [ ] 第一次聽大意題目前綴為 `Câu hỏi:`，未使用 `听课文Ｘ以后，请说说：`。
- [ ] 重要句與翻譯標色正確。
- [ ] Hint 內容完整。
- [ ] 音檔位置正確。
- [ ] 音檔上傳後，學生可見正文中沒有 `[Âm thanh: 檔名]`、音檔檔名或其他音檔佔位文字。
- [ ] 重要句音檔內容與題目卡顯示句子完全一致。
- [ ] 題型、分數、必答狀態正確。
- [ ] 學習困難回報非必答、0 分。
- [ ] 學習困難回報若作為整份作業最後一題，位於最後一個 Phần 下方，不放在最後一個 Phần 右側。
- [ ] 最後有 Submit 提醒。
