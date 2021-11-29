> Part 1 : Create database
  
1. Download MySQL;
2. Install MysQL;
3. Select a subject area end describe the database schema;
4. Create database on the server through the console;
5. Fill in tables;
6. Construct and execute SELECT operator;
7. Execute other different SQL;
8. Create a database on new users, connect to DB;
9. Make a selection from the main table
![1](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m4/DB%20Part%201.png)

> Part 2 : Work with DB
> 
 mysql> SHOW DATABASES;
 
![2](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m4/DB%20Part%202%20.png)

mysql> USE lybrary;
ERROR 1049 (42000): Unknown database 'lybrary'
mysql> USE library;
Reading table information for completion of table and column names
You can turn off this feature to get a quicker startup with -A

Database changed
mysql> SHOW TABLES;

![3](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m4/DB%20Part%202%20(1).png)

mysql> drop table Author;
Query OK, 0 rows affected (0.09 sec)

mysql> SHOW TABLES;

![4](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m4/DB%20Part%202(2).png)

mysql> ^DBye
root@e-bash3:/# mysql library < ahocharenkolbrry.sql
root@e-bash3:/# mysql
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 14
Server version: 8.0.27-0ubuntu0.20.04.1 (Ubuntu)

Copyright (c) 2000, 2021, Oracle and/or its affiliates.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> SHOW TABLES;
ERROR 1046 (3D000): No database selected
mysql> USE library;
Reading table information for completion of table and column names
You can turn off this feature to get a quicker startup with -A

Database changed
mysql> SHOW TABLES;


![4](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m4/DB%20Part%202(3).png)

mysql>

> DB AWS


![5](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m4/DB%20Part%202%20AWS.png)

