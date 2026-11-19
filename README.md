# ml2025f — NTUT Machine Learning Portfolio

本倉庫收錄這門機器學習課程的六次作業（hw01–hw06），主題圍繞
**醫學影像分割**與**物件偵測**。每份作業都做成一個網頁（`index.html`），記錄實作流程、
心得與結果

##  線上瀏覽（GitHub Pages）

網站首頁： **https://beloswww.github.io/ml2025f/**

| 單元 | 內容 | 線上頁面 |
| --- | --- | --- |
| hw00 | 自我介紹頁：以 AI 生成動漫風大頭照，建立作品集首頁 | https://beloswww.github.io/ml2025f/hw00/ |
| hw01 | 3D Slicer 心臟肌肉手動標註（三標籤法、閾值法、球型筆刷等），以 Dice-Sørensen 係數評分 | https://beloswww.github.io/ml2025f/hw01/ |
| hw02 | 在 Colab 以 3D U-Net 訓練心臟影像分割模型（並嘗試 Attn U-Net、UNETR、Swin UNETR），產生權重檔 | https://beloswww.github.io/ml2025f/hw02/ |
| hw03 | 用訓練好的權重對 50 筆資料推論，上傳 AICUP 競賽評分 | https://beloswww.github.io/ml2025f/hw03/ |
| hw04 | 3D Slicer + Labelme 主動脈瓣標註（nii.gz → dcm → png），以 AP 評分 | https://beloswww.github.io/ml2025f/hw04/ |
| hw05 | 在 Colab 訓練 YOLOv12 物件偵測模型，調參將 mAP50 由 0.963 提升至 0.965 | https://beloswww.github.io/ml2025f/hw05/ |
| hw06 | 以 YOLO 權重推論並上傳 AICUP 評分，挑戰 Strong baseline | https://beloswww.github.io/ml2025f/hw06/ |

## 使用的工具與技術

3D Slicer · Labelme · Google Colab · PyTorch · 3D U-Net / Attn U-Net / UNETR / Swin UNETR ·
YOLOv12（Ultralytics）· 醫學影像格式（NIfTI、DICOM）· AICUP 競賽平台

## 專案結構

```
ml2025f/
├── index.html      # 網站首頁（連到各作業）
├── hw00/           # 各次作業，內含 index.html 與相關檔案
├── hw01/
├── hw02/
├── hw03/
├── hw04/
├── hw05/  
└── hw06/      # 期末專題
```

## 關於
內容僅供學習與參考。
