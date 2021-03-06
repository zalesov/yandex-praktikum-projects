# Выбор локации для скважины

Данный **учебный** проект - пример построения модели регресии для предсказания количества запасов нефти в 3-х месторождениях. 
  
**Цель**: Определить с 95% доверительным интервалом, при добыче из которой скважины прибыль будет максимальна (и положительна), основываясь на предсказаниях построенной модели. 

**Метрика качества**:
RMSE

**Условия задачи**:
Для обучения модели подходит только линейная регрессия (остальные — недостаточно предсказуемые).
При разведке региона исследуют 500 точек, из которых с помощью машинного обучения выбирают 200 лучших для разработки.
Бюджет на разработку скважин в регионе — 10 млрд рублей.
При нынешних ценах один баррель сырья приносит 450 рублей дохода. Доход с каждой единицы продукта составляет 450 тыс. рублей, поскольку объём указан в тысячах баррелей.
После оценки рисков нужно оставить лишь те регионы, в которых вероятность убытков меньше 2.5%. Среди них выбирают регион с наибольшей средней прибылью.
Данные синтетические.

### Описание данных

id — уникальный идентификатор скважины;    
f0, f1, f2 — три признака точек (неважно, что они означают, но сами признаки значимы);   
product — объём запасов в скважине


### В ходе работы были следующие важные моменты:

- Подготовить данные
- Построить модель для предсказания объёма запасов в новых скважинах, основываясь на уже известных данных
- Выбирать скважины с самыми высокими оценками значений
- Определить регион с максимальной суммарной прибылью отобранных скважин
- Проанализировать возможную прибыль и риски техникой Bootstrap.
- Найти среднюю прибыль, 95%-й доверительный интервал и риск убытков

  
Каждый количественный ответ требуется сопроводить пояснением.  

### Используемые технологии:

* pandas
* from sklearn.linear_model import LinearRegression
* sklearn.model_selection
* sklearn.metrics
* Bootstrap

*Статус проекта*: завершен

## Итоговый вывод проекта: 

Модель показала наибольшую прибыль в третьем регионе. RMSE третьего региона сопоставима с RMSE первого региона. RMSE 2 региона мала, но, возможно, это связано с количеством дубликатов в целевом столбце таблицы. Также, третий регион показал наименьшую среднюю отрицательную прибыль нижнего порога 95%-доверительного интервала по сравнению с первым. Исходя из лучшей прибыли, наименьшой возможной средними убытками и невозможностью доверять значению RMSE модели по 2-му региону, для разработки предлагаю выбрать третий регион.
