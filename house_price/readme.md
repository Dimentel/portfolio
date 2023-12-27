# Предсказание стоимости жилья

[ipynb](https://github.com/Dimentel/portfolio/tree/main/house_price/house_price.ipynb)

## Описание проекта

Обучена модель линейной регрессии на данных о жилье в Калифорнии в 1990 году. На основе данных предсказывается медианная стоимость дома в жилом массиве.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **pyspark**
- catboost.**CatBoostRegressor**, **cv**
- lightgbm.**LGBMRegressor**, **cv**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.model_selection.**GridSearchCV**, **cross_validate**
- sklearn.metrics.**mean_squared_error**

## 

## Общий вывод

Выполнена загрузка и предобработка данных. Построены модели в двух вариантах: на всех данных и только на числовых данных.