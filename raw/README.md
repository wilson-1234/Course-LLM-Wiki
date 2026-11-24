# 原始教材放置說明 (Raw Materials)

請將老師給的講義、簡報或白板照片放入此資料夾下的對應「科目」中：

### 目錄結構建議：
```text
raw/
└── <科目名稱>/
    ├── pdfs/       # 放講義 PDF、投影片 PDF
    └── images/     # 放白板照、投影片截圖
```

### 例如：
```text
raw/
└── 機器學習/
    ├── pdfs/
    │   └── week1_intro.pdf
    └── images/
        └── board_lecture1.jpg
```

存放完畢後，直接對 LLM 說：
> 「請幫我整理 `raw/機器學習/pdfs/week1_intro.pdf` 的內容」
> 或「請整理 `raw/機器學習/` 裡的所有講義」

LLM 就會自動依照 `AGENTS.md` 規範完成轉譯、概念提煉與雙向連結維護！
