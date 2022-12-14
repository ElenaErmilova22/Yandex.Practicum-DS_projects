# Определение наиболее перспективного тарифа телеком-компании

## Аннотация:
На основе данных 500 пользователей федерального оператора сотовой связи «Мегалайн» за 2018 год нужно провести предварительный статистический анализ данных о тарифах «Смарт» и «Ультра». 

**Цель исследования:** скорректировать рекламный бюджет компании. \
**Задача исследования:** проанализировать поведение клиентов и сделать вывод о том, какой тариф приносит большую выручку.

## Используемые инструменты:
- Pandas;
- NumPy;
- Matplotlib;
- Seaborn;
- Scipy.

## Выводы:
На основании результатов проведенного статистического анализа затруднительно сделать вывод о том, какой из тарифных планов лучше и приносит большую выручку. Мы подтвердили двустороннюю гипотезу о том, что выручка различается в зависимости от тарифа, но для более четкого понимания ситуации нужно провести проверку односторонних гипотез. \
Нагрузка на сети, которую оказывают абоненты тарифа "Ультра" не намного больше, однако абонентская плата за данный тариф существенно выше. В то же время абоненты тарифа "Смарт" часто доплачивают за дополнительные пакеты, в частности пакеты интернета. \
Что касается настроений клиентов, то можно предположить, что они довольно противоречивы. Абоненты "Ультра", которые большую часть времени используют лишь малую долю своих пакетов, могут быть недовольны столь высокой абонентской платой. К тому же она является высоким порогом для большинства клиентов, которые не могут позволить себе ежемесячно расходовать подобную сумму на услуги связи и мобильный интернет. В то же время абоненты "Смарта", часто покупающие дополнительные пакеты, могут испытывать недовольство из-за вынужденных переплат. Все эти факторы могут побудить клиентов "Мегалайн" начать поиск другого оператора.
