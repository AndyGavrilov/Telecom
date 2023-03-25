# Предсказание оттока клиентов
учебный проект


**Цель исследования** - создать модель  для прогноза оттока клиентов телеком оператора (roc_auc не меньше 0.88). Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия.


**Ход исследования**

Данные получаем из файла Яндекс Практикума


Исследование пройдёт в 4 этапа:
1. Подготовка данных
2. Создание моделей
3. Анализ лучшей модели
4. Выводы


Используемые библиотеки: pandas, sklearn, catboost, seaborn, plotly, matplotlib, tqdm, phik

**Выводы:**
В ходе выполнения проекта было использовано 4 алгоритма: CatBoost, Логистическая регрессия, Случайный лес, Решающее дерево. Лучшее качество показал «CatBoost» - roc_auc на тестовой выборке 0.91, что соответствует необходимому уровню качества (roc_auc не меньше 0.88). Данная модель прошла проверку на вменяемость - roc_auc Dummy модели на тестовой выборке 0.5. Исходя из этого можно сделать вывод, что проект выполнен успешно.
