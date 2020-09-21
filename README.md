# MESSENGER_java_spring
MESSENGER java spring application

##Java Sping messaging service

Задание 
###Необходимо реализовать сервис сообщений

##Структура 
* Страница авторизации 
* Страница регистрации 
* Основная страница 
* Страница администратора

##Страница регистрации 
* Поля для ввода: ФИО, email, логин, пароль 
(в случае, если пользователь уже существует, выводится сообщение об ошибке) 
* Ссылка для перехода на главную страницу

##Страница авторизации 
* Поля для ввода: логина и пароля (в случае, если пользователь не найден, 
выводится сообщение об ошибке) 
* Ссылка на страницу регистрации 
* Кнопка вход

##Основная страница (простой пользователь) 
* Список сообщений в табличной форме (От кого, дата - время, тема) 
* Для администратора добавляется поле (кому) 
* Возможность сортировки сообщений по полям таблицы 
* Возможность удалить сообщение 
* При клике по сообщению - открывать всплывающий диалог в том же окне с заголовками 
(Отправитель, Дата, Тема) и текстом сообщения 
* Адресная книга (редактируемый [добавить-удалить] список имен пользователей) 
с ссылкой (кнопкой) для отправки сообщения 
* Ссылка и всплывающий диалог для смены пароля 
* Для администратора добавляется ссылка - управление пользователями
* Ссылка для выхода

##Страница администратора (управление пользователями)
* Список зарегистрированных пользователей (ФИО, email, login, role)
* Возможность добавить / удалить пользователя
* Возможность назначить / удалить права администратора
* Ссылка на главную страницу
* Предусмотреть, чтобы переход по ссылке на страницу администрирования 
был запрещен для обычных пользователей

##Общие требования: 
Использование jsp, servlets, spring-mvc Кросс-браузерность IE 10,11,
 Firefox, Chrome, Opera Все данные хранятся в БД (предпочтительно Postgres)
* Работа с базой через Hibernate
* Наличие текстового логгирования
* Работа всплывающих диалогов через ajax
* Разделение ролей через spring-security

##После реализации необходимо предоставить:
* Исходный код (можно просто архив с проектом) WAR-файл для развертывания проекта
* Внешние конфигурационные файлы (если используются)
* Схему БД (sql)
* Ссылку на развернутую версию портала (если возможно)
