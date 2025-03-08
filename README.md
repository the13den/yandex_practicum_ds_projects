| Название работы | Описание работы | Технологии |
| --------------- | --------------- | ---------- |
| [Предсказание стоимости жилья в Калифорнии с помощью PySpark](https://github.com/the13den/yandex_practicum_ds_pyspark_house_cost_pred_n10) | Используя PySpark, предобработал данные о жилье в Калифорнии и создал pipeline линейной регрессии. Пайплан подготавливает данные и предсказывающий медианную стоимость жилья в районе. Дал множество рекомендаций по улучшению качества предсказаний. Несмотря на объем, считаю эту работу лучшей. Она написана максимально качественно и хорошо структурирована. Если какой-то этап, например, отбор признаков не выполнялся, значит он не был необходим в ТЗ, а задача уже сведена к решенной в предыдущих проектах. | `Python`, `Pandas`, `matplotlib`, `seaborn`, `pyspark`, `pyspark sql` |
| [Терминал. Git. Github](https://github.com/the13den/yandex_practicum_ds_terminal_operations_git_github_n9) | Повторил работу с файлами и катологами через терминал. Научился пользоваться git через консоль и начал делать это постоянно | `Терминал`, `Git`, `Github` |
| [Базовый SQL. Postegre SQL. срезы, агрегирование, объединения таблиц, подзапросы и CTE](https://github.com/the13den/yandex_practicum_ds_sql_basics_joins_subqueries_etc_n8) | После изучения блока с теорией в 20 часов и написания больше 100 запросов, приступил к проекту модуля. Проект проверялся автоматически. По базе данных Startup Investments, опубликованной на популярной платформе для соревнований по исследованию данных Kaggle, написал 23 запроса, среди которых часто встречались и такие: | `SQL`, `PostegreSQL` |
| [ML прогнозирование количества сырья в скважинах региона, расчет прибыли, выбор оптимального региона для разработки с помощью техники Bootstrap](https://github.com/the13den/yandex_practicum_ds_bootrap_risk_modeling_ml_oil_product_prediction_for_oil_company_n7) | Нам даны три региона, для каждого региона отдельный файл. Файлы заполнены записями о скважинах и их характеристиках. Нужно выбрать оптимальный регион, соответсвующий требованиям бизнеса. Для решения задачи я подключил, предобработал данные и подготовил их через пайплайн. Так как информация о природе признаков не раскрыта, исследовательский анализ данных пропущен. С помощью линейной регрессии предсказал количество сырья. Стоимость единицы сырья известна. Затем для каждого региона техникой bootstrap сформировал 1000 выборок размером 500 скважин, после чего рассчитал доверительные интервалы прибыли для каждого региона и предложил регион для разработки | `Python`, `Pandas`, `matplotlib`, `Plotly`, `Sklearn`, `Numpy`, `Sklearn`, `Bootstrap` |
| [Большой проект по предсказанию увольнений сотрудников и удовлетворенности через методы машинного обучения. Анализ факторов, влияющих на решение о расторжении трудового договора и вовлеченности сотрудников.](https://github.com/the13den/yandex_practicum_ds_big_project_supervised_learning_employee_satisfaction_and_dismissal_n6) | Решил две бизнес задачи: Первая - построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика. Почему бизнесу это важно: удовлетворённость работой напрямую влияет на отток сотрудников. А предсказание оттока - одна из важнейших задач HR- аналитиков. Внезапные увольнения несут в себе риски для компании, особенно если уходит важный сотрудник. Вторая задача - построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании. Для этого предобработал данные. Провел исследовательский анализ данных понял на какие категории делятся сотрудника. Узнал, что влияет на уровень удовлетворенности и отток сотрудников. Отобрал признаки, проверил их на мультиколлинеарность и утечку данных. Собрал два пайплана sklearn МО для разных задач с полным циклом подготовки данных. Получил предсказания и оценил пайплайн модели DTR кастомной метрикой SMAPE, а пайплайн классификации метрикой Roc-Auc | `Python`, `Pandas`, `matplotlib`, `Plotly`, `Sklearn`, `Numpy`, `phik` |
| [Предсказание снижения активности клиента интернет магазина с помощью четырех моделей классификации. Решение проблемы дисбаланса классов, использование пайплана и подбора гиперпараметров на кроссвалидации](https://github.com/the13den/yandex_practicum_ds_big_project_supervised_learning_user_activity_prediction_n5) | Бизнес задача - промаркировать уровень финансовой активности постоянных покупателей. В компании принято выделять два уровня активности: «снизилась», если клиент стал покупать меньше товаров, и «прежний уровень». В исследование нужно включить дополнительные данные финансового департамента о прибыльности клиента: какой доход каждый покупатель приносил компании за последние три месяца. Используя данные модели и данные о прибыльности клиентов, нужно выделить сегменты покупателей и разработать для них персонализированные предложения. Решал ее следующим образом. Предобработал и исследовал данные, используя Pandas и библиотеки для визуализации. Отобрал признаки. Затем создал пайплайн sklearn, который заполняет пропуски, кодирует и масштабирует данные. Он использует модели KNN, SVC, DTC, Logistic Regression, для получения предсказаний. После создания пайплайна я отобрал гиперпараметры на кроссвалидации для каждой модели, например, количество соседей для knn, регурялизацию для LogisticRegression. Лучшая модель была выбрана с помощью метрики ROC-AUC. С помощью лучшей модели я промаркировал уровень финансовой активности постоянных покупателей. Для лучшего понимания того, что влияет на поведение покупателей, я интерпретировал модель с помощью shap. В конце выделил один из сегментов пользователей и предложил персональные предложения для него. Также я добавил данные о том, какой доход каждый покупатель приносил компании за последние три месяца. | `Python`, `pandas`, `matplotlib`, `seaborn`, `plotly`, `sklearn`, `phik`, `shap` |
| [Использование моделей линейной и логистической регрессии для предсказания вкуса и количества молока, у коров, планируемых к покупке](https://github.com/the13den/yandex_practicum_ds_linear_models_cows_prediction_n4) | К нам обратился фермер, который хотел купить коров у заводчика. Заводчик и фермер собирали данные о своих коровах. Нужно было помочь фермеру выбрать лучших коров для покупки. В этой работе я предобработал и исследовал данные иcпользуя Pandas и библиотеки для визуализации. Затем отобрал признаки для обучения модели на основе логической взаимосвязи, корелляций Пирсона и Фи, визуальной взаимосвязи переменных на графике рассеяния. С помощью линейной регрессии я получил предсказания количества удоя в кг. Используя sklearn, с помощью модели логистической регрессии я предсказал бинарную характеристику “молоко вкусное”. Фермер лучше не купит корову, чем купит корову с невкусным молоком. Согласно желаниям заказчика я настроил порог модели линейной регрессии так, чтобы минимизировать ошибку первого рода. Результатом работы стал список коров рекомендуемых к покупке | `Python`, `Pandas`, `matplotlib`, `Plotly`, `Sklearn`, `Numpy` |
| [Статистический анализ данных. Проверка гипотез и моделирование событий для сервиса по прокату самокотов](https://github.com/the13den/yandex_practicum_ds_hypothesis_testing_event_modeling_for_scooter_rent_service_n3) | Вначале работы у нас было три таблицы с данными сервиса по прокату самокатов. Я предобработал данные, объединил таблицы с помощью Pandas. Провел исследовательский анализ с помощью matplotlib, seaborn, plotly. В конце с помощью scipy проверил ряд гипотез, смоделировал несколько событий. Дал рекомендации для бизнеса. | `Python`, `pandas`, `matplotlib`, `seaborn`, `plotly`, `scipy` |
| [Большой проект по предобработке и исследовательскому анализу данных. Выяснение того как господдержка влияет на кассовые сборы и рейтинг фильма](https://github.com/the13den/yandex_practicum_ds_big_project_data_analysis_and_exploration_film_popularity_research_n2) | Данный проект содержал меня подробное ТЗ. Я предобработал данные на Pandas. Используя графики и таблицы, корелляцию Пирсона выяснил как господдержка влияет на популярность фильма. Сложность проекта заключалась в обилии строковых столбцов, которые пришлось очищать. Большая часть визуализаций в проекте выполнена с помощью Plotly | `Python`, `Pandas`, `matplotlib`, `plotly` |
| [Исследовательский анализ данных. Изучение влияния различных характеристик жилья на его стоимость](https://github.com/the13den/yandex_practicum_ds_exploratory_data_analysis_housing_spb_price_n1) | Вначале работы, используя Pandas, я обработал пропуски, переименовал столбцы, удалил дубликаты и добавил новые столбцы в таблицу. Затем я выявил выбросы используя гистограммы и box-plot и удалил их. В конце используя корреляцию Пирсона и графики, а также сводные таблицы я дал подробное описание того, какие характеристики влияют на стоимость жилья. | `Python`, `Pandas`, `matplotlib`, `seaborn` |
| [Предобработка данных. Выявление характеристик заямщиков влияющих на возврат кредита](https://github.com/the13den/yandex_practicum_ds_data_preparation_borrower_reliability_assessment_n0) | Использовуя Pandas очистил данные от дубликатов, аномалий и пропусков, преобразовал типы данных и добавил новые категориальные признаки. Эта часть была проверена автоматически. На основании сводных таблиц провел анализ того как различные факторы влияют на воврат кредита | `Python`, `Pandas` |
