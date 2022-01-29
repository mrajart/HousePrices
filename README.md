# HousePrices
Мое решение Kaggle House Prices Competition (https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

Окончательная оценка составила 0.12390, что составляет 15% лучших решений.

Нумерованные блокноты — это основные этапы pipeline. 

1-EDA (exploratory data analysis)
2-Data Cleaning. Очистка данных.
3-Data preparation. Подготовка данных для модели. Обработка категорий — label/ohe/frequency, проекция числовых на категории, трансформация числовых, бининг. Для регрессий (различное масштабирование)
4-Feature Selection. Выбор признаков для модели.
5-Models. Выбор модели, опробовал разные модели, посмотрел, что работает лучше всего
5b-Models-rfecv. Проверка выбранных с помощью Recursive Feature Elimination признаков на моделях.
5c-Models-target-permutation. Проверка выбранных с помощью Target permutation признаков на моделях.
5d-Models-boruta. Проверка выбранных с помощью Boruta признаков на моделях.
6-Ensemble. Ансамбль из лучших решений
