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
