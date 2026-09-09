# 北投圖書館建模測試

線上檢視：https://baf10717.github.io/beitou_library_model_test/

以 ChatGPT Astra 進行的既有建築重建測試成果網站：五個版本的線上 3D 檢視、使用者的完整指示紀錄與精度說明。

重建標的為臺北市立圖書館北投分館（九典聯合建築師事務所）。建模全程以 Blender 5.2 背景模式執行 Python 腳本完成。

## 內容

- `index.html`：說明頁與 three.js 線上模型檢視器
- `models/v1.glb` ～ `models/v5.glb`：五版模型的 glTF 匯出（Draco 壓縮，依集合合併）
- `images/`：Blender 渲染輸出（WebP）

## 資料界線

本版本庫只包含 Blender 自行渲染的輸出與模型幾何匯出。公司內網作品庫原始照片、Google 航照與街景截圖、外部刊載圖說均未上傳，僅保存於本機作為建模參考。

線上模型的程序節點材質無法匯出 glTF，材質簡化為單色近似；材質表現以渲染圖為準。模型尺寸屬圖面與照片估讀，不是實測成果，也不是施工模型。
