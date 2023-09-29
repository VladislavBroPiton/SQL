CREATE TABLE employees  - *создать таблицу employees*  
(  
id SERIAL PRIMARY KEY,   
employee_name VARCHAR(50) NOT NULL  
);   

INSERT INTO employees (employee_name)  
VALUES  
(Влад)  
(Вика)  
(Андрей)  
(Слава)  
(Маша)  
(Юля)  
(Полина)  
(Света)  
(Алпамыс)  
(Влада)  
(Павел)  
(Оля)  
(Алексей)  
(Анатолий)  
(Сергей)  
(Снежана)  
(Сюзанна)  
(Жанна)  
(Ира)  
(Марина)  
(Настя)  
(Глория)  
(Галя)  
(Елена)  

_______________________________________________________
CREATE TABLE salary      
(      
id SERIAL PRIMARY KEY,         
monthly_salary INT NOT NULL        
);         

INSERT INTO salary (monthly_salary)  
VALUES  
(1000)  
(1100)  
(1200)  
(1300)  
(1400)  
(1500)  
(1600)  
(1700)  
(1800)  
(1900)  
(2000)  
(2100)  
(2200)  
(2300)  
(2400)  
(2500)  
____

CREATE TABLE employee_salary   
(  
id SERIAL PRIMARY KEY,  
employee_id INT NOT NULL UNIQUE,  
salary_id INT NOT NULL  
);  

INSERT INTO employee_salary (employee_id, salary_id)   
VALUES  
('3','7'),  
('1','4'),  
('5','9'),  
('40','13'),  
('23','4'),  
('11','2'),  
('52','10'),  
('15','13'),  
('26','4'),  
(16, 1),
('71', '7'),  
('64', '8'),  
('70', '2'),	
('2', '5'),	
('4', '15'),	
('17', '14'),	
('6', '13'),	
('7', '12'),	
('8', '11'),		
('91', '10'),	
('77', '1'),	
('98', '3'),	
('9', '5'),	
('10', '7'),	
('12', '11'),	
	(13, 12),
	(14, 2),
	(18, 4),
	(100, 5),	
	(80, 9),
	(97, 11),
	(89, 10),
	(21, 1),
	(31, 3),
	(41, 6),
	(51, 7),
	(61, 8),
	(67, 9),
	(79, 12),	
	(81, 13);
________

CREATE TABLE roles (  
id SERIAL PRIMARY KEY,  
role_name INT NOT NULL UNIQUE  
);  

ALTER TABLE roles CHANGE role_name role_name VARCHAR(30) NOT NULL UNIQUE  

INSERT INTO roles (role_name)  
VALUES  
('Junior Python developer'),

_____

CREATE TABLE roles_employee (  
id SERIAL PRIMARY KEY,  
employee_id INT NOT NULL UNIQUE,  
role_id INT NOT NULL  
);  
