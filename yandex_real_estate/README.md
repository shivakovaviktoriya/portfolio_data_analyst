# Исследование объявлений о продаже квартир

На вход поступили данные от сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет.

Целью проекта было научиться определять рыночную стоимость объектов недвижимости. Задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

### Итоги исследования: 
Основное исследование прошло в 5 этапов:

1. Изучение общей информации о данных.
На данном этапе я получила общую информации о данных в таблице и увидели, с чем предстоит иметь дело.
Основные проблемы, которые были выявлены:
- Большое количество пропущенных значений.
- Не все типы данных подходили для анализа.

2. Предобработка данных.
На втором этапе я решила проблемы, выявленные на первом этапе и подготовила данные ддля дальнейшего анализа. А именно:
- Заполненила пропуски.
- Измененила типы данных на те, которые подойдут для дальнейшего анализа.
- Избавилась от некорректных данных, которые не повлияют на дальнейший анализ.

3. Расчет и добавление данных в таблицу.
На данном третьем этапе я рассчитала данные, которые понадобятся для анализа и добавила их в новые столбцы исходной таблицы.
- цену квадратного метра;
- день недели, месяц и год публикации объявления;
- этаж квартиры; варианты — первый, последний, другой;
- соотношение жилой и общей площади, а также отношение площади кухни к общей.

4. Исследовательский анализ данных
На 4 этапе я провела исследовательский анализ данных, а именно:
- Изучила, как парметры - площадь, число комнат, высота потолков влияют на цену квадратного метра.
- Изучила время продажи квартиры. Выяснила, сколько обычно занимает продажа.
- Убрала редкие и выбивающиеся значения.
- Выяснила какие факторы больше всего влияют на стоимость квартиры и зависит ли цена от площади, числа комнат, удалённости от центра.
- Изучила зависимость цены от того, на каком этаже расположена квартира: первом, последнем или другом. Также изучила зависимость от даты размещения: дня недели, месяца и года.
- Выбрала 10 населённых пунктов с наибольшим числом объявлений и посчитала среднюю цену квадратного метра в этих населённых пунктах. Узнала населённые пункты с самой высокой и низкой стоимостью жилья.
- Выделила квартиры в центре Санкт-Петербурга и построила график, как цена зависит от удаленности от центра.
- Выделила сегмент квартир в центре. Проанализировала эту территорию и изучили следующие параметры: площадь, цена, число комнат, высота потолков.

5. Общий вывод
Последний, пятый этап посвящен обобщению результатов исследования и рекомендаций заказчику на основе проведенного анализа.
1) Чем выше потолки, тем дороже стоимость кв. м.
2) Самые дорогие - однокомнатные и шести комнатные квартиры. На втором месте двухкомнатные и пятикомнатные. Цена за м.кв. у трехкомнатных и четырехкомнатных самая низкая.
3) Квартиры на первом этаже дешевле остальных.
4) С 2015 по 2019 год квартиры только дорожали.
5) Пик высоких цен на недвижимость приходится на август. Самые низкие цены - в мае-июне и декабре.
6) Пик высоких цен приходится на объявления, опубликованные в среду, далее к концу недели цена за кв.м. снижается.
7) Зависимости между общей площадтю и ценой за кв. м. выявлено не было.
8) В среднем продажа квартиры занимает 95 дней. Можно считать, что продажи прошли очень быстро, если прошли от 1 до 45 дней.Аномально долгие продажи занимают больше 500 дней.
9) Самое дорогое жилье в Санкт-Петербурге, на втором месте Пушкин, на третьем деревня Кудрово. Самое дешевое жилье в городе Выборг, Гатчина и Всеволожск.
10) Квартиры с расстоянием до центра до 7 км - находятся в центральной зоне. А, если расстояние до центра больше 7 км, то это за пределами центральной зоны.
11) Зависимость цены за кв. м от изучаемых параметров у квартир в центре аналогична зависимости по всем данным. Однако, выборка квартир в центре примерно в 2-3 раза дороже.
