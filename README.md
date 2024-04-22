# 차량 번호판 인식 모델 개발
CRNN 구현

## Data 
https://aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=172

## Directory
```bash
├── data
│   ├── tokenizer.json
│   ├── train.pickle
│   └── val.pickle
└── crnn.ipynb

## Result
||val accuracy|
|------|---|
|baseline|91.46|
|+ RandomAdjustSharpness|92.95|
|-|-|
