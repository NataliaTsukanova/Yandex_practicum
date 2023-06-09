# Анализ и исследование продаж по компьютерным играм

## Данные

Исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы

## Задача

Необходимо выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.  

## Используемые библиотеки
Pandas,
NumPy,
Matplotlib,
Seaborn,
Scipy

## Содержание
Шаг.1 Открыть файл с данными и изучить общую информацию  
Шаг 2. Подготовить данные:  
- заменить названия столбцов;
- преобразовать данные в нужные типы;
- обработать пропуски при необходимости:
- описать причины, которые могли привести к пропускам;
- обратить внимание на аббревиатуру 'tbd' в столбце с оценкой пользователей. Отдельно разобрать это значение и описать, как его обработать;
- посчитать суммарные продажи во всех регионах и записать их в отдельный столбец.  

Шаг 3. Проведите исследовательский анализ данных
- посмотреть, сколько игр выпускалось в разные годы;  
- посмотреть, как менялись продажи по платформам. Выбрать платформы с наибольшими суммарными продажами и построить распределение по годам. За какой характерный срок появляются новые и исчезают старые платформы?
- взять данные за соответствующий актуальный период. Актуальный период определите самостоятельно в результате исследования предыдущих вопросов. Основной фактор — эти данные помогут построить прогноз на 2017 год.
- какие платформы лидируют по продажам, растут или падают? Выбрать несколько потенциально прибыльных платформ.
- построить график «ящик с усами» по глобальным продажам игр в разбивке по платформам. Опишите результат.
- посмотреть, как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков. Построить диаграмму рассеяния и посчитать корреляцию между отзывами и продажами. Сформулировать выводы.
- соотнести выводы с продажами игр на других платформах.
- посмотреть на общее распределение игр по жанрам. Что можно сказать о самых прибыльных жанрах? Выделяются ли жанры с высокими и низкими продажами?  
- 
Шаг 4. Составьте портрет пользователя каждого региона 
- самые популярные платформы (топ-5). Описать различия в долях продаж.
- самые популярные жанры (топ-5). Пояснить разницу.
- влияет ли рейтинг ESRB на продажи в отдельном регионе?

Шаг 5. Проверьте гипотезы 
- средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
- средние пользовательские рейтинги жанров Action и Sports разные.

## Выводы
Для того, чтобы продажи в 2017 году шли хорошо, нужно сфокусироваться на играх для таких платформ, как PS4, XOne и 3DS( то есть новые на момент анализа платформы) с упором на жанры: Action, Shooter и Sports, а также чтобы игры были для для всех возрастов либо только для взрослых по рейтингу ESRB. 
Но и не забывать, что люди продолжают играть на PC, пусть это не принесет колоссальных продаж, но до сих пор актуальности своей не теряет.
