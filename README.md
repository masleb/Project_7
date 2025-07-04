Интернет-магазин «В один клик» продаёт разные товары: для детей, для дома, мелкую бытовую технику, косметику и даже продукты. 
Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. 
Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. 
Возможный выход — удерживать активность постоянных клиентов.

***Цель проекта***: разработать решение, которое позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность.

В процессе поиска лучшей модели с помощью инструмента GridSearchCV() были обучены несколько моделей с разными параметрами (KNeighborsClassifier(); DecisionTreeClassifier(); LogisticRegression() и SVC()).

***Итог***: построена модель, которая предсказывает вероятность снижения покупательской активности клиента в следующие три месяца. 
Проведен анализ важности признаков.
Также был исследован сегмент покупателей: **группа клиентов с максимальной долей покупок по акции и высокой вероятностью снижения покупательской активности**, и разработаны персонализированные предложения для них.
