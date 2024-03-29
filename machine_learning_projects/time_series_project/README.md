# Прогнозирование заказов такси
## Описание проекта

Транспортная компания, оказывающая услуги такси, предоставила исторические данные о заказах такси в аэропортах.

Цель исследования - построить модель, предсказывающую количество заказов такси на следующий час. Это позволит привлекать больше водителей в период пиковой нагрузки. Для проверки эффективности модели использовать метрику RMSE, значение которой на тестовой выборке должно быть не больше 48.

## Общий вывод
Выполнен анализ предоставленных данных (ресемплирование, декомпозиция на компоненты: тренд, сезонная составляющая и остатки, анализ автокорреляционной функции). Анализ показал, что данные нестационарные,имеют трендовую и сезонную компоненты. Восходящий тренд ярко выражен в летние месяцы. Сезонная компонента показала наличие суточного хода. Анализ АКФ показал сильную корреляцию для 1 и 24 лагов.
Выполнена подготовка признаков (созданы признаки, данные разбиты на три выборки, выполнено масштабирование количественных признаков).
Исследовано три модели:
- линейная регрессия,
- случайный лес,
- LightGMB

Учитывая критерии заказчика, в качестве наилучшей модели выбрана LightGMB. Проверка модели на тестовой выборке и ее сравнение с Dummy моделью, подтвердило ее адекватность. 

## Примечание
Анализ графиков целевого признака и прогноза показал, что все используемые модели плохо аппроксимируют пики, присутствующие во временном ряде. Возможно стоит рассмотреть другие модели, например, модели временных рядов ARIMA, SARIMA для получения более лучших результатов.
