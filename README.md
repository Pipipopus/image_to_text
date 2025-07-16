# image_to_text
# Web-приложение для распознавания текста (OCR)

![OCR Demo](demo.gif) *(пример работы приложения)*

## Описание

Веб-приложение для распознавания текста с изображений с использованием Tesseract OCR. Позволяет загружать изображения и получать распознанный текст прямо в браузере.

## Особенности

- 📷 Поддержка форматов: PNG, JPG, JPEG, BMP
- 🌍 Распознавание на русском и английском языках
- 🚀 Простой и удобный интерфейс
- 📁 Загрузка файлов через drag-and-drop
- 📋 Копирование распознанного текста

## Технологии

- **Backend**: Python + Flask
- **OCR**: Tesseract 5.x
- **Frontend**: HTML5, CSS3, JavaScript
- **Обработка изображений**: Pillow (PIL)

## Требования

- Python 3.8+
- Tesseract OCR 5.x
- Установленные языковые пакеты для Tesseract (rus, eng)

## Установка

1. Установите Tesseract OCR:

   ```bash
   # Windows: скачайте с https://github.com/UB-Mannheim/tesseract/wiki
   # Linux:
   sudo apt install tesseract-ocr tesseract-ocr-rus tesseract-ocr-eng
   # macOS:
   brew install tesseract tesseract-lang

    Клонируйте репозиторий:
    bash



Установите зависимости Python:
bash

pip install -r requirements.txt

Настройте путь к Tesseract (если нужно) в server.py:
python

    pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'  # для Windows

Запуск

python server.py

Приложение будет доступно по адресу: http://localhost:5000

Лицензия

Этот проект создан в учебных целях. Использование кода разрешено для обучения и некоммерческого использования.

Учебный проект © 2025 | [МИИГАиК]

