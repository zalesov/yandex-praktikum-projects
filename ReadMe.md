**Данный репозиторий содержит выполненные учебные проекты Яндекс.Практикума по направлению Data Science**

## 1. Банковский скоринг  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/1_bank_scoring

Требуется проанализировать факторы, которые увеличивают вероятность невозврата кредита. 

### Используемые технологии:

* pandas
* pymystem3

## 2. Анализ недвижимости в Санкт-Петербурге  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/2_Flats_in_SP

Используя данные о продаже недвижимости, проанализировать рынок недвижимости в Санкт-Петербурге

### Используемые технологии:

* pandas
* matplotlib  
* numpy

## 3. Выбор оптимального тарифа  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/3_Tariff_Megaphone

Используя данные об использовании услуг связи, выбрать наиболее прибыльный для телекоммуникационной компании тариф

### Используемые технологии:
* pandas
* matplotlib
* numpy

## 4. Анализ игр  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/4_Games_project

Требуется выявить определяющие успешность игры закономерности (по продажам)

### Используемые технологии:

* pandas
* matplotlib.pyplot
* scipy.stats
* plotly

## 5. Рекомендация тарифов  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/5_Better_Tariff

Нужно предсказать по признакам объекта (архивные данные клиентов телекоммуникационной компании), перейдет ли клиент на новую тарифную линейку. Метрика качества модели: accuracy.

### Используемые технологии:

* pandas
* scipy.stats
* seaborn
* matplotlib
* sklearn.tree.DecisionTreeClassifier
* sklearn.linear_model.LogisticRegression
* sklearn.metrics



## 6. Отток клиентов из банка  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/6_Bank_leavers

Цель работы - создать модель, предсказывающую уйдет ли клиент из банка или нет. Метрика качества: f1-мера

### Используемые технологии:

* pandas
* sklearn.model_selection
* sklearn.preprocessing
* sklearn.tree.DecisionTreeClassifier
* sklearn.metrics
* matplotlib.pyplot
* numpy
* sklearn.linear_model.LogisticRegression
* sklearn.ensemble.RandomForestClassifier
* sklearn.tree.DecisionTreeClassifier
* seaborn

## 7. Выбор локации для скважины  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/7_Oil_choice

Линейной регрессией предсказать и техникой Bootstrap подтвердить с 95% доверительным интервалом безубыточное локацию для добычи нефти. 

### Используемые технологии:

* pandas
* from sklearn.linear_model import LinearRegression
* sklearn.model_selection
* sklearn.metrics
* Bootstrap

## 8. Предсказание остаточного количества золота после очистки  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/8_Cyfra_project

Требуется построить модель, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды (сразу 2 параметра).


### Используемые технологии:

* pandas
* numpy
* sklearn.metrics
* matplotlib.pyplot
* scipy.stats
* re
* sklearn.metrics
* sklearn.model_selection.cross_val_score
* sklearn.linear_model.LinearRegression
* sklearn.ensemble.RandomForestRegressor

## 9. Матрица шифрования 
https://github.com/zalesov/yandex-praktikum-projects/tree/main/9_insurance_matrix

Задача: создать алгоритм, который сможет изменить табличные данные клиентов без потери качества для обучения модели.

### Используемые технологии:

* pandas
* numpy
* sklearn.metrics
* sklearn.linear_model.LinearRegression

## 10. Предсказание цены автомобиля  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/10_Cars_pricing

Нужно построить модель, способную предсказывать по параметрам автомобиля, его цену на рынке. "Заказчику", кроме качества, важны время работы и обучения модели

### Используемые технологии:

* pandas
* numpy
* matplotlib.pyplot
* sklearn.metrics
* sklearn.ensemble.RandomForestRegressor
* sklearn.linear_model.LinearRegression
* LightGBM




## 11. Предсказание количества заказов такси  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/11_taxi_time_series

Цель - спрогнозировать количество заказов такси на следующий час

### Используемые технологии:

* pandas
* statsmodels.tsa.seasonal
* matplotlib.pyplot
* sklearn.linear_model.LinearRegression
* sklearn.ensemble.RandomForestRegressor



## 12. Классификация твиттов  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/12_wikishop_text_classification

Требуется создать модель бинарной классификации, которая по входному тексту определит его как токсичный или нормальный. 

### Используемые технологии:

* pandas
* numpy
* torch
* transformers
* tqdm.notebook
* re
* sklearn.linear_model
* sklearn.model_selection
* nltk
* sklearn.ensemble.RandomForestClassifier
* GridSearchCV
* WordNetLemmatizer
* TfidfVectorizer
* matplotlib.pyplot
* nltk.corpus.wordnet

## 13. Компьютерное зрение  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/13_Computer_vision

Нужно построить нейросеть, которая по фотографии определит возраст человека (Фотография подается как матрица с информацией о каждом пикселе)

### Используемые технологии:

* pandas
* numpy
* tqdm
* tensorflow.keras
* tensorflow.keras.models.Sequential
* tensorflow.keras.applications.resnet.ResNet50
* tensorflow.keras.optimizers.Adam
* tensorflow.keras.preprocessing.image.ImageDataGenerator
* tensorflow.keras.layers
 * Conv2D 
 * Flatten 
 * Dense
 * AveragePooling2D
 * AvgPool2D 
 * GlobalAveragePooling2D



## 14. Финальный проект  
https://github.com/zalesov/yandex-praktikum-projects/tree/main/14_Final_project

Требуется построить модель бинарной классификации, которая спрогнозирует отток клиентов с высокой метрикой качества ROC-AUC.

### Используемые технологии:

* pandas
* numpy
* matplotlib.pyplot
* sklearn.metrics
* sklearn.model_selection
* sklearn.utils
* sklearn.linear_model.LogisticRegression
* sklearn.ensemble.RandomForestClassifier
* catboost.CatBoostClassifier
* RandomizedSearchCV
* GridSearchCV
* Upsampling
