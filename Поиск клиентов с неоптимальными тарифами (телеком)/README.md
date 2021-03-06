## Поиск клиентов с неоптимальными тарифами (телеком).

Проект предполагает исследование данных по использованию услуг телефонии. Клиенты компании - колл-центры.

**Цель проекта** - определить стратегию перевода клиентов использующих неоптимальные тарифы на более выгодные для уменьшения оттока и увеличения LTV с минимальными потерями выручки для компании.


### Используемые библиотеки:
*pandas, numpy, datetime, matplotlib, scipy, math*

## Вывод:

В ходе исследованы были проанализированы дынные пользователей телеком компаний. Всего 307 пользователей в результате предобработки из анализыа были иселючены неактивные пользователи (менее 10 звонков за месяц) - всего 45 пользователей.

На основе очищенных от аномальных пользователей данных был составлен следующи портрет типичного клиента. Основаная часть проекта былпа посвещена расчету показателей выручки при использовании текущего и оптимального тарифов, а так же предложению по оптимизации потери выручки.

В части по оптимизации выручке была предложена схема смешанного перевода клиентов - 30% с неоптимальнымии тарифами на оптимальный и 10% с оптимальными тарифами на второй по оптимальномти. В результате расчетов удалось определить, что при данной схеме ретромпективно выручка снизилась на 5,2% вместо 30.5% при условии использования клиентами только оптимальных тарифов.

В результате проведения статистических тестов удалось выявить, что выручка статистически различается на текущих и оптимальных тарифах и статичтически не различается на текущихи альтернативных (схема 30-10) тарифах.
