# Learning Log

Требования: Python 3.12, pip.

Запуск (Linux / macOS):

```bash
python3.12 -m venv ll_env
source ll_env/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Запуск (Windows):

```powershell
py -3.12 -m venv ll_env
.\ll_env\Scripts\Activate.ps1
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Адрес: http://127.0.0.1:8000/

Админ-панель: http://127.0.0.1:8000/admin/

Тесты:

```bash
python manage.py test
```

Docker:

```bash
cp .env.example .env
docker compose up -d --build
```