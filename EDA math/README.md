# EDA успеваемости по математике 
____


### Оглавление  
---

[1. Суть проекта](https://github.com/Desolitto/KazakovGit/blob/master/EDA%20math/README.md#Суть-проекта)  
[2. Краткая информация о данных](https://github.com/Desolitto/KazakovGit/blob/master/EDA%20math/README.md#Краткая-информация-о-данных)  
[3. Этапы работы над проектом](https://github.com/Desolitto/KazakovGit/blob/master/EDA%20math/README.md#Этапы-работы-над-проектом)  
[4. Результат](https://github.com/Desolitto/KazakovGit/blob/master/EDA%20math/README.md#Результат)    


## Суть проекта
Провести разведывательный анализ (EDA) датасета для дальнейшего построения модели, которая бы предсказывала результаты госэкзамена по математике для учеников школы.

## Краткая информация о данных  
Датасет содержит информацию об 395 учениках.
Датасет представлен в репозитории в папке.  

:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/EDA%20math/README.md#Оглавление)

#### Описание полей датасета:

- school — аббревиатура школы, в которой учится ученик;  
- sex — пол ученика ('F' - женский, 'M' - мужской);    
- age — возраст ученика (от 15 до 22);  
- address — тип адреса ученика ('U' - городской, 'R' - за городом);  
- Pstatus — статус совместного жилья родителей ('T' - живут вместе 'A' - раздельно);  
- Medu — образование матери (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее);  
- Fedu — образование отца (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее);  
- Mjob — работа матери ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое);  
- Fjob — работа отца ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое);  
- reason — причина выбора школы ('home' - близость к дому, 'reputation' - репутация школы, 'course' - образовательная программа, 'other' - другое);  
- guardian — опекун ('mother' - мать, 'father' - отец, 'other' - другое);  
- traveltime — время в пути до школы (1 - <15 мин., 2 - 15-30 мин., 3 - 30-60 мин., 4 - >60 мин.);  
- studytime — время на учёбу помимо школы в неделю (1 - <2 часов, 2 - 2-5 часов, 3 - 5-10 часов, 4 - >10 часов);  
- failures — количество внеучебных неудач (n, если 1<=n<=3, иначе 0);  
- schoolsup — дополнительная образовательная поддержка (yes или no);  
- famsup — семейная образовательная поддержка (yes или no);  
- paid — дополнительные платные занятия по математике (yes или no);  
- activities — дополнительные внеучебные занятия (yes или no);  
- nursery — посещал детский сад (yes или no);  
- higher — хочет получить высшее образование (yes или no);  
- internet — наличие интернета дома (yes или no);  
- romantic — в романтических отношениях (yes или no);  
- famrel — семейные отношения (от 1 - очень плохо до 5 - очень хорошо);  
- freetime — свободное время после школы (от 1 - очень мало до 5 - очень мого);  
- goout — проведение времени с друзьями (от 1 - очень мало до 5 - очень много);  
- health — текущее состояние здоровья (от 1 - очень плохо до 5 - очень хорошо);  
- absences — количество пропущенных занятий;  
- score — баллы по госэкзамену по математике.

:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/EDA%20math/README.md#Оглавление)

## Этапы работы над проектом     
- Детальный анализ переменных:
  - преобразование перменных;
  - устранение None-элементов;
  - устранение выбросов;
- Визуализация корреляции;   
- Финальная подготовка датасета для построения модели
- Выводы 

:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/EDA%20math/README.md#Оглавление)


## Результат
Пройдемся по каждой из этих переменных:
    - sex - пол имеет два значения и не имеет выбросов;  
    - medu - имеет 5 различных уникальных значений в зависимости от образования матери, в данной категории выбросов нет;  
    - mjob - имеет 5 различных уникальных значений в зависимости от работы матери, в данной категории выбросов нет;   
    - guardian - имеет 3 различных уникальных значения в зависимости от опекунства, в данной категории выбросов нет;   
    - failures - Как уже говорилось данный показатель является не очень точным, поскольку показывает количество внеучебных неудач либо от одного до трех,
    либо все остальное, включая большее количество неудач и меньшее;  
    - schoolsup - имеет 2 различных уникальных значения в зависимости от наличия дополнительной образовательной поддержки;  
    - romantic - имеет 2 различных уникальных значения в зависимости от наличия  романтических отношенияй;   
    - goout - имеет 5 различных уникальных значений в зависимости  времени проводимого с друзьями.  

:arrow_up:[к оглавлению](https://github.com/Desolitto/KazakovGit/blob/master/EDA%20math/README.md#Оглавление)
