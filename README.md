# practikum_projects
Репозиторий содержит учебные проекты курса "Специалист по Data Science" от Яндекс Практикум

# Аналитические проекты
|Название проекта|Описание проекта|Стек|
|----------------|----------------|----|
|[Анализ рынка недвижимости (на примере Санкт-Петербурга)](https://github.com/nadinfet/practikum_projects/tree/71c5fc0cdf2d14c75c0e2f30c469de1845d79095/analytic_project)|Предоставлен архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет (данные сервиса Яндекс.Недвижимость). Необходимо на основе исследовательского анализа данных определить параметры, влияющие на цену объектов недвижимости, рыночную стоимость объектов недвижимости.|Python, Pandas, Matplotlib|

# Классическое машинное обучение
|Название проекта|Описание проекта|Стек|
|----------------|----------------|----|
|[Прогнозирование оттока клиентов телеком-компании](https://github.com/nadinfet/practikum_projects/blob/5b6c8733ce431a7373dbdfa4b1801eb0a3a0b419/machine_learning_projects/customer_outflow/customer_outflow.ipynb)|Телеком-компании необходимо спрогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.|Python, Pandas, Matplotlib, Scikit-learn (LogisticRegression, GridSearchCV, StandardScaler, OHE, RandomForestClassifier, LogisticRegression), LGBMClassifier|
|[Прогнозирование количества заказов такси](https://github.com/nadinfet/practikum_projects/blob/72318218b006493a75f7fdd7f6f474b28c13ea18/machine_learning_projects/time_series_project/taxi_time_series.ipynb)|Компания такси собрала исторические данные о заказах такси в аэропортах. Необходимо построить модель для прогнозирования количества заказов такси на следующий час. Для оценки эффективности модели использовать метрику RMSE, которая на тестовой выборке не должна превышать 48.|Python, Pandas, Scikit-learn, GridSearchCV, RandomForestRegressor, LinearRegression), LGBMRegressor, statsmodels|
|[Определение наиболее выгодного региона нефтедобычи](https://github.com/nadinfet/practikum_projects/blob/e27f92446d0681bf39d22eeccda2bc4ed1b26282/machine_learning_projects/oil_region_project/oil_region.ipynb)|Проект выполнен для нефтедобывающей компании, которая предоставила пробы нефти в трёх регионах. Необходимо построить модель для определения региона, где добыча принесёт наибольшую прибыль.|Pandas, Scikit-learn (LinearRegression), Bootstrap|

# SQL проект
|Название проекта|Описание проекта|Стек|
|----------------|----------------|----|
|[SQL-запросы к реляционной БД](https://github.com/nadinfet/practikum_projects/tree/4842eda160bf4a8dce19b3c1dab48a12c05b26e4/SQL_project)|Произвести выгрузки данных о венчурных фондах и инвестициях в компании-стартапы|PostgreSQL: GROUP BY, подзапросы, JOIN-соединения, оконные функции|
