# Предсказание оттока клиентов (телеком)

[ipynb](https://github.com/Dimentel/portfolio/tree/main/churn_prediction_telecom/churn_prediction_telecom.ipynb)

## Описание проекта

Оператор связи «ТелеДом» с целью предотвращения оттока клиентов планирует предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи. Чтобы заранее находить таких пользователей, «ТелеДому» требуется модель, которая будет предсказывать, разорвёт ли абонент договор.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**
- **matplotlib**
- **torch**
- skorch.classifier.**NeuralNetBinaryClassifier**
- catboost.**CatBoostClassifier**, **cv**
- lightgbm.**LGBMClassifier**, **cv**
- phik.report.**plot_correlation_matrix**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.metrics.**accuracy_score**, **roc_auc_score**, **roc_curve**, **confusion_matrix**
- sklearn.compose.**make_column_transformer**
- sklearn.pipeline.**make_pipeline**
- sklearn.model_selection.**GridSearchCV**, **RandomizedSearchCV**



## 

## Общий вывод

Выполнено подключение к базе данных, анализ и предобработка данных, выбор факторов для моделей машинного обучения. Проработано несколько моделей: на основе случайного леса, модели градиентного бустинга из библиотек LightGBM и Catboost, полносвязная нейронная сеть. Кроссвалидацией выбрана лучшая модель. Лучшая модель протестирована, проведён анализ важности признаков.