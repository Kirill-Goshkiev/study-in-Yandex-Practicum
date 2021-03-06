# Описание проекта "Исследование объявлений о продаже квартир"

## Данные
В распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. 
По каждой квартире на продажу доступны два вида данных - первые вписаны пользователем, вторые получены автоматически на основе картографических данных( наапример, расстояние до центра, аэропорта, ближайшего парка и водоёма):
- total_images - количество фотографий квартиры;
- last_price - цена квартиры;
- total_area - общая площадь квартиры;
- first_day_exposition - дата первой публикации объявления;
- rooms - количество комнат;
- ceiling_height - высота потолка;
- floors_total - общее количество этажей в доме;
- living_area - жилая площадь;
- floor - этаж;
- is_apartment - является ли апартаментами;
- studio - является ли студией;
- open_plan - имеется ли план квартиры;
- kitchen_area - площадь кухни;
- balcony - количество балконов;
- locality_name - наименование населенного пункта;
- airports_nearest - расстояние до аэропорта;
- cityCenters_nearest - расстояние до центра города;
- parks_around3000 - количество парков в зоне 3 км от дома;
- parks_nearest - расстояние до парка;
- ponds_around3000 - количество водоемов в зоне 3 км от дома;
- ponds_nearest - расстояние до водоема;
- days_exposition - количество дней, прошедших от публикации до продажи.

## Задача
Провести исследовательский анализ данных (EDA) и научиться определять рыночную стоимость объектов недвижимости.

## Используемые библиотеки
`pandas`, `numpy`, `matplotlib`, `seaborn`
