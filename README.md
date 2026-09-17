# Inventory API

Каркас API для системы учёта на FastAPI.

## Запуск

```powershell
.\.venv\Scripts\Activate.ps1
fastapi dev app/main.py
```

После запуска доступны:

- API: http://127.0.0.1:8000
- Swagger UI: http://127.0.0.1:8000/docs
- ReDoc: http://127.0.0.1:8000/redoc
- Health-check: http://127.0.0.1:8000/api/v1/health

## Тесты

```powershell
pytest
```

