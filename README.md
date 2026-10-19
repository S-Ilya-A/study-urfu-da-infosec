# study-urfu-da-infosec

Домашние задания курса «Программные инструменты анализа данных в задачах ИБ» (УрФУ, осень 2026).

| ДЗ | Ветка |
|----|-------|
| ДЗ 1: постановка задачи, метрика, EDA (PhiUSIIL Phishing URL) | [hw1](../../tree/hw1) |

## Запуск

Проверено на Python 3.14.

```bash
python -m venv .venv
.venv/Scripts/activate        # Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt
```

Данные в репозиторий не входят (около 57 МБ). Скачайте
[PhiUSIIL Phishing URL Dataset](https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset)
с UCI и положите файл в `data/PhiUSIIL_Phishing_URL_Dataset.csv`, затем откройте `eda.ipynb`.
