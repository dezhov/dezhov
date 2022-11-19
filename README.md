### Hi there 👋

Для связи:
* 12dim04@gmail.com
* t.me/v_tymane

*[Здесь можно ознакомиться с сертификатами пройденных мной курсов](https://github.com/dezhov/practicum-ds-projects/blob/main/Certificates/README.md)* 

*А ниже собраны некоторые проекты, выполненные  
в рамках прохождения курса "Специалист по Data Science" Яндекс.Практикум*

#### Машинное обучение
| Название проекта | Цель | Описание | Навыки и инструменты |
| :---------------------- | :---------------------- | :---------------------- | :----------------------: |
| 1. [Предсказание температуры стали](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%82%D0%B5%D0%BC%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D1%83%D1%80%D1%8B%20%D1%81%D1%82%D0%B0%D0%BB%D0%B8/DS_steel_temperature_prediction.ipynb) | Оптимизация производственных расходов металлургического комбината. | Металлургический комбинат решил уменьшить потребление электроэнергии на этапе обработки стали. На основании данных технологического процесса необходимо построить модель, которая предскажет температуру стали. | `Pandas` `NumPy` `Matplotlib` `Seaborn` `Scikit-learn` `LightGBM` |
| 2. [Прогнозирование количества заказов такси](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BA%D0%BE%D0%BB%D0%B8%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%B0%20%D0%B7%D0%B0%D0%BA%D0%B0%D0%B7%D0%BE%D0%B2%20%D1%82%D0%B0%D0%BA%D1%81%D0%B8/DS_forecasting_taxi_orders.ipynb) | Разработка системы предсказания объема заказов. | Сервисом по заказу такси собраны исторические данные о количестве заказов в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов на следующий час. Строится модель для такого предсказания. |  `Timeseries` `Feature generation` `Pandas` `Matplotlib` `Scikit-learn` `Statsmodels` `LightGBM` `CatBoost` |
| 3. [Прогнозирование оттока клиентов банка](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D0%B1%D0%B0%D0%BD%D0%BA%D0%B0/DS_bank_customers_outflow.ipynb) | Разработка модели для определения недовольных работой банка клиентов. | Из банка периодически стали уходить клиенты. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. На основании исторических данных о поведении клиентов и расторжении договоров нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. | `Imbalanced classification` `Pandas` `Scikit-learn` `Matplotlib` |
| 4. [Определение стоимости автомобиля](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8F/DS_cars_cost_determination.ipynb) | Разработка системы рекомендации стоимости автомобиля на основе его описания. | Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основании исторических данных необходимо построить модель для определения стоимости автомобиля. | `Pandas` `Matplotlib` `Scikit-learn` `LightGBM` `CatBoost` |
| 5. [Определение региона нефтедобычи](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%80%D0%B5%D0%B3%D0%B8%D0%BE%D0%BD%D0%B0%20%D0%BD%D0%B5%D1%84%D1%82%D0%B5%D0%B4%D0%BE%D0%B1%D1%8B%D1%87%D0%B8/DS_oil_production_region.ipynb) | Выбор района добычи нефти на основании данных геологической разведки. | Нефтедобывающей компанией предоставлены пробы нефти в трёх регионах.  На основании характеристик для каждой скважины необходимо построить модель для определения наиболее прибыльного для добычи региона. | `Pandas` `Matplotlib` `Scikit-learn` `Bootstrap` |

#### Анализ данных и визуализация
| Название проекта | Цель | Описание | Навыки и инструменты |
| :---------------------- | :---------------------- | :---------------------- | :----------------------: |
| 1. [Исследование рынка видеоигр](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%80%D1%8B%D0%BD%D0%BA%D0%B0%20%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE%D0%B8%D0%B3%D1%80/DA_video_game_market_research.ipynb) | Выявление закономерностей, определяющих успешность видеоигр. | Интернет-магазин продаёт компьютерные игры. Из открытых источников доступны исторические данные о продажах, оценки пользователей и экспертов, жанры и платформы (Xbox, PlayStation и др.). Нужно выявить определяющие успешность игры закономерности. | `Pandas` `NumPy` `Matplotlib` `Scipy` `Testing Statistical Hypotheses` |
| 2. [Определение перспективного тарифа для телеком-компании](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%82%D0%B0%D1%80%D0%B8%D1%84%D0%BE%D0%B2%20%D1%81%D0%BE%D1%82%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE%20%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%B0/DA_mobile_operator_tariffs.ipynb) | Определие наиболее прибыльного для телеком-компании тарифа на основании поведения клеентов. | федеральный оператор сотовой связи предлагает клиентам два тарифных плана. Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Для этого проводится анализ поведения клиентов, проверка статестических гипотез о различии выручки абонентов разных тарифов и разных регионов | `Pandas` `NumPy` `Matplotlib` `Scipy` `Testing Statistical Hypotheses` |

#### Обработка естественного языка (NLP)
| Название проекта | Цель | Описание | Навыки и инструменты |
| :---------------------- | :---------------------- | :---------------------- | :----------------------: |
| [Классификация тональности комментариев](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D1%82%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%80%D0%B8%D0%B5%D0%B2/NLP_%D1%81omment_classification.ipynb) | Определение тональности комментариев на основании набора данных с разметкой о токсичности правок. | Интернет-магазин запускает новый сервис, благодаря которому пользователи могут редактировать и дополнять описания товаров, т.е. предлагать свои правки и комментировать изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. | `Pandas` `Matplotlib` `Scikit-learn` `NLTK` `TF-IDF` `Stemming`|

#### Компьютерное зрение
| Название проекта | Цель | Описание | Навыки и инструменты |
| :---------------------- | :---------------------- | :---------------------- | :----------------------: |
| [Определение возраста покупателей](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%D0%BE%D0%B7%D1%80%D0%B0%D1%81%D1%82%D0%B0%20%D0%BF%D0%BE%20%D1%84%D0%BE%D1%82%D0%BE/CV_buyers_age.ipynb) | Определение возраста клиента на основании набора фотографий с указанием возраста. | Супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов для анализа покупкок и предложения товаров, которые могут заинтересовать покупателей возрастной группы. Строится модель, определяющая приблизительный возраст человека по фотографии. | `Pandas` `Matplotlib` `Keras` |

#### Шифрование данных
| Название проекта | Цель | Описание | Навыки и инструменты |
| :---------------------- | :---------------------- | :---------------------- | :----------------------: |
| [Защита персональных данных](https://github.com/dezhov/practicum-ds-projects/blob/main/%D0%97%D0%B0%D1%89%D0%B8%D1%82%D0%B0%20%D0%BF%D0%B5%D1%80%D1%81%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85/DS_data_protection.ipynb) | Разработка алгоритма защиты персональных данных с обоснованием корректности его работы. | Необходимо защитить персональные данные клиентов страховой компании. Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить исходную информацию и при этом не менялось качество линейной регрессии. | `Pandas` `NumPy` `Scikit-learn` |

<!--
**dezhov/dezhov** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
