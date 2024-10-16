**SQL (Structured Query Language)** — это язык структурированных запросов, используемый для работы с реляционными базами данных. Он позволяет выполнять такие операции, как `создание`, `изменение`, `удаление` и `извлечение данных из базы данных`.

Основные операции SQL
### 1. Создание таблицы
```
CREATE TABLE users (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100)
);
```
Этот запрос создаёт таблицу users с тремя столбцами: `id`, `name` и `email`.

### 2. Вставка данных
```
INSERT INTO users (id, name, email) VALUES (1, 'Иван', 'ivan@example.com');
INSERT INTO users (id, name, email) VALUES (2, 'Мария', 'maria@example.com');
```
Эти запросы добавляют два новых пользователя в таблицу `users`.

### 3. Выборка данных
```
SELECT * FROM users;
```
Этот запрос извлекает все данные из таблицы `users`.
```
SELECT name FROM users WHERE id = 1;
```
Этот запрос извлекает имя пользователя с `id = 1`.

### 4. Обновление данных
```
UPDATE users SET email = 'ivan_new@example.com' WHERE id = 1;
```
Этот запрос обновляет адрес электронной почты пользователя с `id = 1`.

### 5. Удаление данных
```
DELETE FROM users WHERE id = 2;
```
Этот запрос удаляет пользователя с `id = 2` из таблицы users.
Пример использования
Предположим, что в таблице users у нас следующие данные:
id | name |	email
:--| -- | --:
1 |	Иван |	mailto:ivan@example.com
2 |	Мария |	mailto:maria@example.com

Выборка всех пользователей:
```
   SELECT * FROM users;
```

Обновление имени пользователя Ивана:
```
   UPDATE users SET name = 'Иванов' WHERE id = 1;
```

Удаление пользователя Марии:
```
   DELETE FROM users WHERE id = 2;
```

### 6. Объединение таблиц (JOIN)
Представим, что у нас есть ещё одна таблица orders, содержащая информацию о заказах:
```
CREATE TABLE orders (
    order_id INT PRIMARY KEY,
    user_id INT,
    product VARCHAR(100),
    FOREIGN KEY (user_id) REFERENCES users(id)
);
```
