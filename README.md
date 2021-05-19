1. **В данном проекте перед нами стоит следующая цель: построить прогноз относительно того уйдёт клиент в ближайшее время или нет. Требуется найти модель с предельно большим значением F1-меры (минимум 0.59). Так же требуется измерять AUC-ROC, сравнивая значение с F1-мерой.**
----------------------------------------
2. **ОПИСАНИЕ ДАННЫХ:**
- RowNumber — индекс строки в данных
- CustomerId — уникальный идентификатор клиента
- Surname — фамилия
- CreditScore — кредитный рейтинг
- Geography — страна проживания
- Gender — пол
- Age — возраст
- Tenure — сколько лет человек является клиентом банка
- Balance — баланс на счёте
- NumOfProducts — количество продуктов банка, используемых клиентом
- HasCrCard — наличие кредитной карты
- IsActiveMember — активность клиента
- EstimatedSalary — предполагаемая зарплата
----------------------------------------
3. **ОСНОВНЫЕ ПУНКТЫ И ЦЕЛИ ИССЛЕДОВАНИЯ:**
- Загрузить и предобработать данные;
- Исследовать классы на баланс (посмотреть нет ли дисбаланса классов). Обучить модель на сбалансированных данных.
- Улучшить качество модели, учитывая дисбаланс классов. Обучить модели, найти лучшую.
