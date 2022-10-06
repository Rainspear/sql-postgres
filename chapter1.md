\c test // connect to db test
\l // list all databases
\du // list all users of db
\dt // list all table of a database after connected
\q // exit

CREATE DATABASE cities;

DROP DATABASE cities;

ALTER TABLE cities ADD state VARCHAR(40); // add column

ALTER TABLE cities RENAME COLUMN state TO district;

CREATE TABLE cities (id SERIAL PRIMARY KEY, name VARCHAR(30), country VARCHAR(50), area INTEGER, population INTEGER);

DROP TABLE cities;