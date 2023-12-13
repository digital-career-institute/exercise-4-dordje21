# write steps as below and make a document to refer in future
1. Update:
   sudo apt update
2. Upgrade installed packages:
   sudo apt upgrade
3. Install MySQL Server:
   sudo apt install mysql-server
4. Install MySQL Client:
   sudo apt install mysql-client
5. Check MySQL version:
   mysql --version
6. Start MySQL:
   sudo systemctl start mysql
7. Stop MySQL:
   sudo systemctl stop mysql
8. Restart MySQL:
   sudo systemctl restart mysql
9. Start SQL Editor (e.g., MySQL CLI):
   mysql -u your_username -p
10. Create a database:
    sql CREATE DATABASE your_database;
11. Create a user:
    sql CREATE USER 'your_username'@'localhost' IDENTIFIED BY 'your_password';
12. Grant all permissions for the user on a specific database:
    sql GRANT ALL PRIVILEGES ON your_database.* TO 'your_username'@'localhost';
13. Show all grants for a specific user:
    sql SHOW GRANTS FOR 'your_username'@'localhost';
14. Create a table:
    sql CREATE TABLE your_table ( column1 datatype1, column2 datatype2, ... );
15. Insert values into a table:
    sql INSERT INTO your_table (column1, column2, ...) VALUES (value1, value2, ...);
16. Display the total number of tables:
    sql SHOW TABLES;
17. Display the total number of databases:
    sql SHOW DATABASES;
18. Get all values from a particular table:
    sql SELECT * FROM your_table;
19. Show the number of entries in a table:
    sql SELECT COUNT(*) FROM your_table;
20. Alter a table (add a new column, for example):
    sql ALTER TABLE your_table ADD COLUMN new_column datatype;

