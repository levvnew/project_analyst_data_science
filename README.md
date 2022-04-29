# project_analyst_data_science
Проекты по Data Analyst & Data Science

Каждая папка содержит по одному проекту:
# DS predict exited
[Ссылка на проект](https://github.com/waymylife/project_analyst_data_science/blob/main/DS_predict%20exited/DS%20%D1%84%D0%B8%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%D0%9B%D0%B8%D1%82%D0%B2%D0%B8%D0%BD%D0%BE%D0%B2%D0%B0%20%D0%98%D1%80%D0%B8%D0%BD%D0%B0_%D0%BE%D1%82%D1%87%D0%B5%D1%82.ipynb "Title")
## Проект "Предсказание оттока" с использованием LightGBM и CatBoost
В проекте проанализированы факторы влияния на целевую переменную. Предварительно исследованы модели и метрики качества.
Настроены гиперпараметры. Протестированы модели с лучшими параметрами. Рассчитаны метрики - F1, ROC_AUC, precision, recall.
Стек - Pandas, numpy, scipy.stats, matplotlib.pyplot, seaborn, math, datetime, xgboost, catboost, sklearn.
### В результате исследования: построена лучшая модель с ROC-AUC - 0,93.

# Bank customer reliability
[Ссылка на проект]( https://clck.ru/Xeyz3 "Title") 
## Исследование надёжности заёмщиков
Заказчик — кредитный отдел банка. Проанализированы факторы влияющие на факт погашения кредита в срок. Результаты исследования будут учтены при построении модели кредитного скоринга.
Анализ позволил выявить как наличие детей, семейное положение, уровень дохода, цели кредита влияют на возврат кредита. 
### В результате исследования: определены портреты надежного и ненадежного заемщиков.
Стек – Pandas, pymystem3, collections.


# Bank
[Ссылка на проект](https://clck.ru/XN8Jt "Title")
## Проект «Анализ клиентов регионального банка и сегментация пользователей по количеству потребляемых продуктов»
В проекте проанализированы клиенты банка и сегментированы по количеству потребляемых продуктов, проведен исследовательский анализ данных, сформулированы и проверены статистические гипотезы, проверена гипотеза различия дохода между теми клиентами, которые пользуются двумя продуктами банка, и теми, которые пользуются одним.
### В результате исследования выявлено: как клиенты пользуются продуктом, какие характеристики клиента влияют на отток, портрет клиентов, которые чаще уходят, взаимосвязь дохода и кол-ва банковских продуктов
Стек – Pandas, numpy, scipy.stats, matplotlib.pyplot, seaborn.




# telecom company
[Ссылка на проект](https://clck.ru/XN8UG "Title")
## Проект «Определение перспективного тарифа для телеком-компании»
В проекте проанализировано: поведение клиентов оператора, исходя из выборки, сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц. Рассчитано: помесячная выручка с каждого пользователя, среднее количество, дисперсия и стандартное отклонение, построены гистограммы и описаны распределения.
Проверены гипотезы: о средней выручке пользователей по тарифам,  о средней выручке пользователей из Москвы и из других регионов.
### В результате анализа тарифов и пользователей определен выгодный тариф для сотового оператора, приведены конкретные показатели в сравнении с другим тарифом, проанализировано поведение клиентов, проверены гипотезы
Стек – Pandas, numpy, scipy.stats, matplotlib.pyplot, seaborn.



# traffic
[Ссылка на проект](https://clck.ru/XN8Zf "Title")
## Проект «Выявление невыгодных источников трафика»
В проекте рассчитаны метрики трёх видов: продуктовые метрики (DAU, WAU, MAU, рассчитан Retention Rate применяя когортный анализ), метрики электронной коммерции (сколько времени в среднем проходит с момента первого посещения сайта до совершения покупки, среднее количество покупок на одного покупателя за 6 месяцев, средний чек, средний LTV по когортам за 6 месяцев), маркетинговые метрики (общая сумма расходов на маркетинг, как траты распределены по источникам, визуализированы изменения метрик во времени, средний CAC на одного покупателя для всего проекта и для каждого источника трафика, ROMI по когортам в разрезе источников, сравнение окупаемости за одинаковые периоды жизни когорт, построены графики, отражающие изменения метрик во времени).
### Результат исследования: проанализировано как клиенты пользуются сервисом, когда делают первые покупки на сайте, сколько денег приносит компании каждый клиент, когда расходы на привлечение клиента окупаются, определены источники трафика, на которые маркетологам стоит делать упор, подведены итоги когортного анализа, определены самые перспективные для компании когорты клиентов
Стек – Pandas, numpy, scipy.stats, matplotlib.pyplot, seaborn.  




# Data science predict churn
[Ссылка на проект]( https://clck.ru/XTcbU "Title")
## Проект «Прогнозирование вероятности оттока клиента и кластеризация»

Распространённая проблема сервисов — отток клиентов. Чтобы бороться с оттоком, был проведен анализ и подготовлен план действий по удержанию клиентов. Разработана стратегия взаимодействия с клиентами на основе аналитических данных.
А именно: cпрогнозирована вероятность оттока (на уровне следующего месяца) для каждого клиента, cформированы типичные портреты клиентов: выделено несколько наиболее ярких групп и охарактеризованы их основные свойства, проанализированы основные признаки, наиболее сильно влияющие на отток, сформулированы основные выводы и разработаны рекомендации по повышению качества работы с клиентами:

1) Выделены целевые группы клиентов;
2) Предложены меры по снижению оттока.

### Был проведен исследовательский анализ данных(визуализация признаков, матрица корреляции и т.д.)
### Построена модель прогнозирования оттока клиентов и рассчитаны метрики
### Проведена кластеризация клиентов

Стек – Pandas, scipy, matplotlib, seaborn, sklearn




# hypothesis and A_B_test
[Ссылка на проект]( https://clck.ru/XTcwE "Title")
## Проект «Приоритизация гипотез и анализ А/В-теста»
Проект содержит две части.
### Часть 1. Приоритизация гипотез.
### Часть 2. Анализ A/B-теста:
•	График кумулятивной выручки, среднего чека, конверсии по группам.

•	График относительного изменения кумулятивного среднего чека, конверсии группы B к группе A. 

•	Точечный график количества заказов по пользователям.

•	Перцентили

•	Статистическая значимость 
Стек – Pandas, numpy, scipy, matplotlib, seaborn, math, datetime


# bank_churn
## Проект Прогнозирование оттока клиентов из банка
[Ссылка на проект]( https://clck.ru/Z8L2y "Title")

Исследование баланса классов, обучение модель без учёта дисбаланса. Улучшение качества модели, учитывая дисбаланс классов. Обучение разных моделей и выбор лучшей. Финальное тестирование.
Построена модель с предельно большим значением F1-меры. 
Рассчитана AUC-ROC.


# Predict_profit
## Выбор локации для скважины с максимальными значениями прибыли
[Ссылка на проект]( https://clck.ru/Z8Ly8 "Title")

Построена модель для предсказания объёма запасов в новых скважинах.
Выбраны скважины с самыми высокими оценками значений.
Определен регион с максимальной суммарной прибылью отобранных скважин.
Проанализирована возможная прибыль и риски техникой Bootstrap.
