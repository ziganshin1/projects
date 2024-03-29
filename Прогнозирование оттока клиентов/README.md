# Описания проекта - Прогнозирование оттока клиентов


## Данные
- RowNumber — индекс строки в данных
- CustomerId — уникальный идентификатор клиента
- Surname — фамилия
- CreditScore — кредитный рейтинг
- Geography — страна проживания
- Gender — пол
- Age — возраст
- Tenure — количество недвижимости у клиента
- Balance — баланс на счёте
- NumOfProducts — количество продуктов банка, используемых клиентом
- HasCrCard — наличие кредитной карты
- IsActiveMember — активность клиента
- EstimatedSalary — предполагаемая зарплата
- Exited — факт ухода клиента

## Задача
Анализ оттока клиентов из банка для выбор стратегии (удержание старых клиентов или привлечение новых клиентов).

## Используемые библиотеки
Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Math, ADASYN, XGBoost, машинное обучение;

## Вывод по проекту
Построена модель с предельно большим значением F1-меры с последующей проверкой на тестовой выборке. Доведена метрика до 0.59. 
Дополнительно измерен AUC-ROC, соотнесен с F1-мерой.
