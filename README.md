# my_flask_projects
 

MY SQL 

mysql> CREATE DATABASE my_database;

Query OK, 1 row affected (0.07 sec)

mysql> USE my_database;

Database changed

mysql> CREATE TABLE user(user_name varchar(30));

Query OK, 0 rows affected (0.10 sec)

mysql> INSERT INTO user(user_name) VALUES('Avinash');

Query OK, 1 row affected (0.02 sec)

mysql> INSERT INTO user(user_name) VALUES('avin');

Query OK, 1 row affected (0.01 sec)

mysql> select * from USER ;

+-----------+

| user_name |

+-----------+

| Avinash   |

| avin      |

+-----------+

2 rows in set (0.01 sec)
