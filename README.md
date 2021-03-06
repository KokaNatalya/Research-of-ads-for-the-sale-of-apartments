# Исследование объявлений о продаже квартир

Проект был выполнен в ходе обучения в Яндекс.Практикум по курсу "Аналитик данных".

## Данные
Архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах 2016-2019 гг. сервиса Яндекс.Недвижимость.
В распоряжении были данные: 
- название населённого пункта
- число комнат и балконов, 
- высота потолков,
- площадь (общая, жилая, кухни),
- этаж квартиры,
- общее числе этажей в доме,
- дата публикации,
- цена на момент снятия с публикации,
- свободная планировка / студия,
- число фотографий в объявлении,
- расстояние до аэропорта, парка, водоема и пр. (получены автоматически на основе картографических данных).

## Задача
Установить параметры влияющие на рыночную стоимость квартир, чтобы построить автоматизированную систему, которая отследит аномалии и мошенническую деятельность.

## Используемые библиотеки:
- pandas,
- matplotlib,
- pandas_profiling,
- datetime.
