# Определение стоимости автомобилей

[ipynb](https://github.com/Dimentel/portfolio/tree/main/car_price/car_price.ipynb)

## Описание проекта

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов.
В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторических данных об автомобилях и продажах построена модель для определения стоимости.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- catboost.**CatBoostRegressor**, **cv**
- lightgbm.**LGBMRegressor**, **cv**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.model_selection.**GridSearchCV**, **cross_validate**
- sklearn.metrics.**mean_squared_error**

## 

## Общий вывод

Выполнена загрузка и предобработка данных (заполнены пропуски, обработаны аномалии), выполнен подбор моделей линейной регрессии, catboost, LightGBM и на основе случайного леса.
Проведёно сравнение моделей по времени обучения/предсказания, метрике RMSE.