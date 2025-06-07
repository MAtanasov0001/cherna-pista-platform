# Черна писта — Платформа за пътна безопасност 🚦

**Мисия:** Централизиране, почистване и анализ на данните за ПТП в България с цел визуализиране на рисковите участъци и подпомагане на институциите, шофьорите и пешеходците.

## Структура:
- `data/`: Сурови и обработени данни
- `notebooks/`: Анализи и експерименти
- `src/`: Python код (ETL, модели, визуализации)
- `webapp/`: Уеб визуализация (карта, API)
- `tests/`, `docs/`: Тестове и документация

## Използвани технологии:
- Python, pandas, scikit-learn, xgboost
- PostgreSQL + PostGIS
- FastAPI, Leaflet, Folium

## Стартиране:
```bash
python -m venv venv
source venv/bin/activate  # или venv\\Scripts\\activate за Windows
pip install -r requirements.txt
