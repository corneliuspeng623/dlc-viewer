# DLC 逐幀檢視器

Cornelius Peng · NYCU Neuromodulation Lab

在瀏覽器裡逐幀檢視 DeepLabCut 的預測結果，用於 cylinder test（左手 / 右手 / 雙手摸牆）。

- 載入原始影片 + `analyze_videos(..., save_as_csv=True)` 輸出的 CSV（可多個 iteration 比較）
- pcutoff、低信心幀跳轉（N / P）、likelihood 時間軸、縮放平移
- 人工標記左手 / 右手 / 雙手摸牆片段並匯出 CSV

影片與 CSV 只在使用者自己的瀏覽器中處理，不會上傳。
