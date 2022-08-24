# sololearn-sql
Конспект занятий по SQL
- hello
- изменение 1
- изменение 2

```roomsql
-- Show tables
SELECT name, sql FROM sqlite_master
WHERE type='table'
ORDER BY name;
```

```roomsql
-- смотреть информацию о свойствах столбцов
PRAGMA table_info(fio_dr);
```

```roomsql
SELECT * FROM fio_dr fd ;
```

```roomsql
INSERT INTO fio_dr (name, surname, birthday) VALUES('Мистер', 'Смит', '22.10.1990');
INSERT INTO fio_dr (name, surname, birthday) VALUES('Мисисс', 'Смит', '10.10.1995');
```

```roomsql
SELECT column_list
FROM table_name
```

```roomsql
CREATE TABLE customers (
    ID int,
    LastName varchar(255),
    FirstName varchar(255),
    City varchar(255),
    ZipCode varchar(255) 
    );
    INSERT INTO Customers (ID, LastName, FirstName, City, ZipCode)
VALUES ('1','John','Smith','New York','10199');

 INSERT INTO Customers (ID, LastName, FirstName, City, ZipCode)
VALUES ('2','David','Williams','Los Angeles','90052');

INSERT INTO Customers (ID, LastName, FirstName, City, ZipCode)
VALUES ('3','Chloe','Anderson','Chicago','60607');

INSERT INTO Customers (ID, LastName, FirstName, City, ZipCode)
VALUES ('4','Emily','Adams','Houston','77201');

INSERT INTO Customers (ID, LastName, FirstName, City, ZipCode)
VALUES ('5','James','Roberts','Philadephia','19104');
```