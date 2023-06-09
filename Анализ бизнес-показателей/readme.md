# Анализ бизнес-показателей

## Данные

Данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года.

## Задача

Несмотря на огромные вложения в рекламу в развлекательное приложение Procrastinate Pro+, последние несколько месяцев компания терпит убытки. Необходимо разобраться в причинах и помочь компании выйти в плюс.

## Используемые библиотеки
Pandas,
Numpy,
Matplotlib,
Seaborn

## Содержание
Шаг 1. Загрузить данные и подготовить их к анализу
- приведение названий столбцов в нижний регистр;
- преобразование данных о времени;
- проверка на явные и неявные дубликаты.

Шаг 2. Задать функции для расчёта и анализа LTV, ROI, удержания и конверсии.

Шаг 3. Исследовательский анализ данных
- составить профили пользователей. Определить минимальную и максимальную даты привлечения пользователей.
- выяснить, из каких стран пользователи приходят в приложение и на какую страну приходится больше всего платящих пользователей.
- узнать, какими устройствами пользуются клиенты и какие устройства предпочитают платящие пользователи.
- изучите рекламные источники привлечения и определить каналы, из которых пришло больше всего платящих пользователей.

Шаг 4. Маркетинг
- посчитать общую сумму расходов на маркетинг.
- выяснить, как траты распределены по рекламным источникам.
- построить визуализацию динамики изменения расходов во времени (по неделям и месяцам) по каждому источнику.
- узнать, сколько в среднем стоило привлечение одного пользователя (CAC) из каждого источника. 

Шаг 5. Оцените окупаемость рекламы
- проанализировать окупаемость рекламы c помощью графиков LTV и ROI, а также графики динамики LTV, CAC и ROI.
- проверить конверсию и удержание пользователей и динамику их изменения.
- проанализировать окупаемость рекламы с разбивкой по устройствам. Построить графики LTV и ROI, а также графики динамики LTV, CAC и ROI.
- проанализировать окупаемость рекламы с разбивкой по странам. Построить графики LTV и ROI, а также графики динамики LTV, CAC и ROI.
- проанализировать окупаемость рекламы с разбивкой по рекламным каналам. Построить графики LTV и ROI, а также графики динамики LTV, CAC и ROI.

## Выводы
Реклама нашего приложения не окупается и все дело в больших затратах на рекламу, которые несоразмеримо больше, чем рост LVT.
Окупается только реклама на PC. Затраты на рекламу для Mac и iPhone значительно выше, но они не привели к заветному пересечению уровня окупаемости. Также есть проблемы с удержанием пользователей Mac и iPhone.
Все страны пересекли уровень окупаемости, кроме США и опять из-за колоссальных трат на рекламу.По США, так же мы видим хорошую конверсию пользователей, но удержание клиентов сокращается намного быстрее, чем в других странах.
Канал Tiptop, в который было 'влито' больше всего рекламных средств, является самым убыточным. Затраты на данный канал также выросли в июня 2019. Также каналы FaceBoom и AdNonSense являются убыточными, хотя рекламные средства выделяются равномерно и данный вид расходов не растет, но удержание платящих клиентов по днамм каналам самое низкое.
