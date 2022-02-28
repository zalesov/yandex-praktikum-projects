# Исследование объявлений о продаже квартир

Задача данного **учебного** проекта - установить параметры, влияющие на рыночную стоимость объектов недвижимости.  

Данные — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет от сервиса продажи невижимости.   
  
По каждой объекту, выставленному на продажу доступны два вида данных. Первые вписаны пользователем, вторые получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. 
  
Требуется произвести предобработку данных и feature engineering.

### В ходе исследования требуется ответить на следующие вопросы:

- Опишите, сколько обычно занимает продажа. Когда можно считать, что продажи прошли очень быстро, а когда необычно долго?
- Какие факторы больше всего влияют на стоимость квартиры? Изучите, зависит ли цена от квадратного метра, числа комнат, этажа (первого или последнего), удалённости от центра ?
- Есть ли зависимость от даты размещения: дня недели, месяца и года?
- Найти 10 населённых пунктов с наибольшим числом объявлений. Посчитайте среднюю цену квадратного метра в этих населённых пунктах. Выделите населённые пункты с самой высокой и низкой стоимостью жилья
- Выяснить, какая область входит в "центр" Санкт-Петербурга? (ответ нужно дать в километрах и посчитать среднюю  цену для каждого километра)
- Проанализировать особенности недвижимости в центре города
- Отличаются ли полученные результаты по всему региону от результатов, полученных по центру, и если да, то как?  

  
Каждый количественный ответ требуется сопроводить пояснением. 





### Используемые технологии:

* pandas
* matplotlib  
* numpy

*Статус проекта*: завершен

## Итоговый вывод проекта: 

Данные проанализированы, очищены, изменен тип данных некоторых столбцов, выделены закономерности в факторах, влияющих на цену недвижимости, также выделен радиус квартир в центре, сам сегмент, выявлены закономерности. 
Поведение продавцов недвижимости в центре Санкт-Петербурга не отличается от поведения продавцов недвижимости в Санкт-Петербурге в целом. Отличается ценой и площадью: медиана площади в Санкт-Петербурге = 56.0, а цены = 5650000.0, а в центре: медиана цены: 9900000.0, а медиана площади: 86.0.
