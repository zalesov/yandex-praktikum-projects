# Предсказание оттока клиентов

Данный **учебный** проект - пример построения модели бинарной классификации. 

Цель: создать модель, предсказывающую уйдет ли клиент из банка или нет.

**Описание данных**:
Исторических данные о поведении клиентов и расторжении договоров с банком.

**Целевой признак**:
Exited — факт ухода клиента

**Метрика качества**
F1-мера


### Важные нюансы выполнения работы

- Подготовка данных
- Дисбаланс классов:
 - обучение модели без учета дисбаланса
 - обучение модели с учетом дисбаланса классов
  


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

*Статус проекта*: завершен

## Итоговый вывод проекта: 

Данные были очищены, поставлена задача классификации; данные были разбиты в соотношении 3:1:1, была построена и изучена модель без учета дисбаланса классов; затем дисбаланс был изучен и в ходе анализа AUC-ROC был подобран подходящий порог классов. Было проанализировано три модели: Логистическая регрессия, Решающее дерево и Случайный Лес. Последний был выбран так как показал изначально лучшее значение F1-меры, были подобраны соответствующие гиперпараметры, которые показали на тестовой выборке значение F1-меры в 0.617. а значение AUC-ROC: 0.741599.