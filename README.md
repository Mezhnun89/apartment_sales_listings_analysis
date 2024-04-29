# Исследование объявлений о продаже квартир

## Задача проекта
В вашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Ваша задача — научиться определять рыночную стоимость объектов недвижимости. Установите параметры, которые позволят построить автоматизированную систему для отслеживания аномалий и мошеннической деятельности. По каждой квартире на продажу доступны два вида данных: первые вписаны пользователем, вторые — получены автоматически на основе картографических данных, таких как расстояние до центра, аэропорта, ближайшего парка и водоёма.

## Описание данных
- `airports_nearest`: расстояние до ближайшего аэропорта в метрах (м)
- `balcony`: число балконов
- `ceiling_height`: высота потолков (м)
- `cityCenters_nearest`: расстояние до центра города (м)
- `days_exposition`: сколько дней было размещено объявление (от публикации до снятия)
- `first_day_exposition`: дата публикации
- `floor`: этаж
- `floors_total`: всего этажей в доме
- `is_apartment`: апартаменты (булев тип)
- `kitchen_area`: площадь кухни в квадратных метрах (м²)
- `last_price`: цена на момент снятия с публикации
- `living_area`: жилая площадь в квадратных метрах (м²)
- `locality_name`: название населённого пункта
- `open_plan`: свободная планировка (булев тип)
- `parks_around3000`: число парков в радиусе 3 км
- `parks_nearest`: расстояние до ближайшего парка (м)
- `ponds_around3000`: число водоёмов в радиусе 3 км
- `ponds_nearest`: расстояние до ближайшего водоёма (м)
- `rooms`: число комнат
- `studio`: квартира-студия (булев тип)
- `total_area`: площадь квартиры в квадратных метрах (м²)
- `total_images`: число фотографий квартиры в объявлении
