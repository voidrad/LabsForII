## Постановка задачи

Я выбрал набор данных [Predicting Heart Failure](https://www.kaggle.com/datasets/whenamancodes/heart-failure-clinical-records) для выполнения лабораторной работы. Требуется предсказать, будет ли у наблюдаемого пациента сердечный приступ или нет

## Описание работы

В ЛР 0 проведена обработка и анализ данных:

* анализ на наличие нецельных данных
* проверка типа признаков (все они оказались числовыми)
* анализ попарных зависимостей
* анализ корреляционной матрицы
* анализ распределений данных
* oversampling данных

В ЛР 1 реализованы четыре алгоритма классического машинного обучения:

* метод k-ближайших соседей
* логистическая регрессия
* метод опорных векторов
* наивный байесовский классификатор

Каждый из них сравнивается с готовым из библиотеки scikit-learn.

## Вывод

Полученая точность 70-80% что не самый лучший результат, но данных в датасете достаточно мало, из-за чего провести полноценный анализ было проблематично.