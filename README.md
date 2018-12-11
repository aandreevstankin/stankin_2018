# Отчеты о лабораторных работах
Студента группы ИДБ-15-14
Андреева А.Б.

# Лабораторная работа №1
 - Задание 1 - Диаграмма IDEF0
![Задание 1 - Диаграмма IDEF0](https://github.com/aandreevstankin/stankin_2018/blob/master/IDEF0.PNG)

[Задание 1 - Файл диаграммы IDEF0](https://github.com/aandreevstankin/stankin_2018/blob/master/IDEF0.rsf)

 - Задание 2 - UML диаграмма классов
![Задание 2 - UML диаграмма](https://github.com/aandreevstankin/stankin_2018/blob/master/UML1.png)

[Задание 2 - Код UML диаграммы классов](https://github.com/aandreevstankin/stankin_2018/blob/master/UML_TEXT)

 - Задание 3 - UML диаграмма прецедентов
![Задание 3 - UML диаграмма](https://github.com/aandreevstankin/stankin_2018/blob/master/UML2.png)

[Задание 3 - Код UML диаграммы прецедентов](https://github.com/aandreevstankin/stankin_2018/blob/master/UML_TEXT_2)
# Лабораторная работа №2
 [Ссылка на модель](https://github.com/aandreevstankin/stankin_2018/blob/master/2_and_3_level_decomposition(lab2-3).rsf)
 
 - Задание 1 - Диаграмма "6 вопросов"
  
 ![Задание 1 - диаграмма "6 вопросов"](https://github.com/aandreevstankin/stankin_2018/blob/master/lr3_idef0.PNG)
 
 - Задание 2 - Уровень детализации 1 (PDC)
  
 ![Задание 2 - Уровень детализации 1](https://github.com/aandreevstankin/stankin_2018/blob/master/lr_3_det_1.PNG)
 
 - Задание 3 - Уровень детализации 2 (DFD)
   
 ![Задание 2 - Уровень детализации 2](https://github.com/aandreevstankin/stankin_2018/blob/master/lr_3_det_2.PNG)
# Лабораторная работа №3
 [Ссылка на модель](https://github.com/aandreevstankin/stankin_2018/blob/master/2_and_3_level_decomposition(lab2-3).rsf)
 
 - Диаграмма DFD
   
 ![Диаграмма DFD](https://github.com/aandreevstankin/stankin_2018/blob/master/lr_3_det_2.PNG)
 
  [Диаграмма последовательностей](https://github.com/aandreevstankin/stankin_2018/blob/master/lab3_seq)
  
  ![Диаграмма последовательностей](https://github.com/aandreevstankin/stankin_2018/blob/master/lab3_seq.png)
  
  [Диаграмма ERD](https://github.com/aandreevstankin/stankin_2018/blob/master/lab3_dat)
  
  ![Диаграмма ERD](https://github.com/aandreevstankin/stankin_2018/blob/master/lab3_us.png)

# Лабораторная работа №4
 - Тема курсовой работы: "Проектирование серверной части информационной системы для автоматизации деятельности туристического агентства".
 - Функциональная модель разрабатывается с точки зрения пользователя (вызывающей среды) серверной части информационной системы, обрабатывающей запросы от интерфейса (клиентской части информационной системы).
 - Целью моделирования является представление и формализация процесса функционирования серверного компонента указанной системы при её использовании.
 - Объектом исследования является процесс функционирования серверной части информационной системы для автоматизации деятельности туристического агентства.
 
 - IDEF0 Контекстная:
  ![IDEF0 Контекстная](https://github.com/aandreevstankin/stankin_2018/blob/master/IDEF0_con.PNG)
 - IDEF0 Декомпозиция уровня A0:
  ![IDEF0 Декомпозиция уровня A0](https://github.com/aandreevstankin/stankin_2018/blob/master/IDEF0_A0.PNG)
 - IDEF0 Декомпозиция уровня А2:
  ![IDEF0 Декомпозиция уровня A2](https://github.com/aandreevstankin/stankin_2018/blob/master/IDEF0_A2.PNG)
# Лабораторная работа №5
 - Конфигурация технических средств: сервер для размещения БД.
 - Конфигурация программных средств: СУБД Oracle.
 - Определение допустимых видов хранилищ и их размещения: реляционная база данных.
 
 - DFD Декомпозиция уровня A21
 ![DFD Декомпозиция уровня A21](https://github.com/aandreevstankin/stankin_2018/blob/master/DFD_A21.PNG)
 - DFD Декомпозиция уровня A22
 ![DFD Декомпозиция уровня A22](https://github.com/aandreevstankin/stankin_2018/blob/master/DFD_A22.PNG)
 
 - Все блоки DFD представляют из себя модули обработкию
 
 - Классификаторы:
 
  ![Классификаторы](https://github.com/aandreevstankin/stankin_2018/blob/master/Class-s.PNG)
  + Описание сущностей:
   +  "Данные пользователей": предназначена для хранения данных о конечных пользователях (клиентах туристического агентства), атрибуты: ID, ФИО, мобильный телефон, электронная почта и т.д.
   +  "Заказанные туры": предназначена для хранения истории заказов конечных пользователей, атрибуты: ID, ID пользователя, Страна, Регион, Город, Отель, Дата и т.д.
   +  "Результаты опросов": предназначена для хранения опросов конечных пользователей об их предпочтениях, атрибуты: ID, ID пользователя, Ответ 1, Ответ 2 и т.д.
   +  "Предпочтения пользователей": предназначена для хранения данных о пользовательских предпочтениях, атрибуты: ID, ID пользователя, Позиция в рейтинге, Страна, Тип тура и т.д.
# Лабораторная работа №6
