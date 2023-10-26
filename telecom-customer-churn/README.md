# Прогнозирование оттока телеком компании

Для просмотра проекта можно выбрать 
[**Notebook**](/telecom-customer-churn/telecom-customer-churn.ipynb) 
или [**HTML**](http://htmlpreview.github.io/?https://github.com/ggorodokin/yandex-practicum-projects/blob/main/telecom-customer-churn/telecom-customer-churn.html).

## Описание проекта

Оператор связи хочет научиться прогнозировать отток клиентов. 
Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. 
Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах. 

## Навыки и инструменты

- Предобработка данных
- Исследовательский анализ
- Корреляционный анализ
- Визуализация данных
- Численные методы
- Кастомные функции

- Работа с данными: **pandas**, **numpy**, **re**, **phik**
- Графики: **matplotlib**, **seaborn**
- Подготовка данных: **train_test_split**
- Обработка признаков: **StandardScaler**, **category_encoders**
- Пайплайны: **Pipline**, **FunctionTransformer**, **ColumnTransformer**
- Модели: **Ridge, DecisionTreeClassifier, LGBMClassifier, CatBoostClassifier**
- Тюнинг: **RandomizedSearchCV**
- Метрики: **roc_auc_score, accuracy_score**
- Оценка качества модели: **classification_report, confusion_matrix, ConfusionMatrixDisplay, RocCurveDisplay**

## Выводы

Для прогнозирования оттока клиентов была разработана модель, способная выдать стабильный результат на новых данных. 
При тестировании модели её качество заметно превышает установленный заказчиком порог оценки.