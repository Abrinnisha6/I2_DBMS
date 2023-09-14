# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM :

To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language) :

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.

## List of DDL commands :

CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.

## Query :

1) Create a table student with the following fieds rollno,name,age,address,phoneno.
   
## SQL QUERY :

create table student(rollno numeric(10),name char(10),age numeric(5),address varchar(25),phoneno numeric(15));

## OUTPUT :

![d1](https://github.com/Abrinnisha6/I2_DBMS/assets/118889454/8d87b624-a6f1-4f5e-851f-abe4a3785f6b)

## Query :

2) Change the above student table by adding another attribute department.
   
## SQL QUERY :

alter table student add department varchar(15);

## OUTPUT :

![d2](https://github.com/Abrinnisha6/I2_DBMS/assets/118889454/8dea27a1-2130-4f84-b282-7d137d6b41bb)

## QUERY :

3) Drop the student table
   
## SQL QUERY :

drop table student;

## OUTPUT :

![d3](https://github.com/Abrinnisha6/I2_DBMS/assets/118889454/dda87b1a-9d5b-47eb-a3ae-67f7db05589e)


## QUERY :

4) Delete the student table using truncate keyword.
   
## SQL QUERY :

truncate table student;

## OUTPUT :

![d4](https://github.com/Abrinnisha6/I2_DBMS/assets/118889454/8b6e232e-df90-43f4-add8-b6a8fb7374ce)

## QUERY :

5) Rename the student table to mystudent.
   
## SQL QUERY :

rename table student to mystudent;

## OUTPUT :

![d5](https://github.com/Abrinnisha6/I2_DBMS/assets/118889454/2626c18c-9149-435b-8e12-ad0051846eda)










