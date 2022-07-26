# Исследование объявлений о продаже квартир

На данных сервиса с объявлениями о недвижимости Санкт-Петербурга и прилегающих населенных пунктов за несколько лет необходимо определить рыночную стоимость объектов недвижимости. Задача - установить параметры, что позволит автоматизированную систему: она отследит аномалии и мошенническую деятельность.

## Данные

   * данные, введенные  пользователем
   * данные, полученные автоматически на основе картографических данных (расстояние до центра, аэропорта, ближайшего парка и водоёма и другие)

Данные - датасет, состоящий из 22 колонок и 23699 строк.

    total_images
    last_price
    total_area
    first_day_exposition
    rooms
    ceiling_height
    floors_total
    living_area
    floor
    is_apartment
    studio
    open_plan
    kitchen_area
    balcony
    locality_name
    airports_nearest
    cityCenters_nearest
    parks_around3000
    parks_nearest
    ponds_around3000
    ponds_nearest
    days_exposition
   
## Ход исследования

1.  Изучение данных
2.  Предобработка данных
3.  Расчёты и добавление результатов в таблицу
4.  Исследовательский анализ данных

## Библиотеки

    pandas
    matplotlib

## Выводы

Было выявлено несколько закономерностей и зависимостей. Было найдено 10 топовых населеных пунктов, из них крупнейший - Санкт_Петербург. Также было определено, что квартиры в центре столицы незначительно дороже, чем на окраине, но продажи в целом по городу выше, чем в центре.