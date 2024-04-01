# 12_1


### Задание 1
Опишите не менее семи таблиц, из которых состоит база данных:

* какие данные хранятся в этих таблицах;
* какой тип данных у столбцов в этих таблицах, если данные хранятся в PostgreSQL.
* 
Приведите решение к следующему виду:

Сотрудники (

* идентификатор, первичный ключ, serial,
* фамилия varchar(50),
...
* идентификатор структурного подразделения, внешний ключ, integer).

### employees (

* id_employee, int, not null, auto_increment, primary_key
* last_name, varchar(50), not null
* first_name, varchar(50), not null
* surname, varchar(50)
* rank, foreign_key
* salary, foreign_key
* subdivision, foreign_key
* office, foreign_key
* project, foreign_key
* hired_since, date, not null )


