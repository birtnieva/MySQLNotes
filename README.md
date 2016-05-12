# MySQLNotes


-------------------------------------------
 Installing MySQL Test Database (employees)
-------------------------------------------

1. wget https://github.com/datacharmer/test_db/archive/master.zip

2. unzip master.zip

3. cd test_db-master/ 

4. mysql -u root -p < employees.sql

5. mysql -u root -p -t < test_employees_md5.sql

6. Verify result

a. List databases, verify if 'employees' is present:
`show databases;`
b. Use 'employees' database
`use employees; select database();`
c. Show tables
`show tables;`
d. Show columns on one table
`describe employees;`
