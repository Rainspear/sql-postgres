SELECT * FROM cities;

SELECT name, population / area AS density FROM cities;

SELECT name || ', ' || area FROM cities;

SELECT name, population / area AS density FROM cities WHERE population / area > 6000;

INSERT INTO cities (name, area, population) VALUES 
('Tokyo', 3341, 23405000),
('Sau Paolo', 8565, 7701000),
('Shanghai', 4451, 26205000);

UPDATE cities SET name = 'Seoul' WHERE id <> 1 AND name = "Tokyo"; // <> != = > <

DELETE FROM cities WHERE id = 1;