# Аналитика для разработки стратегии фитнесс центра

## Задача исследования: Понять какие клиенты наиболее вероятно попадут в отток фитнесс центра.

### Описание данных:
'Churn' — факт оттока в текущем месяце;
'gender' — пол;
'Near_Location' — проживание или работа в районе, где находится фитнес-центр;
'Partner' — сотрудник компании-партнёра клуба (сотрудничество с компаниями, чьи сотрудники могут получать скидки на абонемент — в таком случае фитнес-центр хранит информацию о работодателе клиента); 
'Promo_friends' — факт первоначальной записи в рамках акции «приведи друга» (использовал промо-код от знакомого при оплате первого абонемента);
'Phone' — наличие контактного телефона;
'Age' — возраст;
'Lifetime' — время с момента первого обращения в фитнес-центр (в месяцах).
'Contract_period' — длительность текущего действующего абонемента (месяц, 3 месяца, 6 месяцев, год);
'Month_to_end_contract' — срок до окончания текущего действующего абонемента (в месяцах);
'Group_visits' — факт посещения групповых занятий;
'Avg_class_frequency_total' — средняя частота посещений в неделю за все время с начала действия абонемента;
'Avg_class_frequency_current_month' — средняя частота посещений в неделю за предыдущий месяц;
'Avg_additional_charges_total' — суммарная выручка от других услуг фитнес-центра: кафе, спорт-товары, косметический и массажный салон.

#### Библиотеки: plotly, pandas, numpy, matplotlib.pyplot, seaborn, sklearn, os
