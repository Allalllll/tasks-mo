# tasks-mo
## 1
Датасет https://archive.ics.uci.edu/dataset/162/forest+fires
Метрика RMSE

Категориальные признаки закодировать с помощью OneHotEncoder
Не забыть разбить на train и test
Обработать выбросы
Обучить сначала обычную линейную регрессию
Провести отбор признаков с помощью RFE https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFECV.html
Обучить линейную регрессию с наилучшим количеством признаков
Обучить Ridge и Lasso регрессию
