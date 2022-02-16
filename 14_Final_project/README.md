# Прогнозирование оттока клиентов

Данный **учебный** проект - пример задачи построения модели бинарной классификации

**Цель**: построить модель, которая спрогнозирует отток клиентов с метрикой качества .

**Описание данных**    
Данные состоят из файлов, полученных из разных источников:  
Во всех файлах столбец customerID содержит код клиента.  
Информация о договорах актуальна на 1 февраля 2020.


- BeginDate – дата начала пользования услугами,  
- EndDate – дата окончания пользования услугами,  
- Type – тип оплаты: ежемесячный, годовой и тд,  
- PaperlessBilling – безналичный расчет,  
- PaymentMethod – способ оплаты,  
- MonthlyCharges – ежемесячные траты на услуги,  
- TotalCharges – всего потрачено денег на услуги  
- Dependents – наличие иждивенцев  
- Senior Citizen – наличие пенсионного статуса по возрасту  
- Partner – наличие супруга(и)  
- MultipleLines – наличие возможности ведения параллельных линий во время звонка  

**Метрика качества:**
- ROC-AUC


### Особенности данной работы:

- Много категориальных переменных
- Требуется высокая метрика качества (roc_auc_score>0.88)
- Данные хранятся в разных файлах 
- Feature engineering
- Feature generation
- Подбор гиперпараметров
- Дисбаланс классов - Upsampling
  
Каждый этап требуется сопроводить пояснением.  

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
