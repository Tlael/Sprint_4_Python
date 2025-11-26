# Sprint 4 — юнит-тесты на Python (pytest)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![tests](https://img.shields.io/badge/tests-pytest-green)
![style](https://img.shields.io/badge/type-unit--tests-lightgrey)
![status](https://img.shields.io/badge/status-active-success)

Учебный проект по написанию **юнит-тестов** на Python с использованием `pytest`.  
Тесты покрывают класс `BooksCollector`, который управляет коллекцией книг и жанров.

---

## Стек

- Python 3.x  
- `pytest` (юнит-тесты)  

---

## Структура проекта

```text
Sprint_4_Python/
│
├── src/
│   ├── __init__.py
│   └── books_collector.py      # код приложения (BooksCollector)
│
├── tests/
│   ├── __init__.py
│   ├── conftest.py             # общие фикстуры
│   └── test_books_collector.py # набор юнит-тестов
│
├── requirements.txt            # зависимости проекта
├── pytest.ini                  # конфигурация pytest
├── .gitignore                  # игнорируемые файлы
└── README.md
   ``` 

Как запустить тесты

1. Создать и активировать виртуальное окружение
   ```bash
    python -m venv venv
    source venv/bin/activate      # Linux / macOS
    venv\Scripts\activate         # Windows
   ```

2. Установить зависимости
   ```bash
    pip install -r requirements.txt
   ```

3. Запустить все тесты
   ```bash
    pytest
   ```