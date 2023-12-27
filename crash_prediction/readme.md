# Предсказание ДТП

[ipynb](https://github.com/Dimentel/portfolio/tree/main/crash_prediction/crash_prediction.ipynb)

## Описание проекта

В каршеринговой компании возникла идея создать систему, которая могла бы оценить риск ДТП по выбранному маршруту движения.
Как только водитель забронировал автомобиль, сел за руль и выбрал маршрут, система должна оценить уровень риска.
Если уровень риска высок, водитель увидит предупреждение и рекомендации по маршруту. Опираясь на исторические данные одного из регионов,
создана модель предсказания ДТП.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- **sqlalchemy**
- catboost.**CatBoostClassifier**, **cv**
- lightgbm.**LGBMClassifier**, **cv**
- sklearn.linear_model.**RidgeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.compose.**make_column_transformer**
- from sklearn.pipeline.**make_pipeline**
- sklearn.metrics.**roc_auc_score**, **roc_curve**, **confusion_matrix**
- sklearn.model_selection.**GridSearchCV**, **RandomizedSearchCV**

## 

## Общий вывод

Выполнено подключение к базе данных и первичный анализ таблиц, статистический анализ факторов ДТП, выбор факторов для модели машинного обучения.
Проработано несколько моделей (логистическая регрессия, на основе случайного леса, модели градиентного бустинга из библиотек LightGBM и Catboost), кроссвалидацией выбрана лучшая.
Проведён анализ важности признаков.