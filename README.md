# SQL HW_1  
#### Первая часть.  

### Таблица **employees**  

1. Создать таблицу **employees**  
- id. serial,  primary key,  
- employee_name. Varchar(50), not null  
2. Наполнить таблицу **employees** 70 строками.  
### Таблица **salary**
3. Создать таблицу **salary**  
- id. Serial  primary key,    
- monthly_salary. Int, not null  
4. Наполнить таблицу salary 15 строками:  
- 1000  
- 1100  
- 1200  
- 1300  
- 1400  
- 1500  
- 1600  
- 1700  
- 1800  
- 1900  
- 2000  
- 2100  
- 2200  
- 2300  
- 2400  
- 2500  
Таблица **employee_salary**  
5. Создать таблицу **employee_salary**  
- id. Serial  primary key,  
- employee_id. Int, not null, unique  
- salary_id. Int, not null  
6. Наполнить таблицу **employee_salary** 40 строками:  
- в 10 строк из 40 вставить несуществующие **employee_id**  
