##  MYSQL

MySQL is a open-source, free and very popular relational database management system which is developed, distributed and supported by Oracle corporation.

## Key Features:
* Open-source relational database management systems.
* Reliable, very fast and easy to use database server.
* Works on client-server model.
* Highly Secure and Scalable
* High Performance
* High productivity as it uses stored procedures, triggers, views to write a highly productive code.
* Supports large databases efficiently.
* Supports many operating systems like Linux*,CentOS*, Solaris*,Ubuntu*,Windows*, MacOS*,FreeBSD* and others.

## Getting started with MYSQL

## Connecting to Database using command-line client

```sql
mysql -u [username] -p [database];
```

### To exit from mysql command-line client
    ```sql
    exit;
    ```

### Create databases 

```sql
CREATE DATABASE database_name;
```

### Using created database 

```sql
USE database_name;
```
### Create Table

```sql
CREATE TABLE table_name(
	col1_name datatype,
	col2_name datatype,
	coln_name datatype
);
```

### Insert Records 

```sql
INSERT INTO table_name VALUES(value,value,value);
```

### Modifying Records

```sql
UPDATE table_name
SET col1=value1,col2=value2
WHERE condition;
```
### Select 
```sql
SELECT col_name FROM table_name;
SELECT * FROM table_name;
```
### 2. ALTER
```sql 
ALTER TABLE Table_name ADD column_name datatype;
```
### 3. TRUNCATE
```sql
TRUNCATE table table_name;
```


## Joins 

### INNER JOIN 
```sql
SELECT ... FROM t1 JOIN t2 ON t1.id1 = t2.id2 WHERE condition;
```

### LEFT JOIN

```sql
SELECT ... FROM t1 LEFT JOIN t2 ON t1.id1 = t2.id2 WHERE condition;
```

### RIGHT JOIN

```sql
SELECT ... FROM t1 RIGHT JOIN t2 ON t1.id1 = t2.id2 WHERE condition;
```
