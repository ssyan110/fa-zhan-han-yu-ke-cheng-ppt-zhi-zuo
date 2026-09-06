# KN4 回家作業 Formative 上傳版模板

用途：教師審核稿確認後，整理成可直接照著建立 Formative 的乾淨版本。  
依據：已通過的 `KN4回家作業教師審核模板.md`。  
原則：只保留上傳需要的文字、題型、分數、音檔與設定；刪除選題理由、審核討論與老師備註。

## 一、作業基本資訊

作業標題：

```text
Kỹ năng nói 4 - L{{lesson_number}}: Bài tập về nhà.
```

課程：Kỹ năng nói 4  
課次：L{{lesson_number}}  
課名：{{lesson_title_zh_cn}}  
Formative 存放資料夾：Kỹ năng nói 4 Bài Tập về nhà  
總分：100  

Formative 操作與顯示設定：

- 操作前必須確認 Google Chrome 設定檔完整名稱為 `Shihsiang Yan`（帳號可對應 `shihsiangyan1001@gmail.com`）。
- 在 `Assign settings` → `Content display` 關閉 `Display each item as a separate page`。
- 此設定不需先發布作業即可操作；若作業已發布，可從 `Responses` → `Guest students` 的 `Assignment options` → `Adjust settings` 修改。

題數統計：

| 題型種類 | 任務題數 | Formative 題卡數 | 分數小計 |
|---|---:|---:|---:|
| Đọc hiểu：寫答案 | {{count}} | {{count}} | {{points}} |
| Đọc hiểu：錄音 | {{count}} | {{count}} | {{points}} |
| Đọc thử：AB 對話完成句子 | {{count}} | {{count}} | {{points}} |
| Đọc thử：AB 對話完成句子錄音 | {{count}} | {{count}} | {{points}} |
| Đọc thử：语法应用造句 | {{count}} | {{count}} | {{points}} |
| Đọc thử：语法应用造句录音 | {{count}} | {{count}} | {{points}} |
| Luyện tập câu chức năng：完成句子 | {{count}} | {{count}} | {{points}} |
| Luyện tập câu chức năng：錄音 | {{count}} | {{count}} | {{points}} |
| Luyện tập Câu mẫu thực dụng：錄音回答 | {{count}} | {{count}} | {{points}} |
| 總計 | {{task_count}} | {{card_count}} | 100 |

### PPT 題目排除紀錄

本上傳版依已完成的 KN4 課堂 PPT 題目使用登記整理；下列題目不得直接或高度相似地放入回家作業。

| PPT 題目 ID | 語法點 | 課本頁碼／題號 | 題型 | 作業排除狀態 |
|---|---|---|---|---|
| `KN4-L{{lesson_number}}-G{{grammar_number}}-P{{textbook_page}}-Q{{question_number}}` | {{grammar_point}} | P{{textbook_page}}／{{question_number}} | G4／G5／G6／G7 | 已排除／教師指定重複：{{reason}} |

## 二、學生須知頁面

建立位置：Formative 內建「學生須知 / 学生须知」頁面  
類型：內建頁面，不建立 Text 題卡，不計分  
注意：正文第一個區塊必須直接從 `Phần 1` 開始。

```md
<strong>學生須知</strong>

1. <strong>Hãy sử dụng <span style="color:red">Google Chrome</span> để làm bài.</strong>
2. <strong>Hãy <span style="color:red">chú ý thời hạn nộp bài</span>. Sau khi hết hạn nộp, bài tập này sẽ tự động đóng; học sinh không làm bài sẽ nhận <span style="color:red">0 điểm</span> cho bài tập này.</strong>
3. <strong>Bắt buộc phải bấm nút <span style="color:red">Submit(Nộp bài)</span> thì bài tập mới được tính là đã nộp.</strong>
```

## 三、課文單元上傳格式

以下三個 Phần 需依每篇課文重複建立。若一課有 3 篇課文，就建立 3 組。

結構規則：

- 課文標題建立為獨立 Text，使用 Heading 2。
- 每個 Phần 建立為獨立 Text。
- Phần 內的題卡必須從該 Phần Text 右側 `+` 新增，掛在同一個 Phần 的右側欄位。
- 外層 `+` 與底部快速工具列只用來新增課文標題 Text、下一個 Phần Text、最後 Submit 提醒 Text。
- 不可用外層 `+` 或底部快速工具列建立 Phần 內題卡。
- 題卡題幹不手動加題號；Formative 會自動編號。
- 題型作答說明用越南語；簡體中文只保留在題目、對話與學生需產出的中文內容。
- 所有計分題卡都必須設定為「需要 / Required」。
- `Đọc thử` 不建立學生可見的 `Mẫu ngữ pháp` Text 題卡；生詞或超綱詞提示放入 Formative Hint 欄，一個提示一欄。

## 課文{{text_number}}《{{text_title_zh_cn}}》

### Phần {{number}} Text：Đọc lại bài khóa

類型：Text  
分數：0  
不建立題目卡。

```md
<h2><span style="color:#1a73e8">Phần {{number}}: Đọc lại bài khóa.</span></h2>

<strong>Hướng dẫn:</strong>
<strong>P.{{page_range}}, 课文{{text_number}}《{{text_title_zh_cn}}》</strong>

Trước khi làm phần này, hãy <strong>mở sách giáo khoa</strong> và đọc lại bài khóa tương ứng một lần. Formative không hiển thị toàn bộ bài khóa.

| 汉字 | 拼音 | 词性 | 越南语 |
|---|---|---|---|
| <span style="color:red"><strong>{{word}}</strong></span> | {{pinyin}} | {{pos_abbr}} | {{vi}} |
```

### Phần {{number}}：Đọc hiểu

#### Phần Text

類型：Text

```md
<h2><span style="color:#1a73e8">Phần {{number}}: Đọc hiểu.</span></h2>

<strong>Hướng dẫn:</strong>
Hãy trả lời câu hỏi dựa vào bài khóa tương ứng trong sách. Sau khi <strong>viết câu trả lời</strong>, hãy <strong>ghi âm câu trả lời</strong> của mình. Câu trả lời cần là <strong>câu hoàn chỉnh</strong> hoặc <strong>một đoạn ngắn</strong>.

VD:
Câu hỏi: 你今天吃什么？
Câu trả lời <span style="color:red"><strong>Sai</strong></span>: 米饭、面条。
Câu trả lời <span style="color:#1a73e8"><strong>đúng</strong></span>: 我今天吃了米饭、面条。
```

#### Q{{number}} Long Answer：寫答案

題型：Long Answer  
分數：2  
必答：是  
自動批改：否

```md
{{think_speak_question_zh_cn}}
```

參考答案：

```text
{{reference_answer_or_answer_direction}}
```

#### Q{{number}} Audio Response：錄音

題型：Audio Response  
分數：2  
必答：是  
自動批改：否

```md
Hãy ghi âm đọc câu trả lời của bạn cho câu trên.
```

評分重點：

```text
Nội dung đúng trọng tâm; phát âm rõ; ngắt nghỉ tự nhiên; có thể nói liên tục.
```

> 課本該區有幾個問句就建立幾組 Long Answer + Audio Response。

### Phần {{number}}：Luyện tập ngữ pháp/Cấu trúc câu

#### Phần Text

類型：Text

```md
<h2><span style="color:#1a73e8">Phần {{number}}: Luyện tập ngữ pháp/Cấu trúc câu.</span></h2>

<strong>Hướng dẫn:</strong>
Hãy dựa vào đề bài, dùng mẫu ngữ pháp được gợi ý để <strong>hoàn thành câu</strong>, sau đó <strong>ghi âm</strong>.
```

#### Q{{number}} Free Response（自由回应）：AB 對話完成句子

來源題目 ID／自編題：`{{ppt_source_question_id_or_self_authored}}`

題型：Free Response（自由回应）  
分數：2  
必答：是  
自動批改：否
部分信用：開啟

```md
Hãy dựa vào đoạn hội thoại để hoàn thành câu.

{{dialogue_with_blank_zh_cn}}
```

Hint（Formative 提示欄；一個提示一欄）：

```text
{{hint_item_1_optional}}
{{hint_item_2_optional}}
```

參考答案：

```text
{{blank_answer_fragment}}
{{full_completed_sentence_answer}}
```

#### Q{{number}} Audio Response：錄音

題型：Audio Response  
分數：1  
必答：是  
自動批改：否

```md
Hãy ghi âm đọc đầy đủ câu B bạn vừa hoàn thành.
```

#### Q{{number}} Free Response（自由回应）：语法应用造句

來源題目 ID／自編題：`{{ppt_source_question_id_or_self_authored_or_new}}`

題型：Free Response（自由回应）  
分數：2  
必答：是  
自動批改：否
部分信用：開啟

```md
{{application_instruction_vi}}

{{application_prompt_zh_cn}}
```

Hint（Formative 提示欄；一個提示一欄）：

```text
{{hint_item_1_optional}}
{{hint_item_2_optional}}
```

參考答案規則：

```text
學生答案需使用指定語法；若為 AB 對話，需完成另一句；若為給情景造句，需符合情景。句意清楚，語序基本正確，生詞難度符合審核稿。
客觀完成句可加入正確答案；主觀或開放造句不加正確答案。
```

#### Q{{number}} Audio Response：语法应用造句录音

題型：Audio Response  
分數：1  
必答：是  
自動批改：否

```md
Hãy ghi âm đọc đầy đủ câu ứng dụng bạn vừa viết.
```

> 一般語法：課本該區有幾個語法點就建立幾個語法點；每個語法點作業保留 1 題 AB 對話完成句子與 1 題语法应用造句，其餘完成句子留到課堂。功能句不適用此保留規則，另依下方功能句作業規則建立改寫題。

## 四、全課 Phần：Luyện tập câu chức năng

### Phần Text

類型：Text

```md
<h2><span style="color:#1a73e8">Phần {{number}}: Luyện tập câu chức năng.</span></h2>

<strong>Hướng dẫn:</strong>
Hãy đọc đề bài và <strong>hoàn thành câu</strong>. Sau khi viết câu trả lời, hãy <strong>ghi âm</strong> đọc câu bạn đã hoàn thành.
```

### Q{{number}} Free Response（自由回应）：功能項目完成句子

題型：Free Response（自由回应）  
分數：2  
必答：是  
自動批改：否
部分信用：開啟

```md
Hãy đọc đề bài, sau đó hoàn thành câu còn thiếu.

{{rewritten_function_prompt_zh_cn}}
```

提示（Hint）：`Sử dụng câu "{{function_category_vi}}".`

參考答案：

```text
{{reference_answer}}
```

### Q{{number}} Audio Response：功能項目錄音

題型：Audio Response  
分數：1  
必答：是  
自動批改：否

```md
Hãy ghi âm đọc đầy đủ câu trả lời của bạn cho tình huống trên.
```

> 課堂 PPT 需完整保留課本「功能項目練習」；回家作業此處另建同一功能的改寫題。改寫題保留給情境、給對話、挖空與功能句填入的任務結構，但不得直接複製課堂 PPT 題目，並使用獨立作業題目 ID。

## 五、全課 Phần：Luyện tập Câu mẫu thực dụng

### Phần Text

類型：Text

```md
<h2><span style="color:#1a73e8">Phần {{number}}: Luyện tập Câu mẫu thực dụng.</span></h2>

<strong>Hướng dẫn:</strong>
Hãy đọc các câu mẫu thực dụng. Với mỗi đoạn hội thoại, hãy <strong>chọn câu mẫu phù hợp</strong> và <strong>ghi âm câu hoàn chỉnh</strong> sau khi điền vào chỗ trống.
```

### Q{{number}} Audio Response：實用招牌句填空對話

題型：Audio Response  
分數：1  
必答：是  
自動批改：否  
```md
{{dialogue_with_blank_zh_cn}}
```

評分重點：

```text
Chọn đúng câu mẫu hoặc câu chức năng tương đương; ghi âm câu hoàn chỉnh; phát âm rõ; ngắt nghỉ tự nhiên.
```

> 題型與課本一致：給招牌句、給填空對話；作答方式改為錄音回答。

## 六、Submit 提醒 Text

建立位置：作業最後  
類型：Text

```md
<strong>Nhớ bấm nút <span style="color:red">Submit(Nộp bài)</span> sau khi hoàn thành bài tập.</strong>
```

## 七、上傳前 QA

- [ ] 作業標題正確。
- [ ] 操作前已確認 Google Chrome 設定檔完整名稱為 `Shihsiang Yan`，帳號可對應 `shihsiangyan1001@gmail.com`。
- [ ] `Assign settings` → `Content display` 的 `Display each item as a separate page` 已設為關閉；若已發布，已從 `Responses` → `Guest students` → `Assignment options` → `Adjust settings` 檢查。
- [ ] 學生須知已填入 Formative 內建「學生須知 / 学生须知」頁面，且沒有另建學生須知 Text 題卡。
- [ ] 課文標題為獨立 Text，位於該課文第一個 Phần 前。
- [ ] 每個 Phần 內題卡都從所屬 Phần Text 右側 `+` 新增，沒有用外層 `+` 或底部快速工具列建立 Phần 內題卡。
- [ ] 題幹沒有手動編號。
- [ ] 所有題型作答說明皆為越南語；沒有 `请根据...`、`完成句子` 等中文說明句。
- [ ] 寫答案、完成句子與造句題卡使用 `Long Answer` 或 `Free Response（自由回应）`；未使用 `Short Answer（简短答案）`。
- [ ] 所有 Free Response（自由回应）題卡已啟用「部分信用 / Partial credit」。
- [ ] 客觀完成句類 Free Response 已視情況加入正確答案；AB 對話完成句至少有答案片段與完整句兩種答案。
- [ ] 所有計分題卡都設定為「需要 / Required」。
- [ ] Hint 已放入 Formative 提示欄，一個提示一欄，沒有寫在題卡說明欄或題幹正文。
- [ ] 沒有學生可見的 `Mẫu ngữ pháp` Text 題卡。
- [ ] 每個 Phần 是 Text 區塊。
- [ ] 每個 Phần 標題為藍色。
- [ ] 題目卡都從對應 Phần Text 右側新增。
- [ ] Phần 1 不放完整課文。
- [ ] 每個 `Đọc lại bài khóa` 說明文本中已加入對應課本頁碼，格式為 `P.{{page_range}}, 课文...`，且使用課本頁碼不是 PDF 頁碼。
- [ ] 每個 `Đọc lại bài khóa` 說明文本中已加入本篇課文生詞表格，且漢字欄紅色粗體。
- [ ] 每個 `Đọc hiểu` 說明文本已加入固定 VD，且 `Sai` 紅色、`đúng` 藍色。
- [ ] 每篇課文都有 `Đọc lại bài khóa`。
- [ ] 每篇課文都有 `Đọc hiểu`，且已通過審核稿的問答／說明提示全數納入 Long Answer 與 Audio Response。
- [ ] 每篇課文都有 `Luyện tập ngữ pháp/Cấu trúc câu`，且課本語法點全數納入；一般語法每語法點作業保留 1 題 AB 對話完成句子與 1 題语法应用造句。
- [ ] 回家作業每道語法題均已與 PPT 題目使用登記比對，沒有未標記的完全重複或高度相似改寫題；採用題目已記錄來源 ID。
- [ ] `Luyện tập câu chức năng` 作業題型為情境＋挖空對話＋功能句填入，且題目是根據課本功能另建的改寫題，不是直接挪用課堂 PPT 題目。
- [ ] `Luyện tập câu chức năng` 每題 Hint 已依課本功能項目分類寫成 `Sử dụng câu "{{function_category_vi}}".`，不可整課套用同一個功能分類。
- [ ] `Luyện tập Câu mẫu thực dụng` 題型為招牌句＋填空對話＋錄音回答，不需老師音檔，並要求錄完整句。
- [ ] `Luyện tập Câu mẫu thực dụng` 每題只放填空對話，不重複放 `Hãy chọn câu mẫu...` 或 `Đoạn hội thoại:`。
- [ ] 題型、分數、必答狀態正確，總分為 100 分。
- [ ] 作業已放入 `Kỹ năng nói 4 Bài Tập về nhà` 文件夾。
- [ ] 基本資訊已列題數統計與總分 100。
- [ ] 沒有殘留舊版配分或舊版造句題型名稱。
- [ ] 最後有 Submit 提醒。
