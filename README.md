# project_analyst_data_science
Проекты по аналитике и data science

Каждая папка содержит по одному проекту:
# AB test
**Проект «АВ тест и оценка корректности его проведения».** 
В проекте проанализированы: пересечение тестовой аудитории с конкурирующим тестом, совпадение теста и маркетинговых событий, другие проблемы временных границ теста, проведен исследовательский анализ данных (конверсия в воронке на разных этапах, распределения количества событий на пользователя, присутствуют ли в выборках одни и те же пользователи, распределение числа событий по дням), проведена оценка результатов A/B-тестирования (проверена гипотеза о равенстве кол-ва событий на пользователя в группах А и В, гипотеза о равенстве средней выручки с пользователя в группах А и В), проверена гипотеза о равенстве конверсий в группах А и В.
Стек - Pandas, numpy, scipy.stats, matplotlib.pyplot, seaborn, math, datetime.
***В результате исследования: оценена корректность проведения теста, проанализированы результаты теста.***

# Bank
**Проект «Анализ клиентов регионального банка и сегментация пользователей по количеству потребляемых продуктов».** 
В проекте проанализированы клиенты банка и сегментированы по количеству потребляемых продуктов, проведен исследовательский анализ данных, сформулированы и проверены статистические гипотезы, проверена гипотеза различия дохода между теми клиентами, которые пользуются двумя продуктами банка, и теми, которые пользуются одним.
***В результате исследования выявлено: как клиенты пользуются продуктом, какие характеристики клиента влияют на отток, портрет клиентов, которые чаще уходят, взаимосвязь дохода и кол-ва банковских продуктов.***
Стек – Pandas, numpy, scipy.stats, matplotlib.pyplot, seaborn.

# telecom company
**Проект «Определение перспективного тарифа для телеком-компании».** 
В проекте проанализировано: поведение клиентов оператора, исходя из выборки, сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц. Рассчитано: помесячная выручка с каждого пользователя, среднее количество, дисперсия и стандартное отклонение, построены гистограммы и описаны распределения.
Проверены гипотезы: о средней выручке пользователей по тарифам,  о средней выручке пользователей из Москвы и из других регионов.
***В результате анализа тарифов и пользователей определен выгодный тариф для сотового оператора, приведены конкретные показатели в сравнении с другим тарифом, проанализировано поведение клиентов, проверены гипотезы.***

Стек – Pandas, numpy, scipy.stats, matplotlib.pyplot, seaborn.

# traffic
**Проект «Выявление невыгодных источников трафика».** 
В проекте рассчитаны метрики трёх видов: продуктовые метрики (DAU, WAU, MAU, рассчитан Retention Rate применяя когортный анализ), метрики электронной коммерции (сколько времени в среднем проходит с момента первого посещения сайта до совершения покупки, среднее количество покупок на одного покупателя за 6 месяцев, средний чек, средний LTV по когортам за 6 месяцев), маркетинговые метрики (общая сумма расходов на маркетинг, как траты распределены по источникам, визуализированы изменения метрик во времени, средний CAC на одного покупателя для всего проекта и для каждого источника трафика, ROMI по когортам в разрезе источников, сравнение окупаемости за одинаковые периоды жизни когорт, построены графики, отражающие изменения метрик во времени).
***Результат исследования: проанализировано как клиенты пользуются сервисом, когда делают первые покупки на сайте, сколько денег приносит компании каждый клиент, когда расходы на привлечение клиента окупаются, определены источники трафика, на которые маркетологам стоит делать упор, подведены итоги когортного анализа, определены самые перспективные для компании когорты клиентов.***
Стек – Pandas, numpy, scipy.stats, matplotlib.pyplot, seaborn.  
