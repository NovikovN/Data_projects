# YP_projects
Данный репозиторий содержит проекты, который были сделаны мною в процессе учебы на курсах Yandex.Praktikum.

| Проект                |   Описание             | Библиотеки                  |
| :--------------------:| :---------------------: |:---------------------------:|
| Исследование объявлений о продаже квартир | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. | pandas, matplotlib |
| Определение перспективного тарифа для телеком компании | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов. | pandas, numpy, matplotlib, scipy |
| Исследования данных о продаже компьютерных игр | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок. | pandas, numpy, matplotlib, scipy |
| Оптимизация маркетинговых затрат в Яндекс.Афише |Проведен анализ данных от Яндекс.Афиши целью оптимизации маркетинговых затрат. Рассчитаны метрики LTV, CAC, Retention rate, DAU, WAU, MAU, ROMI. | pandas, numpy, matplotlib, seaborn |
| Проверка гипотез по увеличению выручки в интернет-магазине — оценка результатов A/B теста |Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста. | pandas, numpy, matplotlib, scipy |
| Исследование рынка заведений общественного питания Москвы | Мною был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с рекомендациями. В построении графиков я использовали библиотеки seaborn и plotly. Для получения названия улиц, на которых располагаются заведения, я использовал регулярные выражения. | pandas, numpy, matplotlib, plotly, seaborn, модуль re |
| Анализ поведения пользователей мобильного приложения | В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей. | pandas, numpy, matplotlib, plotly, seaborn, scipy, datetime, statsmodels |
| Разработка стратегии взаимодействия с пользователями на основе аналитических данных для сети фитнесс-центров | В данном проекте использовано машинное обучение. Спрогнозирована вероятность оттока (на уровне следующего месяца) для каждого клиента; сформированы типичные портреты пользователей: выделены наиболее яркие группы, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие на отток. | pandas, numpy, matplotlib, seaborn, scipy, scikit-learn |
