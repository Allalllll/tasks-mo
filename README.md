# tasks-mo
## 1 forestfires

Датасет https://archive.ics.uci.edu/dataset/162/forest+fires
Метрика RMSE

Категориальные признаки закодировать с помощью OneHotEncoder
Не забыть разбить на train и test
Обработать выбросы
Обучить сначала обычную линейную регрессию
Провести отбор признаков с помощью RFE https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFECV.html
Обучить линейную регрессию с наилучшим количеством признаков
Обучить Ridge и Lasso регрессию
## 2 МО SVM и деревья решений
Для датасета https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease
Обучить SVM, подобрать параметры, посчитать метрики качества классификации
Обучить Decision Tree Classifier, подобрать параметры, посчитать метрики качества классификации 
