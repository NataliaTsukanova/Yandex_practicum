# Исследование объявлений о продаже квартир

## Данные

Данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. 

## Задача

Изучить данные, чтобы найти интересные особенности и зависимости, которые существуют на рынке недвижимости.

## Используемые библиотеки
Pandas,
Matplotlib

## Содержание
Шаг.1 Открыть файл с данными и изучить общую информацию

Шаг.2 Предобработка данных:  
- проверка пропусков, их обработка
- изменение типов данных в столбцах на корректное
- устранение неявных дубликатов
- обработка аномалий
   
Шаг 3. Добавить в таблицу новые столбцы:   
- цена одного квадратного метра;
- день недели публикации объявления;
- месяц публикации объявления;
- год публикации объявления;
- тип этажа квартиры (значения — «первый», «последний», «другой»);
- расстояние до центра города в километрах. 
 
Шаг 4. Провести исследовательский анализ данных   
4.1. Изучить следующие параметры объектов:   
- общая площадь;
- жилая площадь;
- площадь кухни;
- цена объекта;
- количество комнат;
- высота потолков;
- этаж квартиры;
- тип этажа квартиры («первый», «последний», «другой»);
- общее количество этажей в доме;
- расстояние до центра города в метрах;
- расстояние до ближайшего аэропорта;
- расстояние до ближайшего парка;
- день и месяц публикации объявления.
  
4.2 Изучить, как быстро продавались квартиры   
4.3.Изучите, зависит ли цена от: 
- общей площади;
- жилой площади;
- площади кухни;
- количества комнат;
- этажа, на котором расположена квартира (первый, последний, другой);
- даты размещения (день недели, месяц, год).
    
4.4.Посчитать среднюю цену одного квадратного метра в 10 населённых пунктах с наибольшим числом объявлений. Выделите населённые пункты с самой высокой и низкой стоимостью квадратного метра.   
4.5.Выделить квартиры в Санкт-Петербурге и вычислить среднюю цену каждого километра. Как стоимость объектов зависит от расстояния до центра города.   

## Выводы
На цену влияет нескольких факторов:этаж, на котором находится квартира( самые популярные это те, которые находятся ни на первом, ни на последнем этажах) и общая жилая площадь. В меньшей степени проявилась зависимость от количества комнат и от площади кухни.
Самые благоприятные и "дорогие" месяцы продажи квартир- апрель и сентябрь. Летом и в декабре-январе люди меньше проявляют активности в продажах недвижимости.
Самые дорогие квартиры выявлены в столице Ленинградской области и в самых ближайших от нее населенных пунктах, такие как, Пушкин, Мурино, Всеволжск, Шушары и т.д. 


