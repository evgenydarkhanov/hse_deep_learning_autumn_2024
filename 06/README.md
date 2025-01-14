## Домашнее задание к лекции №6 по детекции

- В файле `hw_utils.py` добавлены функции: `intersection_over_union(), non_max_suppression(), mean_average_precision(), inference()`
- В папке `src/` должны быть:
    - `model.pth`
    - папка `test_data/` с изображениями в формате PNG и разметкой в формате XML
- Инференс происходит через `hw_utils.py`:
```Bash
python3 hw_utils.py
```
- Иллюстрация инференса `hw_06_test.ipynb`

```
06/
├── src/
│   ├── dataset.py
│   ├── hw_utils.py
│   ├── loss.py
│   ├── model.py
│   ├── train.py
│   └── utils.py
├── hw_06_test.ipynb
├── README.md
└── requirements.txt
```