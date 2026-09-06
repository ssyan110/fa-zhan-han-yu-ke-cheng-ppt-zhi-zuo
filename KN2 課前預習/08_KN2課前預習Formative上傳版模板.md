# KN2 課前預習 Formative 上傳版模板

用途：給實際建立 KN2 課前預習 Formative 作業時使用。  
依據：已通過的 `KN2課前預習教師審核模板.md`。  
原則：只保留要輸入 Formative 的內容、格式、題型、分數、音檔位置與必答設定；不放審核理由與長篇規則。

## 一、作業設定

- 作業標題：Kỹ năng nói 2 - L{{lesson_number}}: Bài tập chuẩn bị trước buổi học.
- 總分：{{total_points}}
- 說明語言：越南語
- 題目語言：簡體中文
- 上傳帳號：開始操作前，確認使用 Google Chrome 設定檔 `Shihsiang Yan` 的 Formative。
- 作業顯示設定：在 `Assign` → `Edit settings` → `Content display` 關閉 `Display each item as a separate page`；可在未發布／未指派狀態下設定，不必先發布作業。
- 建立方式：每個 Phần 建立 Text 區塊，再從該 Text 區塊右側／內部 `+` 新增題目卡，使題目卡位於同一張 Text 卡右側欄位內。不可用外層 `+` 讓題目卡獨立出現在文本下方；若已錯置，不可拖曳／移動，必須先在 Text 內重建新題卡，再刪原獨立題卡。
- Phần 說明位置：Phần 題型說明、`Hướng dẫn:` 與學生作答方式必須寫在 Phần Text 主文本內，不可另建右側獨立 Text 說明卡。
- Hint 規則：一個知識點一個 Formative hint 欄；不同生詞、語法或功能句不可合併在同一欄。

## 二、學生須知

建立位置：Formative 內建「學生須知 / 学生须知」頁面。

```md
<strong>學生須知</strong>

1. <strong>Hãy sử dụng <span style="color:red">Google Chrome</span> để làm bài.</strong>
2. <strong>Hãy <span style="color:red">chú ý thời hạn nộp bài</span>. Sau khi hết hạn nộp, bài tập này sẽ tự động đóng; học sinh không làm bài sẽ nhận <span style="color:red">0 điểm</span> cho bài tập này.</strong>
3. <strong>Bắt buộc phải bấm nút <span style="color:red">Submit(Nộp bài)</span> thì bài tập mới được tính là đã nộp.</strong>
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
<strong><span style="color:#1a73e8">Phần {{part_number}}: Ghi âm câu quan trọng.</span></strong>

<strong>Hướng dẫn:</strong>
1. Đọc và nghe câu quan trọng, chú ý phần <strong><span style="color:red">màu đỏ</span></strong> và <strong><span style="color:purple">màu tím</span></strong>, sau đó <strong>ghi âm lặp lại câu này</strong>.
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
{{important_sentence_with_color}}
{{translation_vi_with_color}}
```

Hint（每行代表一個獨立 Formative hint 欄；一個知識點一欄）：

```text
{{hint_line_1}}
{{hint_line_2}}
{{hint_line_3}}
```

### Phần 2 Text：第一次聽大意

類型：Text  
題目卡位置：從此 Text 區塊右側 `+` 新增。

```md
<strong><span style="color:#1a73e8">Phần {{part_number}}: Nghe đoạn hội thoại và chọn ý chính.</span></strong>

<strong>Hướng dẫn:</strong>
Nghe đoạn hội thoại một lần rồi chọn đáp án đúng <strong>(Không mở sách, chỉ nghe thôi).</strong>
```

#### Phần 2 題目卡

題型：Multiple Choice  
必答：是  
選項：3 個  
選項格式：A/B/C 答案選項一律純文字，未標色、未粗體、未加 HTML 標記  
隨機順序：是  
音檔位置：題目卡最前面  
分數：{{points}}

```md
{{audio_file}}
Câu hỏi: {{main_idea_question_zh_cn}}

A. {{option_a}}
B. {{option_b}}
C. {{option_c}}
```

正確答案：

```text
{{correct_answer}}
```

格式注意：

- 第一次聽大意題目前綴固定用 `Câu hỏi:`，不寫 `听课文Ｘ以后，请说说：`。
- 本課 Multiple Choice 正確答案位置需分散，不可全部集中在同一選項。
- Formative 題卡設定必須開啟「隨機順序 / 随机顺序」。
- A/B/C 答案選項只貼純文字，不加顏色、粗體、`<span>` 或其他 HTML 標記。

### Phần 3 Text：看課文後細節理解

類型：Text  
題目卡位置：從此 Text 區塊右側 `+` 新增。

```md
<strong><span style="color:#1a73e8">Phần {{part_number}}: Đọc đoạn hội thoại và chọn đáp án đúng.</span></strong>

<strong>Hướng dẫn:</strong>
<strong>P.{{page_range}}, 课文{{text_number}}《{{text_title_zh_cn}}》</strong>

Formative không hiển thị toàn bộ "bài học". <strong>Hãy mở sách giáo khoa</strong> để đọc.

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
- Formative 中不呈現完整課文。

#### Phần 3 題目卡

題型：Multiple Choice  
必答：是  
題數：每篇課文固定 3 題  
選項：3 個  
選項格式：A/B/C 答案選項一律純文字，未標色、未粗體、未加 HTML 標記  
隨機順序：是  
音檔位置：無  
分數：{{points}}

```md
{{detail_question_zh_cn}}

A. {{option_a}}
B. {{option_b}}
C. {{option_c}}
```

正確答案：

```text
{{correct_answer}}
```

格式注意：同一課的 Multiple Choice 正確答案位置必須分散，連續 3 題不得使用同一個正確答案位置；每題 Formative 題卡設定必須開啟「隨機順序 / 随机顺序」；A/B/C 答案選項只貼純文字，不加顏色、粗體、`<span>` 或其他 HTML 標記。

### Phần 4 Text：第二次聽課文

類型：Text  
題目卡位置：無  
分數：0  
音檔位置：Text 區塊內
音檔清稿：音檔上傳後，Text 正文不可保留 `[Âm thanh: 檔名]`、音檔檔名或其他音檔佔位文字。

```md
<strong><span style="color:#1a73e8">Phần {{part_number}}: Nghe lại và đối chiếu với bài trong sách.</span></strong>

<strong>Hướng dẫn:</strong>

Hãy nghe lại một lần nữa, đồng thời đối chiếu với đoạn trong sách. Hãy chú ý và cố gắng bắt chước giọng, ngữ điệu và các điểm ngắt nghỉ của nhân vật; đừng chỉ đọc qua một cách đơn giản.
```

## 四、學習困難回報

建立位置：所有課文單元之後。  
注意：放在最後一個 Phần 下方，不放在最後一個 Phần 的右側。  
題型：Free Response 或 Long Answer  
分數：0  
必答：否  
自動批改：否

```md
Bài học này bạn còn từ mới, câu hoặc nội dung nào chưa hiểu không? Nếu đã hiểu hết, bạn có thể để trống hoặc viết “沒有”.
```

## 五、Submit 提醒 Text

建立位置：作業最後  
類型：Text

```md
<strong>Nhớ bấm nút <span style="color:red">Submit(Nộp bài)</span> sau khi hoàn thành bài tập.</strong>
```

## 六、上傳操作檢查清單

- [ ] 開始操作前已確認 Google Chrome 設定檔名稱為 `Shihsiang Yan`，未使用其他 Google 設定檔或其他老師帳號。
- [ ] 作業標題正確。
- [ ] `Display each item as a separate page` 已設為關閉；設定路徑為 `Assign` → `Edit settings` → `Content display`，不必先發布作業。
- [ ] 學生須知放在 Formative 內建「學生須知 / 学生须知」頁面。
- [ ] 每個 Phần 先有 Text 區塊。
- [ ] 每個 Phần 標題是一般文字、粗體、藍色，不是 Heading 2。
- [ ] 每個 Phần 標題下方有黑色粗體 `Hướng dẫn:`。
- [ ] Phần 題型說明與 `Hướng dẫn:` 位於 Phần Text 主文本內，未另建右側獨立 Text 說明卡。
- [ ] 課文標題 Text 是獨立 Heading 2，沒有被誤刪，也沒有重複放進 Phần Text。
- [ ] 題目卡從 Phần Text 右側 `+` 新增。
- [ ] 錯誤新增在外層下方的題目卡已刪除。
- [ ] Hint 一個知識點一欄；未把多個知識點合併在同一 hint 欄。
- [ ] 重要句音檔放在 Audio Response 題目卡最前面。
- [ ] 重要句音檔內容與題目卡顯示句子完全一致。
- [ ] 第一次聽課文音檔放在 Multiple Choice 題目卡最前面。
- [ ] 第二次聽課文音檔放在 Text 區塊內。
- [ ] 音檔上傳後，學生可見正文中沒有 `[Âm thanh: 檔名]`、音檔檔名或其他音檔佔位文字。
- [ ] 缺漏音檔未用其他音檔替代。
- [ ] 取得 Formative 分享 link 後，已開啟 link 檢查標題、課次與作業類型；若要產生 QR Code 或放入 PPT，已確認擺放位置正確，本課課前預習 link 不放入同課課堂 PPT。
- [ ] Phần 2 與 Phần 3 題型為 Multiple Choice。
- [ ] Phần 2 與 Phần 3 每題都有 3 個選項。
- [ ] Phần 3 每篇課文固定 3 題。
- [ ] Multiple Choice 正確答案位置已分散，未全部集中在同一選項。
- [ ] 所有 Multiple Choice 題卡已開啟「隨機順序 / 随机顺序」。
- [ ] Multiple Choice 的 A/B/C 答案選項為純文字，未標色、未粗體、未加 HTML 標記。
- [ ] 題型、分數、必答設定正確。
- [ ] 第一次聽大意題目前綴為 `Câu hỏi:`，未使用 `听课文Ｘ以后，请说说：`。
- [ ] Hint 已加入且內容正確；一個知識點一欄。
- [ ] 學習困難回報 0 分、非必答。
- [ ] 學習困難回報在最後一個 Phần 下方，不在最後一個 Phần 右側。
- [ ] Phần 3 生詞表詞性欄位已統一為英文簡寫，例如：`V.`、`N.`、`Adj.`；`非` 已留空。
- [ ] 最後有 Submit 提醒。
- [ ] 總分正確。
