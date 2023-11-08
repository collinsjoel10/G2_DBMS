# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## Date: 3/8/23
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

### SQL QUERY: 
SQL> ``` create table student101(roll_no int,name varchar(30),age int,address varchar(50),phone_no int);```
### OUTPUT:  
![dbmstable1](https://github.com/ASHWINKUMAR2903/G2_DBMS/assets/119407186/5f15b6fe-e253-4e97-9c0a-6e4ef6607f75)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
SQL>``` alter table student101 add department varchar(30);```
### OUTPUT:    
![dbmstable2](https://github.com/ASHWINKUMAR2903/G2_DBMS/assets/119407186/8aacb344-5b90-4910-852d-ac35f9e66c25)

### 3) Drop the student table
 
### SQL QUERY:   
 SQL> ```alter table student101 rename to student202;```
### OUTPUT:
![dbmstable3](https://github.com/ASHWINKUMAR2903/G2_DBMS/assets/119407186/5d676329-e582-4436-ae4a-8b07ca0ea102)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
SQL> ```truncate table student202;```
### OUTPUT:   
![dbmstable4](https://github.com/ASHWINKUMAR2903/G2_DBMS/assets/119407186/9a5b3c8e-3526-4e9d-810e-6b7c94ce3159)



### 5) Rename the student table to mystudent

### SQL QUERY: 
SQL>``` drop table student202;```
### OUTPUT:   
![dbmstable5](https://github.com/ASHWINKUMAR2903/G2_DBMS/assets/119407186/ecec8710-2ea2-4526-b37b-9e7b82bf9ed8)

## RESULT:
the DATA DEFINITION LANGUGE COMMANDS (DDL) are executed successfully. 
