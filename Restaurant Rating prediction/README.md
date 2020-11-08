# ML Restaurant Rating prediction  
____


### Оглавление  
---

[1. Суть проекта](https://github.com/Desolitto/KazakovGit/blob/master/Restaurant%20Rating%20prediction/README.md#Суть-проекта)  
[2. Краткая информация о данных](https://github.com/Desolitto/KazakovGit/blob/master/Restaurant%20Rating%20prediction/README.md#Краткая-информация-о-данных)  
[3. Этапы работы над проектом](https://github.com/Desolitto/KazakovGit/blob/master/Restaurant%20Rating%20prediction/README.md#Этапы-работы-над-проектом)  
[4. Результат](https://github.com/Desolitto/KazakovGit/blob/master/Restaurant%20Rating%20prediction/README.md#Результат)    


## Суть проекта
Предсказание рейтинга ресторана на основе данных из TripAdvisor.

## Краткая информация о данных  
В этом проекты мы  работатем с датасетом, содержащим сведения о 40 000 ресторанах Европы, а модель, которую мы обучим, должна будет предсказывать рейтинг ресторана по данным сайта TripAdvisor на основе имеющихся в датасете данных.
Датасет представлен в репозитории в папке  

:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/Restaurant%20Rating%20prediction/README.md#Оглавление)

#### Описание полей датасета:

- Restaurant_id — идентификационный номер ресторана / сети ресторанов;  
- City — город, в котором находится ресторан;  
- Cuisine Style — кухня или кухни, к которым можно отнести блюда, предлагаемые в ресторане;  
- Ranking — место, которое занимает данный ресторан среди всех ресторанов своего города;  
- Rating — рейтинг ресторана по данным TripAdvisor (именно это значение должна будет предсказывать модель);  
- Price Range — диапазон цен в ресторане;  
- Number of Reviews — количество отзывов о ресторане;  
- Reviews — данные о двух отзывах, которые отображаются на сайте ресторана;  
- URL_TA — URL страницы ресторана на TripAdvosor;  
- ID_TA — идентификатор ресторана в базе данных TripAdvisor.  

:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/Restaurant%20Rating%20prediction/README.md#Оглавление)


## Этапы работы над проектом     
- Детальный анализ переменных:
  - конвертация данных;  
  - добалвение dummy-переменных;  
  - реобразование переменных;
- Визуализация корреляции;   
- Обучение модели.  

:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/Restaurant%20Rating%20prediction/README.md#Оглавление)

## Результат  

MAE = 0.20859 = , попал в первые 50% на kaggle в закрытом соревновании.:arrow_right:[к kaggle leaderboard](https://www.kaggle.com/c/sf-dst-restaurant-rating/leaderboard)  
:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/Restaurant%20Rating%20prediction/README.md#Оглавление)
