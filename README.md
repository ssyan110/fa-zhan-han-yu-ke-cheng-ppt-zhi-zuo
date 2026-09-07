# 發展漢語課程 PPT 製作

這個專案保存 KN2／KN4 課程內容、教師審核稿與 HTML 投影片製作規格。此處 PPT 指 HTML 課堂投影片。

## 製作或修改一課

先讀 [製作契約](製作契約.md)，再開本課 `HTML_PPT製作稿.md`。新課另讀所屬課程的 01 架構與 02 模板；既有單頁修正只讀受影響頁與頁型。AI 助理從 [AGENTS.md](AGENTS.md) 進入，不套用參考專案的個人偏好。

在專案根目錄執行（需要 Python 3，無第三方套件）：

```bash
python3 scripts/check_slide_draft.py "KN2課堂PPT/L2_晚上早点儿睡/KỸ NĂNG NÓI 2-L2_HTML_PPT製作稿.md"
python3 -m unittest discover -s scripts -p 'test_*.py'
```

檢查器會找重複／跳號、輸出檔名、缺少欄位與總頁數衝突，遇到不支援或不完整的製作表會報錯。加 `--json` 可輸出帶來源雜湊的結果；加 `--slides-dir "實際slides資料夾"` 可另核對輸出缺檔與殘留檔。這項檢查不讀取 presenter Manifest，仍須另外核對導覽。它不會改稿、不產生 HTML，也不驗證課本內容或排版。

目前 KN4 L2／L3 仍有需人工核對的編號與內容順序，預檢會阻擋它們；見 [診斷與修正紀錄](docs/診斷與修正紀錄.md)。不要為取得 PASS 而刪題或忽略錯誤。

## 本機 HTML 系統

朋友原有的 `ai-teaching-material-system-main/` 是另一個本機專案，沒有放在這個 Git 倉庫。現有課程仍使用朋友本機的版本；[原始系統](https://github.com/ssyan110/ai-teaching-material-system) 只供程式參考，不能假設與本機修改版相同。

第一次在新電腦生成前，確認本機系統路徑、版本、實際建置命令及一課可開啟的輸出；把非敏感資訊記在本課製作稿。尚未確認時，仍可進行內容與文件預檢，不宣稱已生成可上課投影片。不要直接用上游覆蓋朋友的產生器。

## 本地保留但未上傳

- 音檔（MP3、WAV、M4A 等）。
- `ai-teaching-material-system-main/`：獨立的本地專案，保留自己的 Git 資料。
- 超過 GitHub 單檔限制的檔案。

新增工具只處理本倉庫的製作稿；HTML、素材與匯出仍在原本製作系統進行。
