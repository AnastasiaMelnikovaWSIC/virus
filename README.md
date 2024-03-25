# virus
Классификатор вредоносного ПО.

Используя в качестве исходного набора данных датасет по ссылке, постройте модель для определения, того или иного класса вредоносного ПО.

Проведите K-fold кросс-валидацию (размер тестовой части: 1/K) метрик: accuracy, F1, площадь под ROC при помощи комбинации методов ShuffleSplit и cross_validate, random_state = 63. Как результат для метрики взять среднее значение по folds, K = 8. Обучите три классификатора: LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, random_state = 63.

Оцените модели на тестовых данных.

Ссылка: https://courses.openedu.ru/assets/courseware/v1/0c23e3262b6cf0e730653e275ae18f42/asset-v1:ITMOUniversity+INFSECBAS+spring_2024_ITMO+type@asset+block/Task_5_selected_data.csv
