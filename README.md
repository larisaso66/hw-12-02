# Домашнее задание к занятию "`Работа с данными (DDL/DML)`" - `Фамилия и имя студента`


### Задание 1

`Запрос на получение списка пользователей в базе данных`

<img width="919" height="549" alt="Снимок экрана 2026-01-13 в 11 53 01" src="https://github.com/user-attachments/assets/c3321486-4619-49e2-ad85-8477d38f5d23" />

`Запрос на получение списка прав для пользователя sys_temp`

<img width="1214" height="828" alt="Снимок экрана 2026-01-13 в 11 53 44" src="https://github.com/user-attachments/assets/c4530346-bc38-4191-9d0a-d0f1732b49fe" />


`Получение всех таблиц базы данных`

<img width="784" height="612" alt="Снимок экрана 2026-01-13 в 11 58 37" src="https://github.com/user-attachments/assets/5cb5dc9d-93c5-4c47-b828-a882124ca684" />


`ER-диаграмма базы данных sakila`

<img width="1677" height="915" alt="Снимок экрана 2026-01-14 в 21 50 40" src="https://github.com/user-attachments/assets/e539bf44-80c0-4c1a-a2c5-fdba0265487e" />

`Список всех запросов`

```
CREATE USER 'sys_temp'@'%' IDENTIFIED BY 'temp_password';
SELECT user, host FROM mysql.user;
GRANT ALL PRIVILEGES ON *.* TO 'sys_temp'@'%' WITH GRANT OPTION;
FLUSH PRIVILEGES;
SHOW GRANTS FOR 'sys_temp'@'%';

SOURCE /tmp/sakila-schema.sql;
SOURCE /tmp/sakila-data.sql;

USE sakila;
SHOW TABLES;
```
---

### Задание 2

`Таблица с названиями таблиц базы Sakila и их первичными ключами`

```
 +---------------+--------------+
| TABLE_NAME    | COLUMN_NAME  |
+---------------+--------------+
| actor         | actor_id     |
| address       | address_id   |
| category      | category_id  |
| city          | city_id      |
| country       | country_id   |
| customer      | customer_id  |
| film          | film_id      |
| film_actor    | actor_id     |
| film_actor    | film_id      |
| film_category | film_id      |
| film_category | category_id  |
| film_text     | film_id      |
| inventory     | inventory_id |
| language      | language_id  |
| payment       | payment_id   |
| rental        | rental_id    |
| staff         | staff_id     |
| store         | store_id     |
+---------------+--------------+

```

<img width="1183" height="482" alt="Снимок экрана 2026-01-14 в 22 03 38" src="https://github.com/user-attachments/assets/1a684a11-9019-4795-a3b6-2dcf222d45d0" />


### Задание 4

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`
