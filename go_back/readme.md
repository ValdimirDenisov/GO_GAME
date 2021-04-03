# Запуск Python сервера (Запускать первым)

## Создание venv
```
python3 -m venv venv
```

## Активация venv
### для Windows:
```
venv\Scripts\activate.bat
```

### для Linux и MacOS
```
source venv/bin/activate
```

## Загрузка необходимых библиотек для запуска
```
pip install -r requirements.txt
```

## Запуск сервера
```
python main.py
```
