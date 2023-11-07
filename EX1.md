# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## DATE: 4.08.2023

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: mysql> create table student(Roll_no int PRIMARY KEY, Name varchar(40),Age int,Address varchar(50),Phone_no int);

### OUTPUT:
![image](https://github.com/Meetha22003992/G2_DBMS/assets/119401038/1b592a39-3450-4f75-b6e8-1c1045113206)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: mysql> alter table student add Department varchar(60);

### OUTPUT:
![image](https://github.com/Meetha22003992/G2_DBMS/assets/119401038/2ec7a10e-77af-4727-9db2-e3a83b398bfa)


### 3) Drop the student table
 
### SQL QUERY: mysql> drop table student;

### OUTPUT:
![image](https://github.com/Meetha22003992/G2_DBMS/assets/119401038/16399166-39a8-4673-8d8f-2778514a66a9)


### 4) Delete the student table using truncate keyword

### SQL QUERY: mysql> truncate table student;

### OUTPUT:
![image](https://github.com/Meetha22003992/G2_DBMS/assets/119401038/703fda6c-97da-47fe-a222-85ff123982d7)


### 5) Rename the student table to mystudent

### SQL QUERY: alter table student rename to stud;

### OUTPUT:
![image](https://github.com/Meetha22003992/G2_DBMS/assets/119401038/367536c7-9b80-4f93-b911-a03bbc189042)
