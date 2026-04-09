# Лабораторна робота 2: Аналіз датасету Individual Household Electric Power Consumption

## Опис завдання
Дослідження даних споживання електроенергії домогосподарствами: завантаження та очищення від пропусків, складна фільтрація записів, генерація випадкових вибірок, нормалізація та стандартизація, обчислення кореляцій Пірсона та Спірмена, а також One Hot Encoding (OHE) категоріальних змінних часу.

## Вимоги до системи
- **ОС:** Windows / Linux / macOS
- **Інтерпретатор:** Python 3.10+

## Налаштування середовища та запуск
1. Відкрийте термінал у теці `lab_02`.
2. Створіть та активуйте віртуальне середовище:
   ```bash
   python -m venv venv
   
   # Для Linux/macOS:
   source venv/bin/activate
   
   # Для Windows(powershell):
   .\venv\Scripts\Activate.ps1
   # Якщо помилка UnauthorizedAccess:
   Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUse

   #Усі необхідні пакети:
   pip install -r requirements 
