# KN4 課前預習 Formative 上傳版模板

用途：給實際建立 Formative 作業時使用。  
依據：已通過的 `KN4課前預習教師審核模板.md`。  
原則：只保留要輸入 Formative 的內容、格式、題型、分數、音檔位置與必答設定；不放審核理由與長篇規則。

## 一、作業設定

- 作業標題：Kỹ năng nói 4 - L{{lesson_number}}: Bài tập chuẩn bị trước buổi học.
- 總分：{{total_points}}
- 說明語言：越南語
- 題目語言：簡體中文
- 作業顯示設定：`Display each item as a separate page` 必須設為關閉。
- 建立方式：每個 Phần 建立 Text 區塊，再從該 Text 區塊右側 `+` 新增題目卡。

## 二、學生須知 Text

建立位置：作業最前面  
類型：Text

```md
## Hướng dẫn cho học sinh

1. Hãy sử dụng <span style="color:red"><strong>Google Chrome</strong></span> để làm bài.
2. Hãy chú ý thời hạn nộp bài. Sau khi hết hạn, bài tập sẽ tự động đóng; học sinh chưa làm bài sẽ nhận <span style="color:red"><strong>0 điểm</strong></span>.
3. Nếu có câu hỏi ghi âm, hãy kiểm tra micro trước khi làm bài.
```

## 三、課文單元上傳格式

以下區塊每篇課文重複一次。

### 課文標題 Text

類型：Text  
格式：Heading 2
位置：每篇課文第一個 Phần 之前，獨立建立，不放進 Phần Text。

```md
## 课文{{text_number}}《{{text_title_zh_cn}}》
```

### Phần 1 Text：重要句聽讀

類型：Text  
題目卡位置：從此 Text 區塊右側 `+` 新增。

```md
<strong><span style="color:#1a73e8">Phần 1: Ghi âm câu quan trọng.</span></strong>

<strong>Hướng dẫn:</strong>
1. Đọc và nghe câu quan trọng, chú ý phần <span style="color:red">màu đỏ</span>, <span style="color:purple">màu tím</span> và <span style="color:#1a73e8">màu xanh dương</span>, sau đó <strong>ghi âm lặp lại câu này</strong>.
2. Nếu chưa hiểu nghĩa của câu, bạn có thể bấm nút <strong>hint (gợi ý)</strong> để xem giải thích.
```

#### Phần 1 題目卡

題型：Audio Response  
必答：是  
音檔位置：題目卡最前面  
音檔檢查：播放內容必須和題目卡顯示的重要句完全一致。若重要句縮短，音檔也必須是縮短後句子。  
分數：{{points}}

```md
{{audio_file}}
{{question_number}}. {{important_sentence_with_color}}
{{translation_vi_with_color}}
```

Hint：

```text
{{hint_line_1}}
{{hint_line_2}}
{{hint_line_3}}
```

### Phần 2 Text：第一次聽大意

類型：Text  
題目卡位置：從此 Text 區塊右側 `+` 新增。

```md
<strong><span style="color:#1a73e8">Phần 2: Nghe đoạn hội thoại và trả lời ý chính.</span></strong>

<strong>Hướng dẫn:</strong>
Nghe đoạn hội thoại một lần rồi trả lời câu hỏi (Không mở sách, chỉ nghe thôi). Hãy ghi âm trả lời câu hỏi.
```

#### Phần 2 題目卡

題型：Audio Response  
必答：是  
音檔位置：題目卡最前面  
分數：{{points}}

```md
{{audio_file}}
{{question_number}}. Câu hỏi: {{main_idea_question_zh_cn}}
```

格式注意：第一次聽大意題目前綴固定用 `Câu hỏi:`，不寫 `听课文Ｘ以后，请说说：`。

參考答案：

```text
{{full_sentence_reference_answer}}
```

### Phần 3 Text：看課文後細節理解

類型：Text  
題目卡位置：從此 Text 區塊右側 `+` 新增。

```md
<strong><span style="color:#1a73e8">Phần 3: Đọc đoạn hội thoại và trả lời câu hỏi.</span></strong>

<strong>Hướng dẫn:</strong>
<strong>P.{{page_range}}, 课文{{text_number}}《{{text_title_zh_cn}}》</strong>

Formative không hiển thị toàn bộ "bài học". Hãy mở sách giáo khoa để đọc.

| 汉字 | 拼音 | 词性 | 越南语 |
|---|---|---|---|
| <span style="color:red"><strong>{{word_1}}</strong></span> | {{pinyin_1}} | {{pos_1}} | {{vi_1}} |
| <span style="color:red"><strong>{{word_2}}</strong></span> | {{pinyin_2}} | {{pos_2}} | {{vi_2}} |
```

格式注意：

- `P.{{page_range}}, 课文...` 必須粗體。
- 表格標題 `汉字` 不紅。
- 表格漢字欄位內容紅色粗體。
- 詞性欄位一律用英文簡寫，例如：`V.`、`N.`、`Adj.`。
- 詞性為 `非` 時留空。

#### Phần 3 題目卡

題型：Audio Response  
必答：是  
音檔位置：無  
分數：{{points}}

```md
{{question_number}}. {{detail_question_zh_cn}}
```

參考答案：

```text
{{full_sentence_reference_answer}}
```

### Phần 4 Text：第二次聽課文

類型：Text  
題目卡位置：無  
分數：0  
音檔位置：Text 區塊內

```md
<strong><span style="color:#1a73e8">Phần 4: Nghe lại và đối chiếu với bài trong sách.</span></strong>

<strong>Hướng dẫn:</strong>
{{audio_file}}

Hãy nghe lại một lần nữa, đồng thời đối chiếu với đoạn trong sách. Hãy chú ý và cố gắng bắt chước giọng, ngữ điệu và các điểm ngắt nghỉ của nhân vật; đừng chỉ đọc qua một cách đơn giản.
```

## 四、學習困難回報

建立位置：所有課文單元之後  
注意：放在最後一個 Phần 下方，不放在最後一個 Phần 的右側。  
題型：Short Answer 或 Long Answer  
分數：0  
必答：否  
自動批改：否

```md
Bài học này bạn còn từ mới, câu hoặc nội dung nào chưa hiểu không? Nếu đã hiểu hết, bạn có thể để trống hoặc viết “Không có”.
```

## 五、Submit 提醒 Text

建立位置：作業最後  
類型：Text

```md
<strong>Nhớ bấm nút <span style="color:red">Submit(Nộp bài)</span> sau khi hoàn thành bài tập.</strong>
```

## 六、上傳操作檢查清單

- [ ] 使用 Chrome 設定檔完整名稱 `Shihsiang Yan` 與帳號 `shihsiangyan1001@gmail.com`。
- [ ] 作業標題正確。
- [ ] `Display each item as a separate page` 已設為關閉。
- [ ] 學生須知在最前面。
- [ ] 每個 Phần 先有 Text 區塊。
- [ ] 每個 Phần 標題是一般文字、粗體、藍色，不是 Heading 2。
- [ ] 每個 Phần 標題下方有黑色粗體 `Hướng dẫn:`。
- [ ] 課文標題 Text 是獨立 Heading 2，沒有被誤刪，也沒有重複放進 Phần Text。
- [ ] 題目卡從 Phần Text 右側 `+` 新增。
- [ ] 錯誤新增在外層下方的題目卡已刪除。
- [ ] 重要句音檔放在題目卡最前面。
- [ ] 重要句音檔內容與題目卡顯示句子完全一致。
- [ ] 第一次聽課文音檔放在題目卡最前面。
- [ ] 第二次聽課文音檔放在 Text 區塊內。
- [ ] 缺漏音檔未用其他音檔替代。
- [ ] 題型、分數、必答設定正確。
- [ ] 第一次聽大意題目前綴為 `Câu hỏi:`，未使用 `听课文Ｘ以后，请说说：`。
- [ ] Hint 已加入且內容正確。
- [ ] 學習困難回報 0 分、非必答。
- [ ] 學習困難回報在最後一個 Phần 下方，不在最後一個 Phần 右側。
- [ ] Phần 3 生詞表詞性欄位已統一為英文簡寫，例如：`V.`、`N.`、`Adj.`；`非` 已留空。
- [ ] 最後有 Submit 提醒。
- [ ] 總分正確。
