# GBID
## Задача
На основе данных из соревнования https://www.kaggle.com/c/grupo-bimbo-inventory-demand/overview необходимо разработать модель для точного прогнозирования спроса на товарно-материальные запасы на основе исторических данных о продажах.

XGBoost, а так же провести первичный анализ данных.

* Произвести первичный анализ данных.
  1. Рассмотреть распределение общего спроса по неделям и каналам, распределение спроса по продуктам по неделям.
  2. Воспользоваться дополнительными таблицами, посмотреть распределение по городам и штатам (выявить наиболее частые).
* На основе случайной подвыборки из предоставленных данных:
  1. Рассмотреть изменение метрики при различных способах построения моделей с помощью RandomForest:
     - на "сырых" данных;
     - с разбиением колонок с небольшим ограниченным количеством значений;
     - с использованием наиболее частых штатов, найденных при анализе;
     - с учетом значений выше среднего.
  3. Построить модель с помощью XGBoost.
