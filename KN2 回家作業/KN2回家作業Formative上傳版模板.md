# KN2 回家作業 Formative 上傳版模板

用途：教師審核稿確認後，整理成可直接建立 Formative 的版本。  
存放位置：本模板放在 `KN2 回家作業` 根目錄；每課上傳版放在該課子資料夾。  
原則：只保留上傳需要的文字、題型、分數與設定。

## 一、作業基本資訊

作業標題：

```text
Kỹ năng nói 2 - L{{lesson_number}}: Bài tập về nhà.
```

課程：Kỹ năng nói 2  
課次：L{{lesson_number}}  
課名：{{lesson_title_zh_cn}}  
Formative 存放資料夾：Kỹ năng nói 2 Bài Tập về nhà  
本檔存放位置：`KN2 回家作業/L{{lesson_number}}_{{lesson_title_zh_cn}}/KỸ NĂNG NÓI 2-L{{lesson_number}}回家作業Formative上傳版.md`  
題卡原始分數：{{raw_points_total}}  
Formative 總分設定：100  
配分規則：不管題數多少，本課上傳後的 Formative 最終總分固定調整為 100。

Formative 操作與顯示設定：

- 操作前必須確認 Google Chrome 設定檔完整名稱為 `Shihsiang Yan`（帳號可對應 `shihsiangyan1001@gmail.com`）。
- 在 `Assign settings` → `Content display` 關閉 `Display each item as a separate page`。
- 此設定不需先發布作業即可操作；若作業已發布，可從 `Responses` → `Guest students` 的 `Assignment options` → `Adjust settings` 修改。

題數統計：

| 題型種類 | 任務題數 | Formative 題卡數 | 原始分數小計 |
|---|---:|---:|---:|
| Đọc hiểu：錄音回答 | {{count}} | {{count}} | {{points}} |
| 語法／句型：完成句子或 AB 對話 | {{count}} | {{count}} | {{points}} |
| 語法／句型：錄音 | {{count}} | {{count}} | {{points}} |
| 功能句：完成句子 | {{count}} | {{count}} | {{points}} |
| 功能句：錄音 | {{count}} | {{count}} | {{points}} |
| 脫口而出句：錄音 | {{count}} | {{count}} | {{points}} |
| 總計 | {{task_count}} | {{card_count}} | {{raw_points_total}} |

## 二、學生須知頁面

建立位置：Formative 內建「學生須知 / 学生须知」頁面  
類型：內建頁面，不建立 Text 題卡，不計分

```md
<strong>學生須知</strong>

1. <strong>Hãy sử dụng <span style="color:red">Google Chrome</span> để làm bài.</strong>
2. <strong>Hãy <span style="color:red">chú ý thời hạn nộp bài</span>. Sau khi hết hạn nộp, bài tập này sẽ tự động đóng; học sinh không làm bài sẽ nhận <span style="color:red">0 điểm</span> cho bài tập này.</strong>
3. <strong>Bắt buộc phải bấm nút <span style="color:red">Submit(Nộp bài)</span> thì bài tập mới được tính là đã nộp.</strong>
```

## 三、建置結構規則

- 課文標題建立為獨立 Text，使用 Heading 2。
- 每個 Phần 建立為獨立 Text。
- 課文標題 Text 使用 `<h2>课文...《...》</h2>`。
- 除課文標題外，其他 Text 內容都維持一般文本，只調整必要的粗體與文字顏色。
- Phần 標題 Text 使用一般文本，只將標題設為藍色粗體：`<span style="color:#1a73e8"><strong>Phần ...</strong></span>`。
- Phần 內題卡必須從該 Phần Text 右側 `+` 新增。
- 不可用外層 `+` 或底部快速工具列建立 Phần 內題卡。
- 完成 Formative 後必須展開檢查每個 Phần：題卡要縮排在對應 Phần Text 內，不可變成與 Phần Text 並列的單獨題卡。
- 完成 Formative 後必須再次檢查所有 Text、學生須知與題卡內說明的粗體、文字顏色、標題層級及重點標註。
- 題卡題幹不手動加題號。
- 作答說明用越南語。
- 中文內容用簡體中文。
- 「吧」或「呢」後方若不是問句，句末標點統一使用全形驚嘆號「！」；只有疑問語氣才使用問號「？」。
- 本上傳版經老師確認後，才可開始操作 Google Chrome 建立 Formative。
- 每次操作 Formative 前，必須重新確認當下要操作的 Google Chrome 視窗／分頁設定檔為 `Shihsiang Yan`。
- 可接受的確認證據：Chrome 視窗標題或右上角設定檔按鈕必須顯示完整名稱 `Shihsiang Yan`，且帳號選單可對應 `shihsiangyan1001@gmail.com`。
- 若當下 Chrome 視窗顯示 `柏豪`、`Tuấn`、`ai-mandarin.com`、`Shihsiang`（不完整名稱）或其他非目標設定檔，必須停止 Formative 操作並先回報，不可繼續新增、修改或檢測題卡。
- 在 `Assign settings` → `Content display` 將 `Display each item as a separate page` 關閉；不必等作業發布後才可設定，發布前即可完成。若作業已發布，可從 `Responses` → `Guest students` 的 `Assignment options` → `Adjust settings` 修改，修改後需重新檢查學生作答版面。
- 所有計分題卡 Required。
- 所有 Free Response（自由回应）啟用 Partial credit。
- Hint 放 Formative 提示欄，一個提示一欄。

## 四、課文單元上傳格式

以下三個 Phần 需依每篇課文重複建立。

## 課文{{text_number}}《{{text_title_zh_cn}}》

### 課文{{text_number}} Text

類型：Text

```md
<h2>课文{{text_number}}《{{text_title_zh_cn}}》</h2>
```

### Phần {{number}} Text：Đọc lại bài khóa

類型：Text  
分數：0  
不建立題目卡。

```md
<span style="color:#1a73e8"><strong>Phần {{number}}: Đọc lại bài khóa.</strong></span>

<strong>Hướng dẫn:</strong>
<strong>P.{{page_range}}, 课文{{text_number}}《{{text_title_zh_cn}}》</strong>

Trước khi làm phần này, hãy <strong>mở sách giáo khoa</strong> và đọc lại bài khóa tương ứng một lần. Formative không hiển thị toàn bộ bài khóa.

| 汉字 | 拼音 | 词性 | 越南语 |
|---|---|---|---|
| <span style="color:red"><strong>{{word}}</strong></span> | {{pinyin}} | {{pos_abbr}} | {{vi}} |
```

注意：上方 Markdown 表格是內容記錄格式；建立 Formative 時，必須使用 Formative 的 Table 功能建立真正的四欄表格，不得把 `|` 字元貼成一般文字。表頭固定為 `汉字 / 拼音 / 词性 / 越南语`，每個生詞各占一列。

### Phần {{number}} Text：Đọc hiểu

類型：Text

```md
<span style="color:#1a73e8"><strong>Phần {{number}}: Đọc hiểu.</strong></span>

<strong>Hướng dẫn:</strong>
Hãy trả lời câu hỏi dựa vào bài khóa tương ứng trong sách.
Hãy <strong>ghi âm câu trả lời</strong> của mình.
Câu trả lời cần là <strong>câu hoàn chỉnh</strong> hoặc <strong>một đoạn ngắn</strong>.

VD:
Câu hỏi: 你今天吃什么？
Câu trả lời <span style="color:red"><strong>Sai</strong></span>: 米饭、面条。
Câu trả lời <span style="color:#1a73e8"><strong>đúng</strong></span>: 我今天吃了米饭、面条。
```

#### Q{{number}} Audio Response：錄音

題型：Audio Response  
分數：2  
必答：是  
自動批改：否

```md
{{practice_question_zh_cn}}
```

參考答案方向：

```text
{{reference_answer_or_answer_direction}}
```

### Phần {{number}} Text：Luyện tập ngữ pháp/Cấu trúc câu

類型：Text

```md
<span style="color:#1a73e8"><strong>Phần {{number}}: Luyện tập ngữ pháp/Cấu trúc câu.</strong></span>

<strong>Hướng dẫn:</strong>
Hãy dựa vào đề bài, dùng mẫu ngữ pháp được gợi ý để <strong>hoàn thành câu</strong>, sau đó <strong>ghi âm</strong>.
```

#### Q{{number}} Free Response（自由回应）：完成句子或 AB 對話

題型：Free Response（自由回应）  
分數：2  
必答：是  
自動批改：否  
部分信用：開啟

```md
{{instruction_vi}}

{{prompt_zh_cn}}
```

Hint（Formative 提示欄；一個提示一欄）：

```text
{{hint_item_1_optional}}
{{hint_item_2_optional}}
```

參考答案：

```text
{{answer_fragment_optional}}
{{full_completed_sentence_answer}}
```

#### Q{{number}} Audio Response：錄音

題型：Audio Response  
分數：1  
必答：是  
自動批改：否

```md
Hãy ghi âm đọc đầy đủ câu bạn vừa hoàn thành.
```

## 七、全課 Phần 7：Thay từ và nói

### Phần Text

類型：Text

```md
<span style="color:#1a73e8"><strong>Phần {{number}}: Thay từ và nói.</strong></span>

<strong>Hướng dẫn:</strong>
Hãy nhìn <strong>câu mẫu</strong> và <strong>từ gợi ý</strong>, sau đó <strong>thay từ</strong> và <strong>ghi âm câu mới</strong> bằng tiếng Trung.
```

### Q{{number}} Audio Response：替換詞語錄音

題型：Audio Response
分數：2
必答：是
自動批改：否

```md
<p>{{complete_textbook_sentence_or_dialogue_with_underlined_replacement_slots}}</p>
<table>
<tbody>
<tr><td>{{item_number}}</td><td>{{all_textbook_replacement_items_for_column_1}}</td><td>{{all_textbook_replacement_items_for_column_2_optional}}</td></tr>
</tbody>
</table>
```

規則：題目必須完整保留課本該題的句子或對話，不得只擷取其中一句；句子中要被替換的詞語或片語使用 `<u>底線</u>`；替換詞語表格必須完整保留課本該題的全部列與欄，並在最左側加入每列題號欄，欄數依替換位置數量決定。題卡只放中文題目與完整替換詞表格，不放 `Hãy thay từ theo gợi ý và ghi âm câu mới:` 或 `Từ gợi ý:`。

Hint（Formative 提示欄）：

```text
{{hint_text}}
```

## 八、全課 Phần 8：Luyện tập câu chức năng

編號規則：若本課有兩篇課文，課文單元為 Phần 1-6，全課 Phần 從 Phần 7 開始；若本課另有 `Thay từ và nói`，則 `Luyện tập câu chức năng` 依實際順序順延為 Phần 8。

### Phần Text

類型：Text

```md
<span style="color:#1a73e8"><strong>Phần {{number}}: Luyện tập câu chức năng.</strong></span>

<strong>Hướng dẫn:</strong>
Hãy <strong>đọc tình huống</strong>, sau đó <strong>hoàn thành đối thoại</strong>. Sau khi viết câu trả lời, hãy <strong>ghi âm</strong> đọc đầy đủ câu bạn đã hoàn thành.
```

### Q{{number}} Free Response（自由回应）：功能句完成句子

題型：Free Response（自由回应）  
分數：2  
必答：是  
自動批改：否  
部分信用：開啟

```md
{{rewritten_function_prompt_zh_cn}}
```

題卡內容只放情境與挖空對話，不重複 Phần Text 已提供的 `Hãy đọc tình huống, sau đó hoàn thành đối thoại.`。

Hint（Formative 提示欄）：

```text
Sử dụng câu "{{function_category_vi}}".
```

參考答案：

```text
{{reference_answer}}
```

### Q{{number}} Audio Response：功能句錄音

題型：Audio Response  
分數：1  
必答：是  
自動批改：否

```md
Hãy ghi âm đọc đầy đủ câu trả lời của bạn cho tình huống trên.
```

## 九、全課 Phần 9：Hoàn thành hội thoại

編號規則：若本課有兩篇課文，課文單元為 Phần 1-6，且已有 `Thay từ và nói`、`Luyện tập câu chức năng`，則 `Hoàn thành hội thoại` 順延為 Phần 9。

### Phần Text

類型：Text

```md
<span style="color:#1a73e8"><strong>Phần {{number}}: Hoàn thành hội thoại.</strong></span>

<strong>Hướng dẫn:</strong>
Hãy <strong>hoàn thành hội thoại bằng tiếng Trung</strong>. Sau khi viết câu trả lời, hãy <strong>ghi âm đọc đầy đủ câu A hoặc câu B</strong> mà bạn đã hoàn thành.
```

### Q{{number}} Free Response（自由回应）：完成對話

題型：Free Response（自由回应）  
分數：2  
必答：是  
自動批改：否  
部分信用：開啟

```md
{{dialogue_with_blank_zh_cn}}
```

題卡內容只放對話，不重複 Phần Text 已提供的 `Hãy hoàn thành hội thoại bằng tiếng Trung.`。

Hint（Formative 提示欄）：

```text
{{hint_words_or_expression}}
```

參考答案：

```text
{{reference_answer}}
```

### Q{{number}} Audio Response：錄音整句

題型：Audio Response  
分數：1  
必答：是  
自動批改：否

```md
Hãy <strong>ghi âm đọc đầy đủ câu A hoặc câu B</strong> mà bạn đã hoàn thành.
```

## 十、Submit 提醒 Text

建立位置：作業最後  
類型：Text

```md
<strong>Nhớ bấm nút <span style="color:red">Submit(Nộp bài)</span> sau khi hoàn thành bài tập.</strong>
```

## 十一、上傳前 QA

- [ ] 本檔放在對應課次子資料夾。
- [ ] 教師審核稿已通過。
- [ ] 作業標題正確。
- [ ] Formative 放入 `Kỹ năng nói 2 Bài Tập về nhà`。
- [ ] 每次 Formative 操作前，當下 Chrome 視窗／分頁設定檔已確認為 `Shihsiang Yan`（可見 `Shihsiang`，並可對應 `shihsiangyan1001@gmail.com`）。
- [ ] `Assign settings` → `Content display` 的 `Display each item as a separate page` 已關閉；不必先發布作業，發布前即可設定。若已發布，已從 `Responses` → `Guest students` → `Assignment options` → `Adjust settings` 檢查。
- [ ] 學生須知放入 Formative 內建頁面。
- [ ] 每個 Phần 是 Text 區塊。
- [ ] 每個 Phần 標題為一般文本中的藍色粗體。
- [ ] 每個課文標題為獨立 Text，且使用 Heading 2。
- [ ] 題卡都從對應 Phần Text 右側新增。
- [ ] Formative 完成後已展開檢查，沒有題卡變成與 Phần Text 並列的單獨題卡。
- [ ] Formative 完成後已再次檢查所有 Text、學生須知與題卡內說明的文字格式。
- [ ] 題幹沒有手動編號。
- [ ] 作答說明皆為越南語。
- [ ] 中文皆為簡體中文。
- [ ] 已檢查「吧／呢」後方的語氣與標點：非問句使用「！」，問句才使用「？」。
- [ ] `Đọc lại bài khóa` 有課本頁碼與四欄實際表格生詞表，不放完整課文；Formative 中不可用 `|` 文字模擬表格。
- [ ] `Đọc hiểu` 已納入審核稿通過的 `边学边练` 問題。
- [ ] 語法／句型題使用 Free Response，不使用 Short Answer。
- [ ] 功能句題 Hint 寫成 `Sử dụng câu "{{function_category_vi}}".`
- [ ] `Luyện tập câu nói dùng được` 要求錄完整句。
- [ ] 所有 Free Response 啟用部分信用。
- [ ] 所有計分題 Required。
- [ ] 題型、分數、必答狀態正確。
- [ ] 不管題數多少，本課 Formative 最終總分已調整為 100。
- [ ] 題卡原始分數只作審核參考，未被誤當成最終總分。
- [ ] Phần 7 題句的替換位置有底線，替換詞語使用真正表格；題卡沒有重複固定說明。
- [ ] Phần 7 每題完整保留課本句子／對話，替換表格完整保留課本該題全部內容，未只擷取單一示例。
- [ ] Phần 7 每張替換表最左側都有連續題號欄。
- [ ] 最後有 Submit 提醒。
