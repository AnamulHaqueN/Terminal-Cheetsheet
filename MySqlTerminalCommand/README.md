## MySQL Terminal Commands Cheat Sheet

### Login / Logout
```sql
sudo mysql -u root -p      # Login as root (Linux)
mysql -u user -p           # Login as specific user
exit;                      # Exit MySQL
```

### Show databases
```sql
SHOW DATABASES;
```

### Create / Delete Database
```sql
CREATE DATABASE db_name;
DROP DATABASE db__name;
```

### Use Database
```sql
USE db_name;
```

### Show Tables
```sql
SHOW TABLES;
```

### Create Table
```sql
CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100)
);
```
Drop Table
```sql
DROP TABLE table_name;
```

### Table Structure
```sql
DESCRIBE table_name;
```

### Insert Data
```sql
INSERT INTO users (name, email)
VALUES ('John', 'john@gmail.com');
```

### Read Data
```
SELECT * FROM users;
SELECT name, email FROM users;
```

### Update Data
```sql
UPDATE users
SET name='Alex'
WHERE id=1;
```

### Delete Data
```sql
UPDATE users
SET name='Alex'
WHERE id=1;
```

### Delete Data
```sql
DELETE FROM users WHERE id=1;
```

### Search / Filter
```sql
SELECT * FROM users WHERE name='John';
SELECT * FROM users LIMIT 5;
```

### Users & Privileges
```sql
CREATE USER 'newuser'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON db_name.* TO 'newuser'@'localhost';
FLUSH PRIVILEGES;
```

### Change Root Password
```sql
ALTER USER 'root'@'localhost'
IDENTIFIED WITH mysql_native_password BY 'newpassword';
```

### Check MySQL Version
```sql
mysql --version
```

### Very Common Combo (Daily Use)
```sql
sudo mysql -u root -p
SHOW DATABASES;
USE mydb;
SHOW TABLES;
SELECT * FROM users;
```

