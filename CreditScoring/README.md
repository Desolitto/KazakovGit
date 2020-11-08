# ML Project CreditScoring
____


### Оглавление  
---
[1. Суть проекта](https://github.com/Desolitto/KazakovGit/blob/master/CreditScoring/README.md#Суть-проекта)  
[2. Краткая информация о данных](https://github.com/Desolitto/KazakovGit/blob/master/CreditScoring/README.md#Краткая-информация-о-данных)  
[3. Этапы работы над проектом](https://github.com/Desolitto/KazakovGit/blob/master/CreditScoring/README.md#Этапы-работы-над-проектом)  
[4. Результат](https://github.com/Desolitto/KazakovGit/blob/master/CreditScoring/README.md#Результат)   


## Суть проекта
Построение скоринг модели для вторичных клиентов банка, которая бы предсказывала вероятность дефолта клиента.

## Краткая информация о данных
*Определение.* Кредитная история — это карточка заёмщика, в которую записываются все операции с кредитами: какой банк выдавал, сколько есть долгов и вовремя ли платит гражданин.  Основание: Федеральный закон «О кредитных историях».

Датасет содержит информацию о заемщиках, которые уже брали кредиты (повторных клиентов).  
Информация предоставлена из анкетных данных заемщиков и факт наличия дефолта.  
:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/CreditScoring/README.md#Оглавление)

#### Описание полей датасета:

- client_id - идентификатор клиента
- education - уровень образования
- sex - пол заемщика
- age - возраст заемщика
- car - флаг наличия автомобиля
- car_type - флаг автомобиля иномарки
- decline_app_cnt - количество отказанных прошлых заявок
- good_work - флаг наличия “хорошей” работы
- bki_request_cnt - количество запросов в БКИ
- home_address - категоризатор домашнего адреса
- work_address - категоризатор рабочего адреса
- income - доход заемщика
- foreign_passport - наличие загранпаспорта
- sna - связь заемщика с клиентами банка
- first_time - давность наличия информации о заемщике
- score_bki - скоринговый балл по данным из БКИ
- region_rating - рейтинг региона
- app_date - дата подачи заявки
- default - флаг дефолта по кредиту

:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/CreditScoring/README.md#Оглавление)


## Этапы работы над проектом  
- Первичная обработка датасета:
  - конвертация данных;  
  - добалвение новых признаков;   
- Детальный анализ переменных;  
- Визуализация корреляции;  
- Преобразование переменных;  
- Значимость переменных;  
- Стандартизация;  
- Проверка удаления выбросов;  
- Подготовка данных к машинному обучению;  
- Регуляризация;  
- Обучение модели.  
:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/CreditScoring/README.md#Оглавление)

## Результат  

score ROC-AUC = 0.73854, 7 место на kaggle из 74 команд закрытого соревнования (Top 10%).:arrow_right:[к kaggle leaderboard](https://www.kaggle.com/c/sf-dst-scoring/leaderboard)  
:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/CreditScoring/README.md#Оглавление)
