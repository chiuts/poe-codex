# POE研究所｜Gemini 正式架構 純淨版 v1

## 組件
- 趴水 Gem
- Gemini Deep Research
- 架構／中央知識庫管理端 Gem
- 使用者自己的 Google Drive 中央知識庫

## 資料流
研究素材 → Deep Research（必要時） → 趴水整理 → 架構 Gem 審核 → 產生正式文件 → 使用者存入自己的 Google Drive。

## Gemini 平台差異
一般 Gemini Apps 可讀 Google Workspace 內容，但不應假設能直接管理 Drive 資料夾。正式「寫入」以使用者匯出／建立 Google Docs 並放入正確資料夾完成。

## BD 身份隔離
每套 BD 獨立，不得因職業、技能、名稱相似而共用資料。

## 證據分層
原始資料 → PoB 引擎輸出 → 人工補正 → 遊戲內觀察 → 正式結論。

## 版本
舊版不被新版覆蓋。新版本建立新快照並比較差異。

## 架構哲學
能 Hotfix 就不重建整包；能改一個模組就不碰核心；真的需要才升架構。智庫要累積知識，不要累積負擔。
