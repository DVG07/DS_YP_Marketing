# DS_YP_Marketing

Проект осуществлен по данным интернет-магазина за период с 2022 по 2024 года.
Использованны данные об истории покупок клиентов, проведенных рассылках, а также были предоставлены данные о том, совершил ли клиент покупку в течение 90 дней после первой.

Целью проекта являлось подготовка модели машинного обучения, которая сможет предсказать вероятность совершения покупки клиентом в течение 90 дней.

В рамках проекта было сделано:
- Данные были загружены и рассмотрены, проведен исследовательский анализ.
- Создана первоначальная модель для классификации пользователей (использована модель CatBoostClassifier). По итогу оценки метрики качества (ROC-AUC) получен результат 69,3%.
- В исходные данные о клиентах были добавлены данные о маркетинговых рассылках. Сформированы два новых датафрейма с данными (один с данными о дате покупки, другой с данными о канале рассылки).
- По итогу обучения двух новых моделей и корректировки гиперпараметров, получена модель с метрикой качества 80.3% (на основе данных с данными о дате покупки и совершенным действием с полученной рассылкой).
- Проведен анализ важности параметров.
- Сделан итоговый вывод.
