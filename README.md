# sololearn-sql
Конспект занятий по SQL
- hello
- изменение 1
- изменение 2

-- Посмотреть таблицы в схеме
SELECT name, sql FROM sqlite_master
WHERE type='table'
ORDER BY name;

-- смотреть информацию о свойствах столбцов
PRAGMA table_info(fio_dr);

SELECT * FROM fio_dr fd ;

INSERT INTO fio_dr (name, surname, birthday) VALUES('Мистер', 'Смит', '22.10.1990');
INSERT INTO fio_dr (name, surname, birthday) VALUES('Мисисс', 'Смит', '10.10.1995');