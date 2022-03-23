# yandex_praktikum_projects

Здесь хранятся выполненные мной проекты из Яндекс.Практикума.  
Каждый проект в отдельной папке с кратким описанием в файле README.  

| Название проекта      |Навыки и инструменты     | Описание проекта | 
| :-------------------- | :------------------------|:-----------------|
|**telecom** (определение выгодного тарифа для телеком компании)|Python, Pandas, Matplotlib, SciKitLearn, numpy, tensorflow, keras, lightgbm, catboost.|Компания «Ниединогоразрыва.ком» хочет предсказать отток клиентов. Заказчик предоставил данные о клиентах, договорах, тарифах и предоставляемых услугах. Оператор хочет сохранить максимум клиентов, и при этом не давать лишние скидки платежеспособным клиентам. Для оценки качества модели использую метрику ROC-AUC. Проведен анализ данных. Опробованы разные модели (DecisionTreeClassifier, RandomForest, LGMB, Catboost, а также построена нейронная сеть).|  
|**auto** (Построена модель, способная быстро посчитать стоимость автомобиля по ряду параметров)|pandas, matplotlib, sklearn, lightgbm|Я использвала 3 модели: Catboost, LightGMB и RandomForest. Все три показали результат лучше, чем константая модель. RandomForest показала худший реузльтат rmse=2502. У Lighgbm и Catboost результат похожий: rmse=1635 и 1651 соответственно. При этом RandomForest обучается и предсказывает гороздо дольше, чем другие модели. Самой быстрообучаемой моделью оказалась Lighgbm|    
|**beta_bank** (Прогнозирование оттока клиентов)|pandas, sklearn| Банк хочет спрогнозировать уйдет клиент в ближайшее время или нет.|    
|**cifra** (Построена модель, способная предсказывать коэффициент восстановления золота из золотосодержащей руды)|pandas, matplotlib, sklearn, seaborn, scipy|Изучены исходные данные, проверен расход эффектвности обогащения, проанализированы признаки, недоступные в тестовой выборке. А также проведена предварительная предобработка данных. Изучено как меняется концентрация металлов (Au, Ag, Pb) на различных этапах очистки. Проведено сравнение распределения размеров гранул сырья на обучающей и тестовой выборках. Удалены выбросы в суммарных распределениях концентраций веществ на разных стадиях: в сырье, в черновом и финальном концентратах. Удалены выбросы концентраций веществ в черновом концентрате тестовой выборки. Обучены разные модели, выбрана лучшая: модель случайного леса с параметрами max_depth=1 и n_estimators=11. При проверке на тестовой выборке модель показала на 0.16% результат лучше, чем константная модель. Это мало, но всё же результат положительный есть.|  
|**computer_games** (Выявление закономерностей, определяющих успешность игры)|pandas, matplotlib, seaborn, numpy, scipy| Выявлены закономерности, определяющие успешность игры. Определила самые прибыльные жанры: action и shooter. Составила портрет для пользователей каждого региона. Проверила 2 гипотезы.|  
|**glavrosgosneft** (Определение самого перспективного района добычи нефти)|pandas, numpy, scipy, sklearn, bootstrap| Применена теника Bootstrap, выбраны оптимальные скважины. Посчитаны прибыль и риск убытков в трех регионах. Выбран оптимальный регион для разработки месторождения|    
|**images**(Модель, которая по фотографии определяет приблизительный возраст человека)|pandas, matplotlib, numpy, keras|Построена и обучена свёрточная нейронная сеть на датасете с фотографиями людей. Я применяла архитектуру ResNet50. Результат работы модели МАЕ на тестовой выборке 6.84.|    
|**megaline** (Сравнение двух тарифных планов с целью выявления перспективного.)|pandas, matplotlib, seaborn, numpy, scipy|Проведен предварительный анализ тарифов на небольшой выборке клиентов. Выбран самый прибыльный тариф|  
|**megaline_model** (Модель для задачи классификации, которая выберет подходящий тариф)|pandas, sklearn| Я построила модель для задачи классификации, которая выбирает подходящий тариф в зависимости от того как пользователь пользуется звонками, сообщениями и интернетом. При проверке на тестовой выборке модель показала долю правильных ответов 0.80.|   
|**realty** |pandas, matplotlib| Определяю параметры, необходимые для определения рыночной стоимости объектов недвижимости.|    
|**taxi** (Прогнозирование заказов такси)|pandas, numpy, matplotlib, sklearn, seaborn, LinearRegression, CatBoost| Оператор Такси хочет спрогнозировать пиковые нагрузки, чтобы привлекать большше водителей в эти часы. Компания предоставила данные о кол-ве заказов за несколько месяцев. Проанализированы исторические данные о заказах такси в аэропортах. Построена модель для предсказания количества заказов такси на следующий час. Значение метрики RMSE на тестовой выборке равно 39|  
|**vikishop** (классификация комментариев)| pandas, numpy, matplotlib, sklearn, nltk, lightgbm, NLTK, токенизация, лемматизация, LogisticRegression | Для запуска нового сервиса интернет-магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Проанализирован набор данных с разметкой о токсичности правок. Проведена токенизация и лемматизация, избавилась от стоп-слов, получены матрицы со значениями tf_idf. Обучена модель классифицировать комментарии на позитивные и негативные. Построена модель со значением метрики качества F1 = 0.77.|  




