# crud
 CRUD study with PHP and MySQL

## Creating the Database Table

Execute the following SQL query to create a table named employees inside your MySQL database. We will use this table for all of our future operations.

```
CREATE TABLE employees (
id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
name VARCHAR(100) NOT NULL,
address VARCHAR(255) NOT NULL,
salary INT(10) NOT NULL
);
```

## Config File

Adjust it according to your DB info

```
define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_NAME', 'crud_demo');
```