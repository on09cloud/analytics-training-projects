
# Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста

**Данные**

В наличии были следующие данные в трёх датасетах:
* *hypothesis.csv* - гипотезы по увеличению выручки интернет-магазина с указанными параметрами Reach, Impact, Confidence, Effort
* *orders.csv* и *visitors.csv* - результаты A/B-теста

**Задачи проекта** 

Используя данные интернет-магазина, приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами.

**Описание проекта**

Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провела анализ результатов A/B-теста, построила графики кумулятивной выручки, среднего чека,
конверсии по группам, а затем посчитала статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было
принято решение о нецелесообразности дальнейшего проведения теста.

**Используемые библиотеки**

* *pandas*
* *numpy*
* *plotly.express*
* *plotly.graph_objs*
* *scipy.stats*
* *seaborn*
