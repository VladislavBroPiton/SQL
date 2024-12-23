# SQL
**Язык структурированных запросов (SQL)** – это язык программирования для хранения и обработки информации в реляционной базе данных. Реляционная база данных хранит информацию в табличной форме со строками и столбцами, представляющими различные атрибуты данных и различные связи между значениями данных. Инструкции SQL можно использовать для хранения, обновления, удаления, поиска и извлечения информации из базы данных. Можно также использовать SQL для поддержания и оптимизации производительности базы данных.
**Язык структурированных запросов (SQL)** – популярный язык запросов, который часто используется во всех типах приложений. Аналитики данных и разработчики изучают и используют SQL, потому что это решение хорошо интегрируется с различными языками программирования. Например, они могут внедрять SQL-запросы с языком программирования Java для создания высокопроизводительных приложений обработки данных с основными системами баз данных SQL, такими как Oracle или MS SQL Server. Решение SQL также довольно просто в освоении, так как в его утверждениях используются общепринятые английские ключевые слова.
### История SQL    
Решение **SQL** было изобретено в 1970-х годах на основе реляционной модели данных. Изначально оно было известен как структурированный английский язык запросов (SEQUEL). Позднее этот термин был сокращен до SQL. Компания Oracle, ранее – Relational Software, стала первым поставщиком, предложившим коммерческую систему управления реляционными базами данных SQL.
### Таблица SQL   
**Таблица SQL** – это базовый элемент реляционной базы данных. Таблица базы данных SQL состоит из строк и столбцов. Инженеры баз данных создают связи между несколькими таблицами базы данных, чтобы оптимизировать пространство для хранения данных.
Например, инженер баз данных создает таблицу SQL для продуктов в магазине: 
0001 | Матрас | Цвет 1 
:--|:-------:|-----------------:
0002 | Подушка | Цвет 2

Затем инженер базы данных связывает таблицу продуктов с таблицей цветов с *идентификатором цвета*:
### Идентификатор цвета Название цвета 
Цвет 1 | Голубой 
:--|-----------------:
Цвет 2 | Красный

### Популярные системы управления базами данных      
**Системы управления базами данных (СУБД)** — это инструменты, с помощью которых пользователь обращается к данным, изменяет их или создаёт. СУБД функционируют как менеджеры по работе с базами данных, которые «говорят» на их языке программирования. В российских и зарубежных компаниях используют шесть популярных СУБД:
### 1. Oracle
Объектно-**реляционная** СУБД, созданная одноимённой компанией-лидером на рынке. Преимущества Oracle: быстрая установка и настройка, возможность расширять функционал, практичность и надёжность. Но лицензия стоит дорого, поэтому Oracle обычно используют крупные корпорации.
### 2. MySQL  
**Реляционная СУБД** с открытым исходным кодом, то есть доступна для просмотра, исправления ошибок и создания новых версий программ. MySQL — бесплатная, быстрая и гибкая система, подходящая для таблиц разных типов.  
### 3. Microsoft SQL Server  
Оптимальная СУБД для операционных систем Windows, но совместима и с Linux. Легко интегрируется с другими продуктами Microsoft, удобна в использовании, но потребляет много ресурсов, а лицензия стоит дорого.   
### 4. PostgreSQL   
Объектно-**реляционная** СУБД, которую используют для сайтов, сервисов и платформ. Бесплатный доступ и поддержка многих языков программирования делают эту СУБД одной из самых популярных. По её лицензии создано немало расширенных версий, в том числе для коммерческого использования.   
### 5. Apache Cassandra   
В отличие от вышеназванных, Cassandra — **нереляционная** СУБД. Она разработана на языке Java и принадлежит фонду Apache Software Foundation. Система хранит данные по модели семейства столбцов и «ключ-значение», распределяет данные в несколько дата-центров и легко масштабируется при увеличении объёма информации.   
### 6. Redis   
NoSQL **резидентная** СУБД, которая использует модель «ключ-значение». Она написана на языках C и C++, а применяется для атомарных операций, например, записи и чтения быстро изменяющихся данных.   

**Базы данных (БД)** — это структурированная информация, которая хранится в связанных электронных таблицах. Базы можно встретить в банках, библиотеках, космических наблюдениях и вообще везде, где данных слишком много, чтобы обрабатывать их вручную.   
Не каждая электронная таблица — это база данных. В базе между таблицами есть связи, которые организованы в строгой системе. Отсюда и свойства баз данных: скорость обработки, простота получения и независимость данных.   
По структуре и способу связей основные базы данных делятся на типы: иерархические, сетевые, колоночные, реляционные, нереляционные и объектно-ориентированные.   
Чтобы **управлять данными в базе**, используют СУБД (систему управления базами данных). Каждому типу баз подходят свои СУБД.   
### Примеры использования баз данных   
1. **Показания счётчиков**      
Коммерческое помещение, как и жилое, подключено к системам электро- и водоснабжения. Если счётчики автоматические, они сами передадут показания, управляющая компания назначит плату за услуги, и придёт счёт. После оплаты в системе будет указано, что задолженности нет. Каждая компания обрабатывает огромное количество счётчиков. Базы данных нужны, чтобы хранить ежемесячные показания, сортировать их по номерам квартир, учитывать оплаты и долги. Простые электронные таблицы с такими задачами не справятся.   

2. **Данные сотрудников**
Если список сотрудников небольшой, данные можно записать в таблицу. Но это будет не самый безопасный способ их хранения, поэтому понадобятся базы данных с ограниченным доступом. Кроме личных данных, у каждого сотрудника должны быть медицинские карты и зарплатные счета. Здесь не обойтись без работы с базой данных: в первом случае она хранится на стороне клиники, а во втором — на стороне банка. Владельцу бизнеса останется только проконтролировать, все ли успешно прошли медосмотр и пришла ли зарплата.        

3. **База лояльных клиентов**
Заведения общепита часто предлагают поучаствовать в системе лояльности. Покупатель сообщает имя и телефон, чтобы начислялись бонусы, которыми можно оплатить следующие покупки. Без базы данных с лояльными клиентами сложно выстроить сообщество любителей кофейни. 

4. **Налоги**   
Системы налогообложения тоже работают на базах данных, потому что объём информации колоссальный. Ни одна таблица Excel не вместит всех налоговых резидентов страны, чтобы каждый месяц присылать им уведомление о начисленном налоге.   

5. **Заказы**   
Можно оценивать на глаз, в какие дни и время в кофейне больше всего посетителей, но это малоэффективно.  Надёжнее и проще опираться на базу данных, где учитываются все чеки с суммой, временем и ID клиента.  

6. **Сайты**  
Если сайт чуть больше, чем визитка, в его внутренней механике есть база данных. Это касается не только интернет-магазинов, где нужно хранить данные о заказах, товарах и ценах. В базах сайтов могут храниться изображения, данные о зарегистрированных пользователях, статистика посещений и перемещений.     
______

**CREATE DATABASE** - создание базы данных  
**DROP** - удалить  
**CREATE TABLE** - создание таблицы  
**AUTO_INCREMENT** - оператор, увеличивает значение поля на +1  
**id SERIAL** - уникальный не повторяющийся, значения поля на +1   
**SELECT** ('столбцы или * для выбора всех столбцов; обязательно')
**FROM** ('таблица; обязательно')
**WHERE** ('условие/фильтрация, например, city = 'Moscow'; необязательно')
**GROUP BY** ('столбец, по которому хотим сгруппировать данные; необязательно')
**HAVING** ('условие/фильтрация на уровне сгруппированных данных; необязательно')
**ORDER BY** ('столбец, по которому хотим отсортировать вывод; необязательно')

**id INT NOT NULL** - id (числовое) не может иметь пустое значение   
**id INT NOT NULL AUTO_INCREMENT** - id (числовое) не может иметь пустое значение и каждый раз увеличивает это поле на еденицу, при добавлении новой записи автоматически    
**PRIMARY KEY(id)** будет уникальное и не будет повторяться    
**ALTER TABLE people ADD pass VARCHAR(32)** - добавление нового поля pass к таблице people   
   
**ALTER TABLE people DROP COLUMN pass** -  удалить из таблицы people поле pass    
**INSERT INTO people (name, bio, birth, email) VALUES ('Влад','Тестировщик','2000-01-01','test@mail.ru')**   Добавление новой записи в таблицу people в поля (name,bio,birth,email) значения (Влад...)   
**ALTER TABLE people CHANGE birth birth DATE NOT NULL** - поменял в табл. people значение birth без изменения названия birth поэтому написал два раза и поменял на DATE NOT NULL  
**UPDATE name1 SET name = 'Vlad' WHERE id=5;**  - обновление табл. name1 для поля name в id=5  
**UPDATE name1 SET name = 'Vlad', email = 'Vlad@mail.ru' WHERE name = 'Vlad1';**   - будет изменено поле name и email, где в поле присутствует имя Vlad1      
**UPDATE name1 SET name = 'Vlad', bio = 'tester' WHERE id > 4;**    -  будет изменено поле name и bio, где id>4   

