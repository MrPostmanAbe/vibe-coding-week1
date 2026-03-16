cat > README.md << 'EOF'
# vibe-coding-week1

FastAPI проект - первая неделя обучения.

## Установка и запуск

### 1. Клонировать репозиторий
```
git clone https://github.com/MrPostmanAbe/vibe-coding-week1.git
cd vibe-coding-week1
```

### 2. Создать виртуальное окружение
```
python -m venv venv
```

### 3. Активировать окружение
Windows (CMD):
```
venv\Scripts\activate
```
Windows (Git Bash):
```
source venv/Scripts/activate
```

### 4. Установить зависимости
```
pip install fastapi uvicorn
```

### 5. Запустить приложение
```
uvicorn main:app --reload
```

### 6. Открыть в браузере
- API: http://localhost:8000
- Документация: http://localhost:8000/docs
EOF