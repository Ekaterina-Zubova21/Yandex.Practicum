## Данные
Данные лога стартапа, который через приложение занимается продажей продуктов питания.

## Задача
Используя данные лога:

1. Изучить воронку продаж.
2. Проанализировать результаты А/А/В-тестирования в котором пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами в приложении и одну экспериментальную — с новыми. 
3. Принять решение целесообразно ли менять шрифт в приложении на новый.


**Описание данных:**

Каждая запись в логе — это действие пользователя, или событие.
* EventName — название события;
* DeviceIDHash — уникальный идентификатор пользователя;
* EventTimestamp — время события;
* ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

## Использованные библиотеки
* A/B-тестирование
* Python
* Pandas
* Matplotlib
* Seaborn
* событийная аналитика
* продуктовые метрики
* Plotly
* проверка статистических гипотез
* визуализация данных