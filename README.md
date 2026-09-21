# new_repo
# FastAPI Hello World

Минимальное FastAPI-приложение с разделением точек входа и маршрутов.

## Запуск

Установите зависимости:

```bash
pip install fastapi uvicorn
```

Запустите приложение:

```bash
python main.py
```

После запуска откройте http://127.0.0.1:8000/ — приложение вернет:

```json
{"message": "hello world"}
```

Документация API доступна по адресам `/docs` и `/redoc`.