# Репозиторий с личными проектами анализа данных

| Название проекта | Описание | Используемые библиотеки и инструменты | 
| :---------------------- | :---------------------- | :---------------------- |
| [Надежность заемщиков](banking/scoring.ipynb) | На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Выделены леммы в значениях столбца и категоризированны данные.| *Python*, *pandas*, *PyMystem3*, *предобработка данных*, *лемматизация* |
| [Рынок квартир Санкт-Петербурга](estate/estate.ipynb) | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания.| *Python*, *pandas*, *Matplotlib*, *исследовательский анализ данных*, *визаулизация данных*, *предобработка данных* |
| [Тарифы телеком компании](telecom/telecom.ipynb) | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов.| *Python*, *pandas*, *Matplotlib*, *NumPy*, *SciPy*,  *описательная статистика*, *проверка статистических гипотез*|
| [Исследование платформ и видеоигр](games/games.ipynb) | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок.| *Python*, *pandas*, *Matplotlib*, *NumPy*, *предобработка данных*, *исследовательский анализ данных*, *описательная статистика*, *проверка статистических гипотез*|
| [Аналитика в авиакомпании](airlines/airlines.ipynb) | Проведена выгрузка и подготовка предоставленных данных авиакомпании средствами SQL. Проверена гипотеза о различии среднего спроса на билеты во время проведения различных фестивалей и в обычное время.| *SQL*, *Python*, *pandas*, *Matplotlib*, *SciPy*, *проверка статистических гипотез*|
| [Аналитика продаж и затрат в маркетинге](product/product.ipynb) | Проведен анализ данных компании целью оптимизации маркетинговых затрат. Рассчитаны метрики LTV, CAC, Retention rate, DAU, WAU, MAU, ROMI| *Python*, *pandas*, *Matplotlib*, *когортный анализ*, *юнит-экономика*, *продуктовые метрики*|
| [Проверка гипотез по увеличению выручки интернет-магазина](e-comm/e-comm.ipynb) | Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.| *Python*, *pandas*, *Matplotlib*, *SciPy*, *А/В тестирование*, *проверка статистических гипотез*|
| [Исследование рынка общественного питания Москвы для открытия точки](food/food.ipynb) | Был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с рекомендациями. В построении графиков я использовали библиотеки seaborn и plotly. Также мне потребовалось получить район расположения кафе-конкурентов. Эту задачу я решил, подключившись к API Яндекс.Геокодер библиотекой requests| *Python*, *pandas*, *Seaborn*, *Plotly*, *визуализация данных*|
| [Анализ пользовательского поведения в мобильном приложении](mobile/mobile.ipynb) | В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.| *Python*, *pandas*, *Matplotlib*, *Seaborn*, *Plotly*, *событийная аналитика*, *продуктовые метрики*, *проверка статистических гипотез*, *визуализация данных* |
| [Прогнозирование вероятности оттока пользователей для фитнес-центров](fitness/fitness.ipynb) | В данном проекте использовано машинное обучение. Спрогнозирована вероятность оттока (на уровне следующего месяца) для каждого клиента; сформированы типичные портреты пользователей: выделены наиболее яркие группы, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие на отток.| *Python*, *pandas*, *Scikit-learn*, *Seaborn*, *Matplotlib*, *машинное обучение*, *классификация*, *кластеризация* |
