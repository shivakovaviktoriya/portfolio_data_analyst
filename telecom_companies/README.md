# Исследование тарифов сотовой связи.
### Описание проекта
Комапния оператора сотовой связи предлагает клиентам два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

Входные данные — данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год.

Цель исследования — проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

Гипотезы для проверки:
1) средняя выручка пользователей тарифов «Ультра» и «Смарт» различаются;
2) средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов.

### Итоги исследования

Основное исследование прошло в 5 этапов:

1. Изучение общей информации о данных.
На данном этапе я изучила общую информацию о данных в таблицах и увидели, с чем предстоит иметь дело.
Объеденила данные в сводную таблицу для удобства работы с данными. 

2. Предобработка данных.
На втором этапе я подготовила данные ддля дальнейшего анализа. А именно:
- перевела использованные Mb трафика в Gb и округлила в большую сторону
- округлила использованные минуты в большую сторону
- посчитала и добавила в новый столбец данные с месячной выручкой по каждому клиенту

3. Анализ данных
На третьем этапе я проанализировала поведение клиентов оператора, исходя из выборки:
- посчитала сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц
- посчитала среднее количество, дисперсию и стандартное отклонение.
- построила гистограммы.

4. Проверка гипотез.
На четвертом этапе с помощью тестов я проверила 2 гипотезы и сделала следующие выводы:
1) Средняя выручка пользователей тарифов «Ультра» и «Смарт» различается.
2) Средняя выручка пользователей из Москвы не отличается от выручки пользователей из других регионов.

5. Общий вывод
Исходя из проведенного t-теста, можно сделать вывод, что преспективнее тот тариф, у которого средняя выручка выше - то есть тариф "Ультра".
