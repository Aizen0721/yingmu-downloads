# 映幕 YINGMU

雪伏特 SHASHIFT 的 Windows 桌面工作台。

[官網介紹與下載](https://shashift.com/apps/yingmu/) · [發行版本](https://github.com/Aizen0721/yingmu-downloads/releases)

本儲存庫僅提供官方測試版的二進位下載與版本說明，未包含應用程式原始碼。

## 0.12.0 桌面分區預覽版

- 引用分區與本機資料夾映射：移動、縮放、摺疊、鎖定與名稱搜尋，原始檔案留在原處。
- 唯讀預覽 WitchDrawer 資料庫副本，確認後匯入映射盒；普通／實際儲存盒略過，不變更 WitchDrawer 或 Windhawk。
- 缺檔重新定位、切換映射來源、分區配置匯出與預覽還原。
- 新增「檢查更新」：從官方桌面分區預覽頻道取得對應可攜／精簡套件，核對大小與 SHA-256，退出後替換並重新開啟。保留本機設定及原始素材，上一版留在程式旁的 update-backups；替換過程失敗嘗試還原。平時不輪詢、不新增常駐服務。
- 保留 JPG／JPEG／PNG／BMP 與 MP4 桌布，每款可搭配 MP3／WAV／M4A／WMA，記住音量與獨立循環。
- 最多 24 個分區，資料夾只列第一層、最多 500 項；先顯示快取，再背景列舉，只監看啟用的映射資料夾。
- 兩款最終 ZIP 各通過 200 項回歸檢查，另有更新助手替換、備份與失敗還原測試。

完整解壓縮 ZIP，先從系統匣退出舊版，再開啟最外層「映幕.exe」；建立分區後按「顯示此分區」。請保留 app 資料夾。0.9 舊版需先手動下載本版，之後才能使用程式內更新。

可攜版內含執行環境，精簡版需 .NET 10 Desktop Runtime x64。目前為未簽章預覽版。桌面實際拖放、焦點、多螢幕與混合 DPI、真實 Explorer 重啟與登入開機仍待實機確認；自動檢查與內部首畫面量測不等於人眼驗收或冷開機。未使用 Computer Use。

每版提供 SHA256SUMS.txt。公開倉庫只發布二進位、說明與更新頻道，不包含應用原始碼。匯出配置包含本機路徑，不包含原始檔案內容，分享前請確認。沒有 Dock、工作列模組、Workshop、網頁／3D 桌布。

背景採用 [The Outlander — Free Japanese Backgrounds](https://the-outlander.itch.io/free-japanese-backgrounds) 的 CC0 素材；作者揭露為 AI 輔助製圖。映幕加入循環鏡頭、花瓣與光點，套件保留授權紀錄。
