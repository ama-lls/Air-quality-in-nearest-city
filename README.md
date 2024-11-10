# Качество воздуха в ближайшем городе

[ipynb](https://github.com/ama-lls/Air-quality-in-nearest-city/blob/main/%D0%9A%D0%B0%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%BE%20%D0%B2%D0%BE%D0%B7%D0%B4%D1%83%D1%85%D0%B0%20%D0%B2%20%D0%B1%D0%BB%D0%B8%D0%B6%D0%B0%D0%B9%D1%88%D0%B5%D0%BC%20%D0%B3%D0%BE%D1%80%D0%BE%D0%B4%D0%B5.ipynb)    

## Описание проекта

Получение текущего индекса качества воздуха (AQI) и погоды в ближайшем городе, используя геолокацию IP-адреса.

Ход проекта
- Подключение к API [AQAir](https://www.iqair.com/ru/world-air-quality).
- Получение текущего индекса качества воздуха (AQI) и погоды в ближайшем городе, используя геолокацию IP-адреса.
- Вывод данных в датафрейм.
- Подключение к Google Sheets API.
- Обновление данных в Google Sheets.
- Вывод полученной информации на дашборд в Looker Studio с подключением к Google Sheets.

## Инструменты


- **Python**
- **Pandas**
- **Requests**
- **Gspread**
- **Looker Studio**


## Общий вывод

- Осуществлено подключение к API [AQAir](https://www.iqair.com/ru/world-air-quality).
- Получен текущий индекс качества воздуха (AQI) и погода в ближайшем городе, используя геолокацию IP-адреса.
- Данные выведены в датафрейм.
- Осуществлено подключение к Google Sheets API.
- Произведено обновление данных в Google Sheets.
- Полученная информация выведена на дашборд [«Индекс качества воздуха»](https://lookerstudio.google.com/reporting/e1123b91-adca-4516-914b-1b13d36093a6) в Looker Studio с подключением к Google Sheets.
- Презентация [«Индекс качества воздуха»](https://lookerstudio.google.com/reporting/e1123b91-adca-4516-914b-1b13d36093a6](https://drive.google.com/file/d/1BFE23mUTN0uJif2qrirp9OxFvMyQONVL/view?usp=drive_link).
