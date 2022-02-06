# Автогенератор мерча по бренду

## Описание:
`@merch_generator_bot`  представляет собой реализацию проекта 
«Автогенератор мерча по бренду» в рамках зимней школы
[CompTech School 2022](https://comptechschool.com/).

## Папки и файлы репозитория:
- 🗂️[`YandexImagesParser @ 9e0d9d8`](https://github.com/Ulbwaa/YandexImagesParser/tree/9e0d9d854bc487dadbc01ff240b5cc89efb250ed) - папка необходима для поиска паттернов в Яндексе.
- 🗂️[`clothes_templates`](https://github.com/comptech-winter-school/merch-autogenerator/tree/main/clothes_templates) - папка содержит шаблон для наложения мерча.
- 🗂️[`docs`](https://github.com/comptech-winter-school/merch-autogenerator/tree/main/docs) - папка содержит проектную документацию.

- 🗂️[`merch_generator`](https://github.com/comptech-winter-school/merch-autogenerator/tree/main/merch_generator) - папка содержит скрипты для обработки изображений и парсинга текста.
- [`.gitignore`](https://github.com/comptech-winter-school/merch-autogenerator/blob/main/.gitignore) - каких файлов не должно быть в удалённом репозитории.
- [`gitmodules`](https://github.com/comptech-winter-school/merch-autogenerator/blob/main/.gitignore) - папка содеджит дополнительные модули, внешние репозитории.
- [`app.py`](https://github.com/comptech-winter-school/merch-autogenerator/blob/main/app.py) - приложение, телеграм бот, в который включен мерч .
- [`requirements.txt`](https://github.com/comptech-winter-school/merch-autogenerator/blob/main/requirements.txt) - список зависимостей, необходимых для работы скриптов.
- [`run.py`](https://github.com/comptech-winter-school/merch-autogenerator/blob/main/run.py) - файл для запуска бота.
## Назначение

Каждая компания хоть раз задумывалась о разработке собственного мерча для создания айдентики бренда или повышения лояльности к мероприятию.

Основная цель проекта – предоставить инструмент для генерации мерча к определенным событиям.

## Принцип работы

Исходя из запроса пользователя, бот автоматически генерирует футболку-мерч.

## Целевая аудитория (пользователи продукта)

Проект может представлять интерес для компаний, заинтересованных в мерче для своих целей (айдентика, мероприятия).

### Зависимости

Указаны в [`requirements.txt`](https://github.com/comptech-winter-school/merch-autogenerator/blob/main/requirements.txt).

## Использование



1. Открыть приложение Telegram;
2. Ввести наименование телеграм-бота в строку поиска или воспользоваться ссылкой (наименование телеграм-бота: merch-generator-bot, ссылка: https://t.me/merch_generator_bot);
3. Нажать кнопку «START»;
4. Ввести свои характеристики для мерча:
   - Название бренда, логотип которого вы хотите видеть на футболке
   - Основной цвет футболки
   - Для какого мероприятия предназначена футболка
5. Дождитесь ответного сообщения бота с мерчом 



## Команда:
- Калиниченко Михаил – капитан, Backend, CV разработчик
- Соколов Дмитрий – NLP, CV, Backend разработчик
- Переладова Алина – технический писатель, дизайнер 

## Кураторы:
- Созинов Иван – руководитель команды, FrontEnd разработчик
