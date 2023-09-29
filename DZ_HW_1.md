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
('',''),
('',''),
('',''),
('',''),
