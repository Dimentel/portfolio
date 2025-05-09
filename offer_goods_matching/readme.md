# Сопоставление товаров между собой с целью детекции матчей

[ipynb](https://github.com/Dimentel/portfolio/tree/main/offer_goods_matching/offer_goods_matching.ipynb)

## Описание проекта

Необходимо решить задачу по матчингу товаров, а именно финальную часть пайплайна матчинга. В ней мы должны принять решение для каждой пары (товар предлагаемый продавцом — товар на площадке), является ли она матчем или нет (бинарная классификация).
Для этого у каждой пары есть набор признаков и наборы векторов (картиночные и текстовые), которые описывают товары из этой пары.
В качестве метрики качества решения используется F-score.

## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- catboost **CatBoostClassifier**, **Pool**, **FeaturesData**
- sklearn **make_column_transformer**, **make_pipeline**, **paired_cosine_distances**

## 

## Общий вывод

Выполнена загрузка и предобработка данных, созданы дополнительные признаки, основанные на отличии цен
 и на основе эмбеддингов текстов и изображений. В ходе экспериментов с моделями на основе бустинга из
 библиотеки catboost выбрана наилучшая 
