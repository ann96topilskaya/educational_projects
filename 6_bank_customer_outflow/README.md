# Отток клиентов

**Задача**

Маркетологи банка-заказчика обратили внимание на отток клиентов и выяснили: сохранять текущих клиентов дешевле, чем привлекать новых.

На предоставленных исторических данных о поведении клиентов и расторжении договоров с банком необходимо спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. 

Ключевая метрика - *F1*-мера, дополнительная - *AUC-ROC*

**Данные**

Источник: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

Датасет, состоящий из 10000 строк и 14 колонок:

    RowNumber
    CustomerId
    Surname
    CreditScore
    Geography
    Gender
    Age
    Tenure
    Balance
    NumOfProducts
    HasCrCard
    IsActiveMember
    EstimatedSalary
    Exited

**Ход работы**

1. Подготовка данных
2. Исследование задачи
3. Борьба с дисбалансом
4. Тестирование модели

**Библиотеки**

    Pandas
    Matplotlib
    Scikit-Learn