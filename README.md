# LR6
Лабораторная работа №6  
Цель лабораторной работы: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.  
## Ход работы:  
### 1. Настройка клиент git  
Вводим имя пользователя - "4918 Бабурин С.А" и и email - bombaigr01@gmail.com  
![шаг 1](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/1.jpg)  
### 2. Клонирование удалённого репозитория на компьютер  
клонируем репозиторий и переходим в директорию  
![шаг 2](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/2.jpg)  
### 3. Добавление файла через интерфейс GitHub  
Добавляем файл SR13.txt через интерфейс GitHub. Подтягиваем изменения в локальный репозиторий.  
![шаг 3](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/3.jpg)   
### 4. Получение всей истории операций  
Получаем историю всех операций для каждой из веток.  
### 5. Получение последних изменениий  
Получаем историю последних двух операций для каждой из веток.  
![шаг 4 и 5](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/4.jpg)  
### 6. Слияние в ветку master  
Выполняем слияние ветки branch1 в ветку master, разрешив конфликт c помощью графического интерфейса git.  
![шаг 6](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/5.jpg)  
![шаг 6](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/6.jpg)  
![шаг 6](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/7.jpg)  
![шаг 6](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/8.jpg)  
### 7. Удаление побочной ветки  
Удаляем побочную ветку после успешного слияния.
![шаг 7](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/10.jpg)  
### 8. Фиксирование изменений  
Делаем изменения в файле SR13.txt и зафиксируем их, оставляя комментарии два раза.  
![шаг 8](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/11.jpg)  
### 9. Откат коммита  
Делаем «хард» откат коммита.  
![шаг 9](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/12.jpg)  
### 10. Создание ветки  
Создаем ветку report для отчёта.   
![шаг10](https://github.com/Shnappy01/LR6/blob/master/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/13.jpg)

## Логи команд:  
*  git config --global user.name "4918 Бабурин С.А"
* git config --global usre.email bombaigr01@gmail.com
* git clone https://github.com/Shnappy01/LR6
* cd LR6   
  
  
/*Добавление файл SR13.txt через интерфейс GitHub*/
  
* git pull  
* git log  
* git log -2  
* git checkout branch1  
* git checkout master  
* git merge branch1  
  
/*Устранение конфликта в git GUI*/
    
* git branch -d branch   
    
 /*изменение в файле Sr13.lo №1*/   
   
* git add polyalo.txt  
* git commit -m "changes №1"  
  

 /*изменение в файле Sr13.lo №2*/   
   
* git add polyalo.txt  
* git commit -m "changes №2"  
* git reset --hard @~2  
* git branch report
## История операций:  
![история операций](https://github.com/PolyaLo/LR6/blob/report/скрин/13.png?raw=true)  
Вывод:я изучила базовые возможности системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.  
