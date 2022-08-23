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
